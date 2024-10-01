# Markdown to LinkedIn Converter

This Node.js script converts Markdown (.md) files to a LinkedIn-style format. It reads an input Markdown file (`input.md`), processes the content, and writes the converted text to an output file (`output.ld`).

## Features

- Converts Markdown headers to LinkedIn-style headers.
- Transforms bold text to italics and italics to underline.
- Removes images and links for a cleaner LinkedIn format.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/markdown-to-linkedin.git
    cd markdown-to-linkedin
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

## Usage

1. Place your Markdown file in the root directory and name it `input.md`.

2. Run the script:
    ```bash
    node convert.js
    ```

3. The converted text will be saved in `output.ld`.

## Example

### Input (`input.md`)
```markdown
# Title
## Subtitle
### Subheading

**Bold text**

*Italic text*

!Image

Link
