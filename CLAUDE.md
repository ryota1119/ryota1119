# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a [GitHub profile repository](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme). The sole file is `README.md`, whose contents are rendered directly on the GitHub profile page at github.com/ryota1119.

There is no build system, test suite, or application code. All work here is editing the `README.md` markdown/HTML.

## README structure

The README uses a mix of GitHub-flavored Markdown and raw HTML. Key sections:

- **Profile view counter** — `komarev.com/ghpvc` badge (top-right)
- **Skills** — `skillicons.dev` icon strip; icons are controlled by the `&i=` query parameter
- **Activities** — two `github-readme-stats.vercel.app` cards (stats + top languages), both themed `vue-dark`
- **Currently Working On** — pinned repo cards also via `github-readme-stats`

When editing skills icons, the full list of available icon slugs is linked in the source comment: `https://arc.net/l/quote/zizyykfh`.
