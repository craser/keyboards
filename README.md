# keyboards
Customizations and Layouts for my Keyboards

## Nuphy Air75 v2

### Emacs-style Editing Hotkeys 

I generally use something like [Keyboard Maestro](https://www.keyboardmaestro.com/main/) to let me use a few emacs
hotkeys for editing even when I'm not using emacs. But if I can build that straight into my keyboard, why not?

**HOWEVER**, I've done this by turning the Cmd key into a momentary layer switch. So, (`M(7)`) Mostly this
works great, except that it messes with how Cmd+TAB works to switch between apps. That's pretty ugly, so I'll 
be revisiting that. But for now, the work-around is that holding SPACE is the same as holding Cmd. (_Tapping_ SPACE
works the same as always.)

- `ctrl-f`: forward one character (already default in macOS, not implemented here) 
- `cmd-f`: forward one word (maps `cmd-f` to `alt-right-arrow`)
- `ctrl-b`: backward one character (already default in macOS, not implemented here)
- `cmd-b`: backward one word (maps `cmd-b` to `alt-left-arrow`)
- `cmd-backspace`: delete previous word (maps `cmd-backspace` to `alt-backspace`)
- `ctrl-k`: cut to end of line (already default in macOS, not implemented here)
- `ctrl-y`: paste (already default in macOS, not implemented here)

### Custom Hotkeys for DeskHop

I use a [DeskHop](https://github.com/hrvach/deskhop) to switch between machines on my desk. I've 
customized some of the hotkeys recognized by the deskhop (see [keyboard.c](https://github.
com/craser/deskhop/blob/main/src/keyboard.c) in my forked repo ) 


| keyboard  | sent          | function                                                                |
|-----------|---------------|-------------------------------------------------------------------------|
| `red esc` | `Ctl-Shift-G` | "Gaming Mode" - lock output to current machine, act like a normal mouse |
| `TAB+L`   | `Rctl+L`      | Swtch output to other machine. (Holding TAB = Rctl)                     |
| `TAB+END` | `Rctl+END`    | Lock both computers.                                                    |

  
### Koolertron 23-Key Macropad

I currently use this as a debugging-focused macropad.

  - [product page](https://www.koolertron.com/koolertron-one-handed-macro-mechanical-keyboard-with-23-fully-programmable-keys-portable-mini-one-handed-mechanical-gaming-keypad-black-red-switches-rgb-led.html)
  

