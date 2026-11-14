# Awesome macOS Spreadsheets [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Free and open-source spreadsheet applications that can be used locally on macOS, without requiring an account or cloud service.

This is a **curated list, not a ranking**. Entries are included only when the project is a genuine spreadsheet app or spreadsheet-oriented terminal tool, is free/open source, and has a credible local macOS use path. Most can operate entirely offline after download/installation. Optional cloud connectors are called out. “No telemetry” is not a blanket security guarantee: check the app’s current documentation and network behavior for your own requirements.

## Contents

- [Desktop apps](#desktop-apps)
- [Terminal apps](#terminal-apps)
- [Not included in the top list](#not-included-in-the-top-list)
- [Criteria and privacy notes](#criteria-and-privacy-notes)
- [Contributing](#contributing)

## Desktop apps

1. **[LibreOffice Calc](https://www.libreoffice.org/discover/calc/)** — Mature, full-featured desktop spreadsheet with broad formula and file-format support. Free and open source; runs locally and can be used without an account or cloud service. Optional online integrations are not required. [Download](https://www.libreoffice.org/download/) · [Source](https://github.com/LibreOffice/core) · MPL-2.0/LGPL-3.0-or-later (project components may use other licenses).

2. **[ONLYOFFICE Desktop Editors](https://www.onlyoffice.com/desktop.aspx)** — Desktop suite with a spreadsheet editor and strong OOXML compatibility. The desktop app can edit local files without signing in; cloud connections and AI integrations are optional. [Download](https://www.onlyoffice.com/download-desktop.aspx) · [Source](https://github.com/ONLYOFFICE/DesktopEditors) · AGPL-3.0.

3. **[Apache OpenOffice Calc](https://www.openoffice.org/product/calc.html)** — Offline desktop spreadsheet in the Apache OpenOffice suite. Includes local spreadsheet editing and common spreadsheet features; releases and macOS compatibility may lag behind LibreOffice, so check the current download’s platform requirements. [Download](https://www.openoffice.org/download/) · [Source](https://github.com/apache/openoffice) · Apache-2.0.

4. **[Calligra Sheets](https://calligra.org/sheets/)** — Spreadsheet component of the Calligra suite. Open source and local-first; macOS packaging/support may be less straightforward than the mainstream options, so verify current macOS build availability before installing. [Project/source](https://invent.kde.org/office/calligra) · LGPL-2.1-or-later (verify component licensing).

5. **[Gnumeric](https://gnome.pages.gitlab.gnome.org/gnumeric-web/)** — Spreadsheet-focused desktop application known for its analysis and formula tools. Runs locally. macOS is not its primary distribution target and may require a package manager, X11/XQuartz, or building from source; confirm current support before relying on it. [Source](https://gitlab.gnome.org/GNOME/gnumeric) · GPL-2.0-or-later.

6. **[Pyspread](https://pyspread.gitlab.io/)** — A distinctive Python-based spreadsheet with a grid-oriented interface and Python expressions. Free/open source and local; installation on macOS uses Python and GUI dependencies, so it is best for technically comfortable users. [Source](https://gitlab.com/pyspread/pyspread) · GPL-3.0-or-later.

7. **[900Sheets](https://github.com/900Labs/900Sheets)** — Local-first spreadsheet desktop app with a native macOS build workflow, local workbooks, and common exchange formats. Newer and less mature than the established suites; inspect compatibility notes and release provenance before using it for important data. Its project describes the app as offline-capable and without telemetry or an account requirement. [Source and build instructions](https://github.com/900Labs/900Sheets) · Apache-2.0.

## Terminal apps

8. **[sc-im](https://github.com/andmarti1424/sc-im)** — Vim-inspired ncurses spreadsheet program for the terminal. Runs locally on macOS when installed/built with its dependencies; suitable for keyboard-driven editing of tabular sheets. [Source and installation instructions](https://github.com/andmarti1424/sc-im) · ISC (see the repository’s license file).

9. **[VisiData](https://www.visidata.org/)** — Terminal interface for exploring, editing, and arranging tabular data, including CSV, TSV, and Excel files. It is a versatile data tool rather than a conventional full spreadsheet replacement; works locally on macOS with Python. [Install/docs](https://www.visidata.org/install/) · [Source](https://github.com/saulpw/visidata) · GPL-3.0.

10. **[sc (Spreadsheet Calculator)](https://www.ibiblio.org/pub/Linux/apps/financial/spreadsheet/)** — Classic terminal spreadsheet for Unix-like systems. It can be built/run locally on macOS, but development and documentation are comparatively quiet; treat as a legacy/enthusiast option and check the package’s current source and license before installing. [Source archive and references](https://www.ibiblio.org/pub/Linux/apps/financial/spreadsheet/).

## Not included in the top list

- **EtherCalc** is a collaborative web application/server, not a standalone macOS spreadsheet app. A self-hosted instance may be run locally, but it does not meet the same simple offline desktop-app criteria.
- **GNU Oleo** is an old, effectively legacy spreadsheet project and is not recommended as a current macOS option.
- **SoloSheet / GridCraft**: not included until their official source, license, macOS distribution, and local/offline behavior can be independently verified well enough for this list.

## Criteria and privacy notes

- Entries must be free to use and have an open-source license for the relevant application.
- The application must be usable on macOS, either through a maintained macOS build or a documented local source/package-manager installation. Entries with caveats say so.
- A network connection may be needed to download/install software, check updates, or use optional cloud features. “Local-only” here means spreadsheet files can be created/edited locally without a hosted account or required cloud storage; it does **not** assert that every build makes zero network requests in every configuration.
- “No telemetry” claims are not independently guaranteed by this list. Disable optional online features and audit the relevant version/build if zero network traffic is a strict requirement. A firewall or network monitor can help verify behavior.
- macOS support, minimum OS versions, licenses, and project activity change. Check each project’s official release notes and license before adoption.

## Contributing

Suggestions and corrections are welcome. Please open an issue or pull request and include official project/source links, the applicable license, evidence of macOS support, and a clear note about required accounts, cloud features, and telemetry. Do not add a tool solely to reach a numerical target; accuracy matters more than having ten entries.

---

This list is released under [CC0 1.0](LICENSE).
