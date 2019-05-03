# AToolSoftware Macro Language (APL)

Syntax highlighting for ATool Software PARTNER/ASPAN, MARS and TOOLCAM Macro and Post-Processor programming language (APL) `.mac`, `.pcs` files.<br />
To execute APL Macros it is necessary a valid installation of PARTNER/ASPAN, TOOLCAM (with macro additional module) or MARS.

NOTE:
This is a personal project, to be considered as an unofficial extension and is not directly supported by ATool Software.


Resources:<br />
[APL Language Reference](https://www.maurofecarotta.it/vscode/extensions/resources/apl-language-ref.pdf)<br />
[APL Macro Lessons](https://www.maurofecarotta.it/vscode/extensions/resources/apl-macro-lessons.pdf)<br />
<br />

![screenshot](https://www.maurofecarotta.it/vscode/extensions/images/atoolsoftware-macro-preview.png)

## Links

* [AToolSoftware.it](http://www.atoolsoftware.it/)

## Release Notes

### 1.0.0

Initial release

### 1.2.1
- minor changes to package descritpion;
- updated package devDependencies;

### 1.2.0
- Added more code snippets and improved existing ones:
    section:        creates new section;
    debugmsg:       show debug message;
    ~IF:            create IF statement structure;
    ~START:         subroutine definition;
    ~FOR:           loop statement structure (FOR);
    ~DO WHILE:      loop statement structure (DO WHILE);
    ~LOOP UNTIL:    loop statement structure (LOOP UNTIL)

### 1.1.0
(requires extension 'APL Language Features')
- Improved folding
- Possibility to create folding sections using tags ###section ###endsection
- Fixed highliting of tags ~START and ~END when they are preceded by spaces
- Initial support for snippets:
    section:        creates new section;
    debugmsg:       show debug message;
    ~IF:            create IF statement structure;
- Minor fixes for syntax highlinting.


-----------------------------------------------------------------------------------------------------------

