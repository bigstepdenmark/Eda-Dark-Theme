# Eda Dark Theme for Visual Studio Code
![Screenshot](screenshots/front-vsc.png)

Eda Dark is a simple workbench theme for [Visual Studio Code](https://code.visualstudio.com), and optimized for SCSS, HTML, JS, TS, Markdown, and PHP files.

The Font-family i used in screenshots is *"Menlo, Monaco, 'Courier New', monospace".*

---

## Installation
1. Open your Visual Studio Code App.
2. Go to Extensions from Activity Bar.
3. Search "Eda Dark Theme" and then click install. (remember to reload)

#### Recomended
1. Open your Visual Studio Code App.
2. Go to Preferences->Settings and just add this block to your user settings:
```json
"workbench.statusBar.visible": false,
"editor.minimap.enabled": false,
"workbench.editor.showTabs": false,
"workbench.sideBar.location": "left",
"editor.fontSize": 12,
"editor.lineHeight": 30,
```

3. If you prefer italic comments, just add this block to your user settings:
```json
"editor.tokenColorCustomizations": {
  "textMateRules": [
    {
      "scope": "comment, comment.block.html",
      "settings": {
        "fontStyle": "italic"
      }
    }
  ]
},
```

4. If you like the icons in the Sidebar
	- Go to Extensions from Activity Bar.
	- Search "VSCode Great Icons" by [*Emmanuel Béziat*](https://marketplace.visualstudio.com/items?itemName=emmanuelbeziat.vscode-great-icons), and then click install. (remember to reload)
	- Go to View->Command Palette...(shift+command+p)
	- Type and select "File Icon Theme".
	- Select "Simple Icons".

---

## Screenshots
![Screenshot](screenshots/sc.png)