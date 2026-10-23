# AI Log Analyzer

**Linux log analysis and a web dashboard for reviewing system events.**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

## Overview

AI Log Analyzer is a Linux-based web application built with Python, Flask, HTML, CSS, and JavaScript. It helps review Linux system logs and presents simplified, AI-style explanations of notable events such as failed login attempts, disk-usage warnings, and system activity.

The project is a collaborative engineering exercise. Its documented scope is log review, event classification, and presentation through a web interface; it should not be confused with a production SIEM or autonomous incident-response system.

## Documented capabilities

- Linux system log analysis
- Flask backend API
- Frontend dashboard
- AI-style explanations of log events
- Error and warning classification

## Technology

| Layer | Technologies |
| --- | --- |
| Backend | Python, Flask |
| Frontend | HTML, CSS, JavaScript |
| Environment | Ubuntu Linux, VMware |

## Architecture at a glance

```text
Linux system logs
       |
       v
Log processing and event classification
       |
       v
Flask backend API
       |
       v
Web dashboard and simplified explanations
```

This is a conceptual view of the documented components, not a claim about a specific deployment topology.

## Collaboration and credits

| Contributor | Documented responsibility |
| --- | --- |
| **Ruveeha Ashfaq** | Backend development and API handling |
| **Haziq Afzal** | Frontend UI and API integration |
| **Ambreen Imtiaz** | AI logic and log classification system |

The responsibilities above preserve the project's original contributor attribution.

## Review the project

Explore the repository source and history to inspect the implementation. Deployment requirements and automated test coverage should be confirmed from the source before production use.

---

Part of [Haziq Afzal's engineering portfolio](https://github.com/HaziqBinAfzal). For more collaborative engineering work, see [HR-Presents](https://github.com/HR-Presents).
