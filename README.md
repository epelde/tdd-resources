# The secret in testing is in writing testable-code

The TDD cycle is very detail-oriented and requires you to make some design decisions when writing tests, rather than when writing production code.

> Obviously those who do TDD know that TDD drastically helps to enforce good design.

## Articles

**Mocks aren't stubs.** In this article Martin Fowler talks about *behaviour verification*, a different style of testing using mock objects vs *state verifaction* using stubs objects. This article also clarifies what types of *test doubles* can be used in order to improve our tests. https://martinfowler.com/articles/mocksArentStubs.html

## Talks

**The Magic Tricks of Testing by Sandi Metz.** Don't now what to test and what not to? Test only the interface, not the implementation. Doing so will allow us to change the implementation without causing our tests to break. It’s an overspecification that adds costs, and absolutely no value. https://www.youtube.com/watch?v=URSWYvyc42M

## Courses

*The World's Best Intro to TDD, Level 1: TDD Done Right* https://online-training.jbrains.ca/p/wbitdd-01
