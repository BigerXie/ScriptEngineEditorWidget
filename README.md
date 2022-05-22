# ScriptEngineEditorWidget
An extension to edit and test external scripts (JavaScript and Python).

## Description
This extension allows to edit and test external scripts (JavaScript and Python).

To show the editor the extension uses the [Monaco Editor](https://microsoft.github.io/monaco-editor/), to test the code the extension uses the [ScriptEngineResource](https://github.com/ThingWorx-Extensions/ScriptEngineResource).

## Properties
- debugMode - BOOLEAN (default = false): if set to true it sends to the browser's JS console a set of information useful for debugging the widget
- language - STRING (default = 'python'): the script language (options: python, javascript)
- theme - STRING (default = 'vs'): the theme editor (options: vs, vs-dark, hc-black)
- parameters - JSON (default = {}): the parameters, represented as a JSON object containing numbers, strings, booleans and arrays of numbers, strings, booleans and arrays (recursively)
- resultParameter - STRING ('result'): parameter name of the result value
- code - STRING (no default value): the scripting code

## Dependencies
- ScriptEngineResource - [link](https://github.com/ThingWorx-Extensions/ScriptEngineResource)
- Monaco Editor - [link](https://microsoft.github.io/monaco-editor/)

## Donate
If you would like to support the development of this and/or other extensions, consider making a [donation](https://www.paypal.com/donate/?business=HCDX9BAEYDF4C&no_recurring=0&currency_code=EUR).
