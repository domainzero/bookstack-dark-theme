Casual stab at modifying the Bookstack main theme using the Dracula color scheme.
Download and use at your own risk.

# Installation
1. Deploy this CSS file to your Bookstack install's public/css folder
2. Call the stylesheet in the "Custom HTML head content" section in the settings like so:
	`<link rel="stylesheet" href="https://bookstack.example.com/css/dark-theme.css">`
3. Additionally, put the following block in your Custom HTML Head Content (these rules are also included in the bottom of the CSS sheet. They must be put in your Custom HTML Head Content due to how the CSS loads in Bookstack)
4. Enjoy!

```css
<style>
.title-input.page-title input[type=text]{background:#44475a}
.floating-toolbox div[toolbox-tab-content]{background-color:#282a36}
html.dark-mode .card.drag-card{background-color:#44475a}
html.dark-mode .card.drag-card .handle{background-color:#44475a}
.card.drag-card .outline input{background-color:#282a36;color:#f8f8f2}
#header{background-color:#282a36!important}
html.dark-mode .fake-input,html.dark-mode .input-base,html.dark-mode input[type=color],html.dark-mode input[type=date],html.dark-mode input[type=email],html.dark-mode input[type=number],html.dark-mode input[type=password],html.dark-mode input[type=search],html.dark-mode input[type=text],html.dark-mode input[type=url],html.dark-mode select,html.dark-mode textarea{color:#f8f8f2;background-color:#44475a}
html.dark-mode{background-color:#282a36}
html.dark-mode .card{background-color:transparent}
html.dark-mode body{color:#6272a4;background-color:transparent}
.markdown-editor-display{background-color:#282a36!important}
html.markdown-editor-display.dark-mode body{background-color:#282a36}
.logo-text{color:var(--color-primary)!important}
html.dark-mode code{background-color:#44475a}
html.dark-mode pre{background-color:#44475a}
.title-input.page-title input[type=text]{background:#44475a}
html.dark-mode .editor-toolbar{background-color:#282a36}
html.dark-mode .primary-background-light{background:#282a36}
</style>
```

#### Changing the Codemirror theme for the Markdown editor
Add the following to the "Custom HTML head content" box on the settings page to change the Markdown editor theme:
```
<link rel="stylesheet" href="//cdnjs.cloudflare.com/ajax/libs/codemirror/5.29.0/theme/dracula.min.css"/>
<script>window.codeTheme='dracula';</script>
```

Report any issues you find here.

# Screenshots
**Login:**
![](https://github.com/domainzero/bookstack-dark-theme/blob/master/login.png)
**Library:**
![](https://github.com/domainzero/bookstack-dark-theme/blob/master/library.png)
**Page:**
![](https://github.com/domainzero/bookstack-dark-theme/blob/master/page.png)
**Editor:**
![](https://github.com/domainzero/bookstack-dark-theme/blob/master/editor.png)
