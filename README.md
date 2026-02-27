# AI-First Customer Success: Frameworks & Playbooks

> Practical frameworks for integrating AI into enterprise Customer Success operations — built from 10+ years of scaling CS teams across EMEA at Salesforce/Tableau.

## Why This Exists

Customer Success is being fundamentally reshaped by AI. But most CS teams are still bolting AI onto legacy workflows rather than rethinking the operating model from first principles.

This repo captures frameworks, prompt templates, and operational blueprints I've developed while:
- Leading a **Global AI Enablement programme** at Salesforce, upskilling 40+ CSMs on LLM integration and responsible AI deployment
- Building CS organisations from scratch across 7 countries (3 → 40+ team members)
- Managing $54.5M enterprise portfolios with **113% renewal target achievement**
- Completing **Y Combinator Startup School** and **Anthropic Academy** AI Fluency programmes

---

## 📂 Repository Structure

```
├── frameworks/
│   ├── ai-health-score-model.md        # AI-augmented customer health scoring
│   ├── adoption-signal-detection.md     # Using AI to identify adoption patterns & risks
│   └── ai-first-cs-operating-model.md   # Rethinking CS ops with AI at the core
│
├── prompts/
│   ├── account-research.md              # Pre-meeting account intelligence prompts
│   ├── qbr-preparation.md              # Automated QBR narrative generation
│   ├── risk-signal-analysis.md          # Churn risk identification from usage data
│   ├── executive-briefing.md            # C-suite meeting prep & talking points
│   └── renewal-strategy.md             # Renewal scenario planning & objection handling
│
├── playbooks/
│   ├── onboarding-acceleration.md       # AI-assisted onboarding for faster time-to-value
│   ├── expansion-identification.md      # Cross-sell/upsell signal detection
│   └── scale-cs-automation.md           # Scaling CS coverage with AI-driven workflows
│
└── resources/
    └── reading-list.md                  # Curated resources on AI + Customer Success
```

---

## 🧠 Frameworks

### AI-First CS Operating Model

Traditional CS relies on CSM intuition + lagging indicators. An AI-first model flips this:

| Dimension | Traditional CS | AI-First CS |
|-----------|---------------|-------------|
| **Health Scoring** | Manual input, quarterly refresh | Real-time, multi-signal, auto-weighted |
| **Risk Detection** | CSM gut feel + renewal date proximity | Predictive signals from usage, sentiment, support patterns |
| **QBR Prep** | 3-5 hours manual research | 30 min review of AI-generated narrative + data pack |
| **Expansion Signals** | Anecdotal, sales-driven | Usage pattern analysis, feature adoption velocity |
| **Onboarding** | Generic playbook, CSM-paced | Personalised journey based on use case + persona |
| **Scale Accounts** | Minimal touch, reactive | AI-driven proactive engagement, automated health monitoring |

### Customer Health Score — AI-Augmented Model

A modern health score should combine:

1. **Product telemetry** — usage frequency, feature breadth, API call patterns
2. **Engagement signals** — meeting attendance, response times, champion activity
3. **Sentiment analysis** — support ticket tone, NPS verbatims, meeting transcript analysis
4. **Business context** — renewal timeline, expansion potential, org changes
5. **Predictive layer** — ML model trained on historical churn/expansion data

The AI layer doesn't replace CSM judgment — it surfaces signals humans would miss and frees CSMs to focus on strategy and relationships.

---

## 💬 Sample Prompts

### Account Research — Pre-Meeting Intelligence

```
You are a Customer Success strategist preparing for a Quarterly Business Review.

Given the following inputs:
- Company: [name]
- Industry: [sector]
- Product usage data: [summary]
- Last QBR notes: [paste]
- Open support tickets: [list]
- Renewal date: [date]

Generate:
1. Three key talking points tailored to their industry challenges
2. Adoption gaps based on usage vs. available features
3. Two expansion opportunities with business case framing
4. Risk factors with recommended mitigation actions
5. A one-paragraph executive summary suitable for a VP-level sponsor
```

### Churn Risk Signal Analysis

```
Analyse the following customer engagement data and identify churn risk signals:

- Product login frequency: [trend over 90 days]
- Feature usage breadth: [% of purchased features actively used]
- Support ticket volume and sentiment: [summary]
- Key contact changes: [any champion departures]
- Meeting attendance pattern: [last 3 scheduled meetings]

Classify risk as LOW / MEDIUM / HIGH and provide:
1. The top 3 contributing risk factors
2. A recommended intervention plan with timeline
3. Suggested talking points for a retention-focused conversation
```

### Renewal Strategy Scenario Planning

```
A customer's renewal is in [X] weeks. Based on:
- Current health score: [score]
- Usage trends: [summary]
- Outstanding issues: [list]
- Expansion conversations: [status]
- Competitive threats: [if known]

Generate three renewal scenarios:
1. BEST CASE — full renewal + expansion. What needs to happen?
2. BASE CASE — flat renewal. What are the risks to manage?
3. WORST CASE — downsell or churn risk. What's the save strategy?

For each scenario, provide a specific action plan with owners and deadlines.
```

---

## 📖 Playbooks

### Onboarding Acceleration

The goal: reduce **time-to-first-value** by 40% using AI-assisted personalisation.

**Key principles:**
- Map the customer's use case to a tailored onboarding path (not one-size-fits-all)
- Use AI to generate personalised configuration guides based on their tech stack
- Automate check-in cadence with intelligent triggers (not fixed schedules)
- Surface "stuck" signals early: incomplete setup steps, low initial engagement, support spikes

### Expansion Signal Detection

AI can identify expansion opportunities that CSMs would miss in manual reviews:

- **Usage ceiling approaching** — customer nearing plan limits → upgrade conversation
- **New use case emergence** — features being used in unexpected ways → cross-sell adjacent products
- **Team growth signals** — new user invitations, new department onboarding → seat expansion
- **API usage patterns** — increasing integration depth → platform stickiness + premium tier potential

---

## About Me

**David Le Maistre Zelee** — Customer Success leader with 10+ years building and scaling enterprise CS organisations across EMEA.

- 🏗️ Founding member of Salesforce/Tableau's EMEA CS function (3 → 40+ CSMs, 7 countries)
- 📊 Managed $54.5M enterprise portfolios — 113% renewal target, 96.7% retention rates
- 🤖 Led Global AI Enablement programme at Salesforce
- 🎓 Y Combinator Startup School | Anthropic Academy | Imperial College VC Programme
- 🌍 Based in London | French & English | Passionate about AI-native customer experiences

[LinkedIn](https://www.linkedin.com/in/davidzelee) · [Email](mailto:david.zelee@gmail.com)

---

## License

This work is shared under [MIT License](LICENSE). Use freely, adapt for your context, and share back what you learn.
