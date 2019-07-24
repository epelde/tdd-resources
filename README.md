# My opinions about TDD

> Detestable (adjective) code: software that isn't testable.

(from someone at the Sydney XP group, whose name I sadly forgot. - Martin Fowler)

> The secret in testing is in writing testable-code

What does this mean? **Testing bad code (badly designed code) is difficult. So we should write code that is easy to test from the very beginning**. And this is all about **DESIGN**.

> The TDD cycle is very detail-oriented and requires you to **make some design decisions when writing tests, rather than when writing production code**. Obviously those who do TDD know that TDD drastically helps to **enforce good design**.

**TDD is just as much about design as it is about test**. It's all about developing/designing in a **"slower" (slow is good)** way to be able to think about how I want the different collaborators to relate and collaborate. Quality is not negotiable. **Maybe we can improve our software quality applying TDD but it's not enough**. And here is where design patterns & principles come to scene.

Recommended reading: **Does TDD really lead to good design?** by Sandro Mancuso https://codurance.com/2015/05/12/does-tdd-lead-to-good-design/

And yes, it takes time & money. So does fixing defects in production software.

Recommended reading: **Is High Quality Software Worth the Cost?** by Martin Fowler https://martinfowler.com/articles/is-quality-worth-cost.html

TDD as a software development flow.

> **Test code is just as importante as production code. It is not a second-class citizen. It requieres thought, design and care. It must be kept as clean as production code.**

Tests deserve the same respect as our production code. Apply merciless **refactoring**, just as one should do for production code.

> Understand how to write testable code in the first place. Then understand how to add tests to code that was already written.

# Unit (automated) testing

Unit testing is about testing a single object (Subject Under Test) and test it by itself, in isolation, without worrying about the role it plays in the surrounding system. These tests are a safety net for further changes to tyhe code.

https://blog.thecodewhisperer.com/junit-on-one-page.pdf
