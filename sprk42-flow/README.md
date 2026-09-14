# SPRK42 Flow legal and shared assets

SPRK42 Flow is the reusable workflow platform. Deployment-specific legal pages, branding and store material live underneath `company/<deployment-slug>/` so white-labelled apps can carry the correct business identity without duplicating the platform structure.

Current deployment:

- `company/edp-flow/` — EDP Flow

Each deployment should keep:

- `company.json` — deployment identity and legal-review checklist
- `index.html` — legal/support landing page
- `privacy.html` — deployment privacy notice
- `terms.html` — deployment terms/use notice
- `delete-data.html` — account/data deletion guidance
- `support.html` — support and contact guidance
- `branding/` — deployment logos/wordmarks used by the app and store material
- `store-assets/` — store copy, screenshots and publishing assets

## White-label rule

The repository/Firebase project may retain the SPRK42 technical identity. Public-facing names, company/controller details, support details, logos and legal notices must come from the deployment configuration.

Legal text is deployment-specific and should be reviewed whenever the data model, authentication, analytics, subprocessors, retention, billing or ownership model changes.
