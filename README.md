Aquí tienes un ejemplo de un archivo `README.md` adecuado para tu extensión de resaltado de sintaxis de GeneXus, con detalles sobre las versiones compatibles y una guía de uso:

---

# GeneXus Syntax Highlighter

**GeneXus Syntax Highlighter** is a Visual Studio Code extension that provides syntax highlighting support for **GeneXus versions 7.5, 8.0, and 9.0**. This extension helps developers working with GeneXus by offering accurate syntax coloring for code, variables, rules, and other elements commonly found in GeneXus projects.

## Features

- **Syntax Highlighting**: Provides colorized syntax for GeneXus code files, supporting versions 7.5, 8.0, and 9.0.
- **File Support**: Recognizes `.gx` file extensions as GeneXus source files.
- **Theme Integration**: Works with any VS Code theme, and includes a custom **GeneXus Dark** theme for an authentic GeneXus coding experience.

## Supported GeneXus Versions

This extension is designed to support the following versions of GeneXus:

- **GeneXus 7.5**
- **GeneXus 8.0**
- **GeneXus 9.0**

These versions were selected to cover legacy systems that still use these earlier GeneXus versions. Syntax elements specific to these versions, such as keywords, variables, and predefined functions, are included.

## Installation

To install **GeneXus Syntax Highlighter**, follow these steps:

1. **Open Visual Studio Code**.
2. Go to the **Extensions** view by clicking on the Extensions icon in the Activity Bar or by pressing `Ctrl+Shift+X`.
3. Search for **GeneXus Syntax Highlighter**.
4. Click **Install**.

Alternatively, you can manually install the extension by downloading it from the [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/) or by cloning the repository and using the `vsce` CLI to package and install it.

## Usage

Once installed, this extension will automatically apply syntax highlighting to any `.gx` file opened in Visual Studio Code.

### Example

Here’s an example of a GeneXus code snippet that will be highlighted by this extension:

```genexus
For Each
   Where PgmName = &PgmName
   &Total = &Total + 1
EndFor

If &Total > 0
   PrintReport(&ReportName)
EndIf
```

In this snippet, **keywords** like `For Each`, `Where`, `If`, and `EndFor` will be highlighted according to the active theme.

## Contributing

Contributions are welcome! If you'd like to contribute to the development of this extension, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Submit a pull request.

## Issues

If you find any issues or bugs, feel free to report them by opening an issue in the [GitHub repository](https://github.com/your-repo-url).

## License

This extension is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

### Author

Developed by **Rodrigo Pistón**.

---