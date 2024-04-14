---
layout: page
title: Bayesian Nets and Causality errata
permalink: /publications/BNAC-errata.html
exclude: true
---

<h3>Preface</h3>

<a href="images/bnac.jpg"><img style="float: right;" src="images/bnac.jpg" alt="bnac_big" width="198" height="300" /></a>
How should we reason with causal relationships? Much recent work on this question has been devoted to the theses (i) that Bayesian nets provide a calculus for causal reasoning and (ii) that we can learn causal relationships by the automated learning of Bayesian nets from observational data. The aim of this book is to present coherent foundations for such work.

After an overview of the book in Chapter 1, Chapter 2 provides an introduction to probability and its interpretations. Chapter 3 introduces Bayesian nets and Chapter 4 discusses the problems that beset current proposals for their use in causal reasoning. This book presents new foundations for Bayesian nets based on the objective Bayesian interpretation of probability, according to which probabilities represent the degrees of belief that an agent ought to adopt (Chapter 5). This interpretation leads naturally to a two-stage methodology for constructing Bayesian nets, where one first appeals to causal knowledge to generate a Bayesian net and then refines this net in the light of new information (Chapter 6).

At this point, the book turns to the nature of causality and the problem of discovering causal relationships. Chapter 7 introduces current theories of causality. A range of proposals for discovering causal relationships are presented in Chapter 8. Then Chapter 9 develops epistemic causality, the view that causal relationships are purely a mental device to aid reasoning about the world, and do not exist as physical relations in the world. Such a view fits well with the objective Bayesian interpretation of probability, and forms the basis of a new approach to learning causal relationships using Bayesian nets.

The resulting framework for causal reasoning admits a number of extensions. Reasoning about nested causal relationships requires an extension to recursive Bayesian nets (Chapter 10). Logical relationships can be treated analogously to causal relationships and a general framework can be produced for reasoning about both (Chapter 11). Finally the framework is extended in Chapter 12 to cope with changes in the language an agent uses to speak about causality.

<h3>Reviews</h3>
<em>I'd be very grateful if you can email me if you spot any reviews that are not mentioned here - Jon Williamson.</em>

<strong>Mathematical Reviews 2005k - Olga M. Kosheleva</strong> : "Overall, I strongly recommend this book to anyone interested in the foundations and practical use of different techniques for reasoning under uncertainty."

<strong>Mind <a href="http://mind.oxfordjournals.org/content/vol115/issue458/index.dtl">115</a>, 2006, pp. 502-506 - Sungho Choi</strong> : "Bayesian Nets and Causality is a very well-written and well-organized book. ... No doubt it will be recognized as a very important contribution to the philosophy of probability and causality"
<p style="padding-left: 30px">Some responses to questions posed by Choi in this review:</p>

<ul>
	<li>Under the epistemic view, we have a concept of cause because such a concept is inferentially useful, not because there are physical causal relationships that we somehow perceive. This means that in possible worlds where causal beliefs are never inferentially useful (where one type of event is never strategically dependent on any other) there would simply be no causal relationships at all. Isn't this counter-intuitive? Surely there are still physical mechanisms that explain the occurrence of events in such worlds, so surely there is causality in such worlds?
<ul>
	<li>I'd argue not. It seems quite plausible that, despite the fact that events in such a world admit physical explanations, the inhabitants of the world would never develop a concept of cause. If that is right, then it is evidence for the epistemic view and against a physical account. Intuitions are by no means clear-cut here, but they certainly do not tell against the epistemic account.</li>
</ul>
</li>
	<li>What constitutes causal knowledge?
<ul>
	<li>In my paper Causality I claim that the causal facts can be interpreted as the causal beliefs that an omniscient agent ought to adopt. Causal knowledge is knowledge of this set of causal beliefs. Plausibly, as a rational agent's knowledge increases, her causal beliefs will tend to those of an omniscient rational agent. Thus well-entrenched causal beliefs may count as causal knowledge.</li>
</ul>
</li>
	<li>Isn't the notion of mechanism causal?
<ul>
	<li>It needn't be. Salmon and Dowe's accounts view mechanisms as physical but non causal. Other accounts view mechanisms in terms of chains of probabilistic dependencies - these are not causal. Or one might give an account in terms of chains of theoretical connections - again, not causal.</li>
</ul>
</li>
	<li>How does Probabilistic to Causal Transfer generate positive causal beliefs?
<ul>
	<li>As Choi rightly points out, Strategic Causal Dependence presupposes causal relationships. Hence Probabilistic to Causal Transfer offers a way of testing to see whether an agent's causal belief graph is rational, but not an incremental method for generating such a graph. In principle one can generate a rational causal belief graph by running through all causal graphs on the domain and eliminating those that are not rational. In practice one can use causal Markov methods (section 9.6) or controlled experiments to generate such a graph. In sum, Probabilistic to Causal Transfer does impose positive causal constraints, but in a non-incremental way.</li>
</ul>
</li>
	<li>What justifies the claim that humans think in terms of cause and effect because of the convenience of causality rather than because there is some physical notion of cause that we experience?
