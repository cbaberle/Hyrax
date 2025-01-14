---
pagetitle: About | The Hyrax Project
---
# Welcome to the Hyrax Project!

## An online resource and digital garden for categorical logic and type theory, formalized in Agda

> *The [Hyrax](https://en.wikipedia.org/wiki/Hyrax) is the closest living terrestrial relative of the [Elephant](https://global.oup.com/academic/product/sketches-of-an-elephant-9780198534259?cc=us&lang=en&). Despite its smaller stature, it shares with its larger cousins a high degree of intelligence and social behavior.*

---

The **Hyrax Project** is a personal wiki & [digital garden](https://maggieappleton.com/garden-history) for the formal exploration of topics in and around categorical logic and type theory, with an emphasis on [[Synthetic Mathematics]], written by me, Corinthia Beatrix Aberlé—[[#About Me]].

Aside from serving as my own personal repository of knowledge, Hyrax aims to be an approachable, comprehensive, and explorable resource for learning the topics it encompasses, in the mould of formalization projects such as the [1Lab](https://1lab.dev). To this end, Hyrax is also a literate [Agda](https://wiki.portal.chalmers.se/agda/pmwiki.php) library consisting of both formally-verified code and explanatory prose.

```agda
{-# OPTIONS --rewriting --cohesion --flat-split #-}
module index where
```

However, Hyrax takes a distinct approach to formalization from many of its sister projects, in that it does not aim to use the type theoretic language of Agda to prove results *directly*, but rather uses this language to construct and compare *other* theories and languages in which these results may naturally be proved. In other words, instead of using Agda as a foundational system for mathematics, Hyrax uses Agda as [logical framework](https://en.wikipedia.org/wiki/Logical_framework) for the invention and exploration of such foundational systems themselves.

This kind of [metalinguistic abstraction](https://en.wikipedia.org/wiki/Metalinguistic_abstraction) serves as a key principle of the philosophy of *synthetic mathematics,* for which Hyrax aims to serve as both exposition and proof-of-concept. For more on the philosophy of synthetic mathematics that underlies Hyrax, see [[Synthetic Mathematics]].

For more on the axiomatic framework underlying Hyrax, and its implementation in Agda, take a look at the module [[synthetic-agda.lagda]]:

```agda
open import Prelude.synthetic-agda
```

## Related Projects

Although Hyrax aims to be relatively self-contained, ultimately it exists as part of a much larger network of online references and formalization projects in category theory and type theory, several of which directly inspired the conception of Hyrax:

* [1Lab](https://1lab.dev) – an experiment in discoverable formalisation of univalent mathematics in Cubical Agda.
* [nLab](https://ncatlab.org/nlab/show/HomePage) – a wiki for collaborative work on Mathematics, Physics, and Philosophy from the POV of higher structures.
* [Clowder Project](https://clowderproject.com) – an online reference work and wiki for category theory and mathematics.

## About Me

I am a PhD student studying Pure and Applied Logic in the Computer Science Department at Carnegie Mellon University. My research is focused on type theory, category theory, categorical logic, and applications thereof to programming languages and formal verification. For more about me, see [my personal website](https://cbaberle.com).

My path into academia has been unorthodox and at times complex. Having completed the equivalent of a high-school education by the age of 14, at that time I chose to devote myself to a career in music as a composer. In the course of pursuing my studies of music, however, I became increasingly interested in mathematics, logic, and computer science, and eventually became determined to study these topics at a research level. However, at that time (around 20 years of age) I had no qualifications in these areas, nor even a high school diploma, and it was primarily through access to online resources for learning these subjects that I was able to get where I am today. As such, I strive to ensure that my own academic work is freely available and easily accessible, as my own small way of giving back to the community.