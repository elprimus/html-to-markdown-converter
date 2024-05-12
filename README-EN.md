# htmlToMd

# HTML to Markdown Converter

This is a simple Python program to convert HTML files to Markdown files.

## Features

- Converts HTML files to Markdown.
- Accepts paths to HTML files as input.
- Allows specifying the path where the resulting Markdown file will be saved.
- Provides a help message explaining how to use the program.

## How to Use

To use this program, follow the instructions below:

1. Clone this repository:

   ```bash
   git clone https://github.com/elprimus/html-to-markdown-converter.git
   ```
2. Navigate to the project directory:

   ```bash
   cd html-to-markdown-converter
   ```
3. Run the Python program by providing the path to the HTML file and the path to write the Markdown file:

   ```bash
   python converter.py <path_to_html_file> <path_to_write_md_file>
   ```

   For example:

   ```bash
   python converter.py input.html output.md
   ```

   This will convert the HTML file `input.html` to Markdown and save it as `output.md`.

## Requirements

- Python 3.x
- html2text library (installable via pip)

  ```bash
  pip install html2text
  ```

## Contributing

If you encounter issues or have suggestions for improvements, feel free to open an issue or submit a pull request in this repository.
