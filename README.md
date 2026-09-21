# Caylee McShane

Data scientist working on applied machine learning, multi-agent systems, and AI safety.

This repository hosts my personal site: **https://cayleemcshane.github.io** *(update once Pages is live)*.

---

## About

I design and ship systems built on teams of LLM agents — role hierarchies, dispatch patterns, and shared-memory coordination. Working with these systems daily is what drew me to AI safety: the coordination that makes an agent team effective also makes its behavior harder to oversee. My research applies that hands-on experience to the **AI control** problem for multi-agent deployments.

## Research

**Fragmented Oversight: How Multi-Agent Team Structure Affects Monitorability Under Distributed Attacks** — *in progress, 2026*
An AI-control study of how coordinated agents built on the same model can pursue a hidden objective, and how team topology and monitor placement change whether that behavior stays detectable. Built on Inspect and ControlArena; all adversarial testing runs inside a synthetic sandbox against self-built monitors.
→ [Link to the research repo]([LINK-TO-RESEARCH-REPO])

*(Add writeups and links here as you publish them.)*

## Elsewhere

- Email — [you@email.com](mailto:caylee.mcshane@gmail.com)
- GitHub — [github.com/[username]](https://github.com/caylee-mcshane)
- LinkedIn — [linkedin.com/in/[username]](https://linkedin.com/in/caylee-mcshane)
- LessWrong — [profile link]([profile-link])

---

## Running this site locally (optional)

The site is a single self-contained `index.html`, so you can just open it in a browser. To preview the full GitHub Pages build with Jekyll:

```bash
gem install bundler jekyll
bundle exec jekyll serve
```

Then open `http://localhost:4000`.

## Publishing

1. Push this repo to GitHub.
2. Go to **Settings → Pages**, set the source to the `main` branch (root), and save.
3. Wait for the build, then visit `https://[username].github.io/[repo-name]`.
