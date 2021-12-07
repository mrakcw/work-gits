# Some configs

## VS Code TOP Extensions 💦

### 🏆 My TOP plugins for VS Code workspace 🧰

* AMP Snippets - `catherinekorres.amp-snippets`
* AMP Validator - `amphtml.amphtml-validator`
* Auto Close Tag - `formulahendry.auto-close-tag`
* Auto Rename Tag - `formulahendry.auto-rename-tag`
* Auto Complete Tag - `formulahendry.auto-complete-tag`
* Beautify - `hookyqr.beautify`
* Better Comments - `aaron-bond.better-comments`
* Bracket Pair Colorizer - `coenraads.bracket-pair-colorizer`
* Code Time - `softwaredotcom.swdc-vscode`
* CSS Navigation - `pucelle.vscode-css-navigation`
* Css Compact - `jsonchou.css-compact`
* Expand Region - `letrieu.expand-region`
* HTML Format - `mohd-akram.vscode-html-format`
* HTML Snippets - `abusaidm.html-snippets`
* Wraps Selection - `bradgashler.htmltagwrap`
* Image Preview - `kisstkondoros.vscode-gutter-preview`
* IntelliSense CSS - `zignd.html-css-class-completion`
* JSON Script Tag - `sissel.json-script-tag`
* Kinda Monokai Dark - `braisc.kinda-monokai-dark`
* Live Server - `ritwickdey.liveserver`
* Live Server Preview - `negokaz.live-server-preview`
* Live Share - `ms-vsliveshare.vsliveshare`
* Luna Paint - `tyriar.luna-paint`
* Material Icon - `pkief.material-icon-theme`
* Minify All - `josee9988.minifyall `
* Polacode - `pnp.polacode`
* Prettier Formatter - `esbenp.prettier-vscode`
* Project Manager - `alefragnani.project-manager`
* RegExp Preview - `louiswt.regexp-preview`
* Language Pack - `ms-ceintl.vscode-language-pack-ru`
* SCSS Formatter - `sibiraj-s.vscode-scss-formatter`
* SCSS IntelliSense - `mrmlnc.vscode-scss`
* Settings Sync - `shan.code-settings-sync`
* Shortcut Menu Bar - `jerrygoyal.shortcut-menu-bar`
* Svg Preview - `simonsiefke.svg-preview`
* TinyPNG API - `andi1984.tinypng`
* IntelliCode - `visualstudioexptteam.vscodeintellicode`
* Translate text - `ddot.vscode-translate`
* Uncss - `aojiru-ts.vscode-uncss`
* W3C Web Validator - `celianriboulet.webvalidat`

> And other turned off plugins 🚧

## Config settings

> C:\Users\mrakc\AppData\Roaming\Code\User\settings.json

