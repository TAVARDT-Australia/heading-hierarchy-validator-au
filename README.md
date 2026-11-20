# Heading Tags (H1-H6) Auditor and Semantic Hierarchy Checker

[![Heading Tags Auditor](https://img.shields.io/badge/TAVARDT-Heading%20Hierarchy-5b3cf5.svg)](https://tools.tavardt.com/au/heading-tags-checker/)
[![Jurisdiction](https://img.shields.io/badge/Jurisdiction-Australia-00C853.svg)](https://ag.tavardt.com/au/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Evaluating HTML document outline structure, single H1 adherence, and skipping level detection.

Developed and maintained by the digital systems and accessibility group at **[TAVARDT Australia](https://ag.tavardt.com/au/)**.

---

## Heading Structure Auditing Capabilities

* **H1 Singularity Validation**: Ensuring document outlines adhere to single-H1 semantic standards.
* **Heading Skip Detection**: Flagging improper level leaps that breach WCAG accessibility criteria.
* **Empty Tag Removal Alerts**: Identifying headings rendered without descriptive content.
* **Indented Outline Generation**: Displaying clear visual representations of document nesting.
* **Semantic Structure Rating**: Technical score from 0 to 100 with actionable optimization notes.

---

## Installation and Usage

Compatible with Python 3.8+ without additional packages.

```bash
git clone https://github.com/TAVARDT-Australia/heading-hierarchy-validator-au.git
cd heading-hierarchy-validator-au
python heading_hierarchy_validator.py https://enterprise.com.au
```

Run with structured JSON output:

```bash
python heading_hierarchy_validator.py https://enterprise.com.au --json
```

---

## Australian Diagnostic Suite

For interactive heading structure testing in the cloud:

* **[Official Heading Tags Checker](https://tools.tavardt.com/au/heading-tags-checker/)**
* **[TAVARDT Australia Portal](https://ag.tavardt.com/au/)**

---

## Australian Enterprise Inquiries

For technical assistance aligned with Australian Digital Transformation Agency Web Standards and W3C WCAG, contact **[TAVARDT Australia](https://ag.tavardt.com/au/contact/)**.
