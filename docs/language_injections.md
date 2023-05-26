# Language Injections

Various [language injections](https://www.jetbrains.com/help/idea/using-language-injections.html#top) are provided by the ArchUnit plugin that extend the
bundled configuration.

In general, injections require the **IntelliLang** plugin to be installed (bundled by default).

## Java
| Category               | Location                                                                     | Injected Language | Comment |
|------------------------|------------------------------------------------------------------------------|-------------------|---------|
| ArchUnit ClassesShould | `ClassesShould.haveNameMatching()`<br/>`ClassesShould.haveNameNotMatching()` | RegExp            |         |
