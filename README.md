# MDEditor

![MDEditor Screenshot](http://i.imgur.com/EWYdPkX.png)

## This is a beta version of MDEditor

### Install Editor:

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
	helpIcon: true, // includes help button
	preview: true, // includes preview button
	attachment: true, // includes attachment button
	wordCounter: true, // includes word counter
	includeTipsy: true, // includes tipsy, if you haven't already done this
	wordWrap: true, // wordwrap in textarea
	theme: false, // choose a theme -> false = no theme
	maxUpload: 2000000 // 2MB
});
```

> For attachment you need [php](https://github.com/php/php-src) and the [json extension for php](http://www.php.net/manual/de/book.json.php)!