# nvim-notes

<details>
  <summary><kbd>What is a word?</kbd></summary>
  A word is defined as a sequence of letters, digits, or underscores, or a sequence of other non-blank characters, separated by whitespace.
</details>

<details>
  <summary><kbd>What is a WORD?</kbd></summary>
  A WORD is defined as a sequence of non-blank characters, separated by whitespace.
</details>

## Horizontal Movements

- <kbd>0</kbd> - go to the beginning
- <kbd>$</kbd> - go to the end
- <kbd>\_</kbd> or <kbd>^</kbd> - go to the first non-blank character
- <kbd>g</kbd><kbd>\_</kbd> - go to the last non-blank character in the line

### In-line Movements

- <kbd>w</kbd> - go to the beginning of the next word
- <kbd>W</kbd> - go to the beginning of the next WORD
- <kbd>e</kbd> - go to the end of the next word
- <kbd>b</kbd> - go to the beginning of the previous word
- <kbd>g</kbd><kbd>e</kbd> - go to the end of the previous word
- <kbd>g</kbd><kbd>E</kbd> - go to the end of the previous WORD

### Find Movements

- <kbd>f</kbd><kbd><\*></kbd> - find the next occurrence of a character
- <kbd>F</kbd><kbd><\*></kbd> - find the previous occurrence of a character
- <kbd>t</kbd><kbd><\*></kbd> - till the next occurrence of a character (moves the cursor to one character before the character you want to find)
- <kbd>T</kbd><kbd><\*></kbd> - till the previous occurrence of a character (moves the cursor to one character after the character you want to find)

## Vertical Movements

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
