# Professional Résumé | João Victor Mendes

<p align="left">
  <img src="https://img.shields.io/badge/LaTeX-source-008080?style=for-the-badge&logo=latex&logoColor=white" alt="LaTeX source"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="MIT license"/>
  <a href="https://github.com/victormends/curriculum-victor-mendes/blob/main/Joao_Victor_Mendes_Resume.pdf">
    <img src="https://img.shields.io/badge/VIEW%20R%C3%89SUM%C3%89%20%E2%80%94%20PDF-132046?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="View PDF"/>
  </a>
</p>

This repository contains the LaTeX source and compiled PDF for my professional résumé, focused on **L2/L3 Technical Support Engineering, PostgreSQL Infrastructure, and ETL Automation.**

The repository exists to keep the résumé auditable: the source, wording changes, and compiled PDF are version-controlled together instead of maintained as an opaque document export.

## Profile Focus
- **PostgreSQL Specialist:** Deep-dive diagnostics involving WAL management, replication slots, and system catalog internals.
- **Support Operations:** High-throughput incident response (80+ tickets/week) with a focus on de-escalation and structural RCA.
- **Automation:** Systems-level PowerShell and SQL pipelines for infrastructure recovery and massive dataset ingestion.

## Source
- **Layout:** Clean, single-column layout built on the standard `article` class.
- **Format:** LaTeX source with a compiled PDF checked into the repository.
- **Tooling:** pdfLaTeX, Charter font, and standard packages.

## Build

Compile locally with a LaTeX distribution that includes `pdflatex`:

```powershell
pdflatex template.tex
```

The tracked PDF is the public résumé artifact. If the source changes, rebuild the PDF and review the rendered output before publishing.

## Public Release Checklist

- `template.tex` compiles without LaTeX errors.
- The tracked PDF matches the current source.
- Contact links and GitHub/LinkedIn URLs work.
- Claims and metrics are intentionally résumé-level summaries, not client-identifying case studies.
- No private client names, internal hostnames, credentials, or non-public incident details are included.

---
*Note: This résumé is version-controlled so the source and compiled PDF stay in sync.*
