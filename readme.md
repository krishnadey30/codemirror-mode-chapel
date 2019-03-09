# codemirror-mode-chapel
> A CodeMirror mode for the Chapel language

## Installation

```console
npm install codemirror codemirror-mode-chapel --save
```

## Usage

1. Include `codemirror-mode-chapel` into your project.

    ```html
    <!-- You can simply add codemirror-mode-chapel/index.js as a script tag: -->
    <script src="js/codemirror.js"></script>
    <script src="js/codemirror-mode-chapel/index.js"></script>
    ```

    or

    ```js
    // If you're using frontend build tools like Webpack and Babel,
    // you can simply import the module and register the mode:
    import CodeMirror from 'codemirror'
    import registerChapelMode from 'codemirror-mode-chapel'
    ```

1. Set 'text/chapel' as the mode when creating the CodeMirror editor.

    ```js
    CodeMirror.fromTextArea(document.getElementById('code'), { mode: 'text/chapel' })
    ```

## License

ISC - See [LICENSE][licenseUrl]

&nbsp;

Created by [Krishna Kumar Dey](https://github.com/krishnadey30/)

