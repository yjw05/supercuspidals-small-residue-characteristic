# Supercuspidals in small residue characteristic

This repository is an open collaboration on explicit compact-induction constructions of
supercuspidal representations of reductive groups over nonarchimedean local fields. It is
inspired by the [Foruma discussion, “Types and compact-induction constructions for reductive
groups”](https://foruma.org/discussion/383a884f-bdbc-4a47-8399-221c892c0a4e), especially its
first-step question. Contributions from human researchers and AI-assisted work are welcome.

## The first question

Let $F$ be a nonarchimedean local field of residue characteristic $p$, and let
$G=\mathbf G(F)$, where $\mathbf G$ is a connected reductive $F$-group. We work with
smooth complex representations. How can one explicitly construct all irreducible
supercuspidal representations of $G$, including cases in small residue characteristic beyond
the scope of existing tame constructions?

The intended form of a construction is

$$
\pi\simeq \mathrm{c-Ind}_K^G\rho,
$$

where $K$ is open and compact modulo the center and $\rho$ is a finite-dimensional
irreducible smooth representation of $K$. An answer must address two separate questions:

1. **Construction:** which inducing data give irreducible supercuspidal representations, and why?
2. **Exhaustion:** why does every irreducible supercuspidal representation arise from the
   proposed data?

The existence and explicit determination of such data in this generality are research questions,
not results claimed by this repository. State separately what is proved, conjectural, or conditional.
The residue characteristic $p$ is not the characteristic of the coefficient field. Contributions
should distinguish equal and mixed characteristic and make all hypotheses on $F$, $G$, and $p$
explicit.

Classical approaches provide essential models and already cover substantial cases. For example,
the theory of Bushnell and Kutzko treats $\mathrm{GL}_n$, including wild ramification, and
Stevens's theory treats classical groups under its hypotheses, including odd residue
characteristic. Tame construction data and arbitrary wild data are distinct; small residue
characteristic alone does not determine which occurs. Please refer to the
[discussion](https://foruma.org/discussion/383a884f-bdbc-4a47-8399-221c892c0a4e) for its
literature list and precise context.

## Ways to contribute

- Prove a statement under explicit hypotheses, giving all steps needed to check it.
- Identify a specific gap or obstruction in a proposed construction or exhaustion argument.
- Work out a test case, with enough detail to reproduce the calculation and verify its scope.
- Check hypotheses, references, examples, or intertwining and irreducibility arguments.
- Formulate a precise conditional reduction that isolates an unresolved step.

Further goals include types for Bernstein components, explicit Hecke algebra comparisons,
reduction to depth zero, and central covering groups. These are separate from the first question.

## Collaboration

Start with an issue to describe a question or planned contribution, then submit a pull request
containing the argument, calculation, or correction. Small, independently checkable contributions
are encouraged. See [CONTRIBUTING.md](CONTRIBUTING.md) for a suggested format and review process.

AI agents may propose and review contributions. Their output is a starting point for mathematical
checking: passing an automated check or receiving an AI review does not prove a mathematical
claim. A maintainer reviews the evidence and decides whether to merge a pull request. A merged
contribution can still be corrected if a gap is found.

No general solution or comprehensive literature survey is asserted here. Please cite the original
sources for mathematical results and use issues or pull requests to report missing references.
