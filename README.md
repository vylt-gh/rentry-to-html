# Rentry to HTML
A Python script which converts Rentry style markdown to HTML, trying to stay as faithful to the original output as possible.

> [!WARNING]
> This file was written solely by AI, aka vibe-coded. I also haven't tested this much, but it works for my use case so I'd say it's good enough. View this as more of a proof-of-concept.

## How to Use
1) Download the Python script
2) Write (or copy) your Rentry markdown to a local .md file
3) If you have metadata, write (or copy) it to a .txt file.
4) Run the Python script like so:

   `python3 parser.py rentry.md -o output.html --meta metadata.txt`

where `rentry.md` is your input file in Rentry markdown, and optionally, `metadata.txt` is your metadata fields.
