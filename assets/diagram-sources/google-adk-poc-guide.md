# Google ADK POC guide infographic

Generated with the built-in image tool. Reviewed: 2026-10-26. Proposed architecture, not deployment evidence.

Article and sources: [Google ADK guide](../../development/google-adk-for-our-poc.md). Export: [image](../images/google-adk-poc-guide.png).

## Generation prompt

Use case: infographic-diagram. Create polished landscape learning infographic, white background navy teal purple, large legible text, no logos. Title "Google ADK: What Matters for Our Agent POC". Subtitle "Framework capabilities — not a replacement for identity, gateway or policy". Three rows. Top row three role cards: "Entra ID / Agent ID" "Identity and token issuance"; "Solo Agentgateway" "Routing and configured enforcement"; "OPA — proposed" "Policy decision point". Middle large outlined container "Tachyon SDK + ADK runtime — proposed integration" with four equal cards "A2A: remote agent interaction", "MCP: tool integration", "Hooks / plugins: policy enforcement integration", "Sessions + traces: context and diagnosis". Show a small callout "Hook calls OPA before execution; receiver enforces independently". No arrows suggesting OPA issues tokens or Entra is in every request path. Bottom row priority cards: "1 • Preserve Phase 5 baseline", "2 • Read-only MCP smoke test", "3 • Add OPA allow / deny / unavailable tests", "4 • Verify A2A, identity continuity and traces". Footer caution band "Generic OAuth support ≠ verified Entra Agent ID OBO • Session state ≠ authorization • Tool filtering ≠ access control". Small note "ADK is a framework; A2A and MCP are protocols. Proposed integration, not tested deployment. Sources reviewed 26 Oct 2026." Keep precise spelling and restrained uncluttered layout.
