# Framewise Method

Public method notes for diagnosing weak YouTube packaging before publish.

![Framewise Method social preview](assets/github-social-preview.png)

[![Website](https://img.shields.io/badge/website-framewise.art-c57324?style=flat-square)](https://framewise.art)
[![License: MIT](https://img.shields.io/badge/license-MIT-2f231f?style=flat-square)](LICENSE)
[![Focus](https://img.shields.io/badge/focus-packaging%20diagnosis-3e8b82?style=flat-square)](https://framewise.art)

Framewise is for the moment before publish when the idea may be fine, but the package still is not earning the click.

If this repo helps you think more clearly about titles, thumbnails, audience fit, or low CTR diagnosis, star it and reuse the language.

Live product:

[`framewise.art`](https://framewise.art)

## What you can use this repo for

- Diagnose why a package feels weak before rewriting everything
- Reuse a clearer language for title + thumbnail reviews
- Study bad vs better examples instead of generic advice
- Borrow a lightweight output schema for explainable evaluator projects

## Why this exists

Most creator tools jump straight to generating more titles.

Framewise starts one step earlier:

- What feels weakest in this package?
- Why was it flagged?
- What should be fixed first?

The core idea is simple:

`A lot of low CTR problems are packaging problems, not content problems.`

## What this repo gives you

This is the public method layer behind Framewise.

Inside this repo you will find:

- a rubric for the five packaging checks
- concrete bad vs better examples
- diagnosis notes for audience fit and low CTR
- a lightweight public-facing output schema
- links back to the live evaluator and guide pages

## What is public here

- packaging dimensions
- bad vs better examples
- diagnosis notes
- a lightweight output schema
- links back to the live evaluator and guide pages

## What is intentionally not public here

- production app source
- private environment configuration
- internal prompts and orchestration
- commercial implementation details
- full product logic and scoring internals

## The core questions

Framewise is built around a few simple questions:

- Is the package clear enough fast enough?
- Does it feel specific, or still too broad?
- Is there an actual reason to click now?
- Does the right viewer feel this is for them?
- Are the title and thumbnail helping each other?

## The five packaging checks

Framewise currently evaluates packages across five dimensions:

1. Clarity
2. Specificity
3. Click Motivation
4. Audience Fit
5. Packaging Synergy

These checks are designed to catch issues like:

- the title is too vague
- the package does not signal who it is for clearly enough
- the click reason is not obvious fast enough
- the thumbnail and title repeat instead of helping each other

## Quick tour

Start with these files:

- [rubric/packaging-dimensions.md](rubric/packaging-dimensions.md)  
  Read the five packaging checks in plain language.
- [examples/bad-vs-better.md](examples/bad-vs-better.md)  
  See how stronger packaging usually becomes clearer, not fancier.
- [examples/audience-fit.md](examples/audience-fit.md)  
  See why naming a broad audience is not the same as audience fit.
- [examples/low-ctr-diagnosis.md](examples/low-ctr-diagnosis.md)  
  See how low CTR can be reframed as a packaging diagnosis problem.
- [schema/framewise-output-schema-lite.md](schema/framewise-output-schema-lite.md)  
  Reuse the public output shape if you are building your own evaluator.
- [links/product-and-guides.md](links/product-and-guides.md)  
  Jump back into the live product and focused guide pages.

## How to use this rubric

If you want to apply the method quickly, use this order:

1. Read the draft title and thumbnail once without overthinking.
2. Ask which of the five checks feels weakest first:
   - clarity
   - specificity
   - click motivation
   - audience fit
   - packaging synergy
3. Write one short sentence for the weakness:
   - "The title is too broad."
   - "The click reason is still foggy."
   - "The audience signal is too generic."
4. Decide the first fix before rewriting everything:
   - make the topic more concrete
   - sharpen the reason to click
   - narrow the intended viewer
   - make title and thumbnail do different jobs
5. Only then generate alternatives.

In practice, the method usually works best when you do not ask,
"Can I make this sound better?"

Ask:

- What is still unclear?
- What is still too broad?
- Why should the right viewer click now?

## Quick example

Same topic. Two very different packages.

Bad package:

`Faceless Channels Need This`

Better package:

`Why Most Faceless YouTube Channels Stay Stuck`

Why the second one is stronger:

- it names the audience
- it names the problem
- it gives a clearer reason to click

Main lesson:

Stronger packaging is usually not about sounding fancier.

It is about helping the right viewer understand, quickly:

- this is for me
- this is my problem
- this is why I should click

## Repo structure

```text
framewise-method/
├── README.md
├── LICENSE
├── examples/
│   ├── bad-vs-better.md
│   ├── audience-fit.md
│   └── low-ctr-diagnosis.md
├── schema/
│   └── framewise-output-schema-lite.md
├── rubric/
│   └── packaging-dimensions.md
└── links/
    └── product-and-guides.md
```

## Who this is for

This repo is most useful for:

- YouTube creators
- faceless channel operators
- creator-tool builders
- people trying to think more clearly about packaging before publish

## When to use the live product

Use the repo when you want the method.

Use the live product when you want:

- a quick packaging score
- a weakest-area call
- a best next move
- example rewrites and thumbnail directions

If you want the actual evaluator instead of just the public method notes:

[`framewise.art`](https://framewise.art)
