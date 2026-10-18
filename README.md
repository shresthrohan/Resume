# Resume & Cover Letter

This repository contains my current resume and cover letter, kept under version control so I can track changes over time and tailor versions for different applications.

## Contents

```
.
├── resume.pdf              # Latest version of my resume
├── cover-letter.pdf        # General-purpose cover letter template
├── src/                    # HTML sources; PDFs are printed from these
│   ├── resume.html
│   └── cover-letter.html
├── archive/                # Older resume versions
└── README.md
```

## Building the PDFs

Open a file in `src/` in Chrome and print it with "Save as PDF", or run it headless:

```
chrome --headless --no-pdf-header-footer --print-to-pdf=resume.pdf src/resume.html
```


## License

This content is personal and not licensed for reuse. All rights reserved.
