# Markdown Lazy Links

This program modifies markdown files to:
- add table of contents to the head of your file (ignoring Hugo's frontmatter)
- generate a footer with all non-image links from your file
- change titles to titlecase

The changes are put into a file called "processed" in the same directory, so the original files should be untouched. Vitally, you should backup your files to another directory first if you are unsure or modifying important files with this program (and send me a bug report).

## How to use
1. Place .exe in the same directory as markdown files (optional but easier)
2. In terminal run the .exe
3. Follow prompts

## Options
```
options:
  -h, --help        show this help message and exit
  --path [PATH]     Path to a markdown file or a directory to process.
  --no-links        Do not parse and reformat links as footnotes.
  --no-titlecase    Do not convert headings to title case.
  --no-interactive  Disable interactive mode for title case corrections.
  --no-toc          Do not generate a Table of Contents at the beginning of the document.
```