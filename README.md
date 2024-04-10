# Markdown Lazy Links

This program modifies markdown files to:
- add table of contents to the head of your file (and ignoring [Hugo's](https://gohugo.io/) frontmatter if it exists)
- generate a footer with all (non-image) links from your file
- modify existing titles to titlecase format

The changes are put into a file called "processed" in the same directory, so the original files should be untouched. Vitally, you should backup your files to another directory first if you are unsure or modifying important files with this program.

## Images
Before and after conversion
![Preview web](https://github.com/danieljudd/markdownlazylinks/blob/main/images/example1_preview.png)
The process of manual review (can disable)
![Preview terminal](https://github.com/danieljudd/markdownlazylinks/blob/main/images/example1_program.png)

## Download
Get the MDLL.zip
[v1.0.0 Released Here](https://github.com/danieljudd/markdownlazylinks/releases)

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
