# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

- `mkdocs new [dir-name]` - Create a new project.
- `mkdocs serve` - Start the live-reloading docs server.
- `mkdocs build` - Build the documentation site.
- `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

```py title="bubble_sort.py"
def bubble_sort(items):
  for i in range(len(items)):
    for j in range(0, len(items) - i - 1):
      if items[j] > items[j + 1]:
        items[j], items[j + 1] = items[j + 1], items[j]
```
