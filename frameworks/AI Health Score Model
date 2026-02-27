# AI-Augmented Customer Health Score Model

> Moving from static, CSM-input health scores to dynamic, multi-signal, AI-weighted scoring.

## Why Traditional Health Scores Fail

Most CS health scores suffer from three problems:

1. **Subjectivity** — Heavily dependent on CSM judgment, which varies by experience and optimism bias
2. **Latency** — Updated monthly or quarterly, often after the damage is done
3. **Narrow inputs** — Typically 3-5 manually tracked dimensions that miss critical signals

The result: health scores become a reporting exercise rather than a decision-making tool. CSMs update them for leadership reviews, not because they drive action.

---

## The AI-Augmented Model

### Signal Categories

#### 1. Product Engagement (Weight: 30%)

| Signal | Data Source | What It Tells You |
|--------|-----------|-------------------|
| Login frequency trend (30/60/90 day) | Product analytics | Habitual usage vs. decline |
| Feature breadth (% of purchased features used) | Product analytics | Value realisation depth |
| Power user ratio (daily active / total licensed) | Product analytics | Organic adoption spread |
| API call volume & pattern | Product analytics | Integration depth & dependency |
| Time-in-product per session | Product analytics | Engaged usage vs. drive-by logins |

**AI layer:** Detect anomalies against the customer's own baseline, not generic benchmarks. A 20% usage drop for a customer who was previously stable is a stronger signal than a customer who's always had low usage.

#### 2. Engagement Quality (Weight: 25%)

| Signal | Data Source | What It Tells You |
|--------|-----------|-------------------|
| Meeting attendance rate | Calendar/CRM | Executive sponsorship & prioritisation |
| Response time to CSM outreach | Email/Slack | Engagement level & urgency |
| Champion activity level | CRM + product | Internal advocacy strength |
| Multi-threading depth | CRM contacts | Single point of failure risk |
| QBR/EBR participation seniority | Meeting notes | Strategic importance to customer |

**AI layer:** Track champion engagement patterns over time. A champion who stops attending meetings or reduces product usage may be disengaging or preparing to leave — both critical early warning signals.

#### 3. Support & Sentiment (Weight: 20%)

| Signal | Data Source | What It Tells You |
|--------|-----------|-------------------|
| Ticket volume trend | Support platform | Frustration or complexity issues |
| Ticket severity distribution | Support platform | Severity of product friction |
| Resolution satisfaction scores | Support platform | Support experience quality |
| NPS / CSAT verbatim sentiment | Survey tools | Qualitative satisfaction depth |
| Escalation frequency | Support platform | Relationship stress level |

**AI layer:** Sentiment analysis on support tickets and survey responses. A customer can give a neutral NPS score but express frustration in verbatims that signals deeper dissatisfaction. AI catches what numbers miss.

#### 4. Business Context (Weight: 15%)

| Signal | Data Source | What It Tells You |
|--------|-----------|-------------------|
| Renewal date proximity | CRM | Urgency of intervention window |
| Contract value trend | CRM | Growth trajectory or downsell risk |
| Industry/market conditions | External data | Macro factors affecting budget decisions |
| Organisational changes | LinkedIn/news | M&A, leadership changes, restructuring |
| Competitive mentions | Gong/call transcripts | Vendor evaluation activity |

**AI layer:** Monitor news and LinkedIn for organisational changes at customer accounts. A new CTO, a round of layoffs, or an acquisition can fundamentally shift account dynamics before any product signals appear.

#### 5. Predictive Indicators (Weight: 10%)

| Signal | Data Source | What It Tells You |
|--------|-----------|-------------------|
| Similarity to churned accounts | ML model | Pattern match against historical churn profiles |
| Expansion propensity score | ML model | Likelihood of upsell based on usage trajectory |
| Engagement trajectory forecast | ML model | Projected health 90 days out |

**AI layer:** Train on historical data — what did accounts look like 6 months before they churned? Before they expanded? Use those patterns to score current accounts predictively.

---

## Scoring Framework

### Score Calculation

Each signal category produces a normalised score (0-100). The weighted composite becomes the overall health score.

```
Health Score = (Product × 0.30) + (Engagement × 0.25) + (Support × 0.20) 
             + (Business × 0.15) + (Predictive × 0.10)
```

### Score Bands

| Score | Band | Action |
|-------|------|--------|
| 80-100 | 🟢 Healthy | Expansion focus, advocacy development |
| 60-79 | 🟡 Monitor | Proactive engagement, address emerging risks |
| 40-59 | 🟠 At Risk | Intervention plan, executive sponsor engagement |
| 0-39 | 🔴 Critical | Immediate save plan, leadership escalation |

### Dynamic Weighting

Not all signals matter equally for every customer. The AI layer should adjust weights based on:

- **Lifecycle stage:** Onboarding customers weight product engagement higher; mature customers weight business context higher
- **Segment:** Enterprise accounts weight engagement quality (multi-threading) higher; scale accounts weight product telemetry higher
- **Industry:** Regulated industries weight support sentiment higher; tech companies weight feature adoption higher

---

## Implementation Priorities

### Quick Wins (Week 1-4)
- Connect product analytics to health score model (replace manual CSM inputs)
- Implement automated support sentiment scoring
- Set up weekly automated health score reports for CSM team

### Medium Term (Month 2-3)
- Add engagement quality signals from CRM and calendar data
- Build champion tracking dashboard
- Create automated alert triggers for score band changes

### Advanced (Month 4-6)
- Train predictive model on historical churn/expansion data
- Implement dynamic signal weighting by segment and lifecycle
- Build business context monitoring (news, LinkedIn, org changes)

---

## The Human Layer

AI-augmented health scores are a decision support tool, not a decision-making tool. The CSM's role shifts from *calculating* health to *interpreting and acting on* health insights.

A CSM who sees a health score drop should be asking:
- Does this match my qualitative sense of the account?
- What context do I have that the model doesn't?
- What's the right intervention, and who should deliver it?

The score tells you *where* to look. The CSM decides *what to do*.
