# Manish Rawal — AI Product Manager

I build AI-powered products and use data to make better decisions about what to build next.

Currently: **RoleRadar** — an AI job search advisor that replaces keyword alerts with an agent that reads job descriptions, evaluates fit against your profile, and gets smarter about your preferences over time.

---

## What I'm Building

### [RoleRadar](https://github.com/manishrawal95/RoleRadar) · [roleradar.co](https://roleradar.co)

Job searching is a high-stakes, time-consuming process where the tools haven't kept up with what AI can do. RoleRadar is my answer to that.

**The core idea:** instead of surfacing hundreds of listings and making the user do the filtering, an agentic LLM does the reading and evaluation. The user reviews a curated shortlist, provides feedback, and the system learns their preferences over time — building an advisor that compounds context across sessions.

Key product decisions worth reading about:
- Why a hard guardrails layer runs before the LLM (cost, accuracy, and user trust are all better)
- Why narrative memory instead of pure vector search (reasoning context is lost in embeddings)
- Why a feedback loop built on revealed preference instead of setup forms (people don't know what they want until they see it)
- Why Today Dashboard as the primary surface (job searching needs a daily habit, not sporadic sprints)

Full product case study → [github.com/manishrawal95/RoleRadar](https://github.com/manishrawal95/RoleRadar)

---

## How I Think About Product

**Data first.** Before building a feature, I want to understand the problem in the data. Is the pattern real? Is it concentrated in a segment? Is it causal or correlated? The analysis repos below are how I practice that muscle.

**Agentic systems require different PM thinking.** When the system makes autonomous decisions, the PM's job shifts: you're designing the decision boundaries, the fallback behavior, and the trust calibration — not just the UI. Getting that right requires understanding both the user's mental model and the model's failure modes.

**Feedback loops are a product design problem.** Collecting signal is easy. Closing the loop — making the product meaningfully better from that signal, in a way the user notices — is hard. That's where most AI products fall short.

---

## Data Analysis Work

These aren't course projects. They're practice in finding the non-obvious pattern in a dataset — the kind of analysis that drives a product decision.

| Project | What I was looking for |
|---|---|
| [Consumer Complaints Analysis](https://github.com/manishrawal95/Consumer-Complaints-Analysis) | Which complaint categories had the worst resolution rates — and whether they clustered by company or by product type |
| [Marketing Campaign Analysis](https://github.com/manishrawal95/Marketing-Campaign-Analysis) | Which audience segments drove disproportionate ROI, and whether the high-spend segments were worth it |
| [Netflix Analysis](https://github.com/manishrawal95/Netflix-Analysis) | Catalog gaps by genre and region — where is demand unmet by supply |
| [Bank Churn Analysis](https://github.com/manishrawal95/Bank-Churn-Analysis) | Behavioral signals that predict churn 30 days out — before the customer knows they're leaving |
| [UK Train Rides](https://github.com/manishrawal95/UK-Train-Rides) | Demand concentration across routes — which 20% of routes carry 80% of passengers |
| [USA Crime Data](https://github.com/manishrawal95/USA-Crime-Data) | Geographic correlation with socioeconomic indicators — does income predict crime rate after controlling for density |

---

## Background

Data analysis experience in Python and R. Product thinking built through building RoleRadar from scratch — which means I've made every mistake once: over-engineered features nobody used, shipped things without validating the hypothesis, and learned that the feedback loop is the product.

I'm interested in AI products where the core value proposition is judgment, not just retrieval — where the system has to make a call, not just surface options.

---

*Open to PM roles at AI-first companies. Best contact: [roleradar.co](https://roleradar.co)*
