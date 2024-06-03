---
pagetitle: About | The Hyrax Project
---

<div class="frontmatter">

<div class="title">

<div class="titleblock">
## <span class="dropcap">W</span>elcome to the Hyrax Project! {#intro}
### An online resource and digital garden for categorical logic and type theory, formalized in Agda
</div>

</div>

<div class="titlepicture">
![](img/hyrax8.png){width=240px class="bodyimg"}
</div>

</div>

<nav class="contents mainContents">

### Jump to section

* [Introduction](#intro)
* [Related Projects](#related)
* [About Me](#aboutme)

![](img/decotwo2.png){width=24px class="bodyimg"}

</nav>

---

<blockquote class="sidequote"> 
*The [Hyrax](https://en.wikipedia.org/wiki/Hyrax){class="external"} is the closest living terrestrial relative of the [Elephant](https://global.oup.com/academic/product/sketches-of-an-elephant-9780198534259?cc=us&lang=en&){class="external"}. Despite its smaller stature, it shares with its larger cousins a high degree of intelligence and social behavior.*
</blockquote>

---

The **Hyrax Project** is a personal wiki & [digital garden](https://maggieappleton.com/garden-history){class="external"} for the formal exploration of topics in and around categorical logic and type theory, with an emphasis on [synthetic mathematics](https://ncatlab.org/nlab/show/synthetic+mathematics){class="external"}, written by me, [C.B. Aberlé](https://cbaberle.com){class="external"}.

Aside from serving as my own personal repository of knowledge, Hyrax aims to be an approachable, comprehensive, and explorable resource for learning the topics it encompasses, in the mould of formalization projects such as the [1Lab](https://1lab.dev){class="external"}. To this end, Hyrax is also a literate [Agda](https://wiki.portal.chalmers.se/agda/pmwiki.php){class="external"} library consisting of both formally-verified code and explanatory prose.

<pre class="Agda"><a id="1869" class="Keyword">module</a> <a id="1876" href="index.html" class="Module">index</a> <a id="1882" class="Keyword">where</a>
</pre>
However, Hyrax takes a distinct approach to formalization from many of its sister projects, in that it does not aim to use the type theoretic language of Agda to prove results *directly*, but rather uses this language to construct and compare *other* theories and languages in which these results may naturally be proved. In other words, instead of using Agda as a foundational system for mathematics, Hyrax uses Agda as [logical framework](https://en.wikipedia.org/wiki/Logical_framework){class="external"} for the invention and exploration of such foundational systems themselves.

This kind of [metalinguistic abstraction](https://en.wikipedia.org/wiki/Metalinguistic_abstraction){class="external"} serves as a key principle of the philosophy of *synthetic mathematics,* for which Hyrax aims to serve as both exposition and proof-of-concept. For more on the philosophy of synthetic mathematics that underlies Hyrax, see the module [What is Synthetic Mathematics?](404.html):

<pre class="Agda"><a id="2880" class="Comment">-- open import library.synthetic</a>
</pre>
For more on the underlying theory behind the use of logical frameworks in synthetic mathematics, and why Agda is especially well-suited to serve as such a logical framework, take a look at the module [The Algebraic Essence of Type Theory](404.html):

<pre class="Agda"><a id="3177" class="Comment">-- open import library.algebraicEssence</a>
</pre>
Finally, to get started exploring Hyrax, head on over to the [table of contents](library/contents.html):

<pre class="Agda"><a id="3336" class="Keyword">open</a> <a id="3341" class="Keyword">import</a> <a id="3348" href="library/contents.html" class="Module">library.contents</a>
</pre>
## Related Projects {#related}

Although Hyrax aims to be relatively self-contained, ultimately it exists as part of a much larger network of online references and formalization projects in category theory and type theory, several of which directly inspired the conception of Hyrax:

* [1Lab](https://1lab.dev){class="external"} – an experiment in discoverable formalisation of univalent mathematics in Cubical Agda.

* [Clowder Project](https://clowderproject.com){class="external"} – an online reference work and wiki for category theory and mathematics.

## About Me {#aboutme}

![](img/profile-picture4.jpg){width=180px class="bodyimg framed oval" style="float:left; margin-right: 1em;"}

I am a PhD student in Pure and Applied Logic at the Computer Science Department at Carnegie Mellon University. My research is focused on type theory, category theory, categorical logic, and applications thereof to programming languages and formal verification. For more about me, see [my personal website](https://cbaberle.com){class="external"}.

My path into academia has been unorthodox and at times complex. Having completed the equivalent of a high-school education by the age of 14, at that time I chose to devote myself to a career in music as a composer. In the course of pursuing my studies of music, however, I became increasingly interested in mathematics, logic, and computer science, and eventually became determined to study these topics at a research level. However, at that time (around 20 years of age) I had no qualifications in these areas, nor even a high school diploma, and it was primarily through access to online resources for learning these subjects that I was able to get where I am today. As such, I strive to ensure that my own academic work is freely available and easily accessible, as my own small way of giving back to a the community.