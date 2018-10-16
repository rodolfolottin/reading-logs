### [Brett Slatkin - Refactoring Python: Why and how to restructure your code - PyCon 2016](https://www.youtube.com/watch?v=D_6ybDcU5gc)

Very interesting talk. I've learned about the a usage for the bool operand, despite I do not agree to move a check statement to a class. He presented a interesting way to create a database cache. Which is: if you have always to check something, that may be in your database, you can write a class that holds it to a self attribute and use the bool operand. But for that you would like to have some cache layer. IMHO

### [Thinking about Concurrency, Raymond Hettinger, Python core developer](https://www.youtube.com/watch?v=Bv25Dwe84g0)

Interesting talk despite I did not understand some concepts due to him being late on finishing it. He did show a interesting use case of the queue library with multithread and a lot of ways of doing the same thing in python when trying to work with multithread. His notes about what you should take care when working with multithread are very useful and for sure should be revisited in the future. Queue has its own lock system so we do not have to worry about it when using it.

### [Ned Batchelder - Big-O: How Code Slows as Data Grows - PyCon 2018](https://www.youtube.com/watch?v=duvZ-2UK0fc&t=0s&list=WL&index=6)

Big-O is about caracterizing the time that it takes when data grows. Most of the time you won't need it because `n` is usually small, but as your application grows and you start to have a bigger `n` it is good to have it in mind. I expected that the talk would give more examples, but it was just a few ones. Great example about when not to used (casting a list to a set just to perform a quick search) and a must use case (when you still have to perform another lookups in the data structure).


### [David Beazley | Keynote: Built in Super Heroes](https://www.youtube.com/watch?v=lyDLAutA88s&t=0s&index=4&list=WL)

Interesting talk but specific for new comers. He talked a lot about working with datasets using slicing, strip, defaultdict, Counter.
