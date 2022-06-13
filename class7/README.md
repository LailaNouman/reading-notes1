# Class-07:


### Python scope:
The concept of scope rules how variables and names are looked up in your code. It determines the visibility of a variable within the code. The scope of a name or variable depends on the place in your code where you create that variable. The Python scope concept is generally presented using a rule known as the LEGB rule. The notions of global scope and global names are tightly associated with module files. For example, if you define a name at the top level of any Python module, then that name is considered global to the module. That’s the reason why this kind of scope is also called module scope.

LEGB: stands for (Local, Enclosing(nonlocal), Global, Built-in) scopes
- Global scope: The names that you define in this scope are available to all your code.
- If you assign a value to a name outside of all functions, that name will have a global Python scope.
- To inspect the names within your main global scope, you can use dir()

Nonlocal scope is a special scope that only exists for nested functions. If the local scope is an inner or nested function, then the enclosing scope is the scope of the outer or enclosing function. This scope contains the names that you define in the enclosing function. The names in the enclosing scope are visible from the code of the inner and enclosing functions.
