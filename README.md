# Professional Résumé | João Victor Mendes

<p align="left">
  <a href="https://github.com/victormends/curriculum-victor-mendes/actions/workflows/build-latex.yml">
    <img src="https://github.com/victormends/curriculum-victor-mendes/actions/workflows/build-latex.yml/badge.svg" alt="Build Status"/>
  </a>
  <img src="https://img.shields.io/badge/LaTeX-source-008080?style=for-the-badge&logo=latex&logoColor=white" alt="LaTeX source"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="MIT license"/>
</p>

<p align="left">
  <a href="https://github.com/victormends/curriculum-victor-mendes/blob/main/Joao_Victor_Mendes_Resume.pdf">
    <img src="https://img.shields.io/badge/VIEW%20R%C3%89SUM%C3%89%20%E2%80%94%20EN-132046?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="View EN Résumé"/>
  </a>
  &nbsp;
  <a href="https://github.com/victormends/curriculum-victor-mendes/blob/main/Joao_Victor_Mendes_Curriculo.pdf">
    <img src="https://img.shields.io/badge/VER%20CURR%C3%8DCULO%20%E2%80%94%20PT--BR-1a3a6b?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Ver Currículo PT-BR"/>
  </a>
</p>

This repository contains the LaTeX source and compiled PDFs for my professional résumé (EN) and currículo (PT-BR), focused on **L2/L3 Technical Support Engineering, PostgreSQL Infrastructure, and ETL Automation.**

The repository exists to keep the résumé auditable: the source, wording changes, and compiled PDF are version-controlled together instead of maintained as an opaque document export.

## Profile Focus
- **PostgreSQL Specialist:** Deep-dive diagnostics involving WAL management, replication slots, and system catalog internals.
- **Support Operations:** High-throughput incident response (80+ tickets/week) with a focus on de-escalation and structural RCA.
- **Automation:** Systems-level PowerShell and SQL pipelines for infrastructure recovery and massive dataset ingestion.

## Source
- **Layout:** Clean, single-column layout built on the standard `article` class.
- **Files:** `template.tex` (EN) · `template_ptbr.tex` (PT-BR) · compiled PDFs checked into the repository.
- **Tooling:** pdfLaTeX, Charter font, and standard packages.
- **CI:** GitHub Actions compiles both PDFs automatically on every push and commits the output back to `main`.

## Build

Compile locally with a LaTeX distribution that includes `pdflatex`:

```powershell
pdflatex template.tex        # EN résumé
pdflatex template_ptbr.tex   # PT-BR currículo
```

The tracked PDFs are the public résumé artifacts. CI compiles them automatically on every push to `main`.

## Public Release Checklist

- `template.tex` compiles without LaTeX errors.
- The tracked PDF matches the current source.
- Contact links and GitHub/LinkedIn URLs work.
- Claims and metrics are intentionally résumé-level summaries, not client-identifying case studies.
- No private client names, internal hostnames, credentials, or non-public incident details are included.

---
*The PDFs in this repository are always in sync with the LaTeX source — compiled automatically by CI.*
