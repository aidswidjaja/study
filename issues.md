---
title: "Known Issues"
layout: default
nav_order: 5
---

# Known Issues

## Move from remote to local Jekyll theme

Enhancement
{: .label .label-yellow}

1. Clone original git repo
2. Replace docs folder with my content
3. Replace root files with my root files

## Search function doesn't work

Bug
{: .label .label-red}

- Unescaped amps in search.rake
- search.rake succeeds with my own fix (yes I'm debugging errors of professional developers) but the search function still fails on localhost (`jekyll serve`)
- I'm currently waiting on a bugfix from the developers of Just the Docs, the theme I'm using on this website. In the meantime, use `Ctrl`+`F` on Windows or `Command`+`F` on Mac to find content within a webpage.
- [Click here for more information on the issue.](https://github.com/pmarsceill/just-the-docs/pull/218)

### Sidebar disappears when deployed with search-data.json content that pulls from the variable in search.rake

- how does that even happen? Could be related to new sidebar title override

## Sidebar title override added

Feature
{: .label .label-blue}

- Added new feature (copy and pasted from [ovr/just-the-docs](https://github.com/ovr/just-the-docs/blob/d45890e2b5d594bf2ba24c03f44e5f4dd6d9a76e/_includes/nav.html))
- Untested feature; to be tested after exams
- Check 6 November commit history if it has broken anything
- One of the netlify deploys have a half-working search function but because the variable was escaped it didn't read content

## Last modified

Feature
{: .label .label-blue}

- Will add this later; after exams