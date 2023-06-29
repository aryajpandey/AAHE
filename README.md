# AAHE - Linux Text Editor

AAHE is a lightweight text editor for Linux, inspired by the minimalist design and functionality of the kilo text editor. It aims to provide a simple and efficient editing experience while keeping the codebase concise and easy to understand.

## Features

- Basic text editing functionalities
- VT100-style command mode for efficient navigation and editing
- Support for opening and saving text files
- Syntax highlighting (optional)
- Search and replace functionality
- Undo and redo operations

## Usage

### Installation

To compile and install AAHE, follow these steps:

1. Clone the AAHE repository:

   ```
   git clone <repository-url>
   ```

2. Navigate to the AAHE directory:

   ```
   cd AAHE
   ```

3. Compile the code using GCC:

   ```
   gcc -o aahe aahe.c -lm -lncurses
   ```

   Note: AAHE requires the `ncurses` library for terminal handling and `lm` library for math operations. Ensure that these libraries are installed on your system.

4. Run AAHE:

   ```
   ./aahe
   ```

### Command Mode

AAHE uses a VT100-style command mode for efficient navigation and editing. Here are some basic commands you can use:

- **Navigation**:
  - Arrow keys: Move the cursor up, down, left, or right.
  - Page Up: Scroll up one page.
  - Page Down: Scroll down one page.
  - Home: Move the cursor to the beginning of the current line.
  - End: Move the cursor to the end of the current line.
- **Editing**:
  - Insert: Toggle between insert and overwrite mode.
  - Backspace: Delete the character before the cursor.
  - Delete: Delete the character at the cursor.
  - Tab: Insert a tab character.
- **Saving and Quitting**:
  - Ctrl+S: Save the file.
  - Ctrl+Q: Quit AAHE.

### Syntax Highlighting

AAHE supports optional syntax highlighting for various programming languages. To enable syntax highlighting for a specific file, save the file with an extension that matches the language (e.g., ".c" for C code). When you open the file in AAHE, the syntax highlighting will be automatically applied.

## Contributing

Contributions to AAHE are welcome! If you find any issues or have suggestions for improvements, please submit them through the issue tracker or submit a pull request.

## License

AAHE is open-source software released under the [MIT License](https://opensource.org/licenses/MIT).