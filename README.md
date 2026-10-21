# Kolapo Adedipe — Professional Profile & Portfolio

A personal portfolio showcasing software engineering, artificial intelligence, quantitative finance, teaching, and professional leadership. It includes a photograph, project summaries, career history, education, certifications, contact links, and an MSc Financial Engineering Capstone Review case study.

**Author:** Kolapo Adedipe  
**Portfolio:** https://kolapo-adedipe-portfolio.navylyric132.chatgpt.site  
**Contact:** adedipebabatundekolapo@gmail.com

> The hosted portfolio was deployed with private access. A link alone does not grant visitors access.

## Academic highlight

**Master of Science in Software Engineering — Completed**  
Quantic School of Business and Technology · 2025–2026  
**Overall average score: 89.4%**

Completion and the overall average were supplied by Kolapo Adedipe. The Financial Engineering entry is presented separately; the available records did not consistently establish its final award status.

## Features

- Professional profile and photograph.
- Fourteen project entries with category filters and expandable descriptions.
- A featured, two-part Financial Engineering capstone case study.
- Downloadable capstone reports.
- Professional experience, leadership, education, certifications, and research writing.
- Email, GitHub, and LinkedIn links.
- Responsive layout and a Print / Save as PDF control.
- A standalone HTML edition with an embedded photo and PDF reports.

## Project collection

| Area | Projects and studies |
| --- | --- |
| Software engineering | Parking Management System; Olanjay School Platform; Infrastructure & Architecture Studies |
| Artificial intelligence | Static Malware Detection; Praxa / PraxaApp; Kolrose Policy Assistant; Landmark Classification & Tagging; Kaggle LLM 20 Questions; Gemini API Integration; Student-RAG |
| Quantitative finance | Crude-Oil Risk & Regime Research; Yield-Curve Principal Components; Credit, Funding & Macro Research; FX, Mortgage & Investment Analytics |

The capstone is featured separately. Entries distinguish deployed applications, ongoing development, academic research, and prototypes. Project technologies describe the showcased work; the portfolio website itself uses HTML, CSS, and JavaScript.

## Featured Financial Engineering capstone

**WorldQuant University — MScFE 692 Capstone Review**

### Part I: Integrated Early-Warning Risk Management

Investigates equity co-movement, credit-spread widening, and funding pressure through rolling PCA absorption ratios, quantile regression, HAR-RV, GARCH/DCC dynamics, funding diagnostics, and historical VaR comparisons.

The recorded enhanced credit model and HAR-RV model underperformed their respective holdout baselines. The case study emphasizes validation and interpretation rather than claiming that added complexity guarantees better forecasts.

### Part II: The Regime-Aware Pairs Trader

Compares an always-on XLK–IYW pairs strategy with a regime-filtered version using SPY market signals. Formation covers 2014–2016; evaluation covers 2017–2021.

| Recorded measure | Always-on baseline | Regime-filtered |
| --- | ---: | ---: |
| Net cumulative return | −2.8340% | −2.4402% |
| Annualized Sharpe, risk-free rate = 0 | −0.3854 | −0.5710 |
| Maximum drawdown | −3.4069% | −2.9720% |
| Position entries | 18 | 22 |
| Time in position | 47.5774% | 21.1279% |

**Interpretation:** The filter reduced drawdown but worsened Sharpe. Both strategies lost money. The formation cointegration test failed, so the trading study is exploratory.

**Attribution and evidence:** This is group research. The reports do not identify Kolapo’s individual Student A/B/C allocation, so findings are credited to the group. Results come from saved execution outputs transcribed in the updated reports; they were not independently rerun for the portfolio. The reports retain draft verification notes. These academic results are not investment recommendations.

## Open the downloadable edition

1. Download `Kolapo_Adedipe_Profile_and_Portfolio.html`.
2. Open it in a modern web browser.
3. Use the project filters and expandable descriptions to explore the work.
4. Select either capstone report link to download its embedded PDF.

The photo, styling, scripts, and two PDF reports are embedded in the standalone file. Portfolio content works offline; external websites, repositories, LinkedIn, and email services require the relevant connection or application.

### Export the portfolio to PDF

Select **Print / Save portfolio as PDF**, then choose **Save as PDF** in the browser’s print dialog. The control reveals all projects and expands their descriptions before printing. Enable background graphics if you want to preserve more of the color styling. Pagination can vary by browser.

## Website source layout

The hosted source uses a separate asset folder:

```text
kolapo-portfolio/
├── build.py
├── .openai/
│   └── hosting.json
└── dist/
    ├── index.html
    └── assets/
        ├── kolapo.jpg
        ├── capstone-risk-analysis.pdf
        └── capstone-pairs-trader.pdf
```

`build.py` generates the hosted `dist/index.html`. The downloadable standalone HTML is a separate packaged edition; it does not require this source tree.

## Run locally from source

Prerequisites: Python 3 and a modern browser.

From the source project directory:

```bash
python3 build.py
python3 -m http.server 8000 --directory dist
```

On Windows, use `python` instead of `python3` if that is your installed command.

Open http://localhost:8000 in your browser. Stop the server with `Ctrl+C`. The static website requires no Node.js dependencies or frontend build framework.

## Customize

When working with source, edit `build.py` and regenerate the page so later builds preserve your changes.

- Update the professional summary, experience, education, and contact information.
- Add or revise entries in the project collection.
- Replace `dist/assets/kolapo.jpg` to update the photograph.
- Replace the capstone PDF assets and update their case-study text together.
- Adjust the CSS for colors, typography, spacing, and responsive layouts.
- Verify project links and distinguish completed work from work in progress.

For the standalone edition, edit the HTML directly with a text editor. Its embedded assets are long Base64 data URLs; source-based editing is easier for substantial asset changes. Regenerating the hosted page does not automatically refresh an already exported standalone file.

## Hosting

For a static host, publish the **contents of `dist/`**, preserving the `assets/` folder and using `index.html` as the entry page. No server-side application or database is required.

For a new deployment, use the host’s own configuration. The existing `.openai/hosting.json` identifies the original Site and should not be reused to register an unrelated project.

Review audience settings separately: deploying the current portfolio does not automatically make it public.

## Content maintenance

- The profile was assembled from available records in October 2026.
- The Software Engineering average is 89.4%; it must not be relabeled as the Financial Engineering average.
- Historical project metrics are reported results, not newly reproduced evaluations.
- Some employment dates and credentials reflect the source resume and should be reviewed when updating the portfolio.
- The research-writing entry has no verified publication venue or DOI in the available material.
- External deployments and repository links may change.

## Contact and profiles

- Email: adedipebabatundekolapo@gmail.com
- Project GitHub: https://github.com/kadedipe
- Additional GitHub: https://github.com/Kolapo-code
- LinkedIn: https://www.linkedin.com/in/adedipe-kolapo-phd-ocp-cc-220177b2/

## Rights

No open-source license has been specified for this portfolio. Do not assume permission to reuse the photograph, personal content, group reports, or linked project code. Consult the applicable project licenses and obtain any necessary permissions for group materials.
