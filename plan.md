# RiskShield implementation plan

## Product approach
RiskShield is a demo-ready digital risk protection workspace focused on social and app-store impersonation. The prototype is intentionally static and dependency-free so it can be previewed and published reliably from the managed web project. Seeded intelligence makes the detection and triage flow immediately demonstrable; browser localStorage keeps profile edits, finding statuses, notes, and exclusions across sessions.

## Design direction
- **Design movement:** Forensic Paper — an evidence-led investigative workspace inspired by annotated case files and calm analyst tooling.
- **Core principles:** traceable evidence, calm decision-making, visible confidence, and resilient coverage states.
- **Color philosophy:** ink blue communicates trust and system authority; warm paper surfaces make dense evidence readable; brass marks verified or reviewable signals; coral is reserved for urgent risk.
- **Layout paradigm:** a persistent rail with a wide evidence canvas and offset modules, avoiding a generic centered dashboard grid. Findings read as case files with context on the left and action surfaces on the right.
- **Signature elements:** paper-texture background, brass index tabs, and a ruled evidence rail with monospace metadata.
- **Interaction philosophy:** every action explains what changed; filters and triage are immediate and reversible; unavailable sources stay explicit instead of disappearing.
- **Animation:** restrained 160–240ms transitions, subtle slide-in drawers, pulse only for live source status, no distracting continuous motion.
- **Typography system:** Source Sans 3 for readable UI and headlines; IBM Plex Mono for IDs, timestamps, and evidence metadata.
- **Brand essence:** RiskShield is the evidence-first risk workspace for teams protecting a brand across public social and app ecosystems. Personality: vigilant, grounded, transparent.
- **Brand voice:** clear, specific, and calm. Example lines: “Know what is impersonating you.” and “Every alert carries the evidence that earned it.”
- **Wordmark & logo:** a shield-shaped paper tab with an inset checkmark and a small signal notch; the wordmark pairs a compact label with a heavier “RiskShield” lockup.
- **Signature brand color:** ink blue `#183153`, with brass `#D6A85F` as the ownable evidence marker.

## Project structure
- `index.html` — semantic shell, navigation, content regions, modal and toast containers.
- `styles.css` — responsive Forensic Paper styling, layout, components, motion, and mobile rules.
- `app.js` — seeded findings, filter/search state, profile persistence, triage actions, demo flow, architecture rendering, and UI event wiring.
- `manus-routes.json` — published page route declaration for the single-page workspace.
- `app.config.ts` — durable project logo metadata.
- `package.json` — self-contained static build and preview commands.
- `TODO.md` — acceptance clauses and delivery outcomes.
