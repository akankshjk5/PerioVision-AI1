# docs

| Document | What it covers |
|---|---|
| [ARCHITECTURE.md](ARCHITECTURE.md) | Components, data flow, request lifecycle |
| [API.md](API.md) · [openapi.json](openapi.json) | Every endpoint, its permission and payloads |
| [SECURITY.md](SECURITY.md) · [KEY_ROTATION.md](KEY_ROTATION.md) | Security controls, threat model, key rotation |
| [DEPLOYMENT.md](DEPLOYMENT.md) | Production setup (MongoDB, secrets, waitress, HTTPS proxy) |
| [MODEL_CARD.md](MODEL_CARD.md) | Every model, its training data and its held-out accuracy |
| [DATASETS.md](DATASETS.md) | Datasets used, licences, where to get them |
| [VERIFICATION_REPORT.md](VERIFICATION_REPORT.md) | Independent verification and accuracy audit, with re-run commands |
| [INSTRUCTIONS_FOR_USE.md](INSTRUCTIONS_FOR_USE.md) | How clinicians should read every result, and its limits |
| [PROJECT_REPORT.md](PROJECT_REPORT.md) · [TRACEABILITY.md](TRACEABILITY.md) · [TALPA.md](TALPA.md) | Academic report, synopsis-objective traceability, TALPA notes |
| [evidence/](evidence/) | Raw outputs of every evaluation quoted in these documents |
| [reference/screenshots/](reference/screenshots/) | Screenshots used by the main README |

## Security

Start with **[SECURITY_ARCHITECTURE.md](SECURITY_ARCHITECTURE.md)** â€” the request path, the
layers, the trust boundaries, and the diagrams.

| Document | Answers |
|---|---|
| [SECURITY_ARCHITECTURE.md](SECURITY_ARCHITECTURE.md) | How a request is checked, and where the boundaries are |
| [THREAT_MODEL.md](THREAT_MODEL.md) | Who attacks what, which control stops it, what residual risk remains |
| [SECURITY_CONTROLS.md](SECURITY_CONTROLS.md) | Every control, where it lives, what proves it works |
| [API_SECURITY.md](API_SECURITY.md) | Routes, schemas, headers, rate limits, error handling |
| [DATA_SECURITY.md](DATA_SECURITY.md) | What is classified how, what is encrypted, what may be deleted |
| [KEY_MANAGEMENT.md](KEY_MANAGEMENT.md) | The key hierarchy and how to rotate each one |
| [AI_SECURITY.md](AI_SECURITY.md) | Model integrity, the approval gate, inference-time checks |
| [SECURITY_TESTING.md](SECURITY_TESTING.md) | How any of the above is demonstrated rather than asserted |
| [DEPLOYMENT_SECURITY.md](DEPLOYMENT_SECURITY.md) | Container and supply-chain hardening, how to deploy |
| [INCIDENT_RESPONSE.md](INCIDENT_RESPONSE.md) | What to do when a control fires |
| [SECURITY.md](SECURITY.md) | The original design notes and the RBAC matrix |

Each document states its own limitations. Controls are **aligned with** HIPAA Security Rule
safeguards and the OWASP Top 10; nothing is certified and there has been no external
assessment.
