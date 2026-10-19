# Built-in features for citewise-os

Purpose: academic research

1. **prepare study and research files** — run citewise-os-workspace. It creates ~/Documents/citewise-os-workspace/ with Notes, Sources, Assignments folders.
2. **plan a learning session** — run citewise-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/citewise-os-session-plans/.
3. **check study and source readiness** — run citewise-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/citewise-os-workspace features/citewise-os-plan features/citewise-os-check "$HOME/.local/bin/"
