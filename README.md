# Interesting Software Engineering Article
I found the article [Friday Facts #366 - The only way to go fast, is to go well!](https://www.factorio.com/blog/post/fff-366) to be extremely interesting. In fact, it inspired me to take this course. I love Factorio too.

## "Clean Code"
The article mentions Uncle Bob and his notion of writing "clean code". I happened to watch his entire lecture on "clean code" and found many concepts useful or helpful. Uncle Bob is opinionated, and many of his recommendations should not be followed blindly. Perhaps my greatest takeaway is that "function should do onething only" and "refactoring is important"

## Testing and TDD
Testing is imporant, and TTD (test driven development) is an rather radical approach to testing. In TTD, you write the test cases before the implementations. This forces you to organize your codebase in a test friendly manner and contemplate your requirements carefully. In my experience, TDD works best when the implementation is clear and absolutely needed. After all, designing and writing test cases requires effort. If the requirements change rapidly, the tests are also obselete. Furthermore, coming up with a test dependecy tree is extremely painstaking. It should be avoided when you are unsure that your feature is going to stay.

## The only way to go fast, is to go well
I am convinced that it is especially true in the software industry. Serious software are complex, and it can easily spiral out of control in complexity an the hands of an average undergraduate student. In the early stages of development, it is easy to go fast and accumulate technical debt. In no time, the software will be so complex that no one will be willing to work on it. The guiding principle is to keep it simple so that it is obiviously correct, but breaking down big systems into smaller ones and finding the optimal implementation is no trivial task.