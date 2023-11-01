"# Vue-Prototype-issue" 

Test case for an issue introduced in Vue version 3.2.46 which breaks compatibility with Prototype.js version 1.7.3

There are 2 files here - just open in your browser to see the issue.

working.html uses Vue version 3.2.45 and you can successfully see the "Hello vue!" message

broken.html uses Vue version 3.2.46 and you get no message on the page. The console says:

    Uncaught ReferenceError: _toDisplayString is not defined
    