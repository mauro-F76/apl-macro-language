# Change Log
All notable changes to the "apl-macro-language" extension will be documented in this file.


## [1.2.0] - 2019.03.29

### Changed
- improved following code snippets:
    section:        creates new section;
    debugmsg:       show debug message;
    ~IF:            create IF statement structure;

### Added
- added new code snippets:  
    ~START:         subroutine definition;
    ~FOR:           loop statement structure (FOR);
    ~DO WHILE:      loop statement structure (DO WHILE);
    ~LOOP UNTIL:    loop statement structure (LOOP UNTIL)

## [1.1.0] - 2018.12.26

### Changed
- Improved folding (requires extension 'APL Language Features');
- Fixed highliting of tags ~START and ~END when they are preceded by spaces;
- Minor fixes for syntax highlinting.

### Added
- Possibility to create folding sections using tags ###section ###endsection
- Initial support for snippets:
    section: creates new section;
    ~IF: create IF statement structure;
    debugmsg: show debug message.
- Functions, Variables, PCS Output shown in code structure (requires extension 'APL Language Features');

## [1.0.0]
- Initial release
