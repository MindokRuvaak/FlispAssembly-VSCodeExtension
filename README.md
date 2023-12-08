# FlispAssembly-VSCodeExtension
Creating a VSCode extension for writing assembly code for FLIS-Processors. 

I don't like the DigiFlisp program and would rather write the .sflisp, .fmem and .fcs files in text files than use the DigiFlisp tools. However this project will only concern the .sflisp files.  

Since I couldn't find a VSCode extension I thought "why not create one?" and here we are. 


Currently just following the tutorial at https://code.visualstudio.com/api



TODO: 

    Syntax highlighting
    Snippet completion
    Bracket matching
    Bracket autoclosing
    Bracket autosurrounding
    Comment toggling
    Auto indentation
    Folding (by markers)

AND: 

    Hover information (vscode.languages.registerHoverProvider)
    Auto completion (vscode.languages.registerCompletionItemProvider)
    Jump to definition (vscode.languages.registerDefinitionProvider)
    Error checking
    Formatting
    Refactoring
    Folding
