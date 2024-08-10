# Infinite Jests and Bounded Recognitions- to P or != NP ? 
<p align="center">
  <img alt="aidan arg" src="https://github.com/user-attachments/assets/f10516e5-4880-4d3b-947d-316d03f082db" style=width:65%;>
</p>

On X last week, Aidan🐐[https://x.com/aidan_mclau] made an intriguing claim: "It's easier to spot good ideas than to generate them." This assertion quickly gained traction, with many jumping in the comments and drawing parallels to the (in)famous P vs NP problem in computational complexity theory. However, upon closer examination, this _seemingly_ intuitive statement reveals itself to be a problematic overgeneralization that fails to capture the nuanced reality of idea generation and recognition across diverse domains.

So, let's explicate!

In fairness, the 'argument' is actually more a _statement_ than a structured logical argument with premises leading to a conclusion. As it stands, it's not a valid argument in the formal sense because it doesn't explicitly lay out the logical steps from premises to conclusion. Written another way, the original **proposition** suggests that it is generally easier to spot good ideas than to generate them across all important domains. There's a lot to unpack there, but we can start.

## The Argument and Its Formalization

Aidan's claim can be formalized as follows:

  </p>
<p align="center">
  ∀x(Important Domain(x) → S(G(x)) <  P(G(x)))
</p>

Where:

    G(x) represents "x is a good idea."
    S(x) represents "spotting x."
    P(x) represents "producing/generating x."

Firstly, the claim of universal applicability ("all" _important_ domains) is an overly broad generalization lacking supporting evidence. This formalization, while elegant, immediately raises concerns. It treats idea generation - (P(G(x))) - and recognition - (S(G(x))) - as cleanly separable, quantifiable, and universally comparable processes. In reality, these are often intertwined, iterative processes without clear boundaries.  Many ideas are generated through feedback from evaluation, while the evaluation process itself can involve creative generation. More on that towards the end.

## Overextending P

The invocation of P vs NP problem to justify this claim is thought-provoking but ultimately flawed. P vs NP is a specific conjecture within computational complexity theory, dealing with decision problems and the time complexity of deterministic vs. non-deterministic Turing machines. While it offers an intriguing analogy – verifying solutions (spotting ideas) vs. finding solutions (generating ideas) – extending this to all domains of human creativity and problem-solving is an unwarranted leap.

Moreover, P vs NP remains an unproven conjecture. Using it as a certain premise for a broad argument about idea generation and recognition is doubly tenuous. The generalization from computational complexity to all domains involves a _fallacy of division_, where characteristics of a specific type of problem (NP-complete problems) are incorrectly applied universally.

Further, how do we define "easier" across diverse domains? Consider the following possibilities:

1. Cognitive load: Measured by mental effort, time taken, or resources required.
2. Success rate: Frequency of generating/recognizing good ideas in a given timeframe.
3. Perceived difficulty: Subjective ratings by participants.

Each definition presents its own challenges. Measuring cognitive load for abstract processes like ideation is notoriously difficult. Success rates depend heavily on how we define "good ideas," which varies dramatically across fields. Perceived difficulty is subjective and influenced by factors like expertise and familiarity.
Furthermore, isolating idea generation from recognition processes poses significant methodological hurdles. In many real-world scenarios, these processes occur simultaneously or in rapid alternation. Any comprehensive study would need to account for domain-specific factors, individual differences, and the intertwined nature of idea generation and recognition.

Even in domains more amenable to formalization, the relative difficulty of idea generation and recognition is not some fixed universal law, but highly context-dependent.

In mature, well-explored fields, coming up with novel good ideas can indeed be harder than recognizing the value of existing ones; contrast that with fledlging/nascent, rapidly evolving areas, where the opposite is often true: generating ideas is easy while identifying the truly promising ones is hard due to lack of established evaluation criteria and proven track records. 

The cutting edge of any field tends to have this characteristic (which is why I've loved studying transformational change and paradigmatic change for the past decade!).

## Insights from Cognitive Science
Research offers valuable perspectives that challenge the universality of the original claim:

* Creative problem-solving often involves simultaneous generation and evaluation of ideas (Beaty & Silvia, 2012). This challenges the notion that these processes can be cleanly separated and compared.
* The 'incubation effect' suggests that idea generation can occur unconsciously (Gilhooly, 2016), making it difficult to compare with conscious recognition processes.
* fMRI studies indicate that idea generation and evaluation activate overlapping brain regions (Benedek et al., 2018), suggesting these processes are not entirely distinct.
* Research on 'aha! moments' shows that idea generation and recognition can occur simultaneously in sudden insights (Kounios & Beeman, 2014).
* Studies on expertise demonstrate that in some domains, experts can generate high-quality ideas more easily than novices can recognize them (Ericsson & Pool, 2016).

At a minimum, these findings suggest that the relationship between idea generation and recognition is far more **complex** and **context-dependent** than the original claim implies, varying with factors like domain expertise, problem type, and individual cognitive styles.

## Philosophical Considerations

We can additional scrutinize the claim's universality by by critically examining its key terms. What constitutes an "important domain"? The criteria for importance may vary dramatically across cultures, disciplines, and historical periods. Similarly, the concept of a "good idea" is highly contextual. 
_(Don't worry, I'm not about to launch into a discussion of Plato's forms.)_

In scientific research, a good idea might be one that is testable and has explanatory power 
_(this is a simplistic view, and in reality, more practitioners and experts probably subscribe to the views laid out by the likes of Bas van Fraassen/Lakatos/Longino)_

In art, it might be one that provokes emotion or challenges perceptions. 

In business, it could be one that increases profitability or solves a market need.

This subjectivity and context-dependence undermine the claim's validity as a universal principle. It highlights the need for a more nuanced understanding of ideation processes that accounts for the diverse nature of human creativity and problem-solving across different fields of endeavor.

## Ok Wat Do Weird Frok Man
###I deonomy: A Framework for Understanding

I'm a multidisiplinarian, so I'm going to advocate for an approach that is interdisiplinary in nature; this isn't to unnecessarily complexify things, rather to encourage consilience and eliminate waste and duplicative work where experts have already invested their time and passions. 

The emerging field of ideonomy, which seeks to study the nature and behavior of ideas systematically, offers a promising framework for addressing these complexities. Ideonomy recognizes that ideas are not merely static entities to be generated or recognized, but dynamic, evolving constructs that interact with their environment and with other ideas.

From an ideonomic perspective, the process of idea generation and recognition is not a linear, one-directional flow, but a complex network of interactions. This view aligns more closely with the cognitive science findings and philosophical considerations discussed earlier, suggesting that a more holistic approach is needed to understand the true nature of ideation.

### Appendix and dfs (sources follow):

**P vs NP dfs**

    P: the class of decision problems solvable by a deterministic Turing machine in polynomial time, while 
    NP:  the class of decision problems verifiable by a deterministic Turing machine in polynomial time given a suitable certificate. 
    NP-complete problems: the "hardest" problems in NP, to which any other NP problem can be reduced in polynomial time.

The equation P≠NP suggests that there exist problems for which solutions can be verified in polynomial time but not necessarily _solved_ in polynomial time. Some commenters generalized this to argue that the difficulty of generating good ideas always exceeds that of recognizing them in _any_ domain by connecting it to Aidan's original argument.

* read more here: https://stackoverflow.com/a/127831
* and here: https://en.wikipedia.org/wiki/P_versus_NP_problem

**Research Papers**
* https://www.researchgate.net/publication/380820358_Divergent_Creativity_in_Humans_and_Large_Language_Models


**Ideonomy Master Source**
* https://ideonomy.mit.edu/

**tl;dr**
tl;dr Validity hinges on the logical consistency within the premises: if we accept the premise that all domains can be reduced to a P vs NP problem, the argument might hold. But this is a big assumption, making the validity contingent on this equivalence. As I've tried to suggest, I don't think this is justified, and as such the generalization from computational complexity to all domains involves a _fallacy of division_, where characteristics of a specific type of problem (NP-complete problems) are incorrectly applied to all domains. Computational complexity, while loosely analogous in some ways, does not automatically port over to a universal law about the relative difficulty of idea generation and recognition across all domains.
