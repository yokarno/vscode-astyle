## Release Notes

### 0.1

- Initial release
- Add ReadMe

### 0.2

- Add status bar

### 0.3

- Add option `astyle.astylerc` for lookup astylerc path. (which is same as --options=`path`)

### 0.4

- Add option `astyle.cmd_options` for passing options to astyle command line.

### 0.5 

- ${workspaceRoot} variable substitution is available for `astyle.cmd_options`, `astyle.executable` options

### 0.6

- Add option `astyle.additional_languages` for extending supported languages. For example, you can add "haxe" language to use astyle as formatter. (make sure you check astyle can support the language)
