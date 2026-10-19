# Built-in features for citewise-os

Purpose: academic research

1. **prepare study and research files** — run citewise-os-workspace. It creates ~/Documents/citewise-os-workspace/ with Notes, Sources, Assignments folders.
2. **plan a learning session** — run citewise-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/citewise-os-session-plans/.
3. **check study and source readiness** — run citewise-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/citewise-os-workspace features/citewise-os-plan features/citewise-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for academic research:

1. **Anki** — net.ankiweb.Anki
2. **LibreOffice** — org.libreoffice.LibreOffice
3. **VSCodium** — com.vscodium.codium

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for academic research:

1. **FreeCAD** — design mechanical parts (org.freecadweb.FreeCAD)
2. **OpenSCAD** — model parametric 3D parts in code (org.openscad.OpenSCAD)
3. **KiCad** — design circuits and PCBs (org.kicad.KiCad)
4. **Arduino IDE** — write and upload microcontroller sketches (cc.arduino.IDE2)
5. **Blender** — create 3D assets and animations (org.blender.Blender)
6. **PrusaSlicer** — prepare models for 3D printing (com.prusa3d.PrusaSlicer)
7. **DB Browser for SQLite** — inspect SQLite databases (org.sqlitebrowser.sqlitebrowser)
8. **Wireshark** — inspect network traffic (org.wireshark.Wireshark)
9. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
10. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **QElectroTech** (org.qelectrotech.QElectroTech) — draw electrical schematics and wiring diagrams.
2. **LibreCAD** (org.librecad.librecad) — draft precise 2D technical drawings.
3. **DBeaver Community** (io.dbeaver.DBeaverCommunity) — browse, query, and manage SQL databases.
4. **Gitg** (org.gnome.gitg) — review Git history and branches graphically.
5. **GeoGebra Classic** (org.geogebra.GeoGebra) — explore geometry, algebra, graphing, and 3D math.
6. **Xournal++** (com.github.xournalpp.xournalpp) — annotate PDFs and take handwritten notes.
7. **JabRef** (org.jabref.jabref) — organize BibTeX references and research citations.
8. **Stellarium** (org.stellarium.Stellarium) — explore a planetarium sky for astronomy learning.
9. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
10. **Evolution** (org.gnome.Evolution) — manage email, calendars, and contacts.
11. **RawTherapee** (com.rawtherapee.RawTherapee) — develop RAW photo files with tone and color controls.
12. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
13. **GNOME Text Editor** (org.gnome.TextEditor) — edit plain-text notes and configuration files.
14. **GNOME Logs** (org.gnome.Logs) — inspect logs during troubleshooting.
15. **Disk Usage Analyzer** (org.gnome.baobab) — find large files and manage storage.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.

## Fifteen further purpose-specific preinstalled applications

This second batch adds another set of apps selected for this setup’s purpose. They are installed from Flathub by the setup scripts.

1. **KDevelop** (org.kde.kdevelop) — edit, navigate, build, and debug software projects.
2. **Kate** (org.kde.kate) — edit configuration, code, notes, and structured project files.
3. **Okular** (org.kde.okular) — read, bookmark, and annotate technical drawings, reading lists, and reference PDFs.
4. **KCalc** (org.kde.kcalc) — run scientific and unit calculations for coursework or technical work.
5. **Dolphin** (org.kde.dolphin) — organize project assets and inspect folders.
6. **Ark** (org.kde.ark) — open and create common project archive files.
7. **Filelight** (org.kde.filelight) — find large folders and reclaim disk space.
8. **Meld** (org.gnome.meld) — compare and merge source files, folders, and Git changes.
9. **KDiff3** (org.kde.kdiff3) — compare and merge source files and directory trees.
10. **Warehouse** (io.github.flattool.Warehouse) — review installed Flatpaks, manage versions, and clean app data.
11. **Marble** (org.kde.marble) — explore maps and a virtual globe for geographic context.
12. **KStars** (org.kde.kstars) — plan sky observations and explore astronomy simulations.
13. **KGeography** (org.kde.kgeography) — practice country, capital, and map recognition.
14. **Rnote** (com.github.flxzt.rnote) — sketch diagrams, write by hand, and annotate pictures or documents.
15. **Konsole** (org.kde.konsole) — run shell commands and inspect development or system tasks.

Game frontends do not include proprietary game data; add only games or files you are allowed to use.
