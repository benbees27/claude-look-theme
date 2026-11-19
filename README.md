# paper-look-theme

A warm paper-notebook theme for Claude Code. Cream surfaces and dark-brown text by day, and lamp-lit paper with warm light text at night. It is built from the plugin-authoring example and its `makeColors` helper.

## Install

```
/plugin install paper-look-theme --marketplace benbees27/claude-look-theme
```

Type `y` to add the marketplace, then choose a scope. In the desktop app, click + next to the prompt box, then Plugins, Add marketplace with `benbees27/claude-look-theme`, then Add plugin.

## Notes

- The theme applies in the desktop app. Desktop ignores a theme that fails its contrast check, and a status line says why.
- The theme needs `make-colors.js` and `make-colors.d.ts` in its `hooks/` folder. They are not included here: copy them unchanged from the plugin-authoring skill folder.
