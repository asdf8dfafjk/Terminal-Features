Feature comparison of terminals
--


(More points better)

|                                                                    | Wezterm	               | Alacritty              | Kitty |                    
| -------------          											  | ----------             | -------------------- |
| **Unicode**                                                         |                        |
| Ligatures (shows, allows to disable?)                               | 2                      | 0                      | 2
| Colored emojis                                                      | 0 (copying doesn't work) | 0 (copying doesn't work) | 2 (Copies, shows colors)
| 中文  日本語 East asian (2 if everything good)                      | 1 (shows but doesn't copy) | 1 (shows but doesn't copy) | 2 copies and shows
| Indic                       (2 if everything good)                  | 0 (no show, no copy)   |  1 (shows but doesn't copy) | 2 
| RTL text (2 if everything good)                                     | 0                      | 0  | 1 (some support)
| Input using linux IME                                               | 0                      | 1                     | 0 (custom kitten)
| ** Appearance **
| Colors: COLORTERM=truecolor                                         | 1                       | 1 | 1
| Fontconfig: Respects fontconfig                                     | -                       | 1 (No respect for hints but font backup works) | -
| ** Text functions **
| Copy/paste shortcut keys                                            | 1                      | 1 | 1
| X11 primary selection mouse (selection copies, middle click pastes) | 1                      | 1 | 1 
| Scrollback                                                          | 1                      | 1 | 1
| Search                                                              | 2 Works perfectly      | 0 (Search available but broken) | Needs kitten
| Export visible text                                                 |                    0   | 0 (PR abandoned due to maintainer negligence) | 2
| Hyperlinks (2 if everything works)                                  | 1 (knows, but doesn't act)  | 1 (knows, but doesn't act) | 2
| ** Performance **
| Startup                                                             | 3                      | 3 | 3 
| keypress lag (Qualitative right now more points better)			  | 1                      | 1 | 3 
| output lag   (Qualitative right now more points better)             | 1                      | 2 | 3
| ** Keyboard **
| vim (modifyOtherKeys)                                               | -                       | 0 | -
| ** Misc **
| Bell (1 if present)                                                 | 0                       | 1 | 1
| ** Interface **
| Chromeless (2 if clean interface)                                   | 0                       | 2 | 1
| ** Other features**
| Sane defaults	(3 for good defaults)							      |						   | 3 
| ** Notes **                                                         | Opens login shell? has tabs    | Really buggy since 0.11 alpha 

