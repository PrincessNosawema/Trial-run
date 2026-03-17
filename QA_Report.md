# QA Report — `sample_blog_post.md`

> **Generated:** 2026-03-17T14:55:18.035Z
> **File:** `sample_blog_post.md` on branch `main`
> **Pipeline duration:** 8.1s

---

## Summary

✅ **Patch applied.** 8 operation(s) applied.

| Metric | Value |
|---|---|
| Issues identified by QA Agent | 8 |
| Average confidence (QA Agent) | 97.5% |
| Operations applied | 8 |
| Lines skipped by Editor Agent (Tier 3) | 0 |
| Runtime ops failed | 0 |
| QA Agent loop retries | 0 |
| Editor Agent loop retries | 0 |

---

## QA Agent Analysis

### Assumptions

I assumed the author intended to maintain a professional, authoritative tone suitable for B2B RevOps practitioners. I treated grammatical errors as objective mistakes and the contradiction between lines 45 and 47 as a factual inconsistency requiring attention.

### Issues Found

### Line 9 — 🟡 `medium` · `grammar` · Confidence: 100% · SVR: ❌
**Issue:** Subject-verb agreement error: 'teams knows' should be 'teams know'.
**Agent 1 Suggested Fix:** `Most revenue teams know that their CRM is only as good as the data inside it.`

### Line 11 — 🔴 `high` · `grammar` · Confidence: 100% · SVR: ❌
**Issue:** Homophone error: 'there both right' should be 'they're both right'.
**Agent 1 Suggested Fix:** `Sales and marketing keep arguing about pipeline health, and they're both right: the pipeline looks fine in Salesforce, but the underlying data tells a completely different story.`

### Line 13 — 🟡 `medium` · `grammar` · Confidence: 100% · SVR: ❌
**Issue:** Missing apostrophe in 'Its'.
**Agent 1 Suggested Fix:** `This isn't a people problem. It's a systems problem.`

### Line 19 — 🟡 `medium` · `grammar` · Confidence: 100% · SVR: ❌
**Issue:** Missing apostrophe in 'its'.
**Agent 1 Suggested Fix:** `Before we go into solutions, it's worth being specific about what bad data actually looks like in a RevOps context...`

### Line 45 — 🔴 `high` · `consistency` · Confidence: 90% · SVR: ❌
**Issue:** Logical contradiction: Line 45 claims a 20-person team generates 200-400 activities, but line 47 claims the same team generates over 1,200.
*No direct fix provided.*

### Line 110 — 🟡 `medium` · `grammar` · Confidence: 100% · SVR: ❌
**Issue:** Incorrect use of apostrophe in 'number's'.
**Agent 1 Suggested Fix:** `Plot these weekly. If the numbers go up after you implement an automation, that automation is working.`

### Line 130 — 🟡 `medium` · `grammar` · Confidence: 100% · SVR: ❌
**Issue:** Missing apostrophe in 'Its'.
**Agent 1 Suggested Fix:** `Data quality in CRM isn't a one-time cleanup project. It's an ongoing operational discipline...`

### Line 132 — 🟡 `medium` · `tone` · Confidence: 90% · SVR: ❌
**Issue:** Informal address 'you guys' is inappropriate for a B2B practitioner audience.
**Agent 1 Suggested Fix:** `The teams that don't? Well, they keep doing the quarterly cleanup sprint, wondering why the numbers don't add up, and keep rebuilding the same dashboards on top of the same bad data.`


---

## Editor Agent Decisions

#### Line 9 — ✏️ `replace`
**New Text:** `Most revenue teams know that their CRM is only as good as the data inside it. Yet according to recen…`
**Rationale:** Corrected subject-verb agreement error.

#### Line 11 — ✏️ `replace`
**New Text:** `Sales and marketing keep arguing about pipeline health, and they're both right: the pipeline looks f…`
**Rationale:** Corrected homophone error.

#### Line 13 — ✏️ `replace`
**New Text:** `This isn't a people problem. It's a systems problem. And honestly, automation is the ultimate game-c…`
**Rationale:** Corrected possessive/contraction error.

#### Line 19 — ✏️ `replace`
**New Text:** `Before we go into solutions, it's worth being specific about what bad data actually looks like in a …`
**Rationale:** Corrected possessive/contraction error.

#### Line 45 — ✏️ `replace`
**New Text:** `Neither approach scales. A 20-person sales team generates roughly 1,200 to 1,500 CRM activities per …`
**Rationale:** Resolved logical contradiction between lines 45 and 47 by aligning the activity volume estimate to a more realistic figure for a 20-person team.

#### Line 110 — ✏️ `replace`
**New Text:** `Plot these weekly. If the numbers go up after you implement an automation, that automation is workin…`
**Rationale:** Corrected incorrect apostrophe usage.

#### Line 130 — ✏️ `replace`
**New Text:** `Data quality in CRM isn't a one-time cleanup project. It's an ongoing operational discipline, the sa…`
**Rationale:** Corrected possessive/contraction error.

#### Line 132 — ✏️ `replace`
**New Text:** `The teams that don't? They keep doing the quarterly cleanup sprint, wondering why the numbers don't …`
**Rationale:** Replaced informal 'you guys' with a more professional, objective tone suitable for B2B practitioners.


---

## Tier 3 Lines Skipped by Editor Agent

*Lines with confidence < 0.6 where Agent 2 could not find a suitable alternative.*

*None — Agent 2 found fixes for all verified lines.*

---

## Runtime Skipped Operations

*None.*

---

*Generated automatically by the n8n Two-Agent Blog QA & Auto-Patch workflow.*

---
<!-- next run will append below -->
