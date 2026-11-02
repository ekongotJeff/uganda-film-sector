# Uganda Film Sector Dashboards

Public dashboards for the Uganda National Film Sector Mapping, Diagnostic and Development Framework, prepared by the National Producers Guild of Uganda (PGU).

- `/` : Economic & Employment Baseline (Deliverable 3)
- `/gaps` : Gap & Needs Assessment (Deliverable 5)
- `/assets` : Cultural & Diplomatic Assets Map (Deliverable 6), with the full report suite in `assets/reports/`

## Economic & Employment Baseline (`/`)

Interactive dashboard for Deliverable 3 of the Uganda National Film Sector Mapping, Diagnostic and Development Framework, prepared by the National Producers Guild of Uganda (PGU).

It shows enterprises, direct and indirect employment, gross output, value added, tax, 2029 growth scenarios, data gaps and a 19-indicator tracking framework, each with a Low / Central / High case and an evidence label (Verified, Derived, Estimate, Data gap, Unverified).

### Status

Draft. All headline figures are estimates pending PGU Board approval and UBOS technical review. Quote estimates with their ranges.

### Structure

- `index.html`: the whole site. Static, no build step. Data is embedded in the page.
- `vercel.json`: static hosting config.

### Updating

Replace `index.html` with a regenerated version from the Excel model and push to `main`. Vercel redeploys automatically.

## Gap & Needs Assessment (`/gaps`)

Interactive guide to Deliverable 5: 38 sector gaps across 13 diagnostic domains, each located on the film value chain and scored for severity and tractability. Views: overview, gap explorer with filters, prioritisation matrix, Top 10 needs, sequencing roadmap with dependencies, and evidence and method.

### Status

Consultation draft. Scores and findings are pending stakeholder validation and PGU Board approval. The status banner text is set in the `STATUS` constant at the top of the page script.

### Updating

Replace `gaps/index.html` with a regenerated version and push to `main`.

## Cultural & Diplomatic Assets Map (`/assets`)

Uganda Film Heritage Atlas, the interactive guide to Deliverable 6: 164 stories, heritage elements, archives, locations and international assets for film, with custodian, consent terms, sensitivity and evidence label for each. Views: overview, asset register with filters, map of public sites, at-risk register, diplomacy and tourism, Cultural Use Protocol, and sources.

### Report suite (`assets/reports/`)

- `PGU_D6_Cultural_Diplomatic_Assets_Map.docx` / `.pdf`: full report
- `PGU_D6_Asset_Register.xlsx`: asset register with filters and summary sheets
- `PGU_D6_Public_Sites_Map.csv`: public, non-sensitive sites with approximate coordinates
- `PGU_D6_Cultural_Use_Protocol.docx` / `.pdf`: two-page protocol for producers
- `PGU_D6_MoFA_MTWA_Summary.docx` / `.pdf`: one-page briefing for MoFA and MTWA

### Status

Draft v0.9 for PGU Board review and custodian validation. Not for wide circulation. Cultural institutions are named from public reporting and should be confirmed with each institution. The atlas page carries a noindex tag.

### Updating

Replace `assets/index.html` or the files in `assets/reports/` and push to `main`.

National Producers Guild of Uganda, Lungujja, Kampala. November 2026.
