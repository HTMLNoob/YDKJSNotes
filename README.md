# YDKJSNotes
My Personal Notes for the book series "You Dont Know Javascript"

```js this``` and object prototypes notes.


```js this``` is a binding that is made when a function is invoked, and what it references is determined entirely by the call-site where the function is called.

There are four major rules that are used for ```js this```
1: By default, ```js this``` points to the global scope. In ```js strict-mode``` ```js this``` will be ```js undefined```

2: Called with an object with the call-site inside the object? Use that context object.

3: Called with ```js call``` or ```js apply```? Use the specified object.

4: Called with ```js new``` then use the newly constructed object.
