# Koda Health

Koda Health is a Houston-based digital health company whose AI-enhanced patient decision support platform digitizes serious illness planning for health systems, health plans, and value-based care organizations. Its two solutions — Advance Care Planning (ACP) and Kidney Action Planning (KAP) for chronic kidney disease — guide patients through video-based, interactive goals-of-care conversations and produce legally compliant advance directives, medical power of attorney, and POLST/DNR documents with digital signing and notarization in all 50 states. Completed plans are pushed into the provider's EMR through an integration Koda states meets HL7 FHIR standards. KodaCares adds human Patient Advocates for complex cases.

- Website: https://www.kodahealthcare.com/
- Patients: https://koda.health/
- Application: https://app.kodahealthcare.com/
- Backed by: techstars

## API status

Koda Health publishes **no public API**. There is no developer portal, API reference, OpenAPI or AsyncAPI document, SDK, CLI, MCP server, or public Postman collection. `api.kodahealthcare.com` is a closed AWS load-balanced backend returning HTTP 403 to every unauthenticated request. EMR interoperability is delivered through health-system and partner integrations rather than a self-serve public API.

## Artifacts

| Artifact | File | Method |
|---|---|---|
| Conformance / Compliance | `conformance/koda-health-conformance.yml` | searched |
| Domain security | `security/koda-health-domain-security.yml` | probed |
| Well-known probe (no hits) | `well-known/koda-health-well-known.yml` | searched |
| llms.txt | `llms/koda-health-llms.txt` | generated |
