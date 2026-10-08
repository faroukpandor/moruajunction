# Farouk Collective UI Direction — Visual Thinking × Visual Storytelling

## Portfolio requirement
This repository is part of the Farouk Collective webapp portfolio. Its interface should share the portfolio-wide product philosophy while retaining its own brand, domain, audience, and functional identity.

## Inspiration
Use the **interaction principles** associated with Napkin AI and Gamma AI as inspiration: visual reasoning, turning ideas into structured visual artefacts, narrative composition, progressive disclosure, polished outputs, and easy movement from draft to presentation/shareable result.

**Do not copy** proprietary screens, branding, assets, code, or distinctive trade dress. This is a design-inspiration direction, not a clone.

## Experience model
Design important journeys around:

**Goal → Source/Idea → Structure → Evidence → Visualise → Decide → Act → Share**

Not every screen needs every stage. The interface should make the user's current stage obvious.

## Mandatory UI characteristics
- Make the product purpose immediately understandable.
- Give each primary view one clear next action.
- Prefer calm editorial composition over dashboard clutter.
- Use strong typography, hierarchy, spacing, and meaningful visual blocks.
- Turn relationships into useful diagrams, flows, timelines, maps, matrices, or other visual structures when they improve comprehension.
- Keep sources, evidence, provenance, status, assumptions, and uncertainty distinguishable.
- Use progressive disclosure rather than exposing every control at once.
- Make outputs useful beyond the app: summaries, briefs, dossiers, plans, presentations, exports, or shareable views where appropriate.
- Work well on mobile and desktop.
- Preserve accessibility, performance, portability, and offline-first behaviour where appropriate.
- Avoid decorative AI noise, fake metrics, fabricated evidence, or claims of authority that the product cannot substantiate.

## Shared component vocabulary
Where technically appropriate, converge on lightweight equivalents of:
- Workspace / Canvas
- StoryCard
- VisualNode
- EvidenceChip
- SourceBadge
- WorkflowStep
- InsightPanel
- DecisionCard
- OutputMode
- Dossier / Presentation Renderer

These are conceptual patterns, not a mandate to add unnecessary dependencies.

## Engineering rule
**Inspect first. Preserve what works. Improve incrementally.**

Do not migrate frameworks, replace architecture, or add a heavy design system merely for visual consistency. Prefer semantic HTML, existing project conventions, lightweight CSS/components, progressive enhancement, and portable deployment.

## Brand rule
**One philosophy, many identities.** Shared UX principles must not erase the distinct identity or purpose of this product.

## Release gate
Before shipping a material UI change, verify:
1. The user journey is understandable without explanation.
2. Visualisation adds meaning rather than decoration.
3. Evidence is distinguishable from inference or generated content.
4. Important outputs can be reused or shared.
5. Mobile, keyboard, contrast, and performance are acceptable.
6. The product still feels like its own product.

**Collective principle:** add as much value to as many lives as possible, with fairness, transparency, evidence, and ownership/provenance clarity.
