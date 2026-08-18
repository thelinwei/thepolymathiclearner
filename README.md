# The Polymathic Learner

**A visual learning archive where design, mathematics, geometry, speculative thought and AI meet.**

Twenty-four self-contained interactive documents. Every one began as something not
understood; each is an attempt to give an abstraction a body that can be turned, tested
and broken, on the premise that the understanding arrives through the handling rather
than before it.

The register is closer to art than to engineering — research as speculative play.
Nothing here is a product. The questions were chosen because they are strange enough
to be worth living inside for a while: what mathematics other civilisations might have
grown, what shapes know that proofs do not, and what a three-thousand-year-old book
about change would look like if it could actually move.

**Live:** https://thelinwei.github.io/thepolymathiclearner/

---

## Current investigation — 易 *Yi*, a working model of change

The newest strand, and the reason this repository is being shared now.

易 *yi* is not an abandoned machine waiting to be switched back on. 阴阳 *yinyang*,
五行 *wuxing* and 八卦 *bagua* are carried in Chinese cultural memory as a working
grammar of relation — advance and retreat, fullness and emptiness, timing and
position — and the sequence therefore **begins with the inheritance**, not with the
reconstruction. Two genealogies are held side by side: the lineage the tradition tells
about itself, and what texts, inscriptions and archaeology can presently demonstrate.

Only then does it put the second question. Divination was a pre-computational
technology for thinking under uncertainty: framing, constrained variation, symbolic
encoding, retrieval, judgment. So what happens when that inheritance is rebuilt with
instruments its makers did not have — continuous variables, trajectories,
counterfactuals, graph theory, a model that can disagree with its makers?

This project does **not** claim the *Yi* secretly contained hypercubes or differential
equations. It asks what becomes visible when an inherited symbolic technology is
reconstructed with contemporary formal and computational tools.

**The argument** runs in order, 00 to 03. **The instruments** can be opened in any order —
three turnable bodies, each of which the argument earns. The double cube belongs to 00–03;
the lantern and the loom ask a separate question: what single shape holds all sixty-four
with their adjacencies intact?

### The argument

| | Document | What it establishes |
|---|---|---|
| 序 00 | [`yi-0-inheritance.html`](yi-0-inheritance.html) | The inheritance. Two genealogies — received and critically reconstructed — how 阴阳, 五行 and 八卦 were braided into one language, and divination as pre-computational procedure |
| 一 01 | [`yi-1-state-space.html`](yi-1-state-space.html) | 爻 *yao* as a dial rather than a switch; the sixty-four as sign-regions of a six-cube |
| 二 02 | [`yi-2-motion.html`](yi-2-motion.html) | Velocity: which line turns next, in how long, and whether you are arriving or leaving |
| 三 03 | [`yi-3-forces.html`](yi-3-forces.html) | 五行 *wuxing* read as five verbs — a vector field over the whole space |

### The instruments

| | Document | What it does |
|---|---|---|
| 儀 04 | [`yi-4-instrument.html`](yi-4-instrument.html) | **The double cube** — 兩儀 *liǎngyí*, the two forms. Bounded dynamics, an inverse solver, a measured reach/foresight frontier |
| 灯 05 | [`yi-5-lantern.html`](yi-5-lantern.html) | **The lantern** — sixty-four beads on a single closed curve |
| 織 06 | [`yi-6-loom.html`](yi-6-loom.html) | **The loom** — the sixty-four on a torus; the thread is a shuttle, not a knot |
| 灯 — | [`yi-lantern-thinking.html`](yi-lantern-thinking.html) | Companion: how the lantern was arrived at, and why its shape was not chosen |

**Status: in progress, deliberately.** Part Four carries two retracted claims. The loom's
surface is settled but its ordering is not, and two open questions are stated at the end
of that document rather than tidied away. An archive about learning should show the edge
as the edge actually looks.

## The archive

| Collection | Focus |
|---|---|
| **I — Speculative & Play** | Epistemic plurality: 算學 *suanxue*, Daoist relationality, xenomathematics, game theory beside Sun Tzu |
| **II — Geometry** | Instruments for thinking-through-making: minimal surfaces, phyllotaxis, Voronoi, Penrose tiling |
| **III — Representation** | Formal ideas given interactive form: Calabi–Yau manifolds, modelling, higher-dimensional epistemology |
| **IV — Reflection & Method** | Reflection as a designed condition; the limits of formal self-knowledge; second-order cybernetics |

## Technical notes

Every document is a single HTML file. No build step, no framework, no network calls at
runtime. Mathematics is set with KaTeX where available and degrades to plain text where
it is not; fonts degrade gracefully. Rendering is canvas-based. Open any file directly
in a browser, or clone and serve the directory.

```
git clone https://github.com/thelinwei/thepolymathiclearner.git
cd thepolymathiclearner && python3 -m http.server 8000
```

## Authorship

**Lin Wei 林威** (writing as **linwei**) — direction, argument, design, and the objections that
killed four geometries.
With **Claude** (Anthropic) and **ChatGPT** (OpenAI) as sustained collaborators, and light
touches of **DeepSeek**. The AI contribution is not decorative and it is not concealed:
these documents were argued into existence in dialogue, and where a model's claim was
wrong the retraction is recorded in the document rather than quietly patched.

## Collaboration

These documents were built as instruments for thinking, but several have turned out to
work as exhibition objects — they are interactive, self-contained, projectable, and they
hold an argument rather than merely illustrating one. That direction is open and actively
of interest.

Enquiries welcome from **researchers** (history and philosophy of mathematics, epistemology,
design research, learning sciences), **artists and curators**, and **galleries, museums and
festivals** considering interactive or computational work. Collaboration, exhibition,
commissioning, residency and teaching conversations are all in scope.

Open an issue on this repository, or reach out through https://thelinwei.github.io.

## Citation

See [`CITATION.cff`](CITATION.cff). Short form:

> Lin Wei, with Claude and ChatGPT (2026). *The Polymathic Learner: a visual learning
> archive*. https://thelinwei.github.io/thepolymathiclearner/

To cite one document, name it: *易 Yi · The Loom — the sixty-four on a torus* (2026),
in *The Polymathic Learner*.

## Licence

Text, figures and design: **CC BY-NC-SA 4.0** — share and adapt for non-commercial
purposes with attribution, under the same terms. Code within the documents: **MIT**.
For commercial, exhibition or publication use, please ask; the answer is usually yes.
