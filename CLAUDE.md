# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Is

This is Greg's GitHub profile README: the special `gregdotca/gregdotca` repository, whose `README.md` GitHub shows at the top of https://github.com/gregdotca. There's no code, build, lint, or test step. The only content is `README.md` (plus `CHANGELOG.md`), and a change goes live as soon as it's pushed to `main` on the `public` remote.

## README Structure

- **Stats cards** at the top are four [github-cool-readme](https://github.com/pedrocatalao/github-cool-readme) cards (summary, languages, contributions, and weekly rhythm), in two rows, laid out as that tool's README suggests:
  - A scheduled job outside this repo builds them daily and force-publishes them as a single orphan commit on this repo's `cards` branch. Never edit, rebase, or delete that branch; it's replaced on every run.
  - The README loads them from `https://raw.githubusercontent.com/gregdotca/gregdotca/cards/<name>-light.svg` and `-dark.svg`, each in a `<picture>` whose dark `<source>` follows the viewer's GitHub theme.
  - Widths follow the tool's README: summary and contributions 450, languages and weekly 350, so a wide and a narrow card share a row.
- **Intro text** points readers to the pinned repositories GitHub shows below the README, to Greg's DomainMOD and AI Code Rating organizations, and to https://greg.ca/projects/. Individual repos aren't listed in the README; featured projects are shown with GitHub's pins instead.
- **Contact list** mirrors https://greg.ca/contact/. Keep it in sync with that page rather than editing entries on their own. Each contact line except the last ends in two trailing spaces (Markdown hard line breaks), so don't strip trailing whitespace. The email line deliberately lists both `greg@greg.ca` and `greg@chetcuti.com`; keep both and don't flag `greg@greg.ca` as an old address here.

To check a change, preview the rendered Markdown (GitHub's preview or any Markdown viewer) and open the image URLs to make sure the cards still load.
