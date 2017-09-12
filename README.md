# YDKJSNotes
My Personal Notes for the book series "You Dont Know Javascript"

```this``` and object prototypes notes.


```this``` is a binding that is made when a function is invoked, and what it references is determined entirely by the call-site where the function is called.

There are four major rules that are used for ```this```
1: By default, ```this``` points to the global scope. In ```strict-mode``` ```this``` will be ```undefined```

2: Called with an object with the call-site inside the object? Use that context object.

3: Called with ```call``` or ```apply```? Use the specified object.

4: Called with ```new``` then use the newly constructed object.
