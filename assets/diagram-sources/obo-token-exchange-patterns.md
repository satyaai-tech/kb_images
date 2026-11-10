# OBO exchange placement infographic

Generated and visually reviewed: 2026-10-26.

Export: [image](../images/obo-token-exchange-patterns.png). Technical sources and qualifications: [article](../../identity/obo-token-exchange-patterns.md).

AI-generated educational architecture, not deployment evidence. Four placements refer to acquisition logic; Entra remains issuer. Gateway and broker patterns are architectural options, not confirmed Agent ID integrations.

## Design brief

Landscape infographic on white with navy, teal and purple. Title: Where Can OBO Token Exchange Happen? Subtitle: Four deployment options — Entra issues the tokens in every option. Top sequence: incoming middle-tier access token, authorized request to Entra, new downstream token. Explain that exchange does not edit the old JWT.

Four cards: in-process agent/service, local authentication sidecar, gateway-managed exchange, dedicated token broker. Include each placement's trust boundary and operational tradeoff. Contrast standard application audience alignment with Agent ID blueprint/child assertion flow. Warn that standard gateway OBO examples do not prove Agent ID support. Footer distinguishes forwarding, headless app-only identity, and OPA/PlainID policy decisions from token issuance. Source review date: 26 Oct 2026.
