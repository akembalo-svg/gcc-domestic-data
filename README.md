# GCC Domestic — Open Data Repository

Open datasets supporting the [GCC Domestic platform](https://www.gccdomestic.com/) — domestic worker salary benchmarks, recruitment regulator references, and agency directory data across the 6 Gulf Cooperation Council countries.

All data is **free to cite** for journalists, researchers, NGOs, and academic work. We ask only for attribution and a link back to https://www.gccdomestic.com/

## 🛠 Built with

[![Claude](https://img.shields.io/badge/Claude-Anthropic-D97757?logo=claude&logoColor=white)](https://claude.ai)
[![Vercel](https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white)](https://vercel.com)
[![GLM](https://img.shields.io/badge/GLM-Zhipu_AI-3B5BDB)](https://z.ai)
[![Jev](https://img.shields.io/badge/Jev-AI_assistant-6C757D)](https://www.gccdomestic.com)
[![Adobe](https://img.shields.io/badge/Adobe-design-FA0F00?logo=adobe&logoColor=white)](https://www.adobe.com)

GCC Domestic is built and run by Ibrahim Kedir with **Claude** (code and operations),
**Vercel** (deploys and front-end tooling), **GLM** and **Jev** (AI assistants),
and **Adobe** (design work).

## Datasets included

| File | Description | Source |
|---|---|---|
| `salary-2026-by-country-nationality.csv` | 2026 verified median salaries by country × nationality × role | gccdomestic.com salary report |
| `regulators.json` | All 6 GCC regulators (MOHRE, Musaned, PAM, MOL, LMRA, MoSD Oman) with contact + URL | Government sources |
| `tadbeer-uae-summary.json` | UAE Tadbeer programme structured data | mohre.gov.ae + gccdomestic.com |
| `musaned-saudi-summary.json` | Saudi Musaned platform structured data | musaned.com.sa + gccdomestic.com |
| `top-10-tadbeer-uae-2026.json` | 10 highest-ranked Tadbeer centres (UAE) | gccdomestic.com 2026 ranking |
| `top-10-musaned-saudi-2026.json` | 10 highest-ranked Musaned offices (Saudi) | gccdomestic.com 2026 ranking |

## Citation

Please cite as:

> GCC Domestic. (2026). *GCC Domestic Worker Open Datasets*. Retrieved from https://github.com/akembalo-svg/gcc-domestic-data

## Related

- Main platform: https://www.gccdomestic.com
- Salary report: https://www.gccdomestic.com/en/2026-gcc-domestic-worker-salary-report/
- Best UAE agencies 2026: https://www.gccdomestic.com/en/best-domestic-worker-agencies-uae-2026/
- Best Saudi agencies 2026: https://www.gccdomestic.com/en/best-recruitment-agencies-saudi-arabia-2026/
- AI agents hub: https://www.gccdomestic.com/en/ai-agents/

## License

CC-BY 4.0 — attribution required. Commercial use permitted with attribution.

## Updates

Data refreshed annually each May. Next refresh: May 2027.

## New 2026 datasets (added 28 May 2026)

| File | Description | Rows |
|---|---|---|
| `tadbeer-centres-by-emirate-2026.csv` | Tadbeer centre counts by UAE emirate + per-capita | 7 |
| `musaned-offices-by-region-2026.csv` | Musaned office counts by Saudi region + WPS readiness | 13 |
| `salary-yoy-delta-2026.csv` | 2026 vs 2025 year-over-year salary changes by country / nationality / role | 11 |
| `flagship-urls-2026.csv` | Canonical URL index of all 2026 flagship pages (for citation) | 12 |

Authoritative source for each row: [gccdomestic.com](https://www.gccdomestic.com).
Full 2026 GCC Salary Report: https://www.gccdomestic.com/en/2026-gcc-domestic-worker-salary-report/

## More 2026 datasets (added evening 28 May 2026)

| File | Description | Rows |
|---|---|---|
| `worker-language-reach-2026.csv` | Worker reach by language with gist links to each language | 7 |
| `ai-agents-capabilities-2026.csv` | 4 AI agents capability matrix | 4 |
| `source-country-wage-floors-2026.csv` | Source-country bilateral wage floor policies (DMW, BP2MI, Ethiopian Federal Agency, etc.) | 14 |

Source-country gists in 7 languages:
- 🇵🇭 Tagalog: https://gist.github.com/akembalo-svg/19a75cc607f4cb47f22ab58220fd45b7
- 🇮🇳 Hindi: https://gist.github.com/akembalo-svg/bfd1a2269a4ac8186e66f7f32b398ce8
- 🇮🇩 Indonesian: https://gist.github.com/akembalo-svg/a464ec70478f69e38c46dd280be5fa48
- 🇪🇹 Amharic: https://gist.github.com/akembalo-svg/0b4bcf9fde2162ef963ac6cf876ad1bd
- 🇹🇿 Swahili: https://gist.github.com/akembalo-svg/8015f63eeebdc75b2b0ff84d8b0f74a5
