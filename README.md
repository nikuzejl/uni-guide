## Uni Guide - University Application Guide for International Students

A bilingual guide in English and French for international students, especially from Burundi, applying to universities in North America.

### About This Guide

This site provides a basic overview of the university application process in the U.S. and Canada for both undergraduate and graduate studies. It includes information on scholarships, visa procedures, English language tests, and other academic migration opportunities.

### Bilingual Support

This documentation supports both English and French with clean URL-based language switching through `mkdocs-static-i18n`:

- English: `http://localhost:8000/`
- French: `http://localhost:8000/fr/`

Users can switch languages using the language selector button in the navigation bar.

### Quick Start

#### Prerequisites

- Python 3.6+
- pip

#### Serve Locally

```bash
cd uni-guide
pip install mkdocs mkdocs-material mkdocs-static-i18n
mkdocs serve
```

#### Build

```bash
mkdocs build
```

### File Organization

English pages use normal Markdown filenames. French pages use the `.fr.md` suffix beside their English equivalents.

```text
docs/
+-- index.md
+-- index.fr.md
+-- undergrad.md
+-- undergrad.fr.md
+-- images/
+-- others/
    +-- usa-student-visa.md
    +-- usa-student-visa.fr.md
```

### Key Features

- Bilingual support with English and French language switching
- Clean URLs with English at `/` and French at `/fr/`
- Default English language
- Dark and light mode
- Mobile responsive layout
- Fast navigation

### Configuration

- `mkdocs.yml` builds both English and French using `docs_structure: suffix`

### Contact

Email: `jnikuze3@gatech.edu`
