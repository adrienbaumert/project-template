# Project Documentation Template

This repository provides a **template structure for organizing technical documentation using LaTeX**.  
Documents are written in `.tex` format and compiled into PDF files for distribution.

---

## Table of Contents

- [Overview](#overview)
- [Documentation](#documentation)
- [Repository Structure](#repository-structure)
- [Development Notes](#development-notes)
- [Building the PDFs](#building-the-pdfs)
- [Contributing](#contributing)

---

## Overview

This template demonstrates a clean way to organize project documentation:

- **LaTeX sources** stored separately from generated files
- **PDF outputs** committed for easy viewing
- **Structured documentation folders**
- **Simple manual compilation workflow**

The structure is intended for:

- engineering documentation
- architecture writeups
- design documents
- project mission / goals
- technical deep dives

---

## Documentation

- [Technical Deep Dive](./docs/technical_deep_dive.pdf)  
- [Mission Statement](./docs/mission_statement.pdf)  
- [Project Goals](./docs/goals.pdf)

---

## Repository Structure

```
.
├── dev_docs
│   ├── notes.md
│   └── todo.md
├── docs
│   ├── goals.pdf
│   ├── mission_statement.pdf
│   ├── technical_deep_dive.pdf
│   └── tex_files
│       ├── goals.tex
│       ├── mission_statement.tex
│       └── technical_deep_dive.tex
└── README.md
```

---

## Development Notes

Informal development materials can be placed in:

```
dev_docs/
```

This directory may contain:

- planning notes
- brainstorming documents
- architecture sketches
- development TODO lists

---

## Building the PDFs

The LaTeX sources are located in:

```
docs/tex_files/
```

Compile a document using:

```bash
pdflatex -output-directory=docs docs/tex_files/<document>.tex
```

Example:

```bash
pdflatex -output-directory=docs docs/tex_files/goals.tex
```

This places the generated PDF in the `docs/` directory.

---

## Contributing

1. Edit or add `.tex` files inside `docs/tex_files/`
2. Compile the document locally
3. Commit both the updated source and generated PDF
4. Submit changes through the normal Git workflow

---

## Notes

This repository is intended as a **documentation template**.  
You can freely adapt the folder structure and document types to suit your project.