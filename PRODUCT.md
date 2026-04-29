# Follow The Money — Product Context

## Product Purpose
A multi-agent financial fraud detection platform that analyzes public spending data to detect zombie recipients, funding loops, director network risks, and adverse media. Surfaces actionable risk intelligence to government decision-makers.

## Register
product

## Users
Government Ministers and Deputy Ministers of Alberta. Senior officials reviewing public spending accountability. Non-technical audience who need immediate clarity on which organizations represent the highest risk. Demo context: 5-minute presentation to Ministers at Agency 2026 Ottawa hackathon.

## Brand Tone
Authoritative. Precise. Urgent where warranted. No decoration — every element earns its place. The dashboard should feel like a tactical operations center, not a SaaS startup.

## Design Principles
- Data legibility above aesthetics
- Risk severity must be instantly scannable — CRITICAL reads differently from LOW at a glance
- Dark environment (Ministers in a conference room, projected on a screen)
- Trust signals matter: government-grade, not startup-grade
- Every interaction should feel deliberate and purposeful

## Anti-References
- No gradient text (background-clip: text)
- No glassmorphism
- No hero-metric templates (big number + gradient accent)
- No identical card grids
- No cyan/purple gradient color schemes
- No bouncy or elastic animations

## Color Strategy
Restrained. Dark tactical background (#0a0a0f range). One strong accent per risk tier: red for CRITICAL, amber for HIGH, yellow for MEDIUM, muted for LOW. White for primary data. Tinted neutrals only.

## Typography
Space Grotesk (headings, labels) + Space Mono (data, IDs, codes). Hierarchy through scale and weight contrast, not decoration.

## Key Surfaces
1. Entity list — ranked by risk score, color-coded by tier
2. Entity detail panel — flags, brief, directors, media findings, network graph
3. Network canvas — director/funding relationship graph
4. Risk score + tier badge — the hero data point per entity

## Success Criteria
A Minister can look at the dashboard for 10 seconds and know: which organization is highest risk, why, and what the flags are.
