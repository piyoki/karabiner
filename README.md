## My Karabinar Config

Currently working with HHKB Professional Hybrid Type-S

![](https://github.com/yqlbu/karabinar/blob/master/hhkb.jpg?raw=true)

## Right Shift + HHKB Arrows => Arrows

<kbd>Right Shift</kbd> + <Kbd>HHKB Arrows</Kbd> maps to the <kbd>Arrow</kbd> keys

## Capslock & Control

Single Press <kbd>Left Control</kbd> to trigger <kbd>Capslock</kbd> as normal keyboard

Hold <kbd>Left Control</kbd> to trigger the normal <kbd>Control</kbd> functionality

## Right Command => Alfred

<kbd>Right Command</kbd> maps to toggle `Alfred`

## Right Option => Hyper (f19)

<kbd>Right Option</kbd> maps to <kbd>Hyper (f19)</kbd>

## Shift + Esc => ~

<kbd>Shift</kbd> + <kbd>Esc</kbd> triggers <kbd>~</kbd> as normal keyboard

## Shift => Select Previous Input Method

Double Press <kbd>Left Shift</kbd> to trigger the `Select Previous Input Method` event

Hold <kbd>Left Shift</kbd> triggers the normal <kbd>Shift</kbd> functionality as normal keyboard

## Shortcuts

### Command Editing Shortcuts

|            Shortcut            |                       Usage                       |
| :----------------------------: | :-----------------------------------------------: |
| <kbd>Ctrl</kbd> + <kbd>A</kbd> |        Go to the start of the command line        |
| <kbd>Ctrl</kbd> + <kbd>E</kbd> |         Go to the end of the command line         |
| <kbd>Ctrl</kbd> + <kbd>D</kbd> | Delete from cursor to the end of the command line |
| <kbd>Ctrl</kbd> + <kbd>K</kbd> |    Cut the text from after the cursor position    |
| <kbd>Ctrl</kbd> + <kbd>F</kbd> |            Move forward one character             |
| <kbd>Ctrl</kbd> + <kbd>B</kbd> |            Move backward one character            |
| <kbd>Ctrl</kbd> + <kbd>P</kbd> |      Move to the beginning of the line above      |
| <kbd>Ctrl</kbd> + <kbd>N</kbd> |      Move to the beginning of the line below      |
| <kbd>Ctrl</kbd> + <kbd>D</kbd> |         Delete character under the cursor         |
| <kbd>Ctrl</kbd> + <kbd>H</kbd> |        Delete character before the cursor         |

### Command Control Shortcuts

|            Shortcut            |                                                    Usage                                                    |
| :----------------------------: | :---------------------------------------------------------------------------------------------------------: |
| <kbd>Ctrl</kbd> + <kbd>L</kbd> |                                              clear the screen                                               |
| <kbd>Ctrl</kbd> + <kbd>C</kbd> |                                            terminate the command                                            |
| <kbd>Ctrl</kbd> + <kbd>K</kbd> |                                 Cut the text from after the cursor position                                 |
| <kbd>Ctrl</kbd> + <kbd>U</kbd> |                                Cut the text from before the cursor position                                 |
| <kbd>Ctrl</kbd> + <kbd>W</kbd> |                               Cut the previous word from the cursor position                                |
| <kbd>Ctrl</kbd> + <kbd>Y</kbd> |                     Paste word or text that was cut using one of the deletion shortcuts                     |
| <kbd>Esc</kbd> + <kbd>b</kbd>  |                                      Move cursor to the previous word                                       |
| <kbd>Esc</kbd> + <kbd>f</kbd>  |                                        Move cursor to the next word                                         |
| <kbd>Cmd</kbd> + <kbd>b</kbd>  | Move cursor to the previous word (see [iTerm configuration](#move-word-to-word-forward-and-backward) below) |
| <kbd>Cmd</kbd> + <kbd>f</kbd>  |   Move cursor to the next word (see [iTerm configuration](#move-word-to-word-forward-and-backward) below)   |

## iTerm Configuration

### Move word-to-word forward and backward

- Install iTerm2
- Launch and then go to the `preference` pane
- Click the `+` button to add a new keyboard shortcut
- In the first box type <kbd>Cmd</kbd> + <kbd>Left Arrow</kbd>
- In the second box choose `send escape sequence`
- In the third box type the letter <kbd>b</kbd>

- Click the `+` button to add a new keyboard shortcut
- In the first box type <kbd>Cmd</kbd> + <kbd>Right Arrow</kbd>
- In the second box choose `send escape sequence`
- In the third box type the letter <kbd>f</kbd>

**NOTE**: the above configuration re-map the key combinations for word-to-word movement. <kbd>Esc</kbd> + <kbd>f</kbd> moves one word to the right, and <kbd>Esc</kbd> + <kbd>b</kbd> moves one word to the left,
