
[meteor-gitignore](https://gist.github.com/iMunshi/d69dba7b89eff38d68cd)
<br/>
Atom package: [markdown-preview-plus ](https://atom.io/packages/markdown-preview-plus)
* Ctrl+Shift+m toggles preview mode

# Meteor React Project: soccer-app
### Atom packages
* language-babel
* language-javascript-jsx
* meteor-api
* meteor-snippets
### Chrome Extensions
* Meteor DevTools
	Apt-Cmd-I

### Installation
* install node from nodes.org
* meteor.com
  * curl https://install.meteor.com/ | sh
```
node -v
meteor --help
meteor --version
```
### Create a new app
```
meteor create soccer-app
cd soccer-app
meteor
npm install
```
View meteor app: http://localhost:3000/
```
meteor npm install --save react react-dom
```
### Show hidden files on mac
```
google “make hidden files visible mac”
```
in terminal:
```
defaults write com.apple.finder AppleShowAllFiles YES
```
http://ianlunn.co.uk/articles/quickly-showhide-hidden-files-mac-os-x-mavericks/
on the Finder icon in the application tray
	Opt+Right Click to finder -> relaunch
### Checkout new app
```
cd ~/soccer-app
atom .
```
Cmd \ toggles the file tree in atom
### Meteor configuration
```
.meteor/local/release
  METEOR@1.4.1.3
.meteor/local/packages
```
### Use Materialize UI
```
meteor npm install --save material-ui react-tap-event-plugin
```
http://www.material-ui.com/#/
https://www.npmjs.com/package/material-ui
https://github.com/google/material-design-icons
```
<link href="https://fonts.googleapis.com/icon?family=Material+Icons"
      rel="stylesheet">
```
	for main.html
fonts.google.com
	search for roboto font
```
	<link href="https://fonts.googleapis.com/css?family=Roboto" rel="stylesheet">

```
http://materializecss.com/
http://materializecss.com/getting-started.html
```
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/0.100.1/css/materialize.min.css">
```
[Meteor Developer Docs](https://docs.meteor.com/api/core.html#Meteor-startup)
