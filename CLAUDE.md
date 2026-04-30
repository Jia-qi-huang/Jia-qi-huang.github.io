# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a personal academic webpage for Jiaqi Huang, hosted on GitHub Pages at `Jia-qi-huang.github.io`. It is a single static HTML file with no build system, package manager, or framework.

## Structure

- `index.html` — the entire site: profile photo, bio, working papers, and publications
- `photo.jpg` — profile photo displayed on the page

## Deployment

Changes pushed to the `main` branch are automatically published via GitHub Pages. There is no build step — edits to `index.html` go live directly after push.

## Layout

The page uses a two-column CSS Grid layout (`grid-template-columns: 30% 70%`) where the left column holds labels/headings and the right column holds content. New sections should follow the same pattern: a heading `<div>` on the left paired with a content `<div>` on the right.
