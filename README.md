# Emacs Keyboard Shortcuts

A list of Emacs keyboard shortcuts that I use on a regular basis.

## General Shortcuts

| Shortcut / Command | Description                                                     |
|--------------------|-----------------------------------------------------------------|
| `C-x Esc Esc`      | Edit and re-evaluate last complex command.                      |
| `C-h m`            | Help information for the current buffers modes.                 |
| `C-h f`            | Help information for a function.                                |
| `C-h l`            | Show log for key presses and commands.                          |
| `C-k`              | Kill rest of line, or line if empty.                            |
| `C-/`              | Undo.                                                           |
| `C-g C-/`          | Redo.                                                           |
| `C-y`              | Yank from kill ring.                                            |
| `M-y`              | Yank down the kill ring.                                        |
| `C-y M-y`          | Cycle through kills after a yank.                               |
| `M-%`              | Query replace.                                                  |
| `M-/`              | Dabbrev (word) expand.                                          |
| `M-C-/`            | Dabbrev (word) completion.                                      |
| `C-x s`            | Save all buffers.                                               |
| `C-x C-s`          | Save current buffer.                                            |
| `C-x C-w`          | Write the current buffer, can provide new file name.            |
| `C-o`              | Add blank line below.                                           |
| `C-x C-o`          | Delete all blank lines below.                                   |
| `C-x C-c`          | Quit Emacs.                                                     |
| `M--`              | Prefix to perform negative meta commands.                       |
| `C--`              | Prefix to perform negative commands.                            |
| `M-m`              | Move cursor to the true beginning of the line.                  |
| `C-x f`            | Set fill column number.                                         |
| `M-q`              | Wrap/reformat to fill column.                                   |
| `M-v`              | Page up.                                                        |
| `C-v`              | Page down.                                                      |
| `M-^`              | Join previous line.                                             |
| `M-- M-^`          | Join following line.                                            |
| `M-<`              | Go to start of file.                                            |
| `M->`              | Go to end of file.                                              |
| `M-{`              | Previous paragraph.                                             |
| `M-}`              | Next paragraph.                                                 |
| `C-x C-f`          | Find file.                                                      |
| `C-x C-v`          | Find alternative file.                                          |
| `C-x k`            | Kill current or named buffer.                                   |
| `C-x o`            | Go to next window, split.                                       |
| `C-x O`            | Go back to previous window, split.                              |
| `C-x i`            | Insert a file into the current file.                            |
| `C-x h`            | Highlight entire buffer.                                        |
| `C-x h, C-M \`     | Re-indent entire buffer.                                        |
| `C-x C-j`          | Open Dired jump.                                                |
| `C-x SPC`          | Rectangle edit mode, can use string-insert-rectangle.           |
| `C-x +`            | Resize all splits to equal sizes.                               |
| `C-x 5 2`          | Open in new frame.                                              |
| `C-x r SPC`        | Point-to-register.                                              |
| `C-x r j`          | Jump-to-register.                                               |
| `g`                | Refresh page, workes on many UI pages.                          |
| `M-s o`            | List lines using regex.                                         |
| `M-s h r`          | Highlights regex expression.                                    |
| `M-r`              | Move cursor to top, middle and bottom.                          |
| `C-l`              | Move text in relation to the cursor, to top, middle and bottom. |
| `M-!`              | Run a shell command.                                            |
| `M-&`              | Async shell command.                                            |
| `C-u 0`            | Infinite count prefix.                                          |
| `C-u {count}`      | Repeat operation x amount of times.                             |
| `C-x z`            | Repeat command.                                                 |
| `C-x backspace`    | Clear mini-buffer.                                              |
| `C-k C-k C-y C-y`  | Duplicate line.  (Place cursor at start)                        |
| `M-g M-g`          | Go to line.                                                     |
| `C-x b`            | Quick switch buffer.                                            |
| `C-v`              | Scroll to next page.                                            |
| `M-v`              | Scroll to previous page.                                        |
| `C-x 1`            | Kill other windows.                                             |
| `C-x s`            | Save other buffers.                                             |
| `C-x i`            | Insert a file into the current buffer.                          |
| `M-z (char)`       | Zap up to char.                                                 |
| `C-M-\`            | Re-indent region.                                               |
| `C-x * g`          | Eval in new buffer.                                             |
| `M-<space>`        | Removes extra whitespace between two words.                     |
| `C-u M-x`          | Run command with additional options.                            |
| `locate`           | Find a files matching a pattern across the entire system.       |
| `recentf`          | Shows a list of recent files, if `recentf` mode is enabled.     |

## Macros

| Shortcut / Command | Description                                                            |
|--------------------|------------------------------------------------------------------------|
| `C-x (`            | Define keyboard macro.                                                 |
| `C-x )`            | End keyboard macro definition.                                         |
| `C-x e`            | Playback keyboard macro, can just keep pressing `e` after first press. |
| `C-x C-k <space>`  | Open keyboard macro debugger.                                          |
| `C-x C-k e`        | Enter macro editor, (C-c C-c) to finish editing.                       |
| `C-x C-k n`        | Save the keyboard macro for later use.                                 |
| `insert-kbd-macro` | Insert a saved macro into the file, in Emacs lisp.                     |

## Balanced Expressions

| Shortcut / Command | Description                          |
|--------------------|--------------------------------------|
| `C-M-f`            | Forward over an sexps.               |
| `C-M-b`            | Backward over a sexps.               |
| `C-M-d`            | Move down into a sexps.              |
| `C-M-u`            | Move up out of a sexps.              |
| `C-M-n`            | Move forward to the sexps.           |
| `C-M-p`            | Move backward to the previous sexps. |
| `C-M-k`            | Kill down into sexps.                |

## Incremental Search

| Shortcut / Command | Description                                                                    |
|--------------------|--------------------------------------------------------------------------------|
| `C-M-s`            | Regex search.                                                                  |
| `C-s`              | Incremental search.                                                            |
| `C-s C-s`          | Repeat incremental search.                                                     |
| `C-s C-w`          | Enter incremental search and start expanding the selection.                    |
| `C-r`              | Incremental search backward.                                                   |
| `C-r C-r`          | Repeat incremental search backward.                                            |
| `C-s C-y`          | Start incremental search using yanked text.                                    |
| `C-s M-y`          | Start incremental search from kill ring string.                                |
| `C-r`              | During query replace, enter recursive edit mode.                               |
| `C-M-c`            | During query replace, exit recursive edit mode and continue query replacement. |
| `C-]`              | During query replace, exit recursive edit mode and query replace modes.        |
| `M-s o`            | Show all lines matching the search term in occur.                              |
| `M-s e`            | To edit the search string in the minibuffer.                                   |
| `M-s h r`          | Highlights the last search string.                                             |

## Tags

| Shortcut / Command | Description             |
|--------------------|-------------------------|
| `M-.`              | Jump to tag.            |
| `M-,`              | Jump back.              |
| `C-x 4 .`          | Visit tag in new split. |
| `C-x 5 .`          | Visit tag in new frame. |

## Xref

| Shortcut / Command | Description                         |
|--------------------|-------------------------------------|
| `M-.`              | Find definitions at point.          |
| `M-,`              | Pop marker and return.              |
| `M-?`              | Find references matching a pattern. |
| `C-M-.`            | Find symbols matching a pattern.    |

## Bookmarks

| Shortcut / Command | Description            |
|--------------------|------------------------|
| `C-x r m`          | Create / set bookmark. |
| `C-x r b`          | Open bookmark.         |
| `C-x r l`          | List bookmarks.        |

## Abbrev

| Shortcut / Command | Description        |
|--------------------|--------------------|
| `C-x a g`          | Add global abbrev. |
| `C-x a l`          | Add local abbrev.  |
| `C-q`              | Mute abbrev.       |

## Ivy Buffer

| Shortcut / Command | Description                    |
|--------------------|--------------------------------|
| `S-<space>`        | Narrow search to current term. |
| `C-M-p`            | Preview up.                    |
| `C-M-n`            | Preview down.                  |
| `M-o`              | Open item options.             |

## Occur Buffer

| Shortcut / Command | Description                           |
|--------------------|---------------------------------------|
| `e`                | Directly edit the entry in place.     |
| `C-c C-c`          | Return back to occur mode after edit. |

## Dired Buffer

| Shortcut / Command | Description                                                                        |
|--------------------|------------------------------------------------------------------------------------|
| `C-o`              | Preview file but stay in Dired buffer.                                             |
| `C-u k`            | Remove section.                                                                    |
| `X`                | Execute shell command on file.                                                     |
| `Q`                | Query replace marked files, `<space>` accept, `n` decline and `C-x s` to save all. |
| `+`                | Create directory.                                                                  |
| `find-name-dired`  | Recursively find a file.                                                           |

## Grep Buffer

| Shortcut / Command | Description   |
|--------------------|---------------|
| `C-c C-K`          | Kill process. |

## Compile Buffer

| Shortcut / Command | Description                               |
|--------------------|-------------------------------------------|
| `?`                | Describe-mode.                            |
| `g`                | Recompile.                                |
| `h`                | Describe-mode.                            |
| `q`                | Quit-window.                              |
| `compile`          | Run one of the targets in your make file. |

## Interactively Do Things (Ido) Buffer

| Shortcut / Command | Description                                       |
|--------------------|---------------------------------------------------|
| `M-f`              | Find file recursively. Search into sub directory. |
| `?`                | See a full list of all matching buffers.          |
| `C-j`              | Open folder in Dired.                             |

## Interface To Spell (Ispell) and On The Fly Spell (Flyspell)

| Shortcut / Command   | Description                                                      |
|----------------------|------------------------------------------------------------------|
| `M $`                | Check and correct spelling of the word at point.                 |
| `C-M i`              | Complete the word before point based on the spelling dictionary. |
| `C-c $`              | Correct word before point.                                       |
| `flyspell-mode`      | Enable Fly-spell mode, which highlights all misspelled words.    |
| `flyspell-prog-mode` | Enable Fly-spell mode for comments and strings only.             |
| `flyspell-buffer`    | Check and correct spelling in the buffer.                        |

## Org Buffer

| Shortcut / Command | Description                                    |
|--------------------|------------------------------------------------|
| `S-M-RET`          | Insert a new TODO entry below the current one. |
| `C-c / t`          | View todo items in a sparse tree.              |
| `C-c C-t`          | Toggle todo item state.                        |
| `C-c C-s`          | Schedule todo item.                            |
| `C-c C-d`          | Add deadline to todo item.                     |
| `C-c [`            | Add file to agenda.                            |
| `C-c ]`            | Remove file to agenda.                         |
| `C-c .`            | Insert current date.                           |
| `C-c C-e`          | Open exporter.                                 |
| `C-c C-e #`        | Insert template.                               |
| `C-c C-e P x`      | Export specific project.                       |
