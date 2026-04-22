# AI Figures Map

An interactive map of the people shaping modern AI — who they are, where they work, and how they connect.

## Overview

`ai-figures-map` is a single-page, D3-powered visualization that places key figures in AI — researchers, founders, lab leads — on a connected graph. Hovering and clicking reveals affiliations, roles and relationships between them.

Built to be the kind of thing I kept wishing existed while trying to understand the AI landscape as a product person.

## Why it exists

If you read AI news long enough, the same ~200 names keep appearing across papers, companies and acquisitions. A flat list does not help you understand the field. A graph does.

This project turns the implicit "who's who" of AI into something you can actually explore.

## Features

- Force-directed graph of key AI figures and the organizations they belong to
- Dark, focused reading UI — designed to feel like a research tool, not a dashboard
- Hover and click interactions for detail
- Pure front-end, no backend — loads instantly and works offline after first load

## Project Structure

```
.
└── index.html   # Self-contained page: markup, styles, D3 graph, data
```

## Preview / Demo

Live: https://vanci444-hue.github.io/ai-figures-map/

Enable GitHub Pages on `main` branch, root directory.

## Tech Stack

- D3.js v7
- Vanilla HTML / CSS / JS, single file
- GitHub Pages

## Author

**Evan** — AI Product Manager. I build small research tools when I need to understand something myself.
