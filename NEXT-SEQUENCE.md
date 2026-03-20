# Next Sequence: Vigiles Aeternae Forward Plan

*52/82 issues closed. 30 remaining. This document plans the next execution wave.*

---

## PHASE A: Research Flood (BETA completion — 9 remaining deep dives)

**Why first:** Everything downstream depends on the research corpus being rich. New regimes, new Orders, the comparative analysis, the publishable paper — all gate on having deep, academically-sourced tradition syntheses.

**Method:** Each tradition gets a `synthesis--governance-cosmology.md` following the B1 Greek-Roman template:
- Primary sources (named texts, dates, authors)
- Scholarly references (peer-reviewed, JSTOR/Cambridge/Oxford/Brill)
- Governance model extraction (how does this tradition structure authority?)
- Power taxonomy (delegation, enforcement, rebellion, decay, renewal)
- Regime draft (YAML skeleton with philosophy, priorities, phaethon)
- Vigiles mapping (which Orders does this tradition illuminate or challenge?)
- New Order candidates (does this tradition reveal a governance function the 7 don't cover?)

### Sequence (ordered by Vigiles impact):

| Order | Issue | Tradition | Why This Order | Key Primary Sources |
|-------|-------|-----------|----------------|-------------------|
| 1 | B2 | **Marvel Cosmic** | Directly maps to Watcher Orders — Celestials, Living Tribunal, Watchers | Marvel comics canon (Kirby, Starlin, Hickman runs) |
| 2 | B3 | **Hindu/Buddhist** | Trimurti = alternative triadic model to Zelda. Yugas = time-governance. Dharma = cosmic law. | Rigveda, Bhagavad Gita, Vishnu Purana, Pali Canon |
| 3 | B4 | **Norse** | Ragnarok = governance-with-known-failure. Norns = fate as governance. | Prose Edda (Snorri), Poetic Edda (Codex Regius), Voluspa |
| 4 | B5 | **Egyptian** | Ma'at = governance-as-daily-ritual. Unique model not in current regimes. | Book of the Dead, Pyramid Texts, Papyrus of Ani |
| 5 | B6 | **Mesoamerican** | Sacrifice-as-fuel = governance-as-metabolic-exchange. Radical departure. | Popol Vuh, Codex Borgia, Florentine Codex (Sahagún) |
| 6 | B7 | **African (Yoruba)** | Orisha = distributed divine authority. Ifá = governance-by-divination. | Ifá corpus (UNESCO-recognized), Bascom's studies |
| 7 | B8 | **Abrahamic** | Angelic hierarchies = most developed cosmic bureaucracy. Sefirot = emanation governance. | Hebrew Bible, Pseudo-Dionysius, Zohar, Quran |
| 8 | B9 | **Daoist** | Wu wei = governance-by-non-action. The anti-regime regime. | Daodejing (Laozi), Zhuangzi, Liezi |
| 9 | B10 | **Indigenous Australian** | Dreamtime = governance-as-concurrent-reality. Songlines = law-as-landscape. | Strehlow's studies, Berndt & Berndt, Chatwin's *Songlines* |

### After all 9 dives:

| Order | Issue | Task | Depends On |
|-------|-------|------|-----------|
| 10 | B13 | **Cross-mythology comparative analysis** | B1-B10 all complete |
| 11 | B14 | **Power taxonomy schema formalization** | B13 |
| 12 | B15 | **metaLAWs cross-references to corpus** | B13, B14 |
| 13 | B17 | **Draft regimes for all new traditions** | B1-B10 |
| 14 | B18 | **First publishable paper** | B13, B14 |
| 15 | B11 | **Additional fictional mythologies** (Dune, Foundation, Discworld) | Can parallel with above |

**BETA completion = 16 tasks → closes 17 issues (B2-B18 minus already-closed B16)**

---

## PHASE B: Order Evolution (GAMMA completion — 4 remaining)

**Why second:** Research reveals new Order candidates and deepens existing ones. This phase integrates discoveries.

| Order | Issue | Task | Depends On |
|-------|-------|------|-----------|
| 1 | G14 | **Research: identify new Orders from mythology study** | PHASE A complete |
| 2 | G1 | **Expand Order YAML schema with RPG stats, visual/sonic** | G14 (may add new fields) |
| 3 | G10 | **Wire Orders into organvm-engine** | G1 |
| 4 | G11 | **Add Order audit commands to CLI** | G10 |

**GAMMA completion = 4 tasks → closes 4 issues**

---

## PHASE C: Engine Integration (EPSILON completion — 3 remaining)

**Why third:** With enriched Orders and new regimes from research, integrate everything into the existing ORGANVM toolchain.

| Order | Issue | Task | Depends On |
|-------|-------|------|-----------|
| 1 | E11 | **Wire Colosseum into organvm-engine governance module** | G10 |
| 2 | E12 | **MCP tools — expose via organvm-mcp-server** | E11 |
| 3 | E13 | **Dashboard — regime audit visualizations** | E11 |

**EPSILON completion = 3 tasks → closes 3 issues. Engine 14/14.**

---

## PHASE D: Franchise Activation (ZETA — 13 issues)

**Why fourth:** Content is mature. Products can now be built from real substance.

### Sub-phase D1: Repo creation (5 repos for Organs III-VII)

| Issue | Repo | Organ |
|-------|------|-------|
| Z1 | `vigiles-aeternae--mercatura-mythica` | III |
| Z2 | `vigiles-aeternae--ordo-taxis` | IV |
| Z3 | `vigiles-aeternae--vox-custodes` | V |
| Z4 | `vigiles-aeternae--collegium-mythicum` | VI |
| Z5 | `vigiles-aeternae--kerygma-custodes` | VII |

### Sub-phase D2: First products (8 issues, can parallel)

| Issue | Product | Organ | Priority |
|-------|---------|-------|----------|
| Z9 | **First essay** — "What Happens When Malazan Governs Your Codebase" | V | HIGH (content marketing + intellectual contribution) |
| Z6 | **Watcher Order quiz** — "Which Order Are You?" | III | HIGH (viral, low-effort, revenue) |
| Z8 | **Agent personas** — regime-embodying Claude sessions | IV | MEDIUM (internal value, external demo) |
| Z11 | **First broadcast** — character reveals + audit results | VII | MEDIUM (content drops) |
| Z7 | **Character art prints** | III | MEDIUM (requires art generation) |
| Z10 | **Regime Election** — community votes | VI | LOW (needs community first) |
| Z12 | **Playable RPG** | III | LOW (significant dev effort) |
| Z13 | **The Book** | III | LOW (compilation from mature content) |

**ZETA = 13 tasks → closes 13 issues**

---

## PHASE E: OMEGA (Perpetual — 8 issues, never "close")

These don't close. They are perpetual processes:

| Issue | Process | Trigger |
|-------|---------|---------|
| Ω1 | Research pipeline | Every new tradition studied |
| Ω2 | Community worldbuilding | When community infrastructure exists |
| Ω3 | Constitutional accumulation | Every Agon cycle with consensus |
| Ω4 | Revenue pipeline | When first products ship |
| Ω5 | Autopoietic evolution | When Vigiles audits itself |
| Ω6 | Hybrid regimes | When fusions produce stable governance |
| Ω7 | New Watcher Orders | When research reveals gaps |
| Ω8 | Full franchise revenue | When all 8 organs generate value |

---

## Summary: The Road to 82/82

| Phase | Issues | Running Total | What It Produces |
|-------|--------|---------------|------------------|
| Current | 52/82 closed | 63% | Genesis + Engine + Theatrum + Constitution |
| **A: Research** | +17 | 69/82 (84%) | 10 tradition syntheses + comparative analysis + paper |
| **B: Orders** | +4 | 73/82 (89%) | Evolved Orders + engine integration |
| **C: Engine** | +3 | 76/82 (93%) | Full ORGANVM integration (engine + MCP + dashboard) |
| **D: Franchise** | +13 | 89/82 (wait—) | 5 new repos + first products |

*Note: 82 includes 8 OMEGA issues that never close. Effective target: 74/74 closeable issues.*
*Current: 52/74 = 70%. After Phase A: 69/74 = 93%. After Phase D: 74/74 = 100%.*

---

## Immediate Next Action

**B2: Marvel Cosmic Hierarchy.** The tradition that most directly maps to the Watcher Orders — because Marvel literally has beings called "The Watchers." This synthesis will either validate our Order architecture or reveal gaps we need to fill.

Primary sources: Jack Kirby's *Eternals* and *Celestials* (1976), Jim Starlin's *Infinity Gauntlet/War/Crusade* (1991-93), Jonathan Hickman's *New Avengers/Secret Wars* (2013-15). Scholarly: peer-reviewed comics studies from *ImageTexT*, *Journal of Graphic Novels and Comics* (Taylor & Francis), *Inks: The Journal of the Comics Studies Society* (Ohio State UP).
