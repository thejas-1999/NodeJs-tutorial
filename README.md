# NodeJs-tutorial

#study about local module

1. In node.js, each file is amodule that isolated by default
2. To load a module into another file.We use require function
3. When index.js executed, the code in the module also excecuted
4. If the file we are requiring javascript file, we can also specifying extension and node.js will infer it on our behalf

#module export

#Immediately Invoked Function Expression(IIFE) in Node.js - Before a module's code is excuted. Node.js will wrap it with a function wrapper thet provides module scope
This saves us from having to worry conflicting variables or functions
there is propper encapsulation reusability is uneffected

#Module scope

1. Each loaded module in node.js is wrapped with an IIFE that provides private scoping of the code
2. IIFE alllows you to repeat variable or function names without any conflicts
