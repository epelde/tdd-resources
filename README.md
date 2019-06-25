# My opinions about TDD

> The secret in testing is in writing testable-code

What does this mean? **Testing bad code (badly designed code) is difficult. So we should write code that is easy to test**. And this is all about **DESIGN**.

> The TDD cycle is very detail-oriented and requires you to **make some design decisions when writing tests, rather than when writing production code**. Obviously those who do TDD know that TDD drastically helps to **enforce good design**.

**TDD is just as much about design as it is about test**. It's all about developing/designing in a **"slower" (slow id good)** way to be able to think about how I want the different collaborators to relate and collaborate. **Maybe we can improve our software quality applying TDD**. Quality is not negotiable. And here is where SOLID principles come to scene.

Recommended reading: The Definition of "Bad Design" https://drive.google.com/file/d/0BwhCYaYDn8EgMjdlMWIzNGUtZTQ0NC00ZjQ5LTkwYzQtZjRhMDRlNTQ3ZGMz/view

And yes, it takes time & money. So does fixing defects in production software. Recommended reading: Is High Quality Software Worth the Cost? by Martin Fowler https://martinfowler.com/articles/is-quality-worth-cost.html

> **Test code is just as importante as production code. It is not a second-class citizen. It requieres thought, design and care. It must be kept as clean as production code.**

Tests deserve the same respect as our production code. Apply merciless **refactoring**, just as one should do for production code.

> Los frameworks te hacen ir rápido cuando deberías de ir despacio (Luis Artola en boca de Xabi Saez de Ocariz).

Esto podemos tratar de evitarlo aplicando TDD.

Recommended reading: Odio los framework by Javi Santana http://javisantana.com/2019/04/07/odio-los-framework.html

# Unit (automated) testing

Unit testing is about testing a single object (Subject Under Test) and test it by itself, in isolation, without worrying about the role it plays in the surrounding system. These tests are a safety net for further changes to tyhe code.

https://blog.thecodewhisperer.com/junit-on-one-page.pdf
