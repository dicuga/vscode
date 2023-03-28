# Configuraciones y notas de VSCode

## Instalaciones comunes
* [Visual Studio Code](https://code.visualstudio.com/)
* [Postman](https://www.postman.com/downloads/)
* [Node](https://nodejs.org/es/)
* (Opcional) [Mongo Compass](https://www.mongodb.com/try/download/compass)
* [Git](https://git-scm.com/)
```
git config --global user.name "Tu nombre"
git config --global user.email "Tu correo"
```
* [(Opcional) Yarn](https://yarnpkg.com/)
``` 
npm install --global yarn
```

## Configuraciones
* Desactivar Compact Folders:

    > En settings, `Ctrl + ,` => buscar Compact y "desmarcarlo"

* Bracket-pair-colorizer
    > En settings, `Ctrl + ,` => buscar Compact y "bracketpair" y marcarlo.
    >
    > Después, puedes dejar la configuración por defecto o poner la siguiente:
```
"bracket-pair-colorizer-2.colors": [
    "#fafafa",
    "#9F51B6",
    "#F7C244",
    "#F07850",
    "#9CDD29",
    "#0098FA"
],
```
* Tamaño Tab por lenguaje
```
1. Ctrl + Shift + p => Buscar: "Preferences: Configure Language Specific Settings"
2. Elegir el lenguaje: TypeScript, Python, ...
   En el buscador, cuando tengas selecionado el lenguaje, puedes añadir "tabsize" para ayudar a buscar (p.e.: @lang:python tabsize)
   
    - Para Python => "editor.tabSize": 4
    - Para HTML, TypeScript y JavaScript => "editor.tabSize": 2
```


## Extensiones comunes
* [Iconos](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
* [One Dark theme **Tema 2023**](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme)
* [Monokai night theme](https://marketplace.visualstudio.com/items?itemName=fabiospampinato.vscode-monokai-night)
* [Tokyo Night theme](https://marketplace.visualstudio.com/items?itemName=enkia.tokyo-night)
* [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)
* [Fuente FireCode](https://github.com/tonsky/FiraCode)
* [DotEnv](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)
* [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)

## Extensiones React/Next
* [NextJs Snippets](https://marketplace.visualstudio.com/items?itemName=willstakayama.vscode-nextjs-snippets)
* [ES7 React/Redux](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)
* [Simple React Snippets](https://marketplace.visualstudio.com/items?itemName=burkeholland.simple-react-snippets)
* [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
* [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)
* [TypeScript importer](https://marketplace.visualstudio.com/items?itemName=pmneo.tsimporter)
* [CSS Modules](https://marketplace.visualstudio.com/items?itemName=clinyong.vscode-css-modules)

## Extensiones Python
* [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)


