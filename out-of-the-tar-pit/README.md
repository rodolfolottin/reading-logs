### out-of-the-tar-pit

* Simplicity is the way,
* Often software complexity is confused with computer (algorithmic) complexity. You can have a simple software (with a low level of complexity) but in the other term it can have a higher level of complexity,
* The major contributor of software complexity is the handling of state and flow of control (which can be the same),
* Complexity, Conformity, Changeability and Invisibility,
* Simplicity is hard,
* Improvements in informal reasoning will lead to less errors being created, while improvements in testing will lead to more errors being detected,
* Improvements in informal reasoning will facilitate all future attempts to understand the system,
* Tests on a system or component that is in one particular state tells you nothing about the behaviour of that system or component in another state,
* As the number of states grows it comes harder to reason about all possible scenarios which the system can go throught,
* One of the main problems of managing `state` is that you can even contamine parts of your system that were stateless by default,
* Order too causes complexity, specially when the programming language forces you to do things in its proper way,
* In this way the programmer is being force to specify the aspect of `how` things should go instead of `what` is desired,
* Control affects _informal reasoning_,
* Concurrency directly affects informal reasoning about the system or the component as it also affects testing in a tremendous way. You can't always tell about what will happen the next time you run a test when using the same set of inputs having to manage state too,
* Code volume also increases complexity.
* Duplicated code can exist when a functionality is not clear or it is too complex to understand.
* Power corrupts and by that the paper tries to say that a powerful language (a language that allows you to do a lot of things manually or permits state control, for example) that does not enforce some guarantees can lead to some mistakes. Also, it is harder to understand systems contructed in it.
* Object identity (each object is seen as being a uniquely identifiable entity) make sense when objects are used to provide mutables stateful abstraction. When you need to identify an object as unique by its values, you have to create Value objects, and in this cases you have to create methods to determine whether two objects are equivalents.
* The main problem in OOP relies on state.
* By avoiding you to deal with state FP avoids some problems that can happen within it and informal reasoning becomes much more effective.
* Concurrency becomes more easier to deal with in FP.
