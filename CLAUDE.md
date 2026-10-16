# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Is

This is Greg's GitHub profile README: the special `gregdotca/gregdotca` repository, whose `README.md` GitHub shows at the top of https://github.com/gregdotca. There's no code, build, lint, or test step. The only content is `README.md` (plus `CHANGELOG.md`), and a change goes live as soon as it's pushed to `main` on the `public` remote.

## README Structure

- **Stats cards** at the top are images from external services, configured entirely through their URL query strings:
  - The stats and rank card comes from Greg's own deployment at `gregdotca-stats.vercel.app` (a github-readme-stats instance), using `count_private=true` and `role=OWNER,ORGANIZATION_MEMBER` so private and organization work is counted.
  - The streak card comes from the public `github-readme-streak-stats.herokuapp.com` service.
  - Both use the `prussian` theme; keep them matching when changing either.
- **Intro text** points to Greg's organizations (DomainMOD, HomelabAPI) and to https://greg.ca/projects/.
- **Contact list** mirrors https://greg.ca/contact/. Keep it in sync with that page rather than editing entries on their own. Each contact line except the last ends in two trailing spaces (Markdown hard line breaks), so don't strip trailing whitespace. The email line deliberately lists both `greg@greg.ca` and `greg@chetcuti.com`; keep both and don't flag `greg@greg.ca` as an old address here.

To check a change, preview the rendered Markdown (GitHub's preview or any Markdown viewer) and open the image URLs to make sure the cards still load.
