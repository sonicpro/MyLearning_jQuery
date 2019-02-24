Example of how it is possible to use jQuery in non-browser environment (browser emulators?).
============================================================================================
Try to execute something like the following:


D:\Sources JavaScript\MyLearning_jQuery>node\
\> let factory = require('jquery');\
undefined\
\> let win = { document: {} };\
undefined\
\> let $ = factory(win);\
undefined\
\> win.$ === $;\
true\
\>
