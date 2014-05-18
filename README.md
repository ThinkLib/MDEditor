# MDEditor

![Image](http://i.imgur.com/FybiZOu.png)

MDEditor is a simple Markdown editor.

- Write text in Markdown and look at it in a preview
- Upload files and photos
- Export text as Markdown or HTML

### Installation

> You need [jQuery](https://github.com/jquery/jquery) version 1.11.0 or higher and [Font Awesome](https://github.com/FortAwesome/Font-Awesome) version 4.1.0 or higher!

HTML markup:
```html
<textarea id="mdeditor" name="mdeditor"></textarea>
```
Without options:
```javascript
$.("#mdeditor").mdeditor();
```
With options:
```javascript
$.("#mdeditor").mdeditor({
	output: 'markdown', // choose between markdown and html
	language: 'en-US', // language of editor
	width: '100%', // width of editor
	height: '250px', // height of textarea in the editor
	specialBar: true, // includes the second (special) toolbar
	formControl: true, // includes form submit, reset and a go back button
	codeIcon: true, // includes button for code markup
	mailIcon: true, // includes button for a mail hyperlink markup
	phoneIcon: true, // includes button for a phone hyperlink markup
	headerIcon: true, // includes button for a header markup
	helpIcon: true, // includes help button
	preview: true, // includes preview button
	attachment: true, // includes attachment button
	wordCounter: true, // includes word counter
	includeTipsy: true, // includes tipsy, if you haven't already done this
	wordWrap: true, // wordwrap in textarea
	theme: false, // choose a theme -> false = no theme
	tabs: true, // activate tabs in textarea
	maxUpload: 2000000, // 2MB
	notUpload: [
		'php',
		'py',
		'rb',
		'pl'
	] // .php, .py, .rb and .pl files aren't allowed for upload
});
```

-------------

### Markdown -> HTML

MDEditor use [chjj/marked](https://github.com/chjj/marked) to transform Markdown into HTML.  
[core/marked.js](https://github.com/Teddy95/MDEditor/blob/master/core/marked.js)

-------------

### Examples

[examples/](https://github.com/Teddy95/MDEditor/tree/master/examples) - Directory with examples  
[MDEditor wiki - Examples](https://github.com/Teddy95/MDEditor/wiki/Examples)

-------------

### Documentaion

[https://github.com/Teddy95/MDEditor/wiki](https://github.com/Teddy95/MDEditor/wiki)

-------------

### Download

- [Releases on Github](https://github.com/Teddy95/MDEditor/releases)
- **[Download latest version from Github](https://github.com/Teddy95/MDEditor/archive/v1.1.0.zip)**
- [Download master from Github](https://github.com/Teddy95/MDEditor/archive/master.zip)

-------------

### Contributors

- [Teddy95](https://github.com/Teddy95)

-------------

### License

The MIT License (MIT) - [View LICENSE.md](https://github.com/Teddy95/MDEditor/blob/master/LICENSE.md)