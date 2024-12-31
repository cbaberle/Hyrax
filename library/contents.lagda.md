---
pagetitle: Contents | The Hyrax Project
---

# Table of Contents {#intro}

```agda
{-# OPTIONS --rewriting --cohesion --flat-split #-}
module library.contents where
```

## Prelude {#prelude}

<nav class="contents">

### Jump to section:

* [Introduction](library/contents.html#intro)
* [Prelude](library/contents.html#prelude)
* [Philosophy](library/contents.html#phil)

![](img/decotwo2.png){width=24px class="bodyimg"}

</nav>

The following modules introduce the central concepts and methods behind Hyrax, and are an excellent place to start exploring the rest of the library. 

* [What is Synthetic Mathematics?](404.html) Introduces the concepts of analytic and synthetic methods in mathematics, and argues for the need to develop tools for the latter: ```agda
-- open import library.synthetic
``` 

* [Introduction to Synthetic Agda](library/synthetic-agda.html) Describes the main axiomatic framework used in this library and its implementation in Agda. ```agda
open import library.synthetic-agda
``` 


## Philosophy {#phil}

I studied both Computer Science and Philosophy for my undergraduate degree, and many of the fundamental questions that drive my research remain philosophical in nature. As such, the following modules serve to record my philosophical thoughts as they pertain to the central topics of Hyrax.

* My [Research Manifesto](library/philosophy/research-manifesto.html) describes the aims, motivation, and methods of my research into the abstract structure of logic and computation. ```agda
open import library.philosophy.research-manifesto
```