<ul>
	<li>In the book, I took the failure of physical accounts as motivation for this claim. The success of the epistemic account would also confirm this central tenet. But one might also be able to support this claim via direct empirical evidence: is childhood learning of causal relationships re-inforced though inferential success or through experience? If children learn causal relationships actively by intervening to achieve their goals and by drawing inferences, then that might support this claim. On the other hand, if learning is more passive, akin to perceptual learning, then that might support an account of experiencing physical mechanisms. Causal learning is a hot topic in psychology at the moment, and evidence seems to favour the former account, though it is perhaps too early to draw any firm conclusions.</li>
</ul>
</li>
</ul>
<strong>Computing Reviews, <a href="http://www.reviews.com/review/review_review.cfm?review_id=132640">10 April 2006</a> - Rohan Baxter</strong>: "This book revived the AI dream, for it shows how probabilistic and causal relationships can be discovered and represented automatically using Bayesian nets as the knowledge representation model. ...The writing style is simple and clear, which is an impressive quality, especially considering the philosophical content. ... This book should be of interest to both Bayesian net researchers and philosophers of science."

<strong>Philosophia Mathematica <a href="http://philmat.oxfordjournals.org/cgi/content/extract/15/3/389">15(3)</a>, October 2007 - Kevin B. Korb</strong>: "It will be clear that I have found Jon Williamson’s work provocative. And therein I find its greatest merit, for in presenting these central highly contentious problems for understanding causal Bayesian networks, and in attempting to resolve them, the book must be provocative. It should be welcomed as a real and interesting attempt that any student of Bayesian techniques, and anyone else interested in current philosophy of causality, will benefit from reading."

<strong><a href="http://lgxserve.ciseca.uniba.it/lei/2rEnglish/browse.html">2R</a> - The Journal of Philosophical Reviews 6, 2007 - Andrea L'Episcopo</strong>: "“Bayesian Nets and Causality” si segnala per numerosi e importanti meriti: in primo luogo, pur privilegiando un approccio pragmatico, riesce nella fondazione delle reti bayesiane con chiarezza e soprattutto con una rara compattezza teoretica; in secondo luogo, Williamson è capace di trarre con coerenza dai suoi assunti teorici le estreme conseguenze, e questo gli consente di proporre nuove applicazioni delle reti e di affrontare con autorevolezza problemi filosofici annosi e di vasta portata, come ad esempio quello dell’opposizione fra induzione e deduzione; infine, anche se forse sarebbe stato più opportuno spostare questo punto al principio, la definizione delle relazioni di influenza, il Bayesianesimo oggettivo e la causalità epistemica sono contributi al dibattito corrente di grande originalità e sistematicità, passibili di obiezioni, certo, ma solidi e ingombranti nella misura in cui non è possibile ignorarli. ... Nel complesso, il libro di Williamson è un contributo di grande importanza al dibattito su reti bayesiane, interpretazione del calcolo delle probabilità e teorie causali, e la fortuna che ha conquistato nei mesi trascorsi dalla sua pubblicazione è la migliore conferma di tale opinione.
This roughly translates as (thanks to Federica Russo for her help here):
"Bayesian Nets and Causality" stands out for its numerous and important merits: first, though it favours a pragmatic approach it succeeds in providing foundations for Bayesian networks with exeptional clarity and mostly with a rare theoretical compactness; second, Williamson is able to coherently draw the deep consequences of his theoretical assumptions, and this allows him to propose new applications of Bayesian networks and to powerfully face age-old and big philosophical problems, such as the opposition between induction and deduction; last, even though it would have been more appropriate to move this point to the beginning, the definition of influence relations, together with objective Bayesianism and epistemic causality are highly original and systematicly-developed contributions to the current debate. Of course they are liable to objection, but they are solid and important insofar as it is not possible to ignore them. ... All in all, Williamson's book is a contribution of great importance to the Bayesian network debate, to the interpretation of probability and theories of causality, and the success it gained in the months after its publication is the best confirmation of this opinion.

<strong>Minds and Machines 18:301-302 - Bradford McCall</strong>: "In sum, this book develops a systematic account of causal reasoning and shows how Bayesian nets can be coherently employed to automate the reasoning processes of an artificial agent. The resulting framework for causal reasoning involves new algorithms and new conceptual foundations."

<strong>British Journal for the Philosophy of Science 60:849-855 - Clark Glymour</strong>: this review put forward several criticisms which were rebutted in a response on pp. 857-860 of the same issue.

<h3>Errata</h3>
<em>I'd be very grateful if you can email me if you spot any errors that are not mentioned here - Jon Williamson.</em>

page, line

70, 22: "absence of empirical information" should read "absence of differentiating empirical information".

116, 7: "that our closest to our own world" should read "that are closest to our own world".

179, 12b: "B is a type of A" should read "A is a type of B".
<h3>Postscripts</h3>
Sections 5.5-5.8: I now call a Bayesian net representation of an objective Bayesian probability function an objective Bayesian net.

Sections 9.5-9.7: The analysis presented here has been refined in the appendix to my paper "Causal pluralism versus epistemic causality", available from my home page.