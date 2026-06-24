# Solution Documentation — Oliver och Piratprinsessan

**Last updated:** 2026-06-24

## Project Overview

An open-source children's book project. The goal is to make "Oliver och Piratprinsessan" freely available digitally and open-source, while also offering a print version via Amazon Kindle.

## Architecture

### Current (Initial State)

The project is asset-only at this stage — illustrations, character design templates, and a "Making Of" document. No application code exists yet.

### Repository

- **Remote**: https://github.com/iwarzon/OliverochPiratprinsessan
- **Visibility**: Public
- **Owner**: iwarzon (Robin Iwarzon)

### Asset Organization

- `Bilder/Final/` — Production-ready page illustrations (0.png through 27.png, plus omslag.png cover)
- `Bilder/Design templates/` — Character reference boards used for AI illustration consistency
- `Bilder/` (root level) — Work-in-progress and iteration images

## Future Architecture Decisions

Pending decisions for the digital reader platform:

- Static site vs. hosted web app
- Audio integration approach (embedded player vs. separate)
- Licensing model (Creative Commons variant)
