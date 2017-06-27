# do-you-want-to-be-a-web-developer
Do you want to be a web developer?
### [Javascript]
* ##### Core language features
  > Objects
  > Reserved words
  > Operators
  > Statements
  > Global properties and methods
* Function scopes, variable scopes and closure
  > In JavaScript, objects and functions are also variables.
  > In JavaScript, scope is the set of variables, objects, and functions you have access to.
  > JavaScript has function scope: The scope changes inside functions.
  > A variable declared outside a function, becomes GLOBAL.
  > A global variable has global scope: All scripts and functions on a web page can access it. 
* Most common design patterns in JS ( module definition, singleton, pub/sub, etc )
  > Module
  > Prototype
  > Observer
  > Singleton
* Callbacks, promises, eventEmmiter, continuation-passing style ( CPS ) 
  > **A callback function**, also known as a higher-order function, is a function that is passed to another function (let’s call this other function “otherFunction”) as a parameter, and the callback function is called (or executed) inside the otherFunction. A callback function is essentially a pattern (an established solution to a common problem), and therefore, the use of a callback function is also known as a callback pattern.
  > **The Promise object** represents the eventual completion (or failure) of an asynchronous
operation, and its resulting value.
  > **All objects that emit events are instances of the EventEmitter class.** These objects expose an eventEmitter.on() function that allows one or more functions to be attached to named events emitted by the object. Typically, event names are camel-cased strings but any valid JavaScript property key can be used.
  > If a language supports continuations, the programmer can add control constructs like exceptions, backtracking, threads and generators.
Sadly, many explanations of continuations (mine included) feel vague and unsatisfying. Such power deserves a solid pedagogical foundation.
  > Continuation-passing style is that foundation.
Continuation-passing style gives continuations meaning in terms of code.
Even better, a programmer can discover continuation-passing style by themselves if subjected to one constraint:
  > **No procedure is allowed to return to its caller--ever.**
  > One hint makes programming in this style possible:
  > **Procedures can take a callback to invoke upon their return value.**
   ``` 
       function traverseDocument(node, func) { 
       func(node);
       var children = node.childNodes;
          for (var i = 0; i < children.length; i++)
          traverseDocument(children[i], func);
         }
         function capitaliseText(node) {
         if (node.nodeType == 3) // A text node
         node.nodeValue = node.nodeValue.toUpperCase();
         }
       traverseDocument(document.body, capitaliseText);
       
* ##### Prototypal inheritance
* ##### Main differences between ES5 and ES6 ( let, const, var, arrow functions, class )
* ##### OOP -- in general, not specific to javascript
* ##### Design Patterns -- with a focus on JS specific patterns
* ##### Software Design and Architecture Principles -- SOLID, TRUE
* ##### Development Tools and Practices -- source control, code review, pair programming, unit testing 
* ##### Development workflows (agile, scrum, kanban)
* ##### Web/browser security
### [HTML]
### [CSS]