{
"workbench.startupEditor": "newUntitledFile",
"terminal.integrated.defaultProfile.windows": "Git Bash",
"workbench.statusBar.visible": true,
"window.menuBarVisibility": "visible",
"problems.showCurrentInStatus": false,
"liveshare.publishWorkspaceInfo": false,
"liveshare.codeLens": false,
"terminal.integrated.scrollback": 3000,
"terminal.integrated.minimumContrastRatio": 7,
"html.format.endWithNewline": true,
"css.completion.triggerPropertyValueCompletion": false,
"html-css-class-completion.enableEmmetSupport": true,
"workbench.colorTheme": "Kinda Monokai Dark",
"editor.maxTokenizationLineLength": 2000,
"editor.autoClosingBrackets": "always",
"editor.autoIndent": "brackets",
"editor.tabSize": 2,
"editor.detectIndentation": true,
"editor.hover.enabled": false,
"editor.mouseWheelZoom": true,
"emmet.triggerExpansionOnTab": true,
"emmet.includeLanguages": {"javascript": "javascriptreact","vue-html": "html","plaintext": "pug"},
"emmet.excludeLanguages": ["markdown"],
"workbench.editor.labelFormat": "short",
"html.format.indentInnerHtml": true,
"html.format.preserveNewLines": true,
"html.format.wrapLineLength": 0,
"liveSassCompile.settings.generateMap": true,
"liveSassCompile.settings.formats": [
	{"format": "expanded","autoprefix": "last 5 versions","extensionName": ".css","savePath": "/css"},
	{"format": "compressed","autoprefix": "last 5 versions","extensionName": ".min.css","savePath": "/css/min"}
],
"html.format.indentHandlebars": true,
"[html]": {"editor.defaultFormatter": "vscode.html-language-features"},
"[js]": {"editor.defaultFormatter": "beautify"},
"liveServer.settings.ChromeDebuggingAttachment": true,
"liveServer.settings.CustomBrowser": "chrome",
"liveServer.settings.AdvanceCustomBrowserCmdLine": "chrome",
"liveServer.settings.port": 5500,
"liveServer.settings.root": "/",
"liveServer.settings.host": "192.168.0.111",
"liveServer.settings.https": {"enable": false,"cert": "","key": "","passphrase": ""},
"liveServer.settings.useLocalIp": true,
"preloadCSSFiles": true,
"liveServer.settings.donotVerifyTags": true,
"liveServer.settings.donotShowInfoMsg": true,
"[css]": {"editor.defaultFormatter": "sibiraj-s.vscode-scss-formatter"},
"vscodeGoogleTranslate.preferredLanguage": "Ukrainian",
"googleTranslateExt.replaceText": false,
"explorer.confirmDelete": false,
"Find replace": true,
"Open command pallet": false,
"Save active file": true,
"editor.renderWhitespace": "all",
"workbench.activityBar.visible": true,
"material-icon-theme.activeIconPack": "vue",
"toggleFileEventLogging": true,
"css.lint.duplicateProperties": "warning",
"ecsstractor_port.comment_style": "css",
"emmet.showSuggestionsAsSnippets": true,
"grunt.autoDetect": "off",
"gulp.autoDetect": "off",
"htmltagwrap.autoDeselectClosingTag": false,
"debug.javascript.automaticallyTunnelRemoteServer": false,
"JSON-zain.json.autorefresh": true,
"tabnine.experimentalAutoImports": true,
"editor.renderControlCharacters": true,
"workbench.sideBar.location": "left",
"git.allowForcePush": true,
"git.alwaysSignOff": true,
"git.defaultCloneDirectory": "",
"git.postCommitCommand": "sync",
"git.showPushSuccessNotification": true,
"git.supportCancellation": true,
"githubIssues.ignoreCompletionTrigger": ["makefile","js"],
"git.enableSmartCommit": true,
"projectManager.groupList": true,
"projectManager.filterOnFullPath": true,
"git.autofetch": true,
"tinypng.apiKey": "",
"tinypng.forceOverwrite": true,
"git.confirmSync": false,
"auto-rename-tag.activationOnLanguage": ["html","xml","php","javascript"],
"google.drive.alertMissingCredentials": false,
"Toggle terminal": false,
"ShortcutMenuBar.formatDocumentWith": true,
"ShortcutMenuBar.toggleTerminal": false,
"editor.columnSelection": false,
"vscode-w3cvalidation.validator-token": "Sun, 10 Jan 2021 08:49:52 GMT",
"editor.formatOnSaveMode": "modifications",
"editor.defaultFormatter": "sibiraj-s.vscode-scss-formatter",
"explorer.confirmDragAndDrop": false,
"MinifyAll.disableJsonc": true,
"MinifyAll.disableJson": true,
"amphtml.validator.enabled": true,
"amphtml.validator.documentSelector": ["html","htm"	],
"amphtml.validator.keepIssuesAfterDocumentClose": true,
"debug.javascript.autoExpandGetters": true,
"microsoftTranslatorExt.appendText": false,
"remote.SSH.localServerDownload": "off",
"translateIO.toLanguage": "uk",
"workbench.editor.enablePreview": false,
"liveServer.settings.ignoreFiles": [".vscode/**","**/*.scss","**/*.sass","**/*.ts"],
"ShortcutMenuBar.findReplace": true,
"ShortcutMenuBar.cut": true,
"ShortcutMenuBar.formatWith": true,
"projectManager.git.baseFolders": ["..\\domains.loc\\GITHUB"],
"cSpell.enableFiletypes": ["!asciidoc"],
"editor.suggestSelection": "first",
"vsintellicode.modify.editor.suggestSelection": "disabled",
"sync.gist": "dc06b5e7cae0ee0cc6370c407da8f8f0",
"sync.autoUpload": true,
"sftp.debug": false,
"sftp.privateKeyPath": "",
"security.workspace.trust.untrustedFiles": "open",
"redhat.telemetry.enabled": true,
"editor.largeFileOptimizations": true,
"xml.symbols.maxItemsComputed": 5000,
"extensions.autoUpdate": "onlyEnabledExtensions",
"extensions.ignoreRecommendations": true,
"vscodeGoogleTranslate.host": "120.0.0.1",
"vscodeGoogleTranslate.port": "8080",
"vscodeGoogleTranslate.password": "password",
"vscodeGoogleTranslate.username": "admin",
"vscodeGoogleTranslate.hoverTranslations": true,
"vsintellicode.java.completionsEnabled": false,
"vsintellicode.features.python.deepLearning": "disabled",
"vsintellicode.python.completionsEnabled": false,
"emmet.showExpandedAbbreviation": "inMarkupAndStylesheetFilesOnly",
"workbench.iconTheme": "material-icon-theme",
"microsoftTranslatorExt.apiKey": "api.cognitive.microsofttranslator.com",
"microsoftTranslatorExt.firstLanguage":"uk",
"microsoftTranslatorExt.secondLanguage": "ru",
"sync.autoDownload": true,
"beautify.config": "jsbeautifyrc",
"files.simpleDialog.enable": true,
"editor.insertSpaces": false,
"php.validate.enable": false,
"workbench.editorAssociations": {
	"*.db": "default"
},
"liveshare.presence": true,
"window.zoomLevel": -2,
}

