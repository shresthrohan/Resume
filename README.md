# Resume & Cover Letter

This repository contains my current resume and cover letter, kept under version control so I can track changes over time and tailor versions for different applications.

## Contents

```
.
├── resume.pdf              # Latest version of my resume
├── cover-letter.pdf        # General-purpose cover letter template
├── src/                    # Source files (e.g. LaTeX, Markdown, or Word docs)
│   ├── resume.tex
│   └── cover-letter.tex
└── README.md
```

## Usage

To build the PDFs from source (if using LaTeX):

```bash
cd src
pdflatex resume.tex
pdflatex cover-letter.tex
```

Adjust this section if you're using a different toolchain (e.g. Markdown + Pandoc, Word, or a design tool export).

## Versioning

- `main` holds the most current, general-purpose versions.
- Tailored versions for specific applications can live on branches or in a `versions/` folder, named by company or role (e.g. `versions/2026-01-acme-corp.pdf`).

## License

This content is personal and not licensed for reuse. All rights reserved.
