# Atomize
[![Version](https://vsmarketplacebadge.apphb.com/version/emroussel.atomize-atom-one-dark-theme.svg)](https://marketplace.visualstudio.com/items?itemName=emroussel.atomize-atom-one-dark-theme)

A detailed and accurate Atom One Dark Theme

<img src="https://raw.githubusercontent.com/emroussel/atomize/master/images/screenshot.png" alt="Screenshot of VS Code with Atomize" />

To get the icons in the screenshot above and an experience closer to Atom, check out my [Atom Icons theme](https://github.com/emroussel/atom-icons).

## Contribution
I have mostly used this theme with JavaScript and other web technologies.

If you'd like me to add support for other languages, or notice a bug/discrepancy with Atom's One Dark theme, feel free to open an issue or pull request on this repo.

## Motivation
I love the UI and UX of Atom as well as the speed and reliability of VS Code. After looking for a while, I couldn't find any VS Code theme that accurately replicated Atom's One Dark UI, so I made this one.

## Next steps
Here are some settings I use to make VS Code more minimalistic, so that I can focus on what's important. It also makes the experience more similar to Atom.

```json
{
  "editor.cursorBlinking": "blink",
  "editor.hideCursorInOverviewRuler": true,
  "editor.minimap.enabled": false,
  "editor.occurrencesHighlight": false,
  "editor.renderIndentGuides": false,
  "editor.roundedSelection": false,
  "editor.scrollBeyondLastLine": false,
  "explorer.decorations.colors": false,
  "explorer.openEditors.visible": 0,
  "window.zoomLevel": 0,
  "workbench.activityBar.visible": false,
  "workbench.editor.showIcons": false,
  "workbench.startupEditor": "none",
  "workbench.statusBar.feedback.visible": false
}
```

**Note:** This will hide the activity bar, so you will need to memorize a few shortcuts (they will be different if you changed the defaults):
- Show explorer: ⇧+ ⌘ + E
- Show search: ⇧+ ⌘ + F
- Show extensions: ⇧+ ⌘ + X

I also use [Subtle Match Brackets](https://marketplace.visualstudio.com/items?itemName=rafamel.subtle-brackets) instead of the default bracket matcher to get a better experience:
```json
{
  "editor.matchBrackets": false,
  "subtleBrackets.style": {
    "borderWidth": "1px",
    "borderColor": "#528BFF"
  },
}
```

And if you would like keyword highlighting in comments, I use [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight) with these settings to get Atom's colors:
```json
{
  "todohighlight.keywords": [
    {
      "text": "TODO:",
      "color": "#C678DD",
      "backgroundColor": "transparent"
    },
    {
      "text": "NOTE:",
      "color": "#C678DD",
      "backgroundColor": "transparent"
    },
    {
      "text": "FIXME:",
      "color": "#C678DD",
      "backgroundColor": "transparent"
    }
  ]
}
```

## Credits
This theme is heavily inspired from Atom's [One Dark Syntax theme](https://github.com/atom/one-dark-syntax).

## License
MIT