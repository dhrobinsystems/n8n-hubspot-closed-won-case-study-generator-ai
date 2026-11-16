# ⚠️ Disclaimer & Liability Limitation

**Use at your own risk.** The code, workflows, and scripts in this repository (`n8n-hubspot-closed-won-case-study-generator-ai`) are provided for educational and architectural demonstration purposes.

## No Liability

The author and dhRobin Systems accept no responsibility or liability for any direct, indirect, incidental, or consequential damages that result from using, misusing, or deploying these scripts. This includes, without limitation, inaccurate, misattributed or fabricated metrics or quotes; publication of case study content without customer approval; breach of customer confidentiality or contractual non-disclosure obligations; disclosure of call transcripts or personal data to AI providers or document platforms; reputational harm; regulatory or advertising-standards claims; overwritten HubSpot properties; service interruptions; and API quota exhaustion or AI usage costs.

## No Warranty

All software, n8n JSON blueprints, JavaScript modules and prompts are provided "AS IS", without warranty of any kind, express or implied. This includes, but is not limited to, warranties of merchantability, fitness for a particular purpose, and non-infringement.

No warranty is given that AI output is accurate, complete or free of invented content; that the grounding checks detect every unsupported claim; that redaction removes all personal data; that transcripts are matched to the correct deal; that speaker affiliations reported by Gong, Zoom or any other recorder are correct; that HubSpot, Gong, Zoom, OpenAI, Anthropic, Notion or Google API responses remain compatible with this workflow; or that documents and write-backs succeed.

## Production Testing Required

Always test thoroughly in an isolated staging environment, such as a HubSpot developer test account or sandbox, with `SANDBOX_MODE=true`, `DRY_RUN=true`, `AI_MODE=mock` and `CREATE_DOCUMENT=false` enabled, before you connect live HubSpot, Gong, Zoom, OpenAI, Anthropic, Notion or Google credentials. Compare every verified metric and quote in the first drafts against the original recordings, confirm that consent-declined companies are skipped, and confirm that drafts land only in restricted locations before activating the webhook.

Treat every generated draft as unverified marketing copy. A human must check it against the sources, and the customer must approve the final text in writing before it is published or shared outside your organisation.

## Third-Party APIs & Compliance

You alone are responsible for complying with the terms of service, rate limits, data privacy regulations (GDPR/CCPA and equivalents), advertising and consumer-protection rules, and security policies of HubSpot, Gong, Zoom, OpenAI, Anthropic, Notion, Google and any connected services. That includes:

- having a lawful basis and any required notices for processing call recordings and transcripts, and for sending them to an AI provider;
- honouring confidentiality, publicity and logo-use clauses in customer contracts, and obtaining written customer approval before any publication;
- using AI API tiers and agreements (including a data processing agreement) appropriate for confidential customer data;
- granting only the minimum scopes to the HubSpot private app, Gong, the transcript adapter, Notion and Google;
- securing, rotating and restricting access to every token and key, including the HubSpot app client secret and Google OAuth tokens;
- restricting access to generated drafts and n8n execution data, which contain transcript excerpts, and applying a retention period that matches your policies;
- reviewing every automatically created or updated record.

## No Affiliation

HubSpot, Gong, Zoom, OpenAI, Anthropic, Claude, Notion, Google, Google Docs, Google Drive and n8n are trademarks of their respective owners. This project is independent and is not affiliated with, endorsed by, or sponsored by any of them. All people, companies, deals, identifiers, transcripts and figures in the fixtures, sample payloads and pinned data are fictitious.

## Not Professional Advice

Nothing in this repository constitutes legal, privacy, marketing-compliance, security, or financial advice. Consult qualified professionals for your specific circumstances.

---

Released under the MIT License. Copyright (c) 2026 DH Robin (dhRobin Systems). See [LICENSE](LICENSE).

Full text: DISCLAIMER.md · Licensed under the MIT License. License: MIT © 2026 dhRobin Systems · Provided as-is, see the disclaimer.
