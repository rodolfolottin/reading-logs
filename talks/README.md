### [Brett Slatkin - Refactoring Python: Why and how to restructure your code - PyCon 2016](https://www.youtube.com/watch?v=D_6ybDcU5gc)

Very interesting talk. I've learned about the a usage for the bool operand, despite I do not agree to move a check statement to a class. He presented a interesting way to create a database cache. Which is: if you have always to check something, that may be in your database, you can write a class that holds it to a self attribute and use the bool operand. But for that you would like to have some cache layer. IMHO

### [Thinking about Concurrency, Raymond Hettinger, Python core developer](https://www.youtube.com/watch?v=Bv25Dwe84g0)

Interesting talk despite I did not understand some concepts due to him being late on finishing it. He did show a interesting use case of the queue library with multithread and a lot of ways of doing the same thing in python when trying to work with multithread. His notes about what you should take care when working with multithread are very useful and for sure should be revisited in the future. Queue has its own lock system so we do not have to worry about it when using it.
