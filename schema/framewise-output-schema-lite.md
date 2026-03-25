# Framewise Output Schema Lite

This is a lightweight public-facing representation of the Framewise result shape.

## Input

- `title`
- `thumbnailText`
- `thumbnailImageUrl` (optional, image-aware mode)
- `summary`
- `audience`

## Top-level output

- `totalScore`
- `publishRead`
- `weakestArea`
- `topNextMove`
- `thumbnailReadMode`
- `visualConfidence`
- `dimensionScores`
- `rewriteSuggestions`
- `thumbnailSuggestions`

## Dimension score card

Each dimension can include:

- `score`
- `summary`
- `problem`
- `whyItWasFlagged`
- `fixFirst`
- `evidenceSource`

## Current dimensions

- `clarity`
- `specificity`
- `clickMotivation`
- `audienceFit`
- `packagingSynergy`

## Purpose

The result format is designed to answer:

- what is weak
- why it is weak
- what to fix first

without reducing the whole workflow to “generate more ideas.”
