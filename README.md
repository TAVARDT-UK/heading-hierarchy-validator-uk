# Heading Tags (H1-H6) Hierarchy and Semantic Structure Validator

[![Heading Tags Checker](https://img.shields.io/badge/TAVARDT-Heading%20Hierarchy-5b3cf5.svg)](https://tools.tavardt.com/uk/heading-tags-checker/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Auditing HTML5 document outlines, single H1 uniqueness, heading level skip detection, and screen reader clarity.

Engineered and maintained by the accessibility and semantic architecture team at **TAVARDT UK**.

***

## Heading Tags (H1-H6) Auditing Capabilities

* **Single H1 Tag Verification**: Ensuring the document maintains exactly one authoritative `<h1>` defining page context.
* **Heading Level Skip Detection**: Pinpointing illegal level hops (such as jumping from `<h2>` directly to `<h4>`) that confuse screen reader software.
* **Empty and Redundant Heading Checks**: Flagging empty header elements and excessively long headline strings.
* **Visual Document Outline**: Producing an indented hierarchical tree representing the full semantic flow.
* **Semantic Structure Health Score**: Quantitative rating from 0 to 100 aligned with W3C WCAG guidelines.

***

## Installation and Execution

Requires Python 3.8+ using the Python standard library only.

```bash
git clone https://github.com/TAVARDT-UK/heading-hierarchy-validator-uk.git
cd heading-hierarchy-validator-uk
python heading_hierarchy_validator.py https://enterprise.co.uk
```

To output structured JSON data for automated build testing:

```bash
python heading_hierarchy_validator.py https://enterprise.co.uk -json
```

***

## Official Web Platform

For visual outline rendering and online auditing:

* **Official Heading Tags Checker**
* **TAVARDT UK Portal**

***

## Enterprise Technical Advisory

For professional semantic reviews conforming to UK Government Digital Service and W3C WCAG Standards, contact **TAVARDT UK**.
