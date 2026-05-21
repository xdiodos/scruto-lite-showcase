# Scoring Methodology

Scruto Lite uses a weighted scoring model across multiple assessment categories.

The scoring model is designed to:

- Provide a simplified security posture overview
- Avoid over-penalizing unavailable or non-applicable categories
- Support N/A handling
- Present readable grade output
- Prioritize practical recommendations

Assessment categories may include areas such as:

- Web exposure
- TLS / HTTPS posture
- Security headers
- Mail-related checks
- Basic service exposure
- DNS-related observations
- Recommendation severity
- Overall report quality signals

Some categories may be marked as N/A when they are not applicable to the assessed target.

The public documentation explains the scoring principles but does not disclose the full internal calculation logic, thresholds, weights, or implementation details.
