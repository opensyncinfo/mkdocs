# Welcome to MkDocs2

![Placeholder](https://dummyimage.com/150x100/eee/aaa){: align=right }

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Test1

Das ist ein Test[^1].

## Test2

* [ ] Nicht
* [x] Erledigt

## Test3

==This was marked==

This not

## Test4

```python linenums="1"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

## Test5

| Method      | Description                          |
| ----------- | ------------------------------------ |
| `GET`       | :material-check:     Fetch resource  |
| `PUT`       | :material-check-all: Update resource |
| `DELETE`    | :material-close:     Delete resource |

## Test6

!!! note
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

!!! info
    massa, nec semper lorem quam in massa.

!!! tip
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    massa, nec semper lorem quam in massa.

!!! done
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod

!!! bug
    Nulla et euismod nulla. Curabitur feugiat, tortor non

!!! warning
    justo purus auctor massa, nec semper lorem quam in massa

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

[^1]: Bla Bla
