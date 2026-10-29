<picture>
  <source media="(prefers-color-scheme: dark)" srcset="../assets/oscylo-mark-inverse.svg">
  <img src="../assets/oscylo-mark.svg" alt="Oscylo" width="56">
</picture>

# Oscylo forecast of Reddit, Q3 2026

Oscylo (oscylo.com). Numbers only; the write-up is published separately.

- Frozen: 2026-10-29 02:45 UTC (2026-10-28 21:45 CDT)
- Reddit reports Q3 2026: 2026-10-29, after the US market close
- Data cutoff: 2026-10-26 (quarter end + 26 days)
- Model last changed: 2026-10-27 21:12 UTC
- Units: users are quarterly averages in millions (DAUq, WAUq) as Reddit reports them. Revenue is US$ millions.

## 1. Pulse forecast (headline)

| Q3 2026                  |  Point |     Model spread |       80% interval | Q2 2026 actual |
|--------------------------|-------:|-----------------:|-------------------:|---------------:|
| DAUq, total (M)          | 134.54 | 134.46 to 134.62 |   129.89 to 139.19 |         130.30 |
| DAUq, US (M)             |  53.41 |   53.33 to 53.49 |     51.56 to 55.26 |          53.20 |
| DAUq, international (M)  |  81.13 |   81.13 to 81.13 |     78.33 to 83.93 |          77.10 |
| WAUq, total (M)          | 534.30 | 533.81 to 534.80 |   522.31 to 546.30 |         514.60 |
| WAUq, US (M)             | 198.19 | 197.70 to 198.68 |   190.56 to 205.82 |         197.20 |
| WAUq, international (M)  | 336.11 | 336.11 to 336.11 |   323.14 to 349.08 |         317.40 |
| Revenue, $M              | 959.45 | 952.86 to 966.69 | 895.55 to 1,023.36 |         804.90 |
| ARPU, $ (revenue / DAUq) |   7.13 |     7.08 to 7.19 |            not set |           6.18 |

### Predictions for the logged-in / logged-out split no longer reported

| Q3 2026               | Point |   Model spread |   80% interval | Q2 2026 actual |
|-----------------------|------:|---------------:|---------------:|---------------:|
| DAUq, logged-in       | 53.57 | 53.49 to 53.65 | 51.76 to 55.37 |          52.60 |
| DAUq, logged-out      | 80.97 | 80.97 to 80.97 | 78.12 to 83.83 |          77.70 |
| DAUq, US logged-in    | 23.22 | 23.14 to 23.30 | 22.38 to 24.06 |          23.10 |
| DAUq, US logged-out   | 30.19 | 30.19 to 30.19 | 29.18 to 31.20 |          30.10 |
| DAUq, intl logged-in  | 30.35 | 30.35 to 30.35 | 29.39 to 31.31 |          29.50 |
| DAUq, intl logged-out | 50.78 | 50.78 to 50.78 | 48.55 to 53.02 |          47.60 |

## 2. Track record of the models

Backtest: each past quarter forecast again using only data visible 26 days after that quarter ended. Miss = forecast / actual - 1.

| Metric                | Pulse average miss | Pulse worst miss | Quarters tested | Pulse 80% half-width | Metronome average miss |
|-----------------------|-------------------:|-----------------:|----------------:|---------------------:|-----------------------:|
| DAUq, total           |              1.37% | -4.87% (Q1 2024) |              10 |                3.46% |                  2.15% |
| DAUq, US              |              1.55% | -4.06% (Q1 2024) |              10 |                3.46% |                  2.79% |
| DAUq, international   |              1.89% | -5.68% (Q1 2024) |              10 |                3.45% |                  2.02% |
| WAUq, total           |              1.51% | -5.26% (Q1 2024) |              10 |                2.25% |                  2.61% |
| WAUq, US              |              1.81% | +4.32% (Q4 2024) |              10 |                3.85% |                  3.58% |
| WAUq, international   |              2.37% | -6.64% (Q1 2024) |              10 |                3.86% |                  2.51% |
| Revenue               |              3.11% | -6.66% (Q2 2025) |               6 |                6.66% |                  3.16% |
| DAUq, logged-in       |              1.34% | -3.68% (Q1 2024) |              10 |                3.37% |                  1.42% |
| DAUq, logged-out      |              1.95% | -5.96% (Q1 2024) |              10 |                3.53% |                  3.43% |
| DAUq, US logged-in    |              1.59% | -3.65% (Q1 2024) |              10 |                3.60% |                  1.83% |
| DAUq, US logged-out   |              1.86% | -4.42% (Q1 2024) |              10 |                3.34% |                  4.27% |
| DAUq, intl logged-in  |              1.54% | -3.71% (Q1 2024) |              10 |                3.16% |                  1.46% |
| DAUq, intl logged-out |              2.87% | -7.59% (Q1 2024) |              10 |                4.40% |                  3.20% |

