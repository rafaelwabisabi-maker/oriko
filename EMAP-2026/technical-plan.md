# Technical Requirements & Residency Timeline
## PRAYER RESIDUE — Does Meaning Have Mass?

---

## Technical Requirements from Host

### Essential (BioLab)
- Controlled growing space: temperature-stable (20–25°C), programmable light cycle, isolated from external EM interference
- Space to install calibrated overhead camera (ceiling or fixed arm mounting for growth imaging)
- Access to SPAD chlorophyll meter (or budget for ~€200 rental — see budget)
- Plant surface electrode kit for bioelectric measurement (or budget for ~€200)
- Bench space for 24 Phaseolus vulgaris specimens (2 groups × 12), in separate but identically conditioned zones
- Partial Faraday shielding between Group A and Group B (aluminium mesh barrier, ~€40 materials)

### Essential (Technical)
- Reliable internet connection for BLESS.EXE live data feed
- Power supply for 2 Arduino-based frequency generators (5V USB, minimal draw)
- Monitor or projector minimum 40" for live data visualization
- Workbench access for final assembly and testing on arrival (heavy fabrication completed off-site before residency)

### Desirable
- Contact with plant biologist or biophysicist at JKU Linz or BOKU Vienna (or within Ars Electronica's existing scientific network)
- Oscilloscope or spectrum analyser for validating AI-generated EM output before plant exposure begins
- Exhibition space for final installation presentation during Ars Electronica programming

---

## Pre-Residency Preparation (at home in Zwettl an der Rodt, ~4 weeks before arrival)

> Rafael Vaz is based in Zwettl an der Rodt, 30km from Linz (~35 min drive). He will commute daily during the residency and does not require on-site accommodation — a practical advantage that reduces residency overhead and keeps the artist embedded in the local context of Upper Austria.

To use the 8 weeks of on-site time efficiently, the following is prepared at home before arrival:
- Fabrication of both accumulator sculpture structures (layered organic/metallic delivery apparatus)
- Assembly and testing of Arduino frequency generators + EM coil driver circuits + LED arrays
- BLESS.EXE → AI model → frequency trigger pipeline configured and locally validated
- Corpus preparation for both AI models (Model A: ritual tradition texts; Model B: mathematical/administrative language)

Arriving with all hardware built and software configured means Week 1 on-site is installation and testing, not fabrication from scratch.

---

## Budget Allocation (€4,000 production budget)

> All hardware items will first be sourced secondhand via Willhaben, eBay Kleinanzeigen, and university surplus before purchasing new. Estimates below reflect realistic purchase prices after secondhand search; items unavailable secondhand are priced new.

| Item | Estimated Cost | Notes |
|------|---------------|-------|
| Phaseolus vulgaris seeds × 30 (surplus buffer) + soil + pots + grow light supplement | €120 | Seeds ~€8; containers, substrate, small LED grow panel for consistency |
| Accumulator sculpture materials × 2 (wool batting, timber frame, steel mesh, copper coil wire) | €500 | Built at home pre-residency; materials sourced locally + Willhaben |
| Arduino Uno × 2 + EM coil drivers + toroidal coils + cables | €180 | Arduino clones + secondhand components acceptable |
| Surface electrode sensors (bioelectric measurement, stem-contact) | €200 | Or arranged via scientific collaborator |
| SPAD chlorophyll meter (rental, 8 weeks) | €200 | Via university equipment pool if possible |
| Overhead camera + mounting rig (growth imaging + time-lapse, one system for both) | €350 | Secondhand action cam or Raspberry Pi camera rig |
| Faraday mesh barrier + aluminium frame between groups | €40 | Standard window screen mesh |
| LED sculptural arrays × 2 (addressable RGB strips + controllers + diffusion housing) | €300 | Group A: amber-violet, 0.1 Hz wave. Group B: blue-white, metronomic. Activates at all 3 daily EM windows |
| Monitor/display for live data visualization (if not available at host) | €250 | Secondhand monitor 43"+ |
| Documentation: time-lapse post-processing, short-form video editing, social media pipeline | €600 | Includes one external editing session for Ars-branded documentary material |
| BLESS.EXE hosting + API scaling during 8-week residency | €160 | Vercel Pro + scaling buffer |
| Contingency / consumables / unexpected | €300 | |
| **Total** | **€3,200** | |
| **Reserve from €4,000** | **€800** | Available if scientific collaborator equipment needs supplement |

**Scientific collaborator:** The EMAP €2,000 collaborator support (separate from the €4,000 production budget) covers the scientific co-investigator — a plant biologist or biophysicist from JKU Linz, BOKU Vienna, or Ars Electronica's network. Role: co-design measurement protocol, validate methodology, co-author any resulting publication.

---

## Artist Compensation (how the residency pays Rafael)

EMAP residency terms cover:
- **Per diem:** approximately €45/day × 56 days (8 weeks) = **~€2,500** living and working allowance — this is the artist's income during the residency
- **Travel:** covered by EMAP for any residency-related transport
- **Accommodation:** not required — Rafael commutes daily from Zwettl an der Rodt (~35 min each way). This saves the host institution accommodation costs entirely and is a practical advantage of selecting a locally-based artist.

Rafael's labour contribution — concept, AI pipeline, hardware fabrication, daily experimental protocol, data logging, BLESS.EXE operations, and presentation — is the core investment of the project. It is compensated through the per diem and is not extracted from the production budget.

Elisabeth Braunschmid's contribution (installation co-design, documentation, data visualisation, exhibition coordination) is covered under the EMAP collaborator terms or by agreement with Rafael as co-artist.

---

## Residency Timeline (8 weeks on-site)

**Key principle:** all hardware and software is built and tested at home before arrival. The 8 weeks on-site are used for installation, plant growth, experiment, and presentation — not for construction.

### Week 1: INSTALLATION + SYSTEM VALIDATION
- Install accumulator sculptures, EM coil systems, LED arrays in BioLab
- Mount overhead camera + time-lapse rig
- Connect and validate BLESS.EXE → AI → Arduino → EM coil pipeline end-to-end
- Spectral verification: confirm prayer-trained AI output differs measurably from neutral AI output (oscilloscope)
- Configure data logging and live visualization display
- Test full daily EM deployment cycle including LED activation

### Week 2: PLANTING + BASELINE (Day –7 to Day 0)
- Plant 24 Phaseolus vulgaris (12 per group) under identical conditions
- Install bioelectric electrode arrays and establish baseline readings
- 7-day baseline period: all measurements running, zero EM treatment
- Confirm camera, SPAD, and electrode data pipeline is stable
- First automated social media post: experiment begins

### Weeks 3–6: THE EXPERIMENT (Days 1–40 / 4 × 10-day blocks)

**Daily EM schedule (all 40 days, identical and unvarying):**
Three transmission windows — 08:00, 14:00, 20:00 CET — each lasting 30 minutes. Total daily EM exposure per group: 90 minutes. BLESS.EXE transmissions from global participants are aggregated and batched into the 08:00 and 20:00 windows for Group A. LED arrays activate at each window: Group A amber-violet (0.1 Hz wave), Group B blue-white (metronomic pulse).

| Block | Days | Group A receives | Group B receives |
|-------|------|-----------------|-----------------|
| Block 1 | 1–10 | Prayer-trained AI signal | Neutral AI signal |
| Block 2 | 11–20 | Neutral AI signal (crossover) | Prayer-trained AI signal |
| Block 3 | 21–30 | Prayer-trained AI signal | Neutral AI signal |
| Block 4 | 31–40 | Both groups: prayer-trained (positive control) | ← same |

Daily measurements: growth imaging (overhead), chlorophyll (SPAD), bioelectric (electrodes). Time-lapse footage compiled weekly into social media segments and automated reports published to project channels, honourably anchored by Ars Electronica.

### Week 7: POST-EXPOSURE OBSERVATION + DATA PROCESSING
- EM treatment ends; plants continue growing under identical conditions for 7 additional days
- Post-treatment growth response documented (do differences accelerate, stabilise, or reverse?)
- Statistical analysis begins: repeated-measures ANOVA, p < 0.05 threshold, per-block and aggregate
- 60-day time-lapse video compiled (40 treatment days + 7 baseline + 7 post-exposure + installation days)

### Week 8: ANALYSIS + PRESENTATION
- Final statistical analysis and data visualisation
- Professional presentation at Ars Electronica BioLab
- Full documentation package: dataset, 47-day time-lapse, preliminary findings summary, photos
- Draft paper outline for peer-reviewed submission with scientific collaborator
- BLESS.EXE remains live; community notified of experimental outcomes

---

## Collaboration Plan

**Lead artist + project director:** Rafael Vaz — concept, AI system development, hardware engineering (Arduino + EM + LED), accumulator fabrication, daily experimental protocol, data logging, BLESS.EXE operations, social media production, final presentation. Locally based; commutes daily from Zwettl an der Rodt.

**Co-artist:** Elisabeth Braunschmid — installation aesthetics, LED visual programming, documentation direction, data visualisation, exhibition coordination, video post-production.

**Scientific collaborator (to be confirmed):** Plant biologist or biophysicist. Co-designs measurement protocol, validates methodology, reviews statistics, co-authors publication. Budget: EMAP €2,000 collaborator support.

---

## Post-Residency

1. **Publication:** *Leonardo* (MIT Press) for art-science framing; or plant biology / biophysics journal if results are statistically significant
2. **Exhibition:** Proposal for full installation at Ars Electronica Festival 2027 or Kapelica Gallery
3. **Open data:** Full 47-day dataset released under Creative Commons for independent replication
4. **BLESS.EXE:** Platform remains live as public infrastructure — the experiment ends, the blessing transmission does not
5. **Documentary:** Time-lapse + data visualisation + interview footage developed into short film, distributed via project channels and Ars Electronica communications
