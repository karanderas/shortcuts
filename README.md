# shortcuts

# VSCode Wordpress config
{
    "workbench.editor.highlightModifiedTabs": true,
    "workbench.colorTheme": "Material Theme Darker High Contrast",

    "window.zoomLevel": 0,

    "gitlens.advanced.messages": {
        "suppressLineUncommittedWarning": true
    },

    "terminal.integrated.rendererType": "dom",
    "terminal.integrated.fontFamily": "monospace",
    "terminal.integrated.shell.osx": "/usr/local/bin/zsh",

    "php.validate.executablePath": "/usr/bin/php",
    "php.validate.enable": true,
    "php.validate.run": "onSave",

    "php-docblocker.qualifyClassNames": true,
    "php-docblocker.extra": [
        "@author jcastelain",
        "@version WordPress 5.0.3",
        "@package understrap",
        "@subpackage dlbi-sodexo-theme"
    ],

    "phpformatter.composer": true,
    "phpformatter.arguments": [
        "--rules=@Wordpress"
    ],

    "phpcs.enable": true,
    "phpcs.standard": "Wordpress",
    "phpcs.executablePath": "/Applications/PHP_CodeSniffer/bin/phpcs",

    "phpcbf.enable": true,
    "phpcbf.executablePath": "/Applications/PHP_CodeSniffer/bin/phpcbf",
    "phpcbf.documentFormattingProvider": true,
    "phpcbf.standard": "Wordpress",
    "phpcbf.onsave": true,

    "javascript.format.insertSpaceAfterFunctionKeywordForAnonymousFunctions": false,
    "javascript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyBraces": false,
    "javascript.updateImportsOnFileMove.enabled": "always",

    "git.autofetch": true,

    "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",

    "diffEditor.renderSideBySide": false,

    "[php]": {
        "editor.defaultFormatter": "bmewburn.vscode-intelephense-client"
    },
    "[scss]": {
        "editor.defaultFormatter": "HookyQR.beautify"
    },

    "editor.suggestSelection": "first",
    "editor.smoothScrolling": true,
    "editor.cursorStyle": "block",
    "editor.acceptSuggestionOnEnter": "off",
    "editor.cursorBlinking": "smooth",
    "editor.fontLigatures": true,


    "files.autoSave": "onFocusChange",
    "files.trimFinalNewlines": true,
    "files.trimTrailingWhitespace": false,

    "explorer.sortOrder": "type",

    "eslint.autoFixOnSave": true,
}
