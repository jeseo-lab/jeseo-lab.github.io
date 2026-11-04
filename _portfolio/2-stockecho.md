---
title: "StockEcho"
excerpt: "An investment decision-support service that organizes news and disclosures about a user's holdings into events, and links them to past price reactions and portfolio weights. 2026 · My role: planning, back-end/data, and front-end."
collection: portfolio
---

**Period:** 2026  
**Code:** [github.com/kimminjunnn/StockEcho](https://github.com/kimminjunnn/StockEcho)

Overview
------
StockEcho organizes news and corporate disclosures about the stocks a user holds into events. It then shows how prices reacted to similar past events and how those reactions would affect the user's portfolio weights. It is an educational analysis tool: it explains historical scenarios with sources and does not predict future returns.

My role
------
* **Planning:** Defined user questions and the core flow; designed requirements for Risk Replay, portfolio-impact views, and evidence display.
* **Back-end and data:** Connected KIS price data (current and daily), NAVER News, and OpenDART disclosures. Designed relevance classification, de-duplication, trading-day return calculation, and caching, fallback, and security policies.
* **Front-end:** Helped implement stock selection and weight validation; analysis-result, news, disclosure, and price-reaction screens; and loading, error, and stale-data states.

Design principles
------
* Calculation and explanation are separated: numbers come from the analysis engine, and the LLM only writes evidence-based explanations.
* Every key claim links to its source (title, publication date, original link).
* Sample size, similarity, data timestamp, and limitations are shown with each result.
