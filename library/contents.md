---
pagetitle: Contents | The Hyrax Project
---

# Table of Contents {#intro}

<nav class="contents">

### Jump to section:

* [Introduction](library/contents.html#intro)
* [Prelude](library/contents.html#prelude)
* [Philosophy](library/contents.html#phil)

![](img/decotwo2.png){width=24px class="bodyimg"}

</nav>

<pre class="Agda"><a id="326" class="Keyword">module</a> <a id="333" href="library.contents.html" class="Module">library.contents</a> <a id="350" class="Keyword">where</a>
</pre>
## Prelude {#prelude}

The following modules introduce the central concepts and methods behind Hyrax, and are an excellent place to start exploring the rest of the library.

* [What is Synthetic Mathematics?](404.html) Introduces the concepts of analytic and synthetic methods in mathematics, and argues for the need to develop tools for the latter: <pre class="Agda"><a id="719" class="Comment">-- open import library.synthetic</a>
</pre>
* [The Algebraic Essence of Type Theory](404.html) Describes the theoretical basis of the synthetic approach taken by Hyrax in terms of *dependently-typed algebraic theories.* The module also discusses the pros and cons of using Agda for this purpose, and the reasons why it was chosen over the alternatives. <pre class="Agda"><a id="1075" class="Comment">-- open import library.algebraicEssence</a>
</pre>

## Philosophy {#phil}

I studied both Computer Science and Philosophy for my undergraduate degree, and many of the fundamental questions that drive my research remain philosophical in nature. As such, the following modules serve to record my philosophical thoughts as they pertain to the central topics of Hyrax.

* My [Research Manifesto](library/philosophy/research-manifesto.html) describes the aims, motivation, and methods of my research into the abstract structure of logic and computation. <pre class="Agda"><a id="1627" class="Keyword">open</a> <a id="1632" class="Keyword">import</a> <a id="1639" href="library/philosophy/research-manifesto.html" class="Module">library.philosophy.research-manifesto</a>
</pre>