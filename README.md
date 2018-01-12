# SharePoint Framework Snippets

This extension for Visual Studio Code adds snippets for SharePoint Framework solution development. It contains snippets for working in:
- JavaScript (resource files)
- React
- SASS (SCSS)
- TypeScript

![Extension usage](./assets/spfx-snippet-demo.gif)

See the [changelog](./CHANGELOG.md) for the latest changes.

## Usage

Type part of a snippet and press `enter`, the code will then be added into the file. Or press `Ctrl`+`Space` (Windows, Linux) or `Cmd`+`Space` (macOS) to activate snippets from within the editor.

### React

| Snippet | Purpose |
|---------|---------|
| `spfx-rcc` | Creates a new React Component. |
| `spfx-rcc-state` | Creates a new React Component with state initialization. |
| `spfx-con` | Adds a React `constructor` method. |
| `spfx-ist` | Initializes the React state. |
| `spfx-sst` | Adds the `setState` block. |
| `spfx-ucst` | Adds the `setState` block to correctly update the state based on previous value. |
| `spfx-cwm` | Add `componentWillMount` method which is invoked before the component mounting happens. |
| `spfx-cdm` | Add `componentDidMount` method which is invoked after the component mounting and rendering happened. |
| `spfx-cwu` | Adds `componentWillUpdate` method which is invoked just before rendering when new props or state are retrieved. |
| `spfx-cwu` | Adds `componentDidUpdate` method which is invoked just after rendering when new props or state are retrieved. |

### TypeScript

| Snippet | Purpose |
|---------|---------|
| `spfx-locale-ts` | Defines the content to create a new localization definition file. |
| `spfx-wpinit` | Defines the web part `onInit` method. |
| `spfx-render-elm` | Adds the code required to create and render a React component. |

### TypeScript & React

| Snippet | Purpose |
|---------|---------|
| `spfx-spget` | Adds SPHttpClient get request. |

### SASS (scss)

| Snippet | Purpose |
|---------|---------|
| `spfx-fabcore` | Includes the Office UI Fabric Core styles into your SASS file. |
| `spfx-fabreact` | Includes the core styles from the Office UI Fabric React package into your SASS file. |

### JavaScript

| Snippet | Purpose |
|---------|---------|
| `spfx-locale-js` | Defines the content to create a new localization definition file. |

## Feedback and snippet ideas

Feedback an snippet ideas are always welcome. Please submit them via creating an issue in the repository: [issue list](https://github.com/estruyf/vscode-spfx-snippets/issues).