Casual stab at modifying the Bookstack main theme using the Dracula color scheme.
Download and use at your own risk.

# Installation
1. Deploy this CSS file to your Bookstack install's public/css folder
2. Call the stylesheet in the "Custom HTML head content" section in the settings like so:
	`<link rel="stylesheet" href="https://bookstack.example.com/css/dark-theme.css">`
	
#### Changing the Codemirror theme for the Markdown editor
Add the following to the "Custom HTML head content" box on the settings page to change the Markdown editor theme:
```
<link rel="stylesheet" href="//cdnjs.cloudflare.com/ajax/libs/codemirror/5.29.0/theme/dracula.min.css"/>
<script>window.codeTheme='dracula';</script>
```

Report any issues you find here.

# Screenshots
**Login:**
![](https://raw.githubusercontent.com/domainzero/bookstack-dark-theme/master/screenshots/stacks%20login.png)
**Main page:**
![](https://raw.githubusercontent.com/domainzero/bookstack-dark-theme/master/screenshots/stacks%20main%20page.png)
**Book with chapters:**
![](https://raw.githubusercontent.com/domainzero/bookstack-dark-theme/master/screenshots/stacks%20book.png)
**Page:**
![](https://raw.githubusercontent.com/domainzero/bookstack-dark-theme/master/screenshots/stacks%20page.png)
**Editor:**
![](https://raw.githubusercontent.com/domainzero/bookstack-dark-theme/master/screenshots/stacks%20editor.png)
