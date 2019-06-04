# How do I (start to) see TDD

> The secret in testing is in writing testable-code

What does this mean? **Testing bad code (badly designed code) is difficult**.

> The TDD cycle is very detail-oriented and requires you to **make some design decisions when writing tests, rather than when writing production code**. Obviously those who do TDD know that TDD drastically helps to **enforce good design**.

It's seems it's all about developing in a **"slower" (slow id good)** way to be able to think about how I want the different collaborators to relate and collaborate. **Maybe we can improve our software quality applying TDD**. Quality is not negotiable.

> **Test code is just as importante as production code. It is not a second-class citizen. It requieres thought, design and care. It must be kept as clean as production code.**

Tests deserve the same respect as our production code. So **RESPECT** them!

> Los frameworks te hacen ir rápido cuando deberías de ir despacio (Luis Artola en boca de Xabi Saez de Ocariz).

Esto podemos tratar de evitarlo aplicando TDD.

## Articles

**Mocks aren't stubs.** In this article Martin Fowler talks about *behaviour verification*, a different style of testing using mock objects vs *state verifaction* using stubs objects. This article also clarifies what types of *test doubles* can be used in order to improve our tests. https://martinfowler.com/articles/mocksArentStubs.html

## Talks

**The Magic Tricks of Testing by Sandi Metz.** Don't now what to test and what not to? Test only the interface, not the implementation. Doing so will allow us to change the implementation without causing our tests to break. It’s an overspecification that adds costs, and absolutely no value. https://www.youtube.com/watch?v=URSWYvyc42M

![The Magic Tricks of Testing by Sandi Metz](https://raw.githubusercontent.com/epelde/tdd-resources/master/assets/test_tricks.png)

## Courses

*The World's Best Intro to TDD, Level 1: TDD Done Right* https://online-training.jbrains.ca/p/wbitdd-01
