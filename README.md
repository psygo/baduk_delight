# Baduk Delight

A miscellanea book on Go.

## Development Setup

File paths are very annoying in TeX. And, for this project, we need to set up a global file path because each folder uses its own level as its reference. It's a bit repetitive, the other way around would be to define an environment variable on the terminal. For now, this is what I've been doing at the top of each file:

```tex
\def\repoPath{pathToTheRepo}
\usepackage{\repoPath/config}
```

## References

- [@psygo/tsumego_workbooks](https://github.com/psygo/tsumego_workbooks)
- [@psygo/tecnicas_de_go](https://github.com/psygo/tecnicas_de_go)
- [@101books/101books.github.io](https://github.com/101books/101books.github.io)
  - [101books.github.io](https://101books.github.io/)
