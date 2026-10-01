# Kai Ye

Investment banking analyst in London · BEng Computer Science, Imperial College London (2024) · I build AI tools for investing

<!-- SUMMARY:START -->
**Paper long/short portfolio start date:** 13 May 2026 (TradingView, US$100k)  
**Since inception:** +26.2% vs SPY +3.8%, QQQ +4.8%, IWM −1.2% (as of 30 Sep 2026)
<!-- SUMMARY:END -->

*The portfolio section updates automatically every time I add a TradingView export.*

[Notes](#notes--1-oct-2026) · [AI projects](#ai-projects) · [Paper portfolio](#paper-portfolio) · [Ideas and pitches](#ideas-and-pitches)

## Notes – 1 Oct 2026

I graduated from Imperial College London in 2024 with a BEng in Computer Science. My thesis was on centrality-preserved graph sparsification for graph neural networks, applied to social link prediction. At Imperial I was sector head for Industrials and TMT at QT Capital, where I led a team of student analysts pitching stocks to 500+ members, and Vice President of the Investment Society, where I headed Algothon, London's largest algorithmic trading hackathon with 600+ participants.

I first worked in investment banking as a summer intern in 2023. In June 2024 I joined the Infrastructure & Power team at a bulge-bracket bank in London, first off-cycle and then full-time from January 2025. In July 2025 I moved to the TMT team, where I work on large M&A processes in digital infrastructure. I was also an early contributor to the bank's AI lab, where I built a news-monitoring agent for deal teams and LLM-based M&A target mapping.

Outside work I build AI tools for investing, mostly pipelines that turn primary filings into structured, auditable data. In May 2026 I started a long/short paper portfolio on TradingView, mostly in AI infrastructure, semis, power and software. The track record below is paper trading, not real money, and it updates automatically from my TradingView exports.

## AI projects

- **NeoCloud CapEx Tracker** (2026): an always-on pipeline that pulls hyperscaler and neocloud filings from SEC EDGAR and HKEXnews, extracts AI capex and cloud revenue with LLMs, and cites every number back to the exact filing line. A human-in-the-loop review loop turns reviewer notes into rules for future extractions.
  [Live dashboard on AWS](https://d1pdb32k3hz8st.cloudfront.net/) · [Latest workbook](https://d1pdb32k3hz8st.cloudfront.net/download/latest.xlsx) · [Code](https://github.com/KKKKKKAI/neocloud-capex-tracker)
- **Portfolio tracker** (2026): a plain-Python pipeline (no AI) that turns my TradingView paper-trading exports into the risk report below.

## Paper portfolio

<!-- PORTFOLIO:START -->
| Time-weighted return | Ending balance | Max drawdown | Sharpe ratio | Beta vs SPY |
|---:|---:|---:|---:|---:|
| **+26.2%** | **$126,183** | −9.8% | 1.83 | 1.71 |

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="portfolio/charts/vami-dark.svg">
  <img alt="Growth of 1,000: portfolio vs benchmarks" src="portfolio/charts/vami-light.svg" width="100%">
</picture>

**Risk measures** · 12 May 2026 – 30 Sep 2026 · daily, time-weighted · benchmarks include dividends · risk-free rate is the 13-week T-bill

|  | Portfolio | SPY | QQQ | IWM |
|---|---:|---:|---:|---:|
| Ending VAMI | 1,262 | 1,038 | 1,048 | 988 |
| Total return | +26.2% | +3.8% | +4.8% | −1.2% |
| Max drawdown | −9.8% | −4.5% | −11.2% | −8.7% |
| Peak to valley | 10 Jul – 29 Jul | 2 Jun – 10 Jun | 2 Jun – 29 Jul | 14 Aug – 30 Sep |
| Recovery | 3 trading days | 36 trading days | 38 trading days | Ongoing |
| Sharpe ratio | 1.83 | 0.54 | 0.49 | −0.33 |
| Sortino ratio | 3.11 | 0.81 | 0.73 | −0.48 |
| Standard deviation (daily) | 2.15% | 0.79% | 1.42% | 1.03% |
| Downside deviation (daily) | 1.26% | 0.53% | 0.96% | 0.72% |
| Mean return (daily) | +0.26% | +0.04% | +0.06% | −0.01% |
| Positive days | 52 (54%) | 47 (48%) | 49 (51%) | 47 (48%) |
| Negative days | 45 (46%) | 50 (52%) | 48 (49%) | 50 (52%) |

| Portfolio vs. | SPY | QQQ | IWM |
|---|---:|---:|---:|
| Correlation | 0.63 | 0.72 | 0.47 |
| Beta | 1.71 | 1.09 | 0.99 |

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="portfolio/charts/distribution-dark.svg">
  <img alt="Distribution of daily returns: portfolio vs benchmarks" src="portfolio/charts/distribution-light.svg" width="100%">
</picture>

<details><summary>Table view: daily returns by band</summary>

| Daily return | Portfolio | SPY | QQQ | IWM |
|---|---:|---:|---:|---:|
| −8 to −6% | 1 | 0 | 0 | 0 |
| −6 to −4% | 1 | 0 | 1 | 0 |
| −4 to −2% | 8 | 1 | 2 | 2 |
| −2 to 0% | 35 | 49 | 45 | 48 |
| 0 to 2% | 37 | 47 | 42 | 45 |
| 2 to 4% | 12 | 0 | 7 | 2 |
| 4 to 6% | 1 | 0 | 0 | 0 |
| 6 to 8% | 1 | 0 | 0 | 0 |
| 8 to 10% | 1 | 0 | 0 | 0 |

</details>

**Monthly returns**

| Month | Portfolio | SPY | QQQ | IWM | Ending balance |
|---|---:|---:|---:|---:|---:|
| May 2026 (from 13 May) | +8.6% | +2.5% | +4.4% | +2.8% | $108,599 |
| Jun 2026 | +5.2% | −1.0% | −0.1% | +3.7% | $114,289 |
| Jul 2026 | −0.3% | 0.0% | −6.6% | −3.1% | $113,998 |
| Aug 2026 | +4.0% | +2.7% | +4.2% | +0.9% | $118,564 |
| Sep 2026 | +6.4% | −0.3% | +3.3% | −5.2% | $126,183 |

**Trading statistics** · closed trades

| Trades | Win rate | Profit factor | Average win | Average loss | Expectancy | Average hold |
|---:|---:|---:|---:|---:|---:|---:|
| 77 | 65% | 4.53 | +8.2% (+$775) | −4.0% (−$317) | +$392 | 11.9 days |

Best trade: **IG:NASDAQ** long, +$6,748 (+1.3%). Worst trade: **GLW** long, −$1,511 (−29.4%).

**Open positions** · 30 Sep 2026 close

| Position | Side | Quantity | Average cost | Close | Unrealized | Return | Weight |
|---|---|---:|---:|---:|---:|---:|---:|
| GOOG | Long | 68 | 347.17 | 340.74 | −$437 | −1.9% | 18.4% |
| INTC | Long | 123.96 | 101.98 | 120.23 | +$2,262 | +17.9% | 11.8% |
| NOW | Long | 80.52 | 134.20 | 134.01 | −$15 | −0.1% | 8.6% |
| MSFT | Long | 20 | 494.45 | 512.90 | +$369 | +3.7% | 8.1% |
| CEG | Long | 23.91 | 257.33 | 254.02 | −$79 | −1.3% | 4.8% |
| AVGO | Long | 17 | 349.59 | 351.19 | +$27 | +0.5% | 4.7% |
| LSE:RR. | Long | 300 | 1,442.60 GBX | 1,461.60 GBX | +$75 | +1.3% | 4.6% |
| GEV | Long | 6 | 909.93 | 950.49 | +$243 | +4.5% | 4.5% |
| AMZN | Long | 20 | 256.77 | 249.15 | −$152 | −3.0% | 3.9% |
| CRM | Long | 20.72 | 244.09 | 229.57 | −$301 | −5.9% | 3.8% |

<sub>Built by a plain-Python pipeline (no AI) from my TradingView paper-trading exports. Positions are marked at daily closes from Yahoo Finance and converted to USD. From 12 Aug 2026 the NAV is replayed fill by fill and ties to TradingView's balance history. Before that, TradingView only exports merged trades, so the daily path is estimated: each closed trade is replayed at its average entry and exit prices, and positions still open on 12 Aug 2026 are held at that day's size. The return since inception is exact either way.</sub>
<!-- PORTFOLIO:END -->

## Ideas and pitches

- PH long (Oct 2022, QT Capital): pitched at ~$260 with a $340 NTM target price; traded at ~$390 by Oct 2023
- IFX long (Jul 2022, QT Capital): pitched at ~€24 with a €30 NTM target price; traded at ~€35 by Jul 2023
