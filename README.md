# Evernote to Markdown converter

This is a fork of https://github.com/wormi4ok/evernote2md, please see that for install instructions, etc.

## My modifications

- don't include filename as note title
- undo escaping chars
- allow spaces in filenames
- url-escape resources (eg images), so that filenames can have spaces
- add Obsidian-style highlighting: `==text to highlight==`
- remove note's leading newlines
- remove funky `<0xa0>` space characters