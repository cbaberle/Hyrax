---
pagetitle: Research Manifesto | C.B. Aberlé
---

# Foundations of Procedural Epistemology {#intro}
<nav class="contents">
### Jump to section:

* [Title](library/philosophy/research-manifesto.html#intro)

![](img/decotwo2.png){width=24px class="bodyimg"}

</nav>

> *"Modern logic, as I hope is now evident, has the effect of enlarging our abstract imagination, and providing an infinite number of possible hypotheses to be applied in the analysis of any complex fact. In this respect it is the exact opposite of the logic practised by the classical tradition. In that logic, hypotheses which seem primâ facie possible are professedly proved impossible, and it is decreed in advance that reality must have a certain special character. In modern logic, on the contrary, while the primâ facie hypotheses as a rule remain admissible, others, which only logic would have suggested, are added to our stock, and are very often found to be indispensable if a right analysis of the facts is to be obtained. The old logic put thought in fetters, while the new logic gives it wings."*
>
> – Bertrand Russell, ["Logic as the Essence of Philosophy"](https://ncatlab.org/nlab/show/Logic+as+the+Essence+of+Philosophy)

```agda
module library.philosophy.research-manifesto where
```

In what follows, I will try to say something about the central motivations for my academic work, and outline my "research programme," insofar as I have such a thing. In brief, I am interested in developing what might be called *foundations of procedural epistemology*. The term *procedural epistemology* is here borrowed from Abelson & Sussman's [*Structure and Interpretation of Computer Programs*](https://mitpress.mit.edu/sites/default/files/sicp/index.html). In the preface to that book, the authors remark:

> *"The computer revolution is a revolution in the way we think and in the way we express what we think. The essence of this change is the emergence of what might best be called *procedural epistemology* – the study of the structure of knowledge from an imperative point of view, as opposed to the more declarative point of view taken by classical mathematical subjects. Mathematics provides a framework for dealing precisely with notions of 'what is.' Computation provides a framework for dealing precisely with notions of 'how to.'"*

It is precisely this *procedural structure of knowledge* that I seek to explore further, particularly as it pertains to *logic*. I believe that viewing logic through such a procedural lens can effect the same sort of enlargement of our abstract imagination as spoken of by Russell in the quote at the beginning of this essay. Indeed, my view of the contemporary status of logic is well-expressed by that quote, though in an ironic twist, what for me occupies the place of Russell's "old logic" is the very logic that Russell himself championed – what today goes under the heading of "classical logic.[^1]" Classical logic is typically concerned with the *truth* or *falsity* of expressions in various languages and formalisms. By contrast, the "new logic" that I am interested in is primarily concerned not with the bare truth of expressions, but with the *processes* that substantiate and structure such truth – not *that* something is true, but *how* it is true. In this way, logic becomes capable of expanding its purview beyond mere formal truth to what [Lawvere](https://ncatlab.org/nlab/show/Tools+for+the+advancement+of+objective+logic), following Hegel (whose logic, notably, was vehemently rejected by Russell), called "objective logic", i.e. "A guide to the complex, but very non-arbitrary constructions of the concepts and their interactions which grow out of... any serious object of study".

This novel conception of logic owes its growth in recent decades to a confluence of three mathematical disciplines: constructive mathematics, category theory, and computer science, whose interconnections with one another have become increasingly apparent in that time. It is within the interstices of these connections, then, that I believe the foundations of procedural epistemology are to be found. In particular, as I see it, a pair of common threads runs through each of the above-mentioned disciplines, concerning what might respectively be called *abstraction* (i.e. how various data may be structured) and *interaction* (i.e. how processes that act upon such structured data combine to form complex systems). By following each of these threads so as to develop general theories of such *abstraction* and *interaction*, I hope to thus make whatever contribution I can to the development of *procedural epistemology* and *objective logic*.

Of course, the true test of such theories, whether they deserve to be called *foundations of procedural epistemology*, lies ultimately with the applications they find. I anticipate that such theories, if successful, could profitably contribute to the design and analysis of programming languages, systems of formal proof, and computational systems more generally. I thus take a keen interest in ongoing developments e.g. in the implementation and use of proof assistants and automated theorem provers in mathematics and computer science, etc. Ultimately, however, the greatest prize I see this theory as offering is just what Russell spoke of in the quote which began this manifesto: an expansion of our capacity for invention and depth of insight.

We may agree with Russell that the logic of the ancients kept our reason earthbound, and that classical logic, by coupling logical notions with mathematical methods, was able to propel our theoretical imagination into the stratosphere. Yet just as aeronautics paved the way for astronautics, so it is high time for us to inaugurate the logical space-age, by embracing the computational element of abstract reasoning and objective logic, and making good on the promise of *procedural epistemology*.

[^1]: To be entirely fair to Russell, his logic was not quite synonymous with what we would today call 'classical logic', although the differences between Russell's logic and contemporary classical logic are well beyond the scope of this manifesto.