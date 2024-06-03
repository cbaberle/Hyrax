---
pagetitle: Contents | The Hyrax Project
---

# Table of Contents {#intro}

<nav class="contents">

### Jump to section:

* [Introduction](#intro)
* [Prelude](#prelude)
* [Philosophy](#phil)

![](/img/decotwo2.png){width=24px class="bodyimg"}

</nav>

```agda
module library.contents where
```

## Prelude {#prelude}

The following modules introduce the central concepts and methods behind Hyrax, and are an excellent place to start exploring the rest of the library.

* [What is Synthetic Mathematics?](/404.html) Introduces the concepts of analytic and synthetic methods in mathematics, and argues for the need to develop tools for the latter: ```agda
-- open import library.synthetic
``` 

* [The Algebraic Essence of Type Theory](/404.html) Describes the theoretical basis of the synthetic approach taken by Hyrax in terms of *dependently-typed algebraic theories.* The module also discusses the pros and cons of using Agda for this purpose, and the reasons why it was chosen over the alternatives. ```agda
-- open import library.algebraicEssence
``` 


## Philosophy {#phil}

I studied both Computer Science and Philosophy for my undergraduate degree, and many of the fundamental questions that drive my research remain philosophical in nature. As such, the following modules serve to record my philosophical thoughts as they pertain to the central topics of Hyrax.

* My [Research Manifesto](/404.html) describes the aims, motivation, and methods of my research into the abstract structure of logic and computation. ```agda
-- open import library.philosophy.researchManifesto
```