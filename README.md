# Scruto Lite Showcase

## Access Scruto Lite

Scruto Lite is available at:

https://scruto.xdiodos.com

Please only scan websites, domains, or systems that you own, operate, or are explicitly authorized to assess.

For feedback or report-related questions, contact:

support@xdiodos.com


Scruto Lite is a lightweight security assessment and reporting experience designed for basic website exposure review, readable security reporting, and early-stage security awareness.

This repository is a public showcase repository.

It provides:

- Product overview
- Usage flow
- Screenshots
- Sample reports
- Public documentation
- Roadmap
- Usage disclaimer

This repository does not include:

- Source code
- Scanner engine logic
- Backend implementation
- Deployment scripts
- Infrastructure configuration
- Internal abuse-prevention logic
- Private operational details

## Status

Scruto Lite currently includes:

- Landing Page
- Consent Page
- Scan Policy validation
- Web Report
- PDF Report
- Grade Badge
- Weighted scoring
- Mail N/A handling
- Recommendation aggregation
- Feedback Channel

## Documentation

- [Overview](docs/overview.md)
- [Usage Flow](docs/usage-flow.md)
- [Scan Policy](docs/scan-policy.md)
- [Scoring Methodology](docs/scoring-methodology.md)
- [Report Guide](docs/report-guide.md)
- [Public Scope](docs/public-scope.md)
- [FAQ](docs/faq.md)

## Visual Assets

Public showcase assets are available under:

- assets/logo/
- assets/badges/

The logo and grade badge images are provided for product demonstration and documentation purposes only.

All rights reserved by xDiodos / OSSIP Lab.

## Product Screenshots

### Landing Page

<img src="screenshots/01-landing-page.png" alt="Scruto Lite Landing Page" width="900">

### Consent Page

<img src="screenshots/02-consent-page.png" alt="Scruto Lite Consent Page" width="900">

### Scan Progress

<img src="screenshots/03-scan-progress.png" alt="Scruto Lite Scan Progress" width="900">

### Web Report Summary

<img src="screenshots/04-web-report-summary.png" alt="Scruto Lite Web Report Summary" width="900">

### Scan Reliability and Score Breakdown

<img src="screenshots/05-web-report-reliability-score.png" alt="Scruto Lite Reliability and Score Breakdown" width="900">

### Findings and Evidence

<img src="screenshots/06-web-report-findings.png" alt="Scruto Lite Findings and Evidence" width="900">

### Improvement Roadmap

<img src="screenshots/07-web-report-roadmap.png" alt="Scruto Lite Improvement Roadmap" width="900">

### Recommendations and Feedback

<img src="screenshots/08-web-report-recommendations.png" alt="Scruto Lite Recommendations and Feedback" width="900">

## Sample Report

A redacted sample PDF report will be provided under:

- samples/reports/

## Public Repository Scope

This repository is intended for product showcase and public documentation only.

It is not an open-source scanner repository and does not include implementation details.

## Contact

For product questions, feedback, or report-related inquiries:

support@xdiodos.com

## License

All rights reserved. See [LICENSE](LICENSE).

---

## Scruto API Early Preview

Scruto API is a safe external API exposure scan feature for publicly reachable API endpoints.

It focuses on visibility and risk signals, not exploitation.

Scruto API currently checks for:

- Public API documentation exposure
- CORS risk signals
- GraphQL exposure signals
- Sensitive data indicators
- Error and debug leakage
- Protection Signal / Scan Visibility

Safety policy:

- No login
- No token testing
- No brute force
- No exploitation
- No authentication bypass
- No destructive testing

Scruto API only performs safe, unauthenticated, read-only checks using GET, HEAD, and OPTIONS.

Preview:

https://scruto.xdiodos.com/scruto-api

More details:

- [Scruto API](docs/scruto-api.md)
- [Scruto API Usage Flow](docs/scruto-api-usage-flow.md)

### Scruto API Screenshots

- [Landing page](screenshots/scruto-api/01-api-landing.png)
- [Usage notice](screenshots/scruto-api/02-api-consent.png)
- [API scan report](screenshots/scruto-api/03-api-report.png)

---

## Scruto API Preview Screenshots

### Landing Page

![Scruto API landing page](screenshots/scruto-api/01-api-landing.png)

### Usage Notice

![Scruto API consent page](screenshots/scruto-api/02-api-consent.png)

### API Scan Report

![Scruto API report](screenshots/scruto-api/03-api-report.png)
