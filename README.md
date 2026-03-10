# Documentation

Comprehensive documentation for the project, including technical design, organizational direction, and development goals.

---

## Table of Contents

- [Overview](#overview)
- [Documents](#documents)
- [Repository Structure](#repository-structure)
- [Development Notes](#development-notes)
- [Building the PDFs](#building-the-pdfs)
- [Contributing](#contributing)

---

## Overview

This repository contains structured documentation written in LaTeX and compiled into PDF format.  
The goal is to provide clear, version-controlled technical and organizational documentation.

---

## Documents

- **Technical Deep Dive**  
  [technical_deep_dive.pdf](docs/technical_deep_dive.pdf)

- **Mission Statement**  
  [mission_statement.pdf](docs/mission_statement.pdf)

- **Project Goals**  
  [goals.pdf](docs/goals.pdf)

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

Internal planning and informal documentation can be found in:

```
dev_docs/
```

These files may include:

- design notes
- planning documents
- brainstorming materials
- development TODOs

---

## Building the PDFs

The LaTeX source files are located in:

```
docs/tex_files/
```

To compile a document manually:

```bash
pdflatex -output-directory=docs docs/tex_files/<document>.tex
```

Example:

```bash
pdflatex -output-directory=docs docs/tex_files/goals.tex
```

---

## Contributing

1. Modify the `.tex` source in `docs/tex_files/`
2. Compile the document locally
3. Commit the updated `.tex` and generated `.pdf`
4. Submit changes through normal Git workflow

---

## License

Documentation in this repository is open for use, modification, and distribution according to the repository license.