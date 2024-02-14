---
permalink: /
title: "Hej!"
# excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a Ph.D. student in the computational mathematics division of the
department of mathematics at Stockholm University. Here, I'm doing a project on homotopy type theory under the supervision of Anders Mörtberg.

My primary research interests are synethetic homotopy theory and
computer formalisation, primarily in Cubical Agda. So far, my project
has mainly concerned the formalisation of cohomology theories and
Guillaume Brunerie's Ph.D. thesis. I'm interested in anything HoTT related. If you are too and would like to work on something together, please get in touch!

## Current projects
### The Steenrod squares in HoTT (joint with David Wärn)
David and I are trying our best to develop the theory of Steenrod squares in HoTT. While the Steenrod squares were defined in HoTT by Guillaume Brunerie in 2017, we are trying to verify the various axioms governing this cohomology operation. In particular, we are trying to verify the Cartan formula, Adem relations and the suspension axiom.

### Cellular (co)homology (joint with Anders Mörtberg and Loïc Pujet)
Cellular cohomology was developed by Buchholtz and Favonia in <a href="https://arxiv.org/abs/1802.02191">2018</a>. We are investigating whether their constructions can be used to develop (co)homology in a way that does not rely on previously defined cohomology theories. Thus far we have proved a version of the cellular approximation theorem and, using this, defined a homology functor. We are currently verifying that it satisfies the Eilenberg-Steenrod axioms.


### Whitehead products in HoTT
Whitehead products were extensively used in Guillaume Brunerie's Ph.D. thesis but few of their algebraic properties (e.g. bilinearity, graded commutativity, etc.) have been verified in HoTT. I'm currently working on verifying these, both in pen-and-paper HoTT and in Cubical Agda.
