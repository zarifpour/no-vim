```
███╗   ██╗ ██████╗       ██╗   ██╗██╗███╗   ███╗
████╗  ██║██╔═══██╗      ██║   ██║██║████╗ ████║
██╔██╗ ██║██║   ██║█████╗██║   ██║██║██╔████╔██║
██║╚██╗██║██║   ██║╚════╝╚██╗ ██╔╝██║██║╚██╔╝██║
██║ ╚████║╚██████╔╝       ╚████╔╝ ██║██║ ╚═╝ ██║
╚═╝  ╚═══╝ ╚═════╝         ╚═══╝  ╚═╝╚═╝     ╚═╝
```

> /noʊ.vɪm/

---

Get to "no-vim" with these fundamental shortcuts: explore swift navigation, precise content modification, and master command count motions, such as <kbd>2</kbd><kbd>w</kbd> to leap forward two words, boosting your document handling efficiency. This manual aims to transform you into a proficient and quick editor, adept at facing any text editing challenge.

## Definitions

<details>
  <summary><kbd>🏋️ What is a motion?</kbd></summary>
  A motion is a command that moves the cursor to a new position in the text according to a specific pattern or direction.
</details>

<details>
  <summary><kbd>📯 What is a command?</kbd></summary>
  A command is an instruction that performs a specific action, such as editing text, changing configuration, or navigating through the document.
</details>

<details>
  <summary><kbd>🔡 What is a word?</kbd></summary>
  A word is defined as a sequence of letters, digits, or underscores, or a sequence of other non-blank characters, separated by whitespace.
</details>

<details>
  <summary><kbd>🔠 What is a WORD?</kbd></summary>
  A WORD is defined as a sequence of non-blank characters, separated by whitespace.
</details>

## 🏋️ Motions

Motions are shortcuts that relocate the cursor within the text, ranging from simple one-character moves to complex jumps like starting the next word or reaching document's end. They are essential for efficient navigation and editing, enabling quick cursor movement without hand repositioning from the keyboard.

### ↔️ Horizontal

- <kbd>0</kbd> - go to the beginning
- <kbd>$</kbd> - go to the end
- <kbd>\_</kbd> or <kbd>^</kbd> - go to the first non-blank character
- <kbd>g</kbd><kbd>\_</kbd> - go to the last non-blank character in the line

### ↕️ Vertical

- <kbd>g</kbd><kbd>g</kbd> - go to the first line
- <kbd>G</kbd> - go to the last line
- <kbd>{</kbd> - go to the beginning of the previous paragraph
- <kbd>}</kbd> - go to the beginning of the next paragraph
- <kbd>Ctrl</kbd><kbd>u</kbd> - move half a page up
- <kbd>Ctrl</kbd><kbd>d</kbd> - move half a page down
- <kbd>z</kbd><kbd>z</kbd> - center the line on the screen
- <kbd>z</kbd><kbd>t</kbd> - move the line to the top of the screen
- <kbd>z</kbd><kbd>b</kbd> - move the line to the bottom of the screen
- <kbd>\*</kbd> - go to the next occurrence of the word under the cursor
- <kbd>#</kbd> - go to the previous occurrence of the word under the cursor

## 📯 Commands

Commands are instructions for performing actions such as editing text, changing settings, or manipulating the editor's state. They vary in function and can be executed in different modes, providing a wide range of text manipulation and customization options.

### 🔤 Word

- <kbd>w</kbd> - go to the beginning of the next word
- <kbd>W</kbd> - go to the beginning of the next WORD
- <kbd>e</kbd> - go to the end of the next word
- <kbd>b</kbd> - go to the beginning of the previous word
- <kbd>g</kbd><kbd>e</kbd> - go to the end of the previous word
- <kbd>g</kbd><kbd>E</kbd> - go to the end of the previous WORD

### 🔎 Find

- <kbd>f</kbd><kbd>\<char></kbd> - find the next occurrence of a character
- <kbd>F</kbd><kbd>\<char></kbd> - find the previous occurrence of a character
- <kbd>t</kbd><kbd>\<char></kbd> - till the next occurrence of a character (moves the cursor to one character before the character you want to find)
- <kbd>T</kbd><kbd>\<char></kbd> - till the previous occurrence of a character (moves the cursor to one character after the character you want to find)
