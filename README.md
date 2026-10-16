# AutomatorCopySelection

Adds a contextual menu item to the Finder in macOS that copies the path of the selected item(s) to the clipboard. Programmed in JavaScript for Automation (JXA).

🤖 **Built by the makers of [Agent!](https://github.com/AgentiLoop/Agent)**, an autonomous macOS agent. 🌐 [agentiloop.ai](https://agentiloop.ai)

## Files

- `Automator-TBCopySelection-Source.js` — JXA source for the Automator Quick Action.

## Install

1. Open **Automator** and create a new **Quick Action**.
2. Set *Workflow receives current* to **files or folders** in **Finder**.
3. Add a **Run JavaScript** action and paste in the contents of `Automator-TBCopySelection-Source.js`.
4. Save it. Right-click any file in Finder → **Quick Actions** to copy its path.
