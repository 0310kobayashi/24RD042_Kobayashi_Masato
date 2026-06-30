# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

A personal practice repository created during a university Git lecture
(`Jyugyoude_Thukutta_repository_git_no_recture` — "a repository made in class, the Git lecture").
It is a learning sandbox, not a production project: there is no build system, no
package manager, no test suite, and no application framework.

## Contents

- `index.html` — a single static "Hello World" HTML page (Japanese `lang="ja"`).
- `README.md` — short notes, partly written in romaji Japanese.
- `.gitattributes` — enables automatic LF normalization (`* text=auto`).

## Working in this repo

- There is nothing to build or test. To view the page, open `index.html` directly
  in a browser (no server required).
- The primary activity here is practicing Git itself (commits, edits, history).
  Expect commits to be small, exploratory, and sometimes in Japanese.
- Line endings are normalized to LF on commit via `.gitattributes`; keep that in mind
  on Windows where the working tree may use CRLF.
