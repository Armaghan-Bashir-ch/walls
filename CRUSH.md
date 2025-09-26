# CRUSH.md

This repository contains a collection of desktop wallpapers organized by themes such as Catppuccin, Gruvbox, and others. There is no source code, so no build, lint, or test commands apply.

## Commands
- No build command.
- No lint command.
- No test command (or single test).
- To view images: Use `feh *.png` or similar image viewer in subdirectories.
- To list all wallpapers: `find . -name "*.png" -o -name "*.jpg" -o -name "*.gif" | sort`

## Code Style Guidelines
N/A - This is not a code project. Files are images with descriptive names using hyphens and capitalization (e.g., Abstract-FantasyWorldArt.png).

## Organization
Wallpapers are grouped in theme-based subdirectories. Naming convention: Theme-Color/ for folders, Descriptive-Name.ext for files.

No Cursor rules (.cursor/rules/) or Copilot instructions (.github/copilot-instructions.md) found.

## Notes for Agents
- Use `ls` or `glob` tools to explore subdirectories.
- Download images if needed with `download` tool, but they are already local.