### Pulse misses by quarter, %

| Metric              | Q1 2024 | Q2 2024 | Q3 2024 | Q4 2024 | Q1 2025 | Q2 2025 | Q3 2025 | Q4 2025 | Q1 2026 | Q2 2026 |
|---------------------|--------:|--------:|--------:|--------:|--------:|--------:|--------:|--------:|--------:|--------:|
| DAUq, total         |   -4.87 |   -0.92 |   +0.53 |   -0.05 |   -1.06 |   +3.46 |   -1.14 |   -0.81 |   +0.10 |   +0.79 |
| DAUq, US            |   -4.06 |   +0.68 |   -0.47 |   +2.36 |   -2.02 |   +3.46 |   -0.19 |   -0.89 |   +0.35 |   +1.03 |
| DAUq, international |   -5.68 |   -2.51 |   +1.51 |   -2.21 |   -0.23 |   +3.45 |   -1.90 |   -0.74 |   -0.09 |   +0.62 |
| WAUq, total         |   -5.26 |   -1.28 |   +0.71 |   +0.51 |   -0.33 |   +2.08 |   -2.25 |   -1.64 |   +0.72 |   -0.32 |
| WAUq, US            |   -3.85 |   +1.41 |   -0.87 |   +4.32 |   -1.55 |   +2.35 |   -1.02 |   -1.61 |   +0.95 |   -0.12 |
| WAUq, international |   -6.64 |   -3.86 |   +2.22 |   -2.65 |   +0.64 |   +1.88 |   -3.14 |   -1.66 |   +0.56 |   -0.44 |
| Revenue             |         |         |         |         |   +4.96 |   -6.66 |   +4.74 |   +1.38 |   +0.32 |   -0.58 |

## 3. Metronome - also frozen

Frozen 2026-10-26 00:19:59 UTC as the original headline; Pulse replaced it before the report. Local manifest SHA-256 58e6e21d6f4a49486fe540a215dcded491d2e81e24a6d5a07f8246e312d2aed9. This file is its first public timestamp. Values are as recorded in that manifest.

| Q3 2026                 |    Point |           80% interval |
|-------------------------|---------:|-----------------------:|
| DAUq, total (M)         |  135.275 |   130.3125 to 140.2375 |
| DAUq, US (M)            |   53.925 |     50.6765 to 57.1735 |
| DAUq, international (M) |    81.35 |     77.5673 to 85.1327 |
| WAUq, total (M)         |   539.15 |   514.1749 to 564.1251 |
| WAUq, US (M)            |   201.25 |     188.525 to 213.975 |
| WAUq, international (M) |    337.9 |   316.8779 to 358.9221 |
| Revenue, $M             | 966.6932 | 906.5858 to 1,026.8005 |
| ARPU, $                 |   7.1461 |       6.3451 to 7.9472 |
| ARPU, US, $             |  14.1556 |       12.6312 to 15.68 |
| ARPU, international, $  |   2.4997 |       2.2947 to 2.7048 |

## 4. Consensus at freeze, for comparison only

Zacks (via Yahoo Finance, 2026-10-26): DAUq 133.36, US 53.37, international 80.13; WAUq 531.10, US 197.49, international 333.62; revenue $886.35M; ARPU $6.67. Also seen: revenue $875.0M, the mean of 26 analysts (Equibles, 2026-10-20). US DAUq 53.6 Bloomberg consensus (posted on r/redditstock), from a posted chart of broker estimates; not publicly verifiable.

## 5. Scoring

- Actuals: Reddit's Q3 2026 press release and shareholder letter as first published.
- Pulse, Metronome and Challenger1 are all scored. Results, misses included, will be published after the report.

## 6. Sealed model fingerprint

bafad414f41e0e2869a6459d4eafd16b828304b24938b0d5a549c404c9acb37f

SHA-256 of a private list of file hashes covering the code and tables behind every number above. The files are not published.

## Disclosure

This is an independent forecast built from public data. It is not investment advice, and Oscylo is not affiliated with Reddit. The author of this analysis holds long positions in RDDT, which may include shares, long-dated call options and leveraged ETFs.
