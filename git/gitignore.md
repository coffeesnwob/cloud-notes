# All about gitignore

`gitignore` file specifies intentionally untracked files that git should ignore. Git checks `gitignore` patterns from multiple sources, which following order of precedence, from highest to lowest.

## Pattern Format

- A blank line matches no file however it can serve as a separator for readability.
- A Line starting with `#` serves as a comment. Put a backslash (" \ ") in front of the first hash for patterns that begin with a hash.
- Trailing spaces are ignored unless they are quoted with backslash (" \ ").
- The slash " / " is used as directory separator. Separators may occur at the beginning, middle or end of the `.gitignore` search pattern.
- If there is a separator at the end of the pattern then the pattern will only match directories, otherwise the pattern can match both files and directories.

## Purpose

The purpose of `gitignore` files is to make sure that certain files are not tracked by git. This helps not sure your personal configurations or system files when working with your team.

---
