The only Javascript MVC framework you need.

Well, at least for me, it seems that whenever I compare the pros and cons of using a particular MVC framework, the cons outweight the pros.

The pros

* Framework enforces certain structure to prevent spaghetti code
* Framework gives you a set of helpers for making stuff easier (or at least different)

The cons

* Unnecessary indirection added -> makes the code harder to follow
* Gets in your way when you want shit done

Now these pros don't need a framework, if you ask me. Just sticking to a certain architecture (MVC, maybe) will give you the main pro, which is having an actual architecture instead of spaghetti.

If you need helpers to assign event handlers to DOM elements, use jQuery, plugins and write the rest yourself.

If you need help with asynchronicity and events, use a Reactive Functional Programming library such as 
[RxJS](https://github.com/Reactive-Extensions/RxJS) or [Bacon.js](https://github.com/raimohanska/bacon.js)

So, instead of picking a framework, you should probably harden-the-fuck-up and start writing some code.