# The secret in testing is in writing testable-code

The TDD cycle is very detail-oriented and requires you to make some design decisions when writing tests, rather than when writing production code. Nota mental: lo que me gusta de TDD es que me hace "ir más lento" (en el buen sentido) y pensar en como quiero que se relacionen y colaboren los distintos colaboradores.

> Obviously those who do TDD know that TDD drastically helps to enforce good design.

Como bien me dijo Xabi Saez de Ocariz que le dijo Luis Artola:

> Los frameworks te hacen ir rápido cuando deberías de ir despacio.

Esto podemos tratar de evitarlo aplicando TDD.

**Test code is just as importante as production code. It is not a second-class citizen. It requieres thought, design and care. It must be kept as clean as production code.**

## Articles

**Mocks aren't stubs.** In this article Martin Fowler talks about *behaviour verification*, a different style of testing using mock objects vs *state verifaction* using stubs objects. This article also clarifies what types of *test doubles* can be used in order to improve our tests. https://martinfowler.com/articles/mocksArentStubs.html

## Talks

**The Magic Tricks of Testing by Sandi Metz.** Don't now what to test and what not to? Test only the interface, not the implementation. Doing so will allow us to change the implementation without causing our tests to break. It’s an overspecification that adds costs, and absolutely no value. https://www.youtube.com/watch?v=URSWYvyc42M

![The Magic Tricks of Testing by Sandi Metz]
(https://raw.githubusercontent.com/epelde/tdd-resources/master/assets/test_tricks.png)

## Courses

*The World's Best Intro to TDD, Level 1: TDD Done Right* https://online-training.jbrains.ca/p/wbitdd-01
