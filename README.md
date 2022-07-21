# PythonDebugging

Debugging

    No one writes perfect code, so bugs are inevitable.
    
    So what are some strategies for debugging?

Linting
    
    When writing code, some IDEs have a built-in linter, which will highlight bugs in your code
    and will give you information about the error when you hover over the highlighted line of
    code
    
IDE/Editor

    Always use some kind of IDE or Editor, such as PyCharm, as they have countless tools that are
    there to help you detect errors, remain code compliant, and create clean and efficient code
    
Learn to read errors

    Interpreters will error out and display an error message relevant to the kind of error event
    that occured. For example, if you for to include a colon in an if-statement, you will get
    a syntax error. Based off of the error message, you should be able to quickly understand
    and find the error in your code.
    
Learn to use your IDE's debugger

    For PyCharm, the debugger is PDB. It is an interactive debugger that can be accessed by 
    importing pdb: import pdb.
    
    The most useful object of the pdb module is the pdb.set_trace() method.
    
    It allows you to dive into your code and interact with it and see what is happening behind
    the scenes.
    
    
