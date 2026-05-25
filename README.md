# AI-Native GTM

> Frameworks, methodology, and playbooks for post-sale revenue at AI-native
> companies. The thinking layer behind the tools.

---

## Why this exists

Most GTM and Customer Success methodology was written for a SaaS world where the
product is stable, predictable, and well-understood. AI-native products break those
assumptions: capabilities shift weekly, the customer's mental model is the
bottleneck more often than the feature set, and adoption depends on trust as much
as ROI.

This repo collects the operating frameworks I've shipped and refined for that
reality — across Account Management, Customer Success, Expansion, and Partnerships
motions for B2B AI and SaaS companies scaling in EMEA.

It's also the thinking layer underneath the tools I've built: **Customer Growth OS**
and **SuccessOS** are the applied versions of these frameworks.

---

## Methodology — three working beliefs

1. **AI fluency over AI literacy.** Knowing what AI can do isn't enough. Customers
   need fluency — the ability to delegate, describe, discern, and be diligent with
   AI outputs. CS and AM teams at AI-native companies are in the fluency business,
   not the feature-walkthrough business.

2. **Adoption = trust × workflow fit, not capability.** Capability is usually
   abundant in AI products. The barriers are trust (will this be safe? compliant?
   accurate?) and workflow fit (does this slot into how the team actually works?).
   Both are CS and AM problems, not product problems.

3. **The customer's mental model is the bottleneck.** With AI products, customers
   often don't know what to ask for, how to evaluate outputs, or how to integrate
   the tool into their daily motion. The role of post-sale teams is increasingly
   about shaping that mental model.

---

## What's in the repo

### Frameworks
- **[`ai-native-cs-operating-model.md`](./frameworks/ai-native-cs-operating-model.md)** — operating model blueprint for AI-native Customer Success
- **[`ai-health-score-model.md`](./frameworks/ai-health-score-model.md)** — multi-signal health scoring with CSM augmentation framing
- **[`adoption-signal-detection.md`](./frameworks/adoption-signal-detection.md)** — leading vs lagging adoption indicators and signal types

### Playbooks
- **[`scale-cs-automation.md`](./playbooks/scale-cs-automation.md)** — AI-driven scale CS workflow for high-volume portfolios

### Prompts
- **[`account-research.md`](./prompts/account-research.md)** — pre-meeting intelligence prompts with full templates
- **[`qbr-preparation.md`](./prompts/qbr-preparation.md)** — QBR narrative generation prompts

### Resources
- **[`reading-list.md`](./resources/reading-list.md)** — references on AI-native GTM and Customer Success methodology

---

## Tools I've built on these frameworks

These frameworks aren't theoretical — they power live AI-native apps.

| Tool | What it applies |
|---|---|
| **[Customer Growth OS](https://github.com/DavLMZ/customer-growth-os)** | The agnostic operating model: portfolio health scoring, NBA prioritisation, stakeholder dynamics, expansion pipeline, QBR generation, product feedback synthesis. → [Live demo](https://customer-adoption-hub--davidzelee.replit.app) |
| **SuccessOS** | The vertical instantiation for ElevenLabs — voice-AI Customer Success with a live WebRTC voice agent. → [Command centre](https://claude-successos-d7n7.vercel.app) · [Copilot + Voice](https://eleven-pathfinder-compass.lovable.app) |

The pattern: build the framework first, then apply it to a real product. The apps
prove the frameworks are operable, not just thought pieces.

---

*Frameworks compiled from 10+ years running Customer Success and Strategic Account
motions at Salesforce and Tableau, refined for AI-native scale.*