## Hot keys settings

> C:\Users\mrakc\AppData\Roaming\Code\User\keybindings.json

[
{"key": "ctrl+alt+t",
"command": "extension.translateText"},
{"key": "ctrl+numpad_decimal",
"command": "workbench.action.nextEditorInGroup"},
{"key": "ctrl+k ctrl+pagedown",
"command": "-workbench.action.nextEditorInGroup"},
{"key": "ctrl+'",
"command": "extension.MinifyAllSelectedText"},
{"key": "ctrl+alt+. ctrl+alt+m",
"command": "-extension.MinifyAllSelectedText"},
{"key": "ctrl+shift+/",
"command": "extension.compressFolder"},
{"key": "ctrl+pagedown ctrl+shift",
"command": "extension.liveServerPreview.open"},
{"key": "ctrl+alt+numpad8",
"command": "HookyQR.beautify"},
{"key": "alt+w",
"command": "editor.emmet.action.wrapWithAbbreviation"},
{"key": "alt+w",
"command": "-extension.htmlTagWrap",
"when": "editorTextFocus"}
]

## Sync settings

> C:\Users\mrakc\AppData\Roaming\Code\User\syncLocalSettings.json

{
"ignoreUploadFiles": [
"state.*",
"syncLocalSettings.json",
".DS_Store",
"sync.lock",
"projects.json",
"projects_cache_vscode.json",
"projects_cache_git.json",
"projects_cache_svn.json",
"gpm_projects.json",
"gpm-recentItems.json"
],
"ignoreUploadFolders": [
"workspaceStorage"
],
"ignoreExtensions": [],
"gistDescription": "Visual Studio Code Settings Sync Gist",
"version": 343,
"token": "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",
"downloadPublicGist": false,
"supportedFileExtensions": [
"json",
"code-snippets"
],
"openTokenLink": true,
"disableUpdateMessage": false,
"lastUpload": "2021-11-11T14:22:54.576Z",
"lastDownload": "2021-11-11T14:22:54.576Z",
"githubEnterpriseUrl": null,
"askGistDescription": false,
"customFiles": {},
"hostName": null,
"universalKeybindings": false,
"autoUploadDelay": 20
}
