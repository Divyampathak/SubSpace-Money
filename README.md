# Subspace.money — Product Teardown

A structured product teardown of [Subspace.money](https://subspace.money), an Indian subscription management and sharing marketplace. The analysis covers competitive positioning, feature gaps, and go-to-market issues, with prioritised recommendations for each.

## Contents

| File | Description |
|---|---|
| `report.pdf` | Five product feedbacks across four pillars: Competitor Analysis, Features/Services (×2), GTM & ICPs, and Potential Collaborations |
| `walkthrough.pdf` | Step-by-step research methodology documenting how each finding was derived |
| `ppt.pptx` | Presentation deck summarising the teardown |
| `screenshots/` | Supporting evidence captured directly from the product |

## Key Findings

### 01 — Competitor Analysis (High priority)
CRED Money, launched July 2024, replicates Subspace's core subscription-tracking capability for free using India's RBI-regulated Account Aggregator framework across 252.9M enabled accounts. Subspace's own competitor framing names only Western products. **Recommendation:** retire "subscription tracking" as the hero pitch; reposition entirely around automated price negotiation — the one capability CRED structurally cannot offer.

### 02 — Features / Services: Undisclosed Sharing Models (High priority)
Three structurally distinct sharing flows (credential sharing, platform invitation, sub-profile setup) operate under the single label "buying a slot" with no disclosure to buyers before purchase. Model A (credential sharing) violates platform ToS for Netflix, Canva, and others. **Recommendation:** mandate a "Slot Type" label on every listing set at creation; price credential-sharing slots 15% below dedicated-profile slots.

### 03 — Features / Services: Negotiate API Gap (High priority)
The Negotiate API is marketed as Subspace's primary moat but is implemented as a manual, user-triggered button with no renewal detection and no automated triggering. The Business API documentation page returns a 404. **Recommendation:** build a Renewal Calendar as the primary surface; trigger push notifications and automatic negotiation attempts 30 days before each billing date.

### 04 — GTM & ICPs: Student Segment Misalignment (Medium priority)
The blog hosts substantive student-specific deal content across Canva, Grammarly, Microsoft 365, and Duolingo, but the homepage carries no student messaging, pricing tier, or referral mechanic. **Recommendation:** separate ICPs; build a dedicated student acquisition flow.

### 05 — Potential Collaborations: Untapped OTT Community Channels (Medium priority)
OTT Deals India communities on Telegram have combined membership in the hundreds of thousands — a pre-qualified, deal-seeking audience with no current Subspace presence. **Recommendation:** establish an official presence and structured referral programme in these communities.

## Research Methodology

Total research time: ~4.5 hours. All observations are grounded in direct product use, official documentation, user-generated forum content (OnlyTech, 15+ pages), Play Store reviews, and published sources (TechCrunch, Inc42, HyperVerge AA framework report, RBI AA data).

Frameworks applied: **Jobs-to-Be-Done** (ICP separation) and **Porter's Five Forces** (competitive positioning).

Each feedback follows an **Observed → Problem → Ship Instead** structure with an explicit tradeoff statement and priority rating.
