# Documentation

This repository contains project documentation and supporting materials.

## Documents

- [Technical Deep Dive](docs/technical_deep_dive.pdf)
- [Mission Statement](docs/mission_statement.pdf)
- [Project Goals](docs/goals.pdf)

## Development Notes

Additional notes and planning documents are located in `dev_docs/`.

## LaTeX Sources

The LaTeX source files are located in `docs/tex_files/`.

## Building PDFs

Compile a document manually with:

pdflatex -output-directory=docs docs/tex_files/<document>.tex

Example:

pdflatex -output-directory=docs docs/tex_files/goals.tex