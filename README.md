# My VS Code Setup

## Extensions

### HTML Tools

* **[Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)** - Automatically add HTML/XML close tag, same as Visual Studio IDE or Sublime Text.
  * **NOTE:** I no longer use this extension as the functionality is built in to VS Code these days. Instead, I use these settings to support auto-closing tags in HTML and JSX/TSX:
* **[Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)** – Automatically rename paired HTML/XML tag
  * **NOTE:** While this feature was added to VS Code for HTML via the `editor.linkedEditing` setting, it is not yet supported for JSX/TSX. [Tracking this issue](https://github.com/microsoft/vscode/issues/85707) and I plan on dropping this extension once it's finally supported natively!

### CSS Tools

* **[Intellisense for CSS class names in HTML](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion)** – Could really use a snappier name, but you get the picture.
  * **NOTE:** While handy, I no longer use this extension because it's just a bit too harsh on the CPU.

* **[SCSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-scss)** – Advanced autocompletion and refactoring support for SCSS.

### JavaScript/TypeScript Tools

* **[JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)** – Code snippets for JavaScript in ES6 syntax.
* **[ES7 React/Redux/GraphQL/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)** – Extensions for React, React-Native and Redux in JS/TS with ES7+ syntax. Customizable. Built-in integration with prettier.
* **[CSS-in-JS](https://marketplace.visualstudio.com/items?itemName=paulmolluzzo.convert-css-in-js)** – Auto-complete CSS-in-JS. Also let's you quickly toggle between standard CSS and JS object-syntax, a huge time saver!
* **[Document This](https://marketplace.visualstudio.com/items?itemName=oouo-diogo-perdigao.docthis)** – Automatically generates detailed JSDoc comments in TypeScript and JavaScript files.
* **[npm intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)** – Autocomplete NPM modules in `import`/`require` statements.
* **[TypeScript Importer](https://marketplace.visualstudio.com/items?itemName=pmneo.tsimporter)** – Autocomplete and auto-import types from `node_modules` or elsewhere from your project.
* **[vscode-styled-components](https://marketplace.visualstudio.com/items?itemName=styled-components.vscode-styled-components)** – Syntax highlighting and formatting for Styled Components (though it works with Emotion and other libs that use the same `styled` API).

### Git Tools

* **[Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)** – View git log, file history, compare branches or commits.
* **[GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)** – Loads of goodies here if you prefer to visualize Git history, step through commits, a lots more. One of my favorite extensions on the list.
* **[gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore)** – Language support for `.gitignore` files + generation from templates based on the project type.
* **[GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)** – Your AI pair programmer.
* **[GitHub Pull Requests and Issues](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)** – Pull Request and Issue Provider for GitHub.

### Markdown Tools

* **[Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)** – Lots of features to simplify writing markdown. Click the link if you're curious because they keep adding more!
* **[Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)** – Real-time preview your markdown in a side panel while you write. I'm using it while I write this very document OMG.
* **[Markdown Table Formatter](https://marketplace.visualstudio.com/items?itemName=fcrespo82.markdown-table-formatter)** - A (not so) simple markdown plugin to format tables and other table related features.

### Linting and Formatting Tools

* **[EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)** – Infer formatting settings as you type from your `.editorconfig`. I generally let Prettier handle formatting, but it's nice to see some formatting as you type, especially if I'm writing code for a demo or workshop.
* **[ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)** – Linter for JavaScript and TypeScript.
* **[Stylelint](https://marketplace.visualstudio.com/items?itemName=stylelint.vscode-stylelint)** – Linter for CSS, SCSS, SASS.
* **[Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)** – Code formatter using prettier.

### Theme and Icons

* **[Atom One Dark Theme](https://marketplace.visualstudio.com/items?itemName=akamud.vscode-theme-onedark)** – VSCode Theme based on Atom's One Dark theme.
* **[Ayu](https://marketplace.visualstudio.com/items?itemName=teabyii.ayu)** – A simple theme with bright colors and comes in three versions — dark, light and mirage for all day long comfortable work.
* **[Dracula Official](https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula)** – Official Dracula Theme. A dark theme for many editors, shells, and more.
* **[Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)** – Material Design Icons for Visual Studio Code.
* **[vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)** – Icons for Visual Studio Code.
* **[VSCode Great Icons](https://marketplace.visualstudio.com/items?itemName=emmanuelbeziat.vscode-great-icons)** – A big pack of icons (200+) for your files.

### General Productivity Tools

* **[advanced-new-file](https://marketplace.visualstudio.com/items?itemName=patbenatar.advanced-new-file)** – Shortcut to create new files by path.
* **[change-case](https://marketplace.visualstudio.com/items?itemName=wmaurer.change-case)** – Because sometimes ya gotta do `whatUpHomie` instead of `what_up_homie`.
* **[Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)** – Launch a development local Server with live reload feature for static & dynamic pages.
* **[Quokka.js](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode)** – JavaScript and TypeScript playground in your editor.
* **[Tabnine AI](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode)** – JavaScript, Python, Java, Typescript & all other languages - AI Code completion plugin. Tabnine makes developers more productive by auto-completing their code.
* **[File Utils](https://marketplace.visualstudio.com/items?itemName=sleistner.vscode-fileutils)** – Shortcuts to quickly rename/duplicate/whatever the current working file.
* **[Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)** – Autocomplete for your filenames.
* **[Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager)** – Quickly access and switch between projects. Never leave home without it.
* **[TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)** - highlight TODOs, FIXMEs, and any keywords, annotations...
* **[Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)** - Improve your code commenting by annotating with alert, informational, TODOs, and more!
* **[Comment Anchors](https://marketplace.visualstudio.com/items?itemName=ExodiusStudios.comment-anchors)** - Place anchor tags within comments for easy file and workspace navigation.
* **[Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks)** - Mark lines and jump to them.
* **[indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)** - Makes indentation easier to read.
* **[Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)** - Highlight web colors in your editor.
* **[Image preview](https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-gutter-preview)** - Shows image preview in the gutter and on hover.
* **[Wrap Selection](https://marketplace.visualstudio.com/items?itemName=konstantin.wrapSelection)** – Quickly throw a group of items into brackets, quotes, whatevs.
* **[DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)** – Syntax support for your `.env` files.
* **[REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)** – REST Client for Visual Studio Code.
* **[GraphQL](https://marketplace.visualstudio.com/items?itemName=GraphQL.vscode-graphql)** – GraphQL LSP extension that adds autocompletion, validation, go to definition, hover, outline and more.
* **[Rewrap](https://marketplace.visualstudio.com/items?itemName=stkb.rewrap)** – Hard word wrapping for comments and other text at a given column.
* **[Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)** – Display import/require package size in the editor.
* **[sort-imports](https://marketplace.visualstudio.com/items?itemName=amatiasq.sort-imports)** – Sort ES6 imports automatically.

## My Settings

```json
{
  "breadcrumbs.enabled": true,
  "editor.fontFamily": "Fira Code,'Cascadia Code', Consolas, 'Courier New', monospace",
  "editor.fontLigatures": true,
  "editor.suggestSelection": "first",
  "editor.tabSize": 2,
  "editor.wordWrap": "wordWrapColumn",
  "editor.wordWrapColumn": 100,
  "editor.wrappingIndent": "same",
  "editor.inlineSuggest.enabled": true,
  "editor.renderWhitespace": "none",
  "editor.minimap.enabled": true,
  "editor.renderControlCharacters": false,
  "terminal.integrated.fontSize": 16,
  "terminal.integrated.lineHeight": 1.25,
  "terminal.integrated.defaultProfile.windows": "Git Bash",
  "html.suggest.html5": true,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact",
    "typescript": "typescriptreact",
    "njk": "html",
    "nunjucks": "html",
    "twig": "html"
  },
  /// FORMAT
  // Set the default
  // "editor.formatOnSave": false,
  "editor.formatOnSave": true,
  "editor.formatOnPaste": false,
  "editor.formatOnType": false,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  // Enable per-language
  "[markdown]": {
    "editor.defaultFormatter": "yzhang.markdown-all-in-one",
    "files.trimTrailingWhitespace": false
  },
  "[json]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },
  "editor.codeActionsOnSave": {
    // Auto Fix for all
    "source.fixAll": true,
    // For ESLint
    "source.fixAll.eslint": true,
    // For TSLint
    "source.fixAll.tslint": true,
    // For Stylelint
    "source.fixAll.stylelint": true
  },
  "eslint.validate": [
    "javascript",
    "javascriptreact"
  ],
  "css.validate": false,
  "less.validate": false,
  "scss.validate": false,
  "stylelint.validate": [
    // https://github.com/stylelint/vscode-stylelint
    "css",
    "html",
    "less",
    "markdown",
    "postcss",
    "sass",
    "scss",
    "source.css.styled",
    "styled-css",
    "sugarss",
    "xml",
    "xsl"
  ],
  "markdownlint.config": {
    "default": true,
    "MD001": false,
    "MD010": false,
    "MD024": false,
    "MD025": false
  },
  "files.autoSave": "afterDelay",
  "files.trimTrailingWhitespace": true,
  "files.watcherExclude": {
    "**/.git/**": true,
    "**/.svn": true,
    "**/.hg": true,
    "**/.DS_Store": true,
    "**/bower_components/**": true,
    "**/jspm_packages/**": true,
    "**/node_modules/**": true
  },
  "files.exclude": {
    "**/.DS_Store": true,
    "**/.git": true,
    "**/.hg": true,
    "**/.svn": true,
    "**/CVS": true,
    "node_modules": true
  },
  "files.associations": {
    ".sequelizerc": "javascript",
    ".stylelintrc": "json",
    ".prettierrc": "json"
  },
  "gitlens.currentLine.scrollable": false,
  "gitlens.currentLine.enabled": false,
  // config gitSemanticCommit
  "gitSemanticCommit.types": [
    {
      "type": "📦 build",
      "description": "Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)"
    },
    {
      "type": "🤖 ci",
      "description": "Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs)"
    },
    {
      "type": "📝 docs",
      "description": "Documentation only changes"
    },
    {
      "type": "✨ feat",
      "description": "A new feature"
    },
    {
      "type": "🐛 fix",
      "description": "A bug fix"
    },
    {
      "type": "🎉 init",
      "description": "Initial commit"
    },
    {
      "type": "⚡ perf",
      "description": "A code change that improves performance"
    },
    {
      "type": "♻️ refactor",
      "description": "A code change that neither fixes a bug nor adds a feature"
    },
    {
      "type": "⏪ revert",
      "description": "Reverting changes"
    },
    {
      "type": "💄 style",
      "description": "Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)"
    },
    {
      "type": "✅ test",
      "description": "Adding missing tests or correcting existing tests"
    }
  ],
  "githubPullRequests.createOnPublishBranch": "never",
  "tabnine.experimentalAutoImports": true,
  // live-sass
  "liveServer.settings.donotVerifyTags": true,
  "liveServer.settings.donotShowInfoMsg": true,
  "liveSassCompile.settings.formats": [
    {
      "format": "compressed",
      "extensionName": ".min.css",
      "savePath": "/dist/css"
    }
  ],
  "cSpell.enableFiletypes": [
    "!html"
  ],
  "cSpell.userWords": [
    "stylelint"
  ],
  // Specify paths/files to ignore.
  "cSpell.ignorePaths": [
    "node_modules", // this will ignore anything the node_modules directory
    "**/node_modules", // the same for this one
    "**/node_modules/**", // the same for this one
    "node_modules/**", // Doesn't currently work due to how the current working directory is determined.
    "vscode-extension", //
    ".git", // Ignore the .git directory
    "*.dll", // Ignore all .dll files.
    "**/*.dll", // Ignore all .dll files
    ".vscode/**.json",
    "**.md"
  ],
  "editor.quickSuggestions": {
    "strings": true
  },
  "rewrap.wrappingColumn": 80,
  "todohighlight.exclude": [
    "**/vendor/**",
    "**/node_modules/**",
    "**/dist/**",
    "**/bower_components/**",
    "**/build/**",
    "**/.vscode/**",
    "**/.github/**",
    "**/_output/**",
    "**/*.min.*",
    "**/*.map"
  ],
  "typescript.format.enable": false,
  "typescript.tsdk": "node_modules/typescript/lib",
  "typescript.validate.enable": true,
  "typescript.tsserver.log": "verbose",
  "javascript.suggest.autoImports": true,
  "typescript.suggest.autoImports": true,
  "workbench.activityBar.visible": true,
  "workbench.editor.showIcons": false,
  "workbench.statusBar.visible": true,
  "workbench.colorTheme": "Dracula Soft",
  "workbench.iconTheme": "material-icon-theme",
  "javascript.updateImportsOnFileMove.enabled": "always",
  "typescript.updateImportsOnFileMove.enabled": "never",
  "editor.accessibilitySupport": "off",
  "todohighlight.isEnable": false,
}
```
