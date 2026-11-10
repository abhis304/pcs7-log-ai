# pcs7-log-ai

Open-source toolkit for turning Siemens PCS 7 / Process Historian operator logs into AI-generated shift summaries and alerts for process plants.

## Why

Plant operators and engineers spend hours reviewing DCS alarm and operator logs by hand. Open-source tooling that connects industrial historians to LLMs is very limited, and vendor add-ons are expensive. This project aims to fill that gap.

## Planned features

- Parser for PCS 7 / Process Historian operator-log and alarm exports (CSV/SQL)
- Normalization into a clean, vendor-neutral event schema
- LLM-powered shift summaries (what changed, abnormal events, operator actions)
- Configurable alert rules with email notifications
- Plug-in SOP context so summaries reference your own procedures
- Report templates for daily process and fermentation pulse reports
- Sample (synthetic) datasets and example pipelines

## Status

Early stage. Core components are being extracted from internal tools and generalized, with all proprietary data and procedures removed.

## Roadmap

1. Log parser + event schema
2. Summary generation with pluggable LLM backends
3. Alerting + email
4. Reporting templates
5. Docs, tests, and PyPI release

## Contributing

Issues and PRs welcome, especially from engineers working with other DCS/historian platforms.

## License

MIT
