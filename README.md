# The secret in testing is in writing testable-code

The TDD cycle is very detail-oriented and requires you to make some design decisions when writing tests, rather than when writing production code.

## Don't know what to test?
Test only the interface, not the implementation. Doing so will allow us to change the implementation without causing our tests to break. It’s an overspecification that adds costs, and absolutely no value.

## Articles

Mocks aren't stubs. https://martinfowler.com/articles/mocksArentStubs.html
In this article Martin Fowler talks about adifferent style of testing using mock objects. State verifaction (stubs) vs Behaviour verification (mocks).

## Talks

## Courses

The World's Best Intro to TDD, Level 1: TDD Done Right https://online-training.jbrains.ca/p/wbitdd-01
