# vscode config

```json
{
	// Main editor settings
	"workbench.settings.editor": "json",
	"window.openFilesInNewWindow": "off",
	"window.commandCenter": false,
	"workbench.layoutControl.enabled": false,
	"workbench.activityBar.location": "top",
	"editor.insertSpaces": false,
	"editor.smoothScrolling": true,
	"editor.minimap.enabled": false,
	"editor.detectIndentation": true,
	"editor.suggestSelection": "first",
	"editor.linkedEditing": true,
	"editor.renderControlCharacters": false,
	"editor.quickSuggestionsDelay": 0,
	"html.completion.attributeDefaultValue": "singlequotes",
	"editor.bracketPairColorization.enabled": false,
	"editor.glyphMargin": false,
	"editor.scrollbar.horizontal": "hidden",
	"editor.scrollbar.vertical": "hidden",
	"workbench.productIconTheme": "fluent-icons",
	"window.density.editorTabHeight": "compact",
	"editor.accessibilitySupport": "off",
	"workbench.editor.tabSizing": "shrink",
	"files.exclude": {
		"**/.git": true,
		"**/.svn": true,
		"**/.hg": true,
		"**/CVS": true,
		"**/.DS_Store": true,
		"**/Thumbs.db": true,
		"**/node_modules": true
	},

	// Cursor
	"editor.cursorBlinking": "expand",
	"editor.cursorStyle": "line",
	"editor.cursorSmoothCaretAnimation": "off",

	// Editor settings
	"editor.fontSize": 16,
	"editor.lineHeight": 24,
	"editor.tabSize": 2,
	"editor.fontFamily": "JetBrains Mono, monospace",
	"editor.fontLigatures": true,
	"editor.folding": false,
	"editor.scrollBeyondLastLine": true,
	"editor.multiCursorModifier": "ctrlCmd",
	"explorer.confirmDelete": false,
	"explorer.compactFolders": false,
	"explorer.confirmDragAndDrop": false,

	// Terminal settings
	"terminal.integrated.fontFamily": "FiraCode Nerd Font Mono, monospace",
	"terminal.integrated.fontSize": 14,
	"terminal.integrated.tabs.enabled": false,

	// Auto close tags
	"html.autoClosingTags": true,
	"javascript.autoClosingTags": true,
	"typescript.autoClosingTags": true,

	// Text wrapping
	"editor.wordWrap": "bounded",
	"editor.wrappingIndent": "same",
	"editor.wordWrapColumn": 80,

	// Debug
	"debug.toolBarLocation": "hidden",
	"debug.focusWindowOnBreak": false,
	"debug.showInlineBreakpointCandidates": false,
	"debug.showBreakpointsInOverviewRuler": false,

	// Prettier
	"prettier.semi": false,
	"prettier.useTabs": true,
	"editor.formatOnSave": true,
	"prettier.singleQuote": true,
	"prettier.jsxSingleQuote": true,
	"editor.defaultFormatter": "esbenp.prettier-vscode",
	"editor.inlineSuggest.enabled": true,
	"[json]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[html]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[javascript]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[javascriptreact]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[typescript]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[typescriptreact]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[jsonc]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},

	// JS & TS
	"javascript.updateImportsOnFileMove.enabled": "always",
	"typescript.updateImportsOnFileMove.enabled": "always",
	"javascript.preferences.quoteStyle": "single",
	"typescript.preferences.quoteStyle": "single",
	"javascript.format.semicolons": "remove",
	"typescript.format.semicolons": "remove",

	// Breadcrumbs
	"breadcrumbs.enabled": false,

	// Other
	"security.workspace.trust.untrustedFiles": "open",
	"workbench.colorTheme": "After Dark",
	"workbench.iconTheme": "icons",
	"window.zoomLevel": 1,
	"workbench.startupEditor": "none"
}
```

## VSCODE PLUGINS

- After Dark (Theme)
- Backticks (Extension)
- ES7+ React/Redux/React-Native snippets (Extension)
- Fluent Icons (Icon theme)
- Icons (Icon Theme)
- JetBrains Icon Theme (Icon Theme)
- Prettier - Code Formatter (Extension)
- Svg Preview (Extension)
- TODO Highlight (Extension)
