# Expanded Azure circle map

Created 2026-10-24 with the built-in image generator; original image retained.

[Final export](../images/product-roles-overlap-azure-v2.png)

Optional Azure services are illustrative, not confirmed Tachyon deployments. Entra is a Microsoft identity service; not all depicted Microsoft capabilities are Azure resources. Licensing and supported identity flows matter. Azure Policy governs Azure resource compliance, while OPA/PlainID can evaluate application-specific operations. Key Vault stores secrets/keys/certificates; it does not automatically rotate every blueprint credential. Private connectivity is not business authorization. Azure Monitor and Arize may overlap; telemetry routing and governance require design.

Sources checked 2026-10-24:

- [Blueprint creation](https://learn.microsoft.com/en-us/entra/agent-id/create-blueprint)
- [Agent governance](https://learn.microsoft.com/en-us/entra/id-governance/agent-id-governance-overview)
- [Azure Policy](https://learn.microsoft.com/en-us/azure/governance/policy/overview)
- [Key Vault](https://learn.microsoft.com/en-us/azure/key-vault/general/overview)
- [Private Link](https://learn.microsoft.com/en-us/azure/private-link/private-link-overview)
- [Azure Monitor](https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/overview)

## Initial edit prompt

Edit the attached circle infographic into a larger expanded version. Preserve clean white/navy style, circle motif, OPA blue PlainID purple MACAW amber meanings, and retain Tachyon, Solo.io AgentGateway and Arize. Re-layout for legibility with THREE clearly separated horizontal sections; much more space and larger canvas is fine. Title 'Enterprise Agent Platform — Azure & Product Overlaps'. Subtitle 'Identity & cloud foundations • Runtime authorization • Agent platform'. SECTION 1 top 'Microsoft Entra — identity & access' with three blue/green CIRCLES side-by-side: 'Entra ID' text 'Users • Authentication • Tokens • Scopes & roles'; 'Entra Agent ID' text 'Blueprints → Agent identities' 'Authentication foundation for agent families' 'Approved permission inheritance'; 'Access & Lifecycle Governance' text 'Owners & sponsors • Access reviews' 'Conditional Access where supported'. A shared caption 'Governance and security controls depend on licensing, configuration and supported identity flows'. Blueprint not code deployment template, children not necessarily per LOB, no blanket permission. SECTION2 middle, main existing THREE-circle Venn cluster OPA PlainID MACAW: OPA 'Open-source policy engine' 'Rego + programmable decisions'; PlainID 'Enterprise authorization platform' 'Policy administration + integrations'; MACAW 'Agent-focused security' 'Signed invocations • Delegation lineage • Session-bound context'. OPA/PlainID overlap label 'Business authorization'; triple overlap 'Runtime policy controls'. Put Tachyon smaller distinct circle to left 'Registry • Agent cards • SDK' 'ADK / LangChain • LLM Bridge'. To right TWO small distinct circles 'Solo.io AgentGateway' 'Routing & gateway enforcement', and 'Arize' 'Observability & evaluation'. Do not add product-to-product arrows; use small shared caption 'Integration options—not proven interoperability or required deployment'. SECTION3 bottom 'Optional Azure supporting services — select by requirement' FOUR pale-blue circles or roundels in a row: 'Azure Key Vault' 'Secrets • Keys • Certificates'; 'Azure Policy + Azure RBAC' 'Azure resource governance & access'; 'VNet + Private Link' 'Private connectivity'; 'Azure Monitor + Application Insights' 'Metrics • Logs • Traces'. Add two explicit short cautions below: 'Azure Policy is not a replacement for per-tool business authorization.' and 'Azure Monitor overlaps observability needs; complement or rationalize with Arize.' Footer 'Conceptual responsibilities, not exact feature sets. Azure services shown are optional, not verified Tachyon deployments. MACAW capabilities are vendor-documented. Reviewed 24 Oct 2026.' No invented logos, no whole Azure circle enclosing OPA, no automatic secret rotation promise, no immediate token revocation claims. Keep text large, avoid overloaded circles and crossing lines. No guarantee of universal cross-product integration.

## Targeted correction

The first draft mislabeled blueprints as deployment templates. Final edit replaced only the top-left explanatory paragraph: Identity foundation for humans and agents. Blueprints are identity templates and an authentication foundation—not code deployment templates. Agent identities need approved access; blueprint membership is not blanket business permission.

