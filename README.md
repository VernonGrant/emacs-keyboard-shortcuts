# Emacs Keyboard Shortcuts

A list of Emacs keyboard shortcuts that I use on a regular basis.

## General Shortcuts

| Shortcut              | Command Invoked                  | Description                                                        |
|-----------------------|----------------------------------|--------------------------------------------------------------------|
| `C-x Esc Esc`         | `repeat-complex-command`         | Edit and re-evaluate last complex command.                         |
| `C-h m`               | `describe-mode`                  | Help information for the current buffers modes.                    |
| `C-h f`               | `describe-function`              | Help information for a function.                                   |
| `C-h x`               | `describe-command`               | Help information for a command (a function available using `M-x`). |
| `C-h l`               | `view-lossage`                   | Show log for key presses and commands.                             |
| `C-k`                 | `kill-line`                      | Kill rest of line, or line if empty.                               |
| `C-/`                 | `undo`                           | Undo.                                                              |
| `C-g C-/`             | `undo-redo`                      | Redo.                                                              |
| `C-y`                 | `yank`                           | Yank from kill ring.                                               |
| `M-y`                 | `yank-pop`                       | Yank down the kill ring.                                           |
| `C-y M-y`             | `yank-pop`                       | Cycle through kills after a yank.                                  |
| `M-/`                 | `dabbrev-expand`                 | Dabbrev (word) expand.                                             |
| `M-C-/`               | `dabbrev-completion`             | Dabbrev (word) completion.                                         |
| `C-x s`               | `save-some-buffers`              | Save all buffers.                                                  |
| `C-x C-s`             | `save-buffer`                    | Save current buffer.                                               |
| `C-x C-w`             | `write-file`                     | Write the current buffer, can provide new file name.               |
| `C-o`                 | `open-line`                      | Add blank line below.                                              |
| `C-x C-o`             | `delete-blank-lines`             | Delete all blank lines below.                                      |
| `C-x C-c`             | `save-buffers-kill-terminal`     | Quit Emacs.                                                        |
| `C-x <left>`          | `previous-buffer`                | Switch to the previous buffer.                                     |
| `C-x <right>`         | `next-buffer`                    | Switch to the next buffer.                                         |
| `M--`                 | `negative-argument`              | Prefix to perform negative meta commands.                          |
| `C--`                 | `negative-argument`              | Prefix to perform negative commands.                               |
| `C-a`                 | `move-beginning-of-line`         | Move cursor to the beginning of the line.                          |
| `C-e`                 | `move-end-of-line`               | Move cursor to the end of the line.                                |
| `M-a`                 | `backward-sentence`              | Move cursor to the beginning of the sentence.                      |
| `M-e`                 | `forward-sentence`               | Move cursor to the end of the sentence.                            |
| `M-m`                 | `back-to-indentation`            | Move cursor to the first non-whitepsace character on the line.     |
| `M-k`                 | `kill-sentence`                  | Kill rest the rest of theing of the line.                          |
| `M-l`                 | `downcase-word`                  | Lowercase word forward.                                            |
| `M-c`                 | `capitalize-word`                | Capitalize word forward.                                           |
| `M-u`                 | `upcase-word`                    | Uppercase word forward.                                            |
| `C-<space> C-<space>` | `set-mark-command`               | Add mark to mark ring.                                             |
| `C-u C-<space>`       | `set-mark-command`               | Jump to previous mark.                                             |
| `C-x f`               | `set-fill-column`                | Set fill column number.                                            |
| `M-q`                 | `fill-paragraph`                 | Wrap/reformat to fill column.                                      |
| `M-v`                 | `scroll-down-command`            | Page up.                                                           |
| `C-v`                 | `scroll-up-command`              | Page down.                                                         |
| `M-^`                 | `delete-indentation`             | Join previous line.                                                |
| `M-- M-^`             | `delete-indentation`             | Join following line.                                               |
| `M-<`                 | `beginning-of-buffer`            | Go to start of file.                                               |
| `M->`                 | `end-of-buffer`                  | Go to end of file.                                                 |
| `M-{`                 | `backward-paragraph`             | Previous paragraph.                                                |
| `M-}`                 | `forward-paragraph`              | Next paragraph.                                                    |
| `C-x C-f`             | `find-file`                      | Find file.                                                         |
| `C-x C-v`             | `find-alternate-file`            | Find alternative file.                                             |
| `C-x k`               | `kill-buffer`                    | Kill current or named buffer.                                      |
| `C-x o`               | `other-window`                   | Go to next window, split.                                          |
| `C-x O`               | `other-window`                   | Go back to previous window, split.                                 |
| `C-x i`               | `insert-file`                    | Insert file contents into the current file.                        |
| `C-x h`               | `mark-whole-buffer`              | Highlight entire buffer.                                           |
| `C-M-\`               | `indent-region`                  | Re-indent code region in region or from previous mark point.       |
| `C-x C-x`             | `exchange-point-and-mark`        | Put the mark where point is now, and point where the mark is now.  |
| `C-x C-j`             | `dired-jump`                     | Open Dired jump.                                                   |
| `C-x SPC`             | `rectangle-mark-mode`            | Rectangle edit mode, can use string-insert-rectangle.              |
| `C-x +`               | `balance-windows`                | Resize all splits to equal sizes.                                  |
| `C-x 5 2`             | `make-frame-command`             | Open in new frame.                                                 |
| `C-x r SPC`           | `point-to-register`              | Point-to-register.                                                 |
| `C-x r j`             | `jump-to-register`               | Jump-to-register.                                                  |
| `g`                   | `revert-buffer`                  | Refresh page, workes on many UI pages.                             |
| `M-s o`               | `occur`                          | List lines using regex.                                            |
| `M-s h r`             | `highlight-regexp`               | Highlights regex expression.                                       |
| `M-r`                 | `move-to-window-line-top-bottom` | Move cursor to top, middle and bottom.                             |
| `C-l`                 | `recenter-top-bottom`            | Move text in relation to the cursor, to top, middle and bottom.    |
| `M-!`                 | `shell-command`                  | Run a shell command.                                               |
| `M-&`                 | `async-shell-command`            | Async shell command.                                               |
| `C-u 0`               | `universal-argument`             | Infinite count prefix.                                             |
| `C-u {count}`         | `universal-argument`             | Repeat operation x amount of times.                                |
| `C-x z`               | `repeat`                         | Repeat command.                                                    |
| `C-x backspace`       | `backward-kill-sentence`         | Clear mini-buffer.                                                 |
| `C-k C-k C-y C-y`     |                                  | Duplicate line.  (Place cursor at start)                           |
| `M-g M-g`             | `goto-line`                      | Go to line.                                                        |
| `C-x b`               | `switch-to-buffer`               | Quick switch buffer.                                               |
| `C-x 1`               | `delete-other-windows`           | Kill other windows.                                                |
| `M-z (char)`          | `zap-to-char`                    | Zap up to char.                                                    |
| `C-M-\`               | `indent-region`                  | Re-indent region.                                                  |
| `C-x * g`             | `calc-dispatch`                  | Eval in new buffer.                                                |
| `M-<space>`           | `just-one-space`                 | Removes extra whitespace between two words.                        |
| `C-u M-x`             | `universal-argument`             | Run command with additional options.                               |
| `C-x TAB`             | `indent-rigidly`                 | Allows you to manually indent a region inwards or outwards.        |
| `C-x x t`             | `toggle-truncate-lines`          | Turn on or off line truncation.                                    |
|                       | `locate`                         | Find a files matching a pattern across the entire system.          |
|                       | `recentf`                        | Shows a list of recent files, if `recentf` mode is enabled.        |

## Highlighting

| Shortcut  | Command Invoked                   | Description                                                 |
|-----------|-----------------------------------|-------------------------------------------------------------|
| `M-s h .` | `highlight-symbol-at-point`       | Highlight each instance of the symbol at point.             |
| `M-s h l` | `highlight-lines-matching-regexp` | Highlight all lines that match REGEXP using FACE.           |
| `M-s h p` | `highlight-phrase`                | Set face of each match of phrase REGEXP to FACE.            |
| `M-s h r` | `highlight-regexp`                | Set face of each match of REGEXP to FACE.                   |
| `M-s h u` | `unhighlight-regexp`              | Remove highlighting of each match to REGEXP set by hi-lock. |

## Macros

| Shortcut          | Command Invoked             | Description                                                            |
|-------------------|-----------------------------|------------------------------------------------------------------------|
| `C-x (`           | `kmacro-start-macro`        | Define keyboard macro.                                                 |
| `C-x )`           | `kmacro-end-macro`          | End keyboard macro definition.                                         |
| `C-x e`           | `kmacro-end-and-call-macro` | Playback keyboard macro, can just keep pressing `e` after first press. |
| `C-x C-k <space>` | `kmacro-step-edit-macro`    | Open keyboard macro debugger.                                          |
| `C-x C-k e`       | `edit-kbd-macro`            | Enter macro editor, (C-c C-c) to finish editing.                       |
| `C-x C-k n`       | `kmacro-name-last-macro`    | Save the keyboard macro for later use.                                 |
|                   | `insert-kbd-macro`          | Insert a saved macro into the file, in Emacs lisp.                     |

## Project

| Shortcut  | Command Invoked                    | Description                                                                           |
|-----------|------------------------------------|---------------------------------------------------------------------------------------|
| `C-x p !` | `project-shell-command`            | Run `shell-command` in the current project's root directory.                          |
| `C-x p &` | `project-async-shell-command`      | Run `async-shell-command` in the current project's root directory.                    |
| `C-x p f` | `project-find-file`                | Visit a file (with completion) in the current project.                                |
| `C-x p F` | `project-or-external-find-file`    | Visit a file (with completion) in the current project or external roots.              |
| `C-x p b` | `project-switch-to-buffer`         | Display buffer in the selected window, for a buffer belonging to the current project. |
| `C-x p s` | `project-shell`                    | Start an inferior shell in the current project's root directory.                      |
| `C-x p d` | `project-find-dir`                 | Start Dired in a directory inside the current project.                                |
| `C-x p D` | `project-dired`                    | Start Dired in the current project's root.                                            |
| `C-x p v` | `project-vc-dir`                   | Run VC-Dir in the current project's root.                                             |
| `C-x p c` | `project-compile`                  | Run `compile` in the project root.                                                    |
| `C-x p e` | `project-eshell`                   | Start Eshell in the current project's root directory.                                 |
| `C-x p k` | `project-kill-buffers`             | Kill the buffers belonging to the current project.                                    |
| `C-x p p` | `project-switch-project`           | Switch to another project by running an Emacs command.                                |
| `C-x p g` | `project-find-regexp`              | Find all matches for REGEXP in the current project's roots.                           |
| `C-x p G` | `project-or-external-find-regexp`  | Find all matches for REGEXP in the project roots or external roots.                   |
| `C-x p r` | `project-query-replace-regexp`     | Query-replace REGEXP in all the files of the project.                                 |
| `C-x p x` | `project-execute-extended-command` | Execute an extended command in project root.                                          |

## Balanced Expressions

| Shortcut | Command Invoked      | Description                          |
|----------|----------------------|--------------------------------------|
| `C-M-f`  | `forward-sexp`       | Forward over an sexps.               |
| `C-M-b`  | `backward-sexp`      | Backward over a sexps.               |
| `C-M-d`  | `down-list`          | Move down into a sexps.              |
| `C-M-u`  | `backward-up-list`   | Move up out of a sexps.              |
| `C-M-n`  | `forward-list`       | Move forward to the sexps.           |
| `C-M-p`  | `backward-list`      | Move backward to the previous sexps. |
| `C-M-k`  | `kill-sexp`          | Kill down into sexps.                |
| `M-(`    | `insert-parentheses` | Wraps region in parenthesis.         |

## Incremental Search

| Shortcut  | Command Invoked             | Description                                                                    |
|-----------|-----------------------------|--------------------------------------------------------------------------------|
| `C-M-s`   | `isearch-forward-regexp`    | Regex search.                                                                  |
| `C-s`     | `isearch-forward`           | Incremental search.                                                            |
| `C-s C-s` | `isearch-repeat-forward`    | Repeat incremental search.                                                     |
| `C-s C-w` | `isearch-yank-word-or-char` | Enter incremental search and start expanding the selection.                    |
| `C-r`     | `isearch-backward`          | Incremental search backward.                                                   |
| `C-r C-r` | `isearch-repeat-backward`   | Repeat incremental search backward.                                            |
| `C-s C-y` | `isearch-yank-kill`         | Start incremental search using yanked text.                                    |
| `C-s M-y` | `isearch-yank-pop-only`     | Start incremental search from kill ring string.                                |
| `C-r`     | `recursive-edit`            | During query replace, enter recursive edit mode.                               |
| `C-M-c`   | `exit-recursive-edit`       | During query replace, exit recursive edit mode and continue query replacement. |
| `C-]`     | `abort-recursive-edit`      | During query replace, exit recursive edit mode and query replace modes.        |
| `M-s o`   | `isearch-occur`             | Show all lines matching the search term in occur.                              |
| `M-s e`   | `isearch-edit-string`       | To edit the search string in the minibuffer.                                   |
| `M-s h r` | `isearch-highlight-regexp`  | Highlights the last search string.                                             |

## Query Replace

| Shortcut | Command Invoked | Description                                                          |
|----------|-----------------|----------------------------------------------------------------------|
| `M-%`    | `query-replace` | Start a query replace operation.                                     |
| `!`      |                 | Replace all remaining matches in this buffer with no more questions. |
| `^`      |                 | Move point back to previous match.                                   |
| `u`      |                 | Undo previous replacement.                                           |
| `U`      |                 | undo all replacements.                                               |
| `E`      |                 | Edit the replacement string.                                         |

## Tags

| Shortcut  | Command Invoked                      | Description             |
|-----------|--------------------------------------|-------------------------|
| `M-.`     | `xref-find-definitions`              | Jump to tag.            |
| `M-,`     | `xref-go-back`                       | Jump back.              |
| `C-x 4 .` | `xref-find-definitions-other-window` | Visit tag in new split. |
| `C-x 5 .` | `xref-find-definitions-other-frame`  | Visit tag in new frame. |

## Xref

| Shortcut | Command Invoked         | Description                         |
|------------|-------------------------|-------------------------------------|
| `M-.`      | `xref-find-definitions` | Find definitions at point.          |
| `M-,`      | `xref-go-back`          | Pop marker and return.              |
| `M-?`      | `xref-find-references`  | Find references matching a pattern. |
| `C-M-.`    | `xref-find-apropos`     | Find symbols matching a pattern.    |

## Bookmarks

| Shortcut  | Command Invoked       | Description            |
|-----------|-----------------------|------------------------|
| `C-x r m` | `bookmark-set`        | Create / set bookmark. |
| `C-x r b` | `bookmark-jump`       | Open bookmark.         |
| `C-x r l` | `bookmark-bmenu-list` | List bookmarks.        |

## Abbrev

| Shortcut  | Command Invoked     | Description        |
|-----------|---------------------|--------------------|
| `C-x a g` | `add-global-abbrev` | Add global abbrev. |
| `C-x a l` | `add-mode-abbrev`   | Add local abbrev.  |
| `C-q`     |                     | Mute abbrev.       |

## Ivy Buffer

| Shortcut    | Command Invoked              | Description                    |
|-------------|------------------------------|--------------------------------|
| `S-<space>` | `ivy-restrict-to-matches`    | Narrow search to current term. |
| `C-M-p`     | `ivy-previous-line-and-call` | Preview up.                    |
| `C-M-n`     | `ivy-next-line-and-call`     | Preview down.                  |
| `M-o`       | `ivy-dispatching-done`       | Open item options.             |

## Occur Buffer

| Shortcut  | Command Invoked              | Description                           |
|-----------|------------------------------|---------------------------------------|
| `e`       | `occur-edit-mode`            | Directly edit the entry in place.     |
| `C-c C-c` | `occur-mode-goto-occurrence` | Return back to occur mode after edit. |

## Dired Buffer

| Shortcut | Command Invoked                    | Description                                                                        |
|----------|------------------------------------|------------------------------------------------------------------------------------|
| `C-o`    | `dired-display-file`               | Preview file but stay in Dired buffer.                                             |
| `C-u k`  | `dired-do-kill-lines`              | Remove section.                                                                    |
| `X`      | `dired-do-shell-command`           | Execute shell command on file.                                                     |
| `Q`      | `dired-do-find-regexp-and-replace` | Query replace marked files, `<space>` accept, `n` decline and `C-x s` to save all. |
| `+`      | `dired-create-directory`           | Create directory.                                                                  |
| `^`      | `dired-up-directory`               | Go up one directory.                                                               |
|          | `find-name-dired`                  | Recursively find a file.                                                           |

## IBuffer

| Shortcut | Command Invoked               | Description                                  |
|----------|-------------------------------|----------------------------------------------|
| `/ /`    | `ibuffer-filter-disable`      | Remove all filtering currently in effect.    |
| `/ m`    | `ibuffer-filter-by-used-mode` | Add a filter by a major mode now in use.     |
| `/ n`    | `ibuffer-filter-by-name`      | Add a filter by buffer name.                 |
| `/ f`    | `ibuffer-filter-by-filename`  | Add a filter by filename.                    |
| `Q`      | `ibuffer-do-query-replace`    | Query replace in each of the marked buffers. |

## Grep Buffer

| Shortcut  | Command Invoked            | Description   |
|-----------|----------------------------|---------------|
| `C-c C-K` | `command kill-compilation` | Kill process. |

## Compile Buffer

| Shortcut | Command Invoked | Description                               |
|----------|-----------------|-------------------------------------------|
| `?`      | `describe-mode` | Describe-mode.                            |
| `g`      | `recompile`     | Recompile.                                |
| `h`      | `describe-mode` | Describe-mode.                            |
| `q`      | `quit-window`   | Quit-window.                              |
|          | `compile`       | Run one of the targets in your make file. |

## Interactively Do Things (Ido) Buffer

| Shortcut          | Command Invoked                 | Description                                                                   |
|-------------------|---------------------------------|-------------------------------------------------------------------------------|
| `M-f`             | `ido-wide-find-file-or-pop-dir` | Find file recursively. Search into sub directory.                             |
| `?`               | `ido-completion-help`           | See a full list of all matching buffers.                                      |
| `C-j`             | `ido-select-text`               | Choose selected file/folder/text from minibuffer. e,g. Open folder in Dired . |
| `C-x C-f ... C-d` | `dired`                         | Enter `dired` on the current directory.                                       |
| `C-x C-f ... C-f` | `find-file`                     | Fallback to non-Ido, while finding a files.                                   |
| `C-x C-b ... C-b` | `ido-switch-buffer`             | Fallback to non-Ido, while finding a buffer.                                  |

## Interface To Spell (Ispell) and On The Fly Spell (Flyspell)

| Shortcut | Command Invoked                      | Description                                                                       |
|----------|--------------------------------------|-----------------------------------------------------------------------------------|
| `M $`    | `ispell-word`                        | Check and correct spelling of the word at point.                                  |
| `C-M i`  | `completion-at-point`                | Complete the word before point based on the spelling dictionary.                  |
| `M-TAB`  | `flyspell-auto-correct-word`         | Automatically corrects the current word at point, will also cycle between option. |
| `C-c $`  | `flyspell-correct-word-before-point` | Correct word before point.                                                        |
|          | `flyspell-mode`                      | Enable Fly-spell mode, which highlights all misspelled words.                     |
|          | `flyspell-prog-mode`                 | Enable Fly-spell mode for comments and strings only.                              |
|          | `flyspell-buffer`                    | Check and correct spelling in the buffer.                                         |

## Org Buffer

| Shortcut      | Command Invoked            | Description                                    |
|---------------|----------------------------|------------------------------------------------|
| `S-M-RET`     | `org-insert-todo-heading`  | Insert a new TODO entry below the current one. |
| `C-c / t`     | `org-match-sparse-tree`    | View todo items in a sparse tree.              |
| `C-c C-t`     | `org-todo`                 | Toggle todo item state.                        |
| `C-c C-s`     | `org-schedule`             | Schedule todo item.                            |
| `C-c C-d`     | `org-deadline`             | Add deadline to todo item.                     |
| `C-c [`       | `org-agenda-file-to-front` | Add file to agenda.                            |
| `C-c ]`       | `org-remove-file`          | Remove file to agenda.                         |
| `C-c .`       | `org-timestamp`            | Insert current date.                           |
| `C-c C-e`     | `org-export-dispatch`      | Open exporter.                                 |
| `C-c C-e #`   | `org-export-dispatch`      | Insert template.                               |
| `C-c C-e P x` | `org-export-dispatch`      | Export specific project.                       |

## EWW

| Shortcut | Command Invoked      | Description                          |
|----------|----------------------|--------------------------------------|
| `B`      | `eww-list-bookmarks` | Display your bookmarks.              |
| `b`      | `eww-add-bookmark`   | Add the current page as a bookmark.  |
| `l`      | `eww-back-url`       | Go to the previously displayed page. |
| `r`      | `eww-forward-url`    | Go to the next displayed page.       |
| `g`      | `eww-reload`         | Reload the current page.             |
| `G`      | `eww`                | Go to a new address.                 |
| `H`      | `eww-list-histories` | Shows a list of your histories.      |
| `TAB`    | `shr-next-link`      | Skip to the next link.               |

## Useful Commands

| Command                  | Description                                                   |
|--------------------------|---------------------------------------------------------------|
| `keep-lines`             | Delete all lines not matching the provided regex.             |
| `flush-lines`            | Delete all lines matching the provided regex.                 |
| `sort-lines`             | Sort lines in region alphabetically.                          |
| `delete-duplicate-lines` | Delete all but one copy of any identical lines in the region. |
| `ff-find-other-file`     | Find the header or source file corresponding to this file.    |
