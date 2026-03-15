# Certificates

![Language](https://img.shields.io/badge/Language-Python-3776AB?style=flat-square) ![Stars](https://img.shields.io/github/stars/Devanik21/Certificates?style=flat-square&color=yellow) ![Forks](https://img.shields.io/github/forks/Devanik21/Certificates?style=flat-square&color=blue) ![Author](https://img.shields.io/badge/Author-Devanik21-black?style=flat-square&logo=github) ![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)

> A curated record of professional learning — certifications, credentials, and completed courses in AI, ML, and software engineering.

---

**Topics:** `python` · `achievements` · `ai-research` · `certifications` · `data-science` · `deep-learning` · `education` · `machine-learning` · `portfolio` · `professional-development`

## Overview

This repository serves as a transparent, version-controlled portfolio of professional certifications and
completed training programmes. Rather than leaving credentials scattered across platforms like Coursera,
Udemy, Google, and LinkedIn Learning, this repository centralises them as a single, linkable reference —
useful for sharing with recruiters, collaborators, or academic supervisors.

Each certificate is catalogued with its issuing organisation, completion date, credential ID (where applicable),
and a brief description of the skills it validates. The collection spans machine learning fundamentals,
deep learning, cloud platforms, data engineering, software development, and domain-specific AI applications.

The repository is structured to grow continuously as new certifications are earned. It acts both as a
professional credential archive and as a learning log that documents the trajectory of skill acquisition
over time — from foundational statistics and programming through to advanced deep learning and MLOps.

---

## Motivation

Professional certifications represent concrete, externally validated milestones in a learning journey.
Maintaining them in a public, version-controlled repository rather than as PDFs on a local drive makes
them accessible, searchable, and verifiable — demonstrating not just what was learned, but the
sustained commitment to continuous professional development.

---

## Architecture

```
Certificates Repository Structure
        │
  README.md (master index with links)
        │
  ┌─────────────────────────────────┐
  │  /certificates/                 │
  │  ├── ML_Fundamentals/           │
  │  ├── Deep_Learning/             │
  │  ├── Cloud_AI/                  │
  │  ├── Data_Engineering/          │
  │  └── Software_Engineering/      │
  └─────────────────────────────────┘
        │
  Each entry: issuer, date, credential_id, skills_validated
```

---

## Features

### Centralized Credential Archive
All certificates consolidated in one repository with consistent metadata: issuing organisation, completion date, credential ID, and skill tags.

### Category Organisation
Certificates grouped by domain (ML/DL, Cloud, Data, Software) for navigable browsing rather than a flat list.

### Verified Credential Links
Where platforms provide public verification URLs (Coursera, Google, Credly), direct links are included for third-party validation.

### Skill Taxonomy Tags
Each certificate tagged with the specific technical skills it validates (e.g., `#PyTorch`, `#NLP`, `#GCP`, `#FastAPI`) for keyword searchability.

### Learning Timeline
Certificates presented in chronological order to visualise the progression of skill acquisition over time.

### PDF Archive
Certificate PDFs stored in the repository or linked to permanent cloud storage for offline reference.

### Domain Coverage Summary
A summary table at the top of the README provides an at-a-glance view of covered domains and total credential count.

### Continuous Updates
Repository updated immediately upon completion of each new certification — maintained as a living document.

---

## Tech Stack

| Library / Tool | Role | Why This Choice |
|---|---|---|
| **GitHub** | Repository hosting | Version control, public accessibility, commit history as timestamp proof |
| **Markdown** | Documentation | Human-readable index with tables, links, and badges |
| **Git LFS (optional)** | Large file storage | PDF certificate storage without bloating repo history |

---

## Getting Started

### Prerequisites

- Python 3.9+ (or Node.js 18+ for TypeScript/JavaScript projects)
- A virtual environment manager (`venv`, `conda`, or equivalent)
- API keys as listed in the Configuration section

### Installation

```bash
git clone https://github.com/Devanik21/Certificates.git
cd Certificates
# Browse README.md for the full certificate index
```

---

## Usage

```bash
# View the certificate index
cat README.md

# Find certificates by skill tag
grep -r "PyTorch" .

# List certificates by issuer
grep -r "Coursera" certificates/
```

---

## Configuration

| Variable | Default | Description |
|---|---|---|
| `CERT_DIR` | `certificates/` | Root directory for certificate files |
| `INDEX_FILE` | `README.md` | Master index document |

> Copy `.env.example` to `.env` and populate required values before running.

---

## Project Structure

```
Certificates/
├── README.md
└── ...
```

---

## Roadmap

- [ ] Add digital badge embeds from Credly and LinkedIn Learning for visual credential display
- [ ] Automated certificate metadata extraction script from PDF files using pdfplumber
- [ ] GitHub Actions workflow to auto-update the README index when new certificates are added
- [ ] Skills radar chart generated from certificate tags to visualise competency breadth
- [ ] Integration with LinkedIn profile API to sync certifications automatically

---

## Contributing

Contributions, issues, and suggestions are welcome.

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-idea`
3. Commit your changes: `git commit -m 'feat: add your idea'`
4. Push to your branch: `git push origin feature/your-idea`
5. Open a Pull Request with a clear description

Please follow conventional commit messages and add documentation for new features.

---

## Notes

All certificates listed are genuine completions. Credential IDs are provided where platforms offer public verification. This repository is maintained as an honest professional record.

---

## Author

**Devanik Debnath**  
B.Tech, Electronics & Communication Engineering  
National Institute of Technology Agartala

[![GitHub](https://img.shields.io/badge/GitHub-Devanik21-black?style=flat-square&logo=github)](https://github.com/Devanik21)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-devanik-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/devanik/)

---

## License

This project is open source and available under the [MIT License](LICENSE).

---

*Built with curiosity, depth, and care — because good projects deserve good documentation.*
