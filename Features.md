Feature comparison of terminals
--


(More points better)

|                                   | Wezterm	               | Alacritty              | Kitty |       
|           -											  | -------                         | ---------                 | ----- |
| **Unicode**                                                         |                        |
| Ligatures (shows, allows to disable)                               | 2                      | 0                      | 2
| Colored emojis                                                      | 2 | 1 (emoji's yes, colored no) | 2
| 中文  日本語 East asian (2 if everything good)                      | 2 |2  | 2 
| Indic                       (2 if everything good)                  | 0 (needs config)  |  1 ( shows but no ligagures) | 2 
| RTL text (2 if everything good)                                     | 1                      | 1  | 1  
| Input using linux IME                                               | 1                      | 1                     | 0 (custom kitten)
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
| Sane defaults	(3 for good defaults)							      |						   | 3  | -
| ** Notes **                                                         | Opens login shell? has tabs    | Arguably the maintainer has OSS fatigue and doesn't seem very positive about PRs 

