# Built-in features for pocket-ledger-os

Purpose: personal finance

1. **organize work and records** — run pocket-ledger-os-workspace. It creates ~/Documents/pocket-ledger-os-workspace/ with Tasks, Records, Reference folders.
2. **plan a focused work session** — run pocket-ledger-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/pocket-ledger-os-session-plans/.
3. **check records and task readiness** — run pocket-ledger-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/pocket-ledger-os-workspace features/pocket-ledger-os-plan features/pocket-ledger-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for personal finance:

1. **GNOME Calendar** — org.gnome.Calendar
2. **VSCodium** — com.vscodium.codium
3. **GIMP** — org.gimp.GIMP

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.
