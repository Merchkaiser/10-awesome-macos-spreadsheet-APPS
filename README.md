# 10 Free & Open-Source Spreadsheet Apps for Mac

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![macOS](https://img.shields.io/badge/platform-macOS-111111?logo=apple)](https://www.apple.com/macos/) [![Free & open source](https://img.shields.io/badge/free-%26%20open%20source-2ea44f)](#selection-criteria)

> Compare 10 free, open-source spreadsheet apps for macOS—from full-featured Excel alternatives to offline-capable desktop tools and keyboard-first terminal spreadsheets.

Looking for an **Excel alternative for Mac** that lets you work with local files instead of depending on a cloud account? Start here. This independent directory compares 10 macOS spreadsheet apps by strengths, license, privacy caveats, and real-world Mac support—so you can find the right tool for your workflow, whether you need a powerful desktop suite or a lightweight terminal app.

**Quick picks:** [LibreOffice Calc](#desktop-spreadsheet-apps) for a full-featured general-purpose spreadsheet · [ONLYOFFICE](#desktop-spreadsheet-apps) for OOXML compatibility · [sc-im](#terminal-spreadsheets--data-tools) for a keyboard-driven terminal spreadsheet.

⭐ If this list helps you, **star the repo** so other Mac users can find it. Have a correction or a genuinely useful app to add? [Open an issue](https://github.com/Merchkaiser/awesome-macos-spreadsheets/issues) or [submit a pull request](https://github.com/Merchkaiser/awesome-macos-spreadsheets/pulls).

## At a glance

| App | Best for | macOS experience | License |
| --- | --- | --- | --- |
| [LibreOffice Calc](#desktop-spreadsheet-apps) | Full-featured, everyday spreadsheet work | Official desktop builds | MPL-2.0 / LGPL-3.0-or-later* |
| [ONLYOFFICE Desktop Editors](#desktop-spreadsheet-apps) | Excel/OOXML-oriented workflows | Official desktop builds | AGPL-3.0 |
| [Apache OpenOffice Calc](#desktop-spreadsheet-apps) | Familiar, local office suite | Official Mac downloads; check current compatibility | Apache-2.0 |
| [Calligra Sheets](#desktop-spreadsheet-apps) | KDE/Calligra suite users | Mac availability may require extra setup | LGPL-2.1-or-later* |
| [Gnumeric](#desktop-spreadsheet-apps) | Spreadsheet-focused analysis | Community/package-manager setup; not a mainstream Mac build | GPL-2.0-or-later |
| [Pyspread](#desktop-spreadsheet-apps) | Python-powered, unconventional spreadsheets | Python/GUI dependency setup | GPL-3.0-or-later |
| [900Sheets](#desktop-spreadsheet-apps) | Newer local-first desktop spreadsheet | macOS build workflow; review release status | Apache-2.0 |
| [sc-im](#terminal-spreadsheets--data-tools) | Vim-like terminal spreadsheet editing | Terminal; install/build dependencies | ISC* |
| [VisiData](#terminal-spreadsheets--data-tools) | Exploring and transforming tabular files | Terminal + Python | GPL-3.0 |
| [sc](#terminal-spreadsheets--data-tools) | Classic Unix terminal spreadsheet | Terminal; legacy/enthusiast option | Verify upstream/package license |

## Desktop spreadsheet apps

1. **[LibreOffice Calc](https://www.libreoffice.org/discover/calc/)** — The strongest all-round free Excel alternative for Mac: a mature spreadsheet with formulas, charts, pivot tables, and broad file-format support. Use local files without an account; optional online features are not required. Get the [official macOS download](https://www.libreoffice.org/download/) or browse the [source](https://github.com/LibreOffice/core). **License:** MPL-2.0 and LGPL-3.0-or-later; components may have additional licenses.

2. **[ONLYOFFICE Desktop Editors](https://www.onlyoffice.com/desktop.aspx)** — A polished office suite with a spreadsheet editor and strong Microsoft Office/OOXML compatibility. The desktop app can work on local files without a cloud account; cloud connections and AI integrations are optional. [macOS download](https://www.onlyoffice.com/download-desktop.aspx) · [Source](https://github.com/ONLYOFFICE/DesktopEditors) · **AGPL-3.0**.

3. **[Apache OpenOffice Calc](https://www.openoffice.org/product/calc.html)** — A familiar spreadsheet in a free, offline-capable office suite. It has official Mac downloads, but its release pace and macOS compatibility can lag; compare current requirements with LibreOffice before choosing it. [Download](https://www.openoffice.org/download/) · [Source](https://github.com/apache/openoffice) · **Apache-2.0**.

4. **[Calligra Sheets](https://calligra.org/sheets/)** — The spreadsheet app in the Calligra suite, suited to users already in the KDE ecosystem. It is local and open source, though a convenient, current macOS package may be harder to find than for LibreOffice or ONLYOFFICE. Check the [project](https://calligra.org/) and [source](https://invent.kde.org/office/calligra) for current Mac options. **License:** LGPL-family; verify the specific component’s license.

5. **[Gnumeric](https://gnome.pages.gitlab.gnome.org/gnumeric-web/)** — A spreadsheet-first application with a long history of strong formula and data-analysis features. It runs locally, but macOS is not its primary distribution target: expect package-manager, X11/XQuartz, or build-from-source setup rather than a standard Mac app download. [GNOME source](https://gitlab.gnome.org/GNOME/gnumeric) · **GPL-2.0-or-later**.

6. **[Pyspread](https://pyspread.gitlab.io/)** — A specialist spreadsheet that uses Python expressions in cells, for people who want a programmable grid rather than a conventional Excel clone. Open source and local; installation on macOS involves Python and GUI dependencies. [Project and install guidance](https://pyspread.gitlab.io/) · [Source](https://gitlab.com/pyspread/pyspread) · **GPL-3.0-or-later**.

7. **[900Sheets](https://github.com/900Labs/900Sheets)** — A newer local-first spreadsheet project focused on editable local workbooks and common import/export workflows. It is much less established than the major office suites; review its compatibility notes, release artifacts, and signing/notarization status before using it for important work. [Source, build instructions, and project privacy claims](https://github.com/900Labs/900Sheets) · **Apache-2.0**.

## Terminal spreadsheets & data tools

8. **[sc-im](https://github.com/andmarti1424/sc-im)** — A capable ncurses spreadsheet for the terminal, with Vim-inspired keyboard controls. A good fit for keyboard-first workflows and users comfortable installing command-line dependencies; it edits data locally. [Source and installation instructions](https://github.com/andmarti1424/sc-im) · **ISC** (see upstream license file).

9. **[VisiData](https://www.visidata.org/)** — A powerful terminal tool for exploring, editing, and reshaping CSV, TSV, Excel, and many other tabular formats. It is excellent for data work, but is **not a like-for-like desktop Excel replacement**. Runs locally on macOS with Python. [Install](https://www.visidata.org/install/) · [Source](https://github.com/saulpw/visidata) · **GPL-3.0**.

10. **[sc (Spreadsheet Calculator)](https://www.ibiblio.org/pub/Linux/apps/financial/spreadsheet/)** — A classic Unix terminal spreadsheet that can interest command-line enthusiasts. Its maintenance and modern macOS experience are limited compared with current desktop apps; treat it as a legacy option and verify the source and license supplied by your package. [Project/archive references](https://www.ibiblio.org/pub/Linux/apps/financial/spreadsheet/).

## How to choose

- **Want the best all-round free Mac spreadsheet?** Try **LibreOffice Calc** first.
- **Need Microsoft Office file-format compatibility?** Compare **ONLYOFFICE** and **LibreOffice** with your actual XLSX files.
- **Want a conventional GUI?** Choose one of the desktop apps above; **VisiData** and **sc-im** are terminal tools, not drop-in graphical replacements.
- **Want local-first software?** These projects can work on local files, but online integrations, update checks, and optional services differ by app and build.
- **Need zero network traffic?** Don’t rely on a list description alone. Test the exact version, disable online features, and monitor or block network access.

## Selection criteria

Apps are included because they are free/open source, spreadsheet-oriented, and have a plausible way to use them locally on macOS. This list is **not a ranking or a security audit**. To keep it useful, Mac distribution caveats and project maturity are stated rather than hidden.

**Privacy, plainly:** “Can edit local files” does not prove “never sends network traffic.” This list does not independently certify that every app, build, plugin, update checker, or optional feature is telemetry-free. If no telemetry or network access is a hard requirement, inspect the source and privacy documentation for the exact release, turn off optional services, and verify traffic yourself. Internet access may be needed to download or update an app.

Project support, minimum macOS versions, licenses, and privacy behavior change. Follow the official links for current requirements and license terms. *A license marked with an asterisk should be confirmed in the upstream license file for the version/component you use.*

## Not included

- **EtherCalc** — primarily a collaborative web application/server, not a standalone macOS spreadsheet app.
- **GNU Oleo** — legacy software without a practical current macOS recommendation.
- **Unverified newcomers** — projects such as SoloSheet or GridCraft should be added when their official source, license, Mac support, and offline behavior can be checked reliably.

## Contributing

Help make this the most useful **macOS open-source spreadsheet directory**: submit corrections, report outdated Mac support, or suggest an app. Please include an official project/source link, license, evidence of macOS support, and accurate notes on accounts, cloud features, and telemetry. Quality and verifiability beat padding the list.

---

Released under [CC0 1.0](LICENSE).
