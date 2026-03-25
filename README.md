# Framewise Method

A lightweight public method repo for diagnosing YouTube packaging before publish.

Main product:

`https://framewise.art`

## What Framewise is

Framewise is not a generic title generator.

It is a pre-publish packaging read designed to answer:

- What feels weakest in this package?
- Why was it flagged?
- What should be fixed first?

The working idea behind the product is simple:

`A lot of low CTR problems are packaging problems, not content problems.`

## What this public repo contains

This repository intentionally exposes the method layer, not the full SaaS product.

Included here:

- public framing
- packaging dimensions
- example diagnosis notes
- bad vs better examples
- a lightweight output schema

Not included here:

- production app source
- private environment configuration
- internal prompts
- commercial implementation details

## The five packaging checks

Framewise currently frames packaging evaluation around five dimensions:

1. Clarity
2. Specificity
3. Click Motivation
4. Audience Fit
5. Packaging Synergy

These are meant to catch issues like:

- the title is too vague
- the package does not signal who it is for clearly enough
- the click reason is not obvious fast enough
- the thumbnail and title repeat instead of helping each other

## Example

Same topic. Two very different packages.

Bad package:

`Faceless Channels Need This`

Better package:

`Why Most Faceless YouTube Channels Stay Stuck`

The second one is stronger because it:

- names the audience
- names the problem
- gives a clearer reason to click

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

## Try the live product

If you want the actual evaluator instead of just the public method notes:

`https://framewise.art`
