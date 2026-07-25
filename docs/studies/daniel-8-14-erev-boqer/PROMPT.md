# Bible Study: In Daniel 8:14, did Daniel intentionally use 'erev boqer' (evening-morning) instead of his usual 'yamim' (days) as a deliberate fingerprint of concealment for the time period — encodable because a day-for-year decoder already existed in Numbers 14:34 and Ezekiel 4:6 — with Gabriel's command to 'seal the vision' (Daniel 8:26) confirming the concealment is intentional? And is the resulting years-reading confirmed (with Daniel 9's 'chathak' the strongest confirmation, not the sole proof)?

## Question
In Daniel 8:14, did Daniel intentionally use 'erev boqer' (evening-morning) instead of his usual 'yamim' (days) as a deliberate fingerprint of concealment for the time period — encodable because a day-for-year decoder already existed in Numbers 14:34 and Ezekiel 4:6 — with Gabriel's command to 'seal the vision' (Daniel 8:26) confirming the concealment is intentional? And is the resulting years-reading confirmed (with Daniel 9's 'chathak' the strongest confirmation, not the sole proof)?

**Prompt schema:** v2

## Prior Research Summary
12 prior studies and ~7 external corpus claims were gathered as LEADS ONLY (this is a standalone rederivation per CUSTOM-INSTRUCTIONS.md). The sv-10/sv-11 series already PUBLISHED the intentional-encoding conclusion; this study must TEST the chain defeasibly from Scripture, not inherit it. Three non-negotiable traps: (a) satham (Dan 8:26, conceal) is a different verb from chatham (Dan 9:24, authenticate) — never cite 9:24 sealing as concealment; (b) the day-for-year ratio is grounded in Num 14:34 + Ezek 4:6, NOT in Daniel 8 (Dan 8 is the application site); (c) the tamid-primary and Genesis-1 day-definition readings must stay live — 'erev boqer may be natural-to-topic, not obscure-by-design. Calibration ceiling: MEDIUM-HIGH that the 2300 specifically = years; authorial-motive ('chose X to conceal') is an inference, rarely explicit, held to a high bar. Dan 9 chathak = strongest confirmation among several (Num/Ezek ratio + apocalyptic genre + scope-demand also point to years), not the sole proof.

## Authorial Vernacular Audit

**Scope:** Book of Daniel (Daniel's own time-vocabulary), widening to the OT — Daniel, Genesis, Exodus, Numbers, Ezekiel

### cat-daniel-names-durations-directly: When Daniel names time durations DIRECTLY with yamim/normal units

**Candidate categories:** cand-deliberate-concealment-cipher, cand-tamid-primary-natural

**Focus area:** 1

**Direct-label passages:**
- Dan 12:11: 1290 stated as YAMIM (parser-verified Noun.mp.Abs yom + 'eleph mathayim wetish'im) — apocalyptic time period in the SAME book and genre uses days, not 'erev boqer
- Dan 12:12: 1335 YAMIM — second in-book apocalyptic duration using the normal word
- Dan 8:26: 'for many DAYS' (leyamim rabbim, parser-verified) — Daniel uses yamim in the very verse that seals the erev-boqer vision
- Dan 10:2-3: 'three full weeks' / mourning duration stated in ordinary units (yamim)
- Dan 1:5: 'three years' nourishment — ordinary duration language
- Dan 1:12: 'ten days' (yamim) test proposal — ordinary counting unit
- Dan 1:14-15: 'ten days' fulfilled — Daniel's plain yamim usage

**Structural analogies:**
- Ex 29:38-42: morning-then-evening tamid order
- Num 28:3-8: morning-then-evening tamid order restated

**Negative controls:**
- Dan 12:11: Daniel wrote 1290 as yamim, so he demonstrably HAD and USED yamim for apocalyptic periods
- Dan 8:26: yamim appears in the same pericope (leyamim rabbim)

**Required searches:**
- `python hebrew/hebrew_parser.py --verse "Daniel 12:11"`
- `python hebrew/hebrew_parser.py --verse "Daniel 8:14"`
- `python search/search_strongs.py --verses H3117 --scope "Dan"`

### cat-creation-evening-morning-refrain: Genesis-1 evening-morning creation refrain and its order (structural analogy for the term's availability)

**Candidate categories:** cand-genesis-allusion-driven, cand-deliberate-concealment-cipher

**Focus area:** 2

**Direct-label passages:**
- Gen 1:5: wayehi 'erev wayehi boqer yom 'echad — evening-first order defining one day (parser-verified 'ereb, boqer, yom)
- Gen 1:8: creation-day refrain, day two
- Gen 1:13: creation-day refrain, day three
- Gen 1:19: creation-day refrain, day four
- Gen 1:23: creation-day refrain, day five
- Gen 1:31: creation-day refrain, day six

**Structural analogies:**
- Gen 1:5: evening-then-morning = one full day

**Negative controls:**
- Gen 1:5: Genesis joins 'ereb and boqer each with waw (wayehi...wayehi) and pairs them with the word yom; Dan 8:14 is bare asyndetic with NO yom

**Required searches:**
- `python hebrew/hebrew_parser.py --verse "Genesis 1:5"`
- `python hebrew/hebrew_parser.py --verse "Daniel 8:14"`

### cat-seal-vocabulary-satham-vs-chatham: Seal vocabulary: satham (conceal) vs chatham (authenticate) — direct-label vs contrast-trap

**Candidate categories:** cand-deliberate-concealment-cipher, cand-literary-sealing-convention

**Focus area:** 3

**Direct-label passages:**
- Dan 8:26: setom hechazon (satham, parser-verified Qal.Impv.2ms 'stop up') = the direct concealment label on the vision
- Dan 12:4: satham + chatham on the words 'until the time of the end' — concealment-for-distant-time
- Dan 12:9: 'the words are shut up (satham) and sealed till the time of the end' — confirms satham = temporary concealment

**Structural analogies:**
- Gen 26:15: satham of wells (stopping/blocking access)
- Isa 29:11: sealed book none can read

**Negative controls:**
- Dan 9:24: lachtom chazon wenabi uses chatham (√חתם, parser-verified), a DIFFERENT verb = affix-a-seal / authenticate, NOT satham/conceal

**Required searches:**
- `python hebrew/hebrew_parser.py --verse "Daniel 8:26"`
- `python hebrew/hebrew_parser.py --verse "Daniel 9:24"`
- `python search/search_strongs.py --verses H5640`
- `python search/search_strongs.py --verses H2856`

## Identity Axes

- **What the 2300 'erev boqer count/modify** (required): What is the 2300 counting — full days (one evening-morning = one day, 2300 times), individual sacrifice-events (2300 tamid offerings = 1150 days), or an unanchored symbolic time-unit? What does the single cardinal grammatically scope?
- **Functional identity of 'erev boqer** (required): Does 'erev boqer FUNCTION as a deliberate concealment cipher, a natural tamid-cycle counting unit, a creation-week day-definition allusion, or a combination — and are these mutually exclusive or layered?
- **Documentary/grammatical subtype of the compound** (required): The asyndetic bare singular-noun pair (Noun.ms.Abs + Noun.ms.Abs, no waw, no article, one cardinal): is it uniquely marked (only Dan 8:14; 8:26 articulated-anaphoric)? Does the singular form force 2300 FULL days versus the 1150-days halving reading?
- **Authorial motive (did Daniel choose the term IN ORDER to conceal)** (optional): Is the yamim-to-erev-boqer switch a deliberate act done for the PURPOSE of concealment, or is it accounted for by tamid-context/Genesis-allusion without a concealment motive? Calibrate this load-bearing motive inference to a high bar (rarely explicit; no scholarly precedent).
- **Seal-till-time-of-end economy and the pre-existing decoder** (optional): Does the text present a sealed-until-the-time-of-the-end economy (Dan 8:26; 12:4,9) with a day-for-year decoder already in place (Num 14:34; Ezek 4:6) — i.e., designed to be unreadable when given but decodable later? Distinguish concealment from preservation/authentication.

## Available Library Entries

### Word Studies

- `$WORD_STUDIES/H6153-ereb.md` — 'ereb (evening), H6153
- `$WORD_STUDIES/H1242-boqer.md` — boqer (morning), H1242
- `$WORD_STUDIES/H3117-yowm.md` — yom/yamim (day/days), H3117
- `$WORD_STUDIES/H5640-catham.md` — satham (stop up / shut up / seal), H5640
- `$WORD_STUDIES/H2856-chatham.md` — chatham (affix a seal / authenticate), H2856
- `$WORD_STUDIES/H2852-chathak.md` — chathak (cut off / determine, hapax), H2852
- `$WORD_STUDIES/H8548-tamid.md` — tamid (continual / the daily), H8548
- `$WORD_STUDIES/H4758-mareh.md` — mareh (appearance / vision-sight), H4758
- `$WORD_STUDIES/H4759-marah.md` — marah (vision, fem. variant), H4759
- `$WORD_STUDIES/H2377-chazon.md` — chazon (vision), H2377
- `$WORD_STUDIES/H2384-chizzayon.md` — chizzayon (vision), H2384
- `$WORD_STUDIES/H6663-tsadaq.md` — tsadaq (be just / vindicated), H6663
- `$WORD_STUDIES/H6944-qodesh.md` — qodesh (holiness / sanctuary), H6944
- `$WORD_STUDIES/H6942-qadash.md` — qadash (be holy / consecrate), H6942

### Grammar References

- `$GRAMMAR_REF/hebrew/asyndetic-noun-pair.md` — Asyndetic noun pair — Dan 8:14 'erev boqer as fused counted unit vs Dan 8:26 articulated anaphoric pair
- `$GRAMMAR_REF/hebrew/apocalyptic-time-unit-grammar.md` — Apocalyptic time-unit grammar — counted-unit displacement of yamim; Dan 8:14/8:26/9:24/12:11 signal stack
- `$GRAMMAR_REF/hebrew/day-year-formula.md` — Day-year formula — yom lashanah 1:1 conversion (Num 14:34; Ezek 4:6)
- `$GRAMMAR_REF/hebrew/distributive-lamed-ratio.md` — Distributive lamed ratio — the broader construction behind yom lashanah; operator vs value
- `$GRAMMAR_REF/hebrew/lamed-recipient-vs-destination.md` — Lamed senses — disambiguates the distributive/ratio lamed
- `$GRAMMAR_REF/hebrew/stem-niphal.md` — Niphal stem — nitsdaq (Dan 8:14) and nechtak (Dan 9:24) are both Niphal
- `$GRAMMAR_REF/hebrew/ben-adam-vocative-construct.md` — Ben-adam vocative — Gabriel's address to Daniel (Dan 8:17), the 8-to-9 bridge
- `$GRAMMAR_REF/hebrew/syntax-compound-object-waw.md` — Compound object with waw — Dan 9:24 chazon we-nabi under lachtom; Dan 8:13 qodesh we-tsava
- `$GRAMMAR_REF/hebrew/attributive-apposition-double-article.md` — Double article / apposition — Dan 8:26 ha-'erev we-ha-boqer articulation

### Missing Library Entries (generate)

- H2782 charats (decree / determine) — Daniel's ordinary decree-verb (9:26-27) needed as the contrast to chathak at 9:24; no library entry found
- H8141 shanah (year) — the year term in the day-year decoder (Num 14:34; Ezek 4:6); no library entry found
- Hebrew hapax legomenon (methodology) — how to weigh a once-occurring word's sense (chathak) — no grammar-reference entry on hapax adjudication

### Strong's Numbers

| Strong's | Word | Relevance | Library Entry |
|----------|------|-----------|---------------|
| H6153 | 'ereb (evening) | first member of the crux asyndetic pair at Dan 8:14/8:26; deliberate choice over layil (night) | yes |
| H1242 | boqer (morning) | second member of the crux pair; deliberate choice over shachar (dawn) | yes |
| H3117 | yom / yamim (day/days) | Daniel's DEFAULT time-word and the contrast term; the yamim-vs-erev-boqer switch is the whole tell (Dan 12:11-12 control) | yes |
| H5640 | satham (stop up / shut up / seal) | the concealment verb at Dan 8:26; 12:4,9 — load-bearing for the seal-confirms-intent claim | yes |
| H2856 | chatham (affix a seal / authenticate) | the CONTRAST-TRAP verb at Dan 9:24 — must stay distinct from satham; conflation breaks the argument | yes |
| H2852 | chathak (cut off / determine — hapax) | the strongest-among-several years confirmation at Dan 9:24 (nechtak); parser-verified Hebrew hapax, not Aramaic A2857 | yes |
| H8548 | tamid (continual / the daily) | anchors the tamid-primary candidate; Dan 8:13's question is about the tamid, driving the counting unit | yes |
| H4758 | mareh (appearance / vision-sight) | Dan 8:26 labels the erev boqer element the mareh; the 8-to-9 bridge (9:23) sends Daniel back to the mareh | yes |
| H2377 | chazon (vision) | the broad vision that is sealed (8:26); distinguished from mareh (the time element) | yes |
| H6663 | tsadaq (be just / vindicated) | nitsdaq at Dan 8:14, the only OT Niphal of tsadaq; the terminus event and a marker of deliberate word-choice | yes |
| H2782 | charats (decree / determine) | Daniel's ordinary decree-verb (9:26-27) that was available but NOT chosen at 9:24 — the contrast that makes chathak marked | (missing) |
| H8141 | shanah (year) | the year term in the day-year decoder (Num 14:34; Ezek 4:6, yom lashanah) | (missing) |
| H6944 | qodesh (holiness / sanctuary) | the object of nitsdaq at Dan 8:14 (the sanctuary vindicated) — the terminus | yes |
| H4759 | marah (vision — fem. variant) | related vision-sight vocabulary bearing on the mareh/chazon distinction | yes |
| H2384 | chizzayon (vision) | related vision vocabulary for the genre/sealing analysis | yes |

## Discovered Scope

### Topics Found (from naves_semantic.py)

| Topic | Subtopic | Verse Count |
|-------|----------|-------------|
| DAY | CREATIVE PERIOD + PROPHETIC | 20 |
| DAILY OFFERING | SACRIFICIAL | 8 |
| SEAL | FIGURATIVE — SECRECY / CERTAINTY | 30 |
| SANCTUARY | GENERAL | 11 |
| VISION | MODE OF REVELATION | 40 |
| CREATION | HISTORY OF | 6 |
| BURNT OFFERING | CONTINUAL / DAILY | 12 |
| PROPHECY | SEALED / TIME OF THE END | 25 |
| MESSIAH | SEVENTY WEEKS / CUT OFF | 15 |
| NIGHT | EVENING-MORNING RECKONING | 10 |

### Primary Verses (25 — full analysis required)

**Crux passages:**
_The core texts requiring full verse-by-verse analysis with full chapter context_
- Dan 8:13 — the question posed — about the tamid, the transgression, the sanctuary and host trampled; sets up the 8:14 answer and grounds the tamid-primary candidate
- Dan 8:14 — CRUX — 'unto 2300 erev boqer then the sanctuary shall be nitsdaq'; the asyndetic bare pair, single cardinal, Niphal nitsdaq (all parser-verified)
- Dan 8:26 — CRUX — 'the mareh of the erev boqer is true; shut thou up (satham) the vision, for it shall be for many days (yamim)'; the anaphoric articulated pair + the seal command + yamim-in-same-verse control
- Dan 9:24 — CRUX — 'seventy weeks are nechtak (chathak, hapax) upon thy people'; also lachtom (chatham, the authenticate-verb TRAP); the strongest-among-several years confirmation
- Dan 9:25 — 'from the going forth of the commandment to restore and build Jerusalem' — the shared starting-point anchor the 490 supplies to the 2300

**Negative-control durations (Daniel's yamim):**
_Daniel using days for apocalyptic periods — the tell that 8:14 is marked_
- Dan 12:11 — NEGATIVE CONTROL — 1290 stated as YAMIM (parser-verified) — same book, same genre, apocalyptic period in days; proves 8:14's switch is marked
- Dan 12:12 — NEGATIVE CONTROL — 1335 YAMIM; second in-book apocalyptic duration using the normal word

**Day-for-year decoder precedents:**
_The pre-existing conversion key_
- Num 14:34 — CRUX PRECEDENT — 'yom lashanah yom lashanah' (reduplicated distributive lamed, parser-verified) — the day-for-year decoder, first witness
- Ezek 4:4-5 — the 390/40-day sign-act context giving the 'each day for a year' its setting
- Ezek 4:6 — CRUX PRECEDENT — 'yom lashanah' (parser-verified) — the day-for-year decoder, second witness (two-witness principle)

**Genesis creation-day refrain:**
_The evening-first day-definition source_
- Gen 1:5 — creation-day refrain 'evening...morning...one day' (parser-verified evening-first order + yom) — the day-definition allusion source
- Gen 1:8 — creation-day refrain day two — establishes the fixed evening-morning formula
- Gen 1:31 — creation-day refrain day six — completes the six-day evening-morning pattern

**Tamid / daily offering:**
_The tamid subject and its morning-first order_
- Ex 29:38-42 — the tamid daily offering — MORNING then evening order; grounds tamid-primary candidate and the order-difference datum
- Num 28:3-8 — tamid restated as one continual offering ('olat tamid, singular) — bears on 2300-full-days vs 1150-halving
- Dan 8:11 — the tamid 'taken away' (Hophal huram) — establishes ha-tamid as the vision's subject feeding 8:13's question
- Dan 8:12 — host given against the tamid; truth cast down — the trampling the 2300 answers, feeding 8:13's 'how long' question

**Sealing economy and reversal:**
_satham/chatham, time-of-the-end, and the Rev 22:10 inversion_
- Dan 12:4 — 'shut up (satham) the words and seal (chatham) the book to the time of the end; knowledge shall be increased' — satham/chatham distinction + unsealing horizon
- Dan 12:9 — 'the words are closed up (satham) and sealed (chatham) till the time of the end' — confirms satham = temporary concealment, chatham alongside
- Isa 29:11 — the sealed book none can read — seal-on-prophecy motif PREDATES Daniel; tests genuine-concealment vs genre-convention
- Rev 22:10 — 'Seal NOT the sayings of the prophecy of this book, for the time is at hand' — canonical inversion of Dan 12:4; sealing = withholding until due time

**Additional Primary Verses:**
- Dan 8:17 — 'at the time of the end shall be the vision' (chazon); Gabriel's 'understand, son of man' — the end-time horizon of the sealed vision
- Dan 8:19 — 'at the time appointed the end shall be' — reinforces the distant-fulfillment frame that motivates sealing
- Dan 9:23 — 'understand the matter and consider the mareh' — the 8-to-9 bridge sending Daniel back to the unexplained time element of ch. 8
- Dan 9:26-27 — Messiah 'cut off' (karath) after 69 weeks; charats (Daniel's ordinary decree-verb) used here — contrast with the deliberately-chosen hapax chathak in 9:24

### Supporting Verses (17 — retrieve for context, no individual analysis)

- Gen 1:13 — creation-day refrain day three
- Gen 1:19 — creation-day refrain day four
- Gen 1:23 — creation-day refrain day five
- Isa 8:16 — 'bind up the testimony, seal (chatham) the law among my disciples' — sealing = entrust to the faithful; tests the concealment-vs-preservation spread
- Jer 32:10-14 — sealed deed preserved for the future — sealing as preservation/authentication, the counter-reading to pure concealment
- Gen 26:15 — Philistines satham (stopped up) the wells — base sense of satham = block access; grounds the concealment meaning
- Amos 3:7 — 'the Lord revealeth his secret to his servants the prophets' — advance-planning frame supporting sealed-then-decodable design
- Hab 2:2-3 — 'write the vision... for the vision is yet for an appointed time... it will surely come' — sealed-for-appointed-time frame
- Dan 12:7 — 'time, times, and a half' — apocalyptic time-unit given non-standard (moed) — parallel to the erev-boqer displacement of yamim
- Dan 7:25 — 'time and times and the dividing of time' (Aramaic iddan) — non-standard apocalyptic counter, corroborating the displaced-unit pattern
- 2 Pet 3:8 — 'one day is with the Lord as a thousand years' — often cited on prophetic time; test whether it grounds day-year or is unrelated
- Num 12:6 — God speaks to prophets in vision (mareh/chazon distinction background) — informs the mareh vs chazon vocabulary bridging 8:26 and 9:23
- Lev 23:32 — Day of Atonement 'evening to evening' — has NO morning; shows Dan 8:14 does NOT match the DoA reckoning (rules out one alternative)
- Dan 1:5 — 'three years' nourishment — Daniel's ordinary duration language (audit negative-control that he names durations in normal units)
- Dan 1:12 — 'ten days' (yamim) test proposal — Daniel's plain yamim usage
- Dan 1:14-15 — 'ten days' fulfilled — Daniel's ordinary yamim counting
- Dan 10:2-3 — 'three full weeks' mourning duration in ordinary units — Daniel's default time language, audit control

### Focus Areas

1. **The yamim-vs-erev-boqer switch and the Dan 12:11-12 negative control:**
This is the decisive first link. READ the grammar entries $GRAMMAR_REF/hebrew/asyndetic-noun-pair.md (documents Dan 8:14 'erev boqer as Noun.ms.Abs + Noun.ms.Abs, no waw, one cardinal scoping the pair, versus Dan 8:26 ha-'erev we-ha-boqer articulated + waw = anaphoric reference) and $GRAMMAR_REF/hebrew/apocalyptic-time-unit-grammar.md (documents the three-register signal stack: counted-unit displacement, asyndetic anarthrous juxtaposition, sealing + 'et qets co-text; and explicitly notes Dan 12:11 DOES use yamim while remaining flagged, and Dan 8:26 le-yamim rabbim shows Daniel CAN use yamim in the same vision-complex so the 8:14 avoidance is deliberate). Run hebrew_parser.py --verse on Daniel 8:14, 12:11, 12:12, and 8:26. The parser (already run in scoping) confirms: 8:14 = 'ereb boqer both ms.Abs asyndetic; 12:11 = yamim 'eleph mathayim wetish'im (1290 days); 8:26 = le-yamim rabbim (yamim in the sealing verse). Establish the negative control: Daniel HAD and USED yamim for apocalyptic durations (12:11-12) and in the very sealing verse (8:26), so the switch at 8:14 is not vocabulary-poverty. THEN reconcile with the competing tamid-primary candidate (focus area 4): even a marked switch could be explained by counting-in-kind rather than concealment. Keep both 'obscure-by-design' and 'natural-to-topic' live; do not let deliberateness alone prove concealment-motive. Read $WORD_STUDIES/H3117-yowm.md and $WORD_STUDIES/H6153-ereb.md and $WORD_STUDIES/H1242-boqer.md.
**Verses:** Dan 8:14, Dan 8:26, Dan 12:11, Dan 12:12, Dan 1:12, Dan 10:2-3
**Strong's:** H6153, H1242, H3117

2. **The Genesis-1 creation-week allusion and the evening-first order test:**
READ $GRAMMAR_REF/hebrew/asyndetic-noun-pair.md again for the Dan 8:14 vs Gen 1 contrast. Run hebrew_parser.py --verse on Genesis 1:5, 1:8, 1:31 (scoping confirmed Gen 1:5 = 'ereb ... boqer ... yom, evening-first, each joined with waw wayehi). The key ANALYTICAL move: Gen 1 order is evening-then-morning (matching Dan 8:14) whereas the sanctuary tamid is morning-then-evening (Ex 29:39; Num 28:4) — so the ORDER supports a creation/day-definition source over a strict sanctuary-service source. BUT the negative control is real: Genesis joins the two nouns with waw and pairs them with yom ('one day'); Dan 8:14 is bare asyndetic with NO yom. So Dan 8:14 is NOT a verbatim Genesis copy — the allusion supplies availability and the full-day (not half-day) definition, but the compressed marked form is Daniel's own. CONCLUDE: the Genesis echo is supporting corroboration for the FULL-day reading (candidate cand-genesis-allusion-driven and against 1150-halving), but it can FAIL as proof of a concealment cipher. Do not conflate 'alludes to Genesis' with 'encodes a concealed year-count.' Verify Bohr's lead (GPOT2V1 L#14: 'This precise order of evening and morning is in Genesis one') against Gen 1 directly — as a lead, not authority.
**Verses:** Gen 1:5, Gen 1:8, Gen 1:31, Dan 8:14, Ex 29:38-42, Num 28:3-8
**Strong's:** H6153, H1242, H3117

3. **satham (conceal) vs chatham (authenticate) — the seal-verb distinction and the Dan 9:24 trap:**
READ $WORD_STUDIES/H5640-catham.md (satham) and $WORD_STUDIES/H2856-chatham.md (chatham) — the library has BOTH. Run hebrew_parser.py --verse on Daniel 8:26, 9:24, 12:4, 12:9. Scoping confirmed: Dan 8:26 setom hechazon = satham √סתם 'stop up' (Qal.Impv.2ms); Dan 9:24 lachtom chazon wenabi = chatham √חתם 'affix seal.' Establish satham's base meaning from Gen 26:15 (Philistines satham/stopped the wells = block access to content). Establish that satham in Dan 8:26; 12:4; 12:9 = concealment temporary 'for many days'/'till the time of the end,' explicitly reversible (Rev 22:10 'seal NOT'; Dan 12:4 'knowledge shall be increased'). THEN the trap: Dan 9:24's chatham 'seal up vision and prophecy' occurs in a list of six positive accomplishments (finish transgression, make an end of sins, make reconciliation, bring in everlasting righteousness, seal up vision and prophecy, anoint the most holy) — the sense is AUTHENTICATE/certify by fulfillment, NOT conceal. Do NOT cite Dan 9:24 as concealment evidence. Compare Isa 29:11 (sealed book none can read) and Jer 32:10-14 (sealed deed preserved) to test whether Dan 8:26 sealing is concealment, preservation, or authentication — argue the concealment reading from satham's own usage while representing the preservation/genre-convention counter (candidate cand-literary-sealing-convention) fairly. Read $GRAMMAR_REF/hebrew/apocalyptic-time-unit-grammar.md for the sealing co-text (satom/chatom).
**Verses:** Dan 8:26, Dan 9:24, Dan 12:4, Dan 12:9, Gen 26:15, Isa 29:11, Jer 32:10-14, Rev 22:10
**Strong's:** H5640, H2856

4. **The tamid-primary candidate — is erev boqer natural-to-topic rather than obscure-by-design?:**
READ $WORD_STUDIES/H8548-tamid.md. Run hebrew_parser.py --verse on Daniel 8:11, 8:12, 8:13 (scoping confirmed 8:13 has tamid Noun.ms.Abs and the qodesh/tsava trampling). Dan 8:13's question is literally 'how long the vision concerning the tamid...?' — the tamid is an evening+morning service (Ex 29:38-42, morning + evening), so a candidate reading is that the ANSWER counts in the tamid's own evening-morning units ('the measurement unit mirrors the thing measured'). Test this from the text. The COUNTER-datum: the sanctuary tamid runs morning-THEN-evening (Ex 29:39; Num 28:4), but Dan 8:14 runs evening-THEN-morning — matching Genesis (focus area 2), NOT the tamid service order. So a pure tamid-order derivation is complicated. Also weigh the singular-summation 'olat tamid (Num 28:3-8; the two daily offerings counted as ONE continual offering) against the 1150-halving reading (focus area 6). CONCLUDE by keeping cand-tamid-primary-natural live and reconciling: the tamid supplies the TOPIC and availability, Genesis supplies the ORDER and full-day definition, and concealment (if established) is a further layer — these are not mutually exclusive, but the thesis may not claim concealment as the sole reason. This is the required reconciliation the custom instructions demand.
**Verses:** Dan 8:11, Dan 8:12, Dan 8:13, Ex 29:38-42, Num 28:3-8, Dan 12:11
**Strong's:** H8548

5. **The pre-existing day-for-year decoder in Num 14:34 and Ezek 4:6 (grounded there, NOT in Dan 8):**
READ $GRAMMAR_REF/hebrew/day-year-formula.md and $GRAMMAR_REF/hebrew/distributive-lamed-ratio.md and $GRAMMAR_REF/hebrew/lamed-recipient-vs-destination.md. Run hebrew_parser.py --verse on Numbers 14:34 and Ezekiel 4:6 (scoping confirmed Num 14:34 = yom lashanah yom lashanah reduplicated; Ezek 4:6 = yom lashanah). The grammar entry establishes that the distributive lamed + definite shanah supplies the 'per/for-each' operator while the numerical apposition supplies the 1:1 VALUE, and reduplication marks fixity/decree. CRITICAL BOUNDARY (per custom instructions and prior study day-for-year-principle-grounding): the ratio-formula lives ONLY at Num 14:34 + Ezek 4:6 — Dan 8 is the first major APPLICATION site, NOT the hermeneutical generator; 'a reader with only Dan 8 could know the unit is symbolic but could not derive the conversion factor.' State this precisely: the decoder PRE-EXISTED, which is exactly what the encoding claim needs. Address the two-witness principle (Deut 19:15) — the ratio appears in two independent texts. Represent the critical counter fairly: many scholars hold these are self-contained applications, not a general rule. The distributive-lamed-ratio entry notes the grammar is broadly productive (e.g. 2:1 in Num 28:3) so the 1:1 value is contextual, not grammatically forced — acknowledge this. Do NOT slide into 'the day-year principle is grounded in Dan 8.'
**Verses:** Num 14:34, Ezek 4:6, Ezek 4:4-5, Dan 8:14, 2 Pet 3:8
**Strong's:** H3117, H8141

6. **2300 full days vs 1150 (the halving reading) — the singular-noun and single-cardinal test:**
READ $GRAMMAR_REF/hebrew/asyndetic-noun-pair.md (function 1: compound unit fusing two nouns into a single counted concept, one cardinal scoping the pair). Run hebrew_parser.py --verse on Daniel 8:14 and 8:26. The grammar shows: at 8:14 one cardinal ('alpayim ushlosh me'oth, 2300) scopes the FUSED asyndetic singular pair as a single unit — supporting one evening-morning = one full day counted 2300 times (2300 full days). At 8:26 the anaphoric ha-'erev we-ha-boqer with singular hu ('it is true') treats the time element as ONE unit, arguing against splitting into 2300 separate half-day sacrifices. Weigh the 'olat tamid singular summation (Num 28:3-8; the morning+evening daily counted as one continual offering) which undercuts the sacrifice-count basis for dividing by two. Represent the 1150-halving reading (Collins, Goldingay, ABR/Lanser; ~1095 actual Maccabean days) fairly as the dominant academic position and note the ancient Greek versions' (Septuagint and Theodotion) 'days' rendering (Bohr GPOT2V1 L#14 lead) as corroboration for full-days — verify against the Hebrew, do not cite as authority. CONCLUDE whether the grammar makes full-days the stronger reading and calibrate honestly. Cross-check with Lev 23:32 (DoA is evening-to-evening, NO morning — Dan 8:14 does not match DoA reckoning either).
**Verses:** Dan 8:14, Dan 8:26, Num 28:3-8, Lev 23:32
**Strong's:** H6153, H1242, H505

7. **Dan 9 chathak as the STRONGEST confirmation of years — among several, not the sole proof:**
READ $WORD_STUDIES/H2852-chathak.md (scoping parser-verified Dan 9:24 nechtak, lemma חתך, Niphal.Perf.3ms 'be determined' — this IS H2852, the Hebrew hapax, NOT the Aramaic A2857 chatham). Run hebrew_parser.py --verse on Daniel 9:24, 9:25, 9:26, and 8:26. The argument: chathak is a Hebrew-Bible hapax whose root sense is 'cut off/sever a portion'; Daniel had charats (H2782, his ordinary decree-verb, used at 9:26-27) available and chose the hapax instead — arguably 'cut off FROM' the only adjacent parent period, the 2300 of 8:14, making the 490 a subset sharing the 2300's start (9:25 'the going forth of the commandment'). READ $WORD_STUDIES/H4758-mareh.md and $WORD_STUDIES/H2377-chazon.md for the mareh (time element, 8:26) vs chazon (broad vision) distinction and the 8:26->9:23 bridge (Gabriel returns to make Daniel 'understand the mareh'). CRITICAL CALIBRATION (per custom instructions): frame chathak as the STRONGEST confirmation ALONGSIDE (a) the Num/Ezek day-year ratio (focus 5), (b) apocalyptic genre displacing yamim (focus 1), and (c) the sheer scope-demand (2300 literal days ~6.3 years does not reach 'the time of the end'). Do NOT claim Dan 9 is the sole proof of years. Represent the critical counter fairly: 'cut off FROM the 2300' is a historicist inference, not a lexical necessity (chathak can mean simply 'decree/determine'); flag this as the most contestable load-bearing link. Calibrate the parent-2300-equals-years to MEDIUM-HIGH.
**Verses:** Dan 9:24, Dan 9:25, Dan 9:26-27, Dan 8:26, Dan 9:23
**Strong's:** H2852, H2782, H4758, H2377

8. **The concealment TARGET — the WHEN (unanchored 2300) vs the unit-ambiguity (days/years) as designed:**
Synthesize the prior focus areas. From Dan 8:14 note the 2300 has NO stated starting point — the 'how long from when?' is left open, and 8:26 seals precisely the mareh/time element 'for many days.' Test framing (a): the sealed content = the WHEN (the missing anchor), which Dan 9:25's decree-date later supplies. Test framing (b) — the study's sharpened claim: the choice of the ambiguous 'erev boqer (readable as either 2300 half-days/1150 or 2300 full-days, and, via the pre-existing Num/Ezek decoder, as 2300 years) means the days-vs-years UNIT is itself deliberately ambiguous, resolvable only by combining the decoder (focus 5) with the Dan 9 anchor (focus 7). Argue this from the text; do NOT assume it defeats framing (a). Weigh whether the text supports a DESIGNED unit-ambiguity or whether the ambiguity is a later interpreter's artifact (the critical counter, cand-literary-sealing-convention). Verify the EGW/Bohr leads (sealed = the last-days/time portion of Daniel; 'designed to be unreadable when given but unmistakable when fulfilled') against Dan 8:26 + 12:4,9 directly — as leads pointing to the text, not as authority. Distinguish the concealment-to-hide half from the preservation/authentication half so the framing is not one-sidedly cipher-to-hide (Isa 8:16; Jer 32; Amos 3:7; Hab 2:2-3).
**Verses:** Dan 8:14, Dan 8:26, Dan 9:25, Dan 12:4, Dan 12:9, Isa 8:16, Hab 2:2-3
**Strong's:** H5640, H4758, H2377

9. **Authorial-intent / motive calibration — did Daniel choose the term IN ORDER to conceal?:**
This is the honesty-gate focus area. Distinguish three claim-levels sharply: (1) TEXT-STATED — Gabriel commands 'shut up (satham) the vision' (8:26), the vision is 'for many days' / 'to the time of the end' (8:26; 12:4,9), and 'erev boqer is a marked, grammatically unique construction (focus 1). (2) STRONG INFERENCE — the word-choice is deliberate (Daniel had yamim and used it elsewhere). (3) AGGRESSIVE INFERENCE — Daniel chose 'erev boqer IN ORDER TO conceal, consciously anticipating a future decoder. Level 3 is the load-bearing motive claim. Weigh whether the sealing COMMAND (divine, Gabriel-issued) supplies the concealment purpose that the human writer merely obeys — in which case the 'design' is divine, and 'Daniel's own motive' is a weaker, separable claim. Note the web-research finding: NO mainstream scholar (SDA or critical) argues Daniel consciously cipher-encoded the number; SDA scholars frame it as prophetic/divine design, and the critical camp reads sealing as genre convention. Therefore calibrate the authorial-motive link explicitly — likely MEDIUM at best for conscious-authorial-cipher, higher for divine-design-obeyed. State it as calibrated inference, never as something the text says. Do not use loaded/system vocabulary; quote KJV verbatim with Hebrew notes.
**Verses:** Dan 8:26, Dan 12:4, Dan 12:9, Dan 8:14, Dan 9:24
**Strong's:** H5640, H6153, H1242

10. **The mareh/chazon vision vocabulary and the Daniel 8-to-9 bridge:**
READ $WORD_STUDIES/H4758-mareh.md and $WORD_STUDIES/H2377-chazon.md. Run hebrew_parser.py --verse on Daniel 8:26, 9:23, 8:13, 8:15, 8:17. Establish that Dan 8:26 specifically calls the erev boqer element the mareh ('the mareh of the evening and the morning ... is true'), while chazon is the broader vision that Gabriel seals. The bridge: Dan 8:26 seals the mareh 'for many days'; Dan 8:27 Daniel 'was astonished at the mareh but none understood it'; Dan 9:23 Gabriel returns and says 'understand the matter, and consider the mareh' — sending Daniel back to the ONE unexplained element of ch. 8, the time period. READ $GRAMMAR_REF/hebrew/ben-adam-vocative-construct.md (documents Gabriel's 'haben ben-adam' vocative address at Dan 8:17, the parallel to the angelic address in ch. 9). Verify the hist-05 lead (biyn/understanding chain 8:16->9:23) from the text. This focus area supplies the linguistic warrant that Dan 9 continues Dan 8's explanation — the precondition for chathak confirming the 2300 as years.
**Verses:** Dan 8:26, Dan 9:23, Dan 8:13, Dan 8:15, Dan 8:17, Dan 8:27
**Strong's:** H4758, H2377, H4759, H2384

11. **nitsdaq — the terminus event (the sanctuary vindicated/justified) and its non-sealed status:**
READ $GRAMMAR_REF/hebrew/stem-niphal.md and $WORD_STUDIES/H6663-tsadaq.md (and $WORD_STUDIES/H6942-qadash.md / $WORD_STUDIES/H6944-qodesh.md for the qodesh object). Run hebrew_parser.py --verse on Daniel 8:14 (scoping confirmed we-nitsdaq qodesh = Niphal.Perf.3ms of tsadaq 'be just/vindicated' + qodesh 'holiness/sanctuary'). Note that nitsdaq is the only Niphal of tsadaq in the OT — a forensic/declarative sense ('be set right/vindicated'), and Daniel chose tsadaq over the expected sanctuary-verbs taher (cleanse) or kaphar (atone), fitting his broader pattern of deliberate, theologically-loaded word choices (supports authorial deliberateness generally, focus 1/9). ANALYTICAL point for the concealment target: the terminus EVENT (the sanctuary vindicated) is stated openly and is the resolution any reader anticipates — it is NOT the sealed element. What is sealed (satham, 8:26) is the mareh/time element (the WHEN), per focus 8. This distinction sharpens the concealment-target analysis: concealment operates on the timing, not the outcome. Keep the identification of the terminus event within textual bounds; do not import sanctuary-theology conclusions as premises.
**Verses:** Dan 8:14, Dan 8:13, Dan 9:24
**Strong's:** H6663, H6944, H6942

12. **The sealed-until-time-of-end economy and its reversal (why unreadable when given, decodable later):**
Run hebrew_parser.py --verse on Daniel 12:4 and 12:9. Establish the sealing is EXPLICITLY temporary and end-referenced: 'shut up (satham) the words, and seal (chatham) the book, even to the time of the end ... knowledge shall be increased' (12:4); 'the words are closed up and sealed till the time of the end' (12:9). The reversal is canonical: Rev 22:10 'Seal NOT the sayings ... for the time is at hand' — the deliberate NT inversion of Dan 12:4, confirming sealing = withholding until due time, not permanent concealment. This supports the 'unreadable when given, decodable later' half of the thesis (verify the Bohr KSBI lead about Josephus/Antiochus interpreters failing because they did not live in the time of the end — against Dan 12:4,9-10, as a lead). BALANCE: also weigh the preservation/authentication/entrust-to-the-faithful purposes (Isa 8:16 seal the law among disciples; Jer 32 sealed deed preserved; Amos 3:7 God reveals to his servants; Hab 2:2-3 vision for an appointed time). Conclude what the sealing FUNCTION is from the full spread, not one purpose. Distinguish satham (12:4a,9a conceal) from chatham (12:4b,9b authenticate/secure) even where they appear together (focus 3).
**Verses:** Dan 12:4, Dan 12:9, Rev 22:10, Isa 8:16, Amos 3:7, Hab 2:2-3
**Strong's:** H5640, H2856

### External Corpus Leads (from 00-references.md)

1. **'erev boqer is a deliberately encoded counting unit, the visible fingerprint of the sealing act; the sealing command supplies the motive; already a PUBLISHED conclusion** (Source: sv-10 / sv-11 (prior study))
   - **Verify:** TEST the chain defeasibly from Scripture — do NOT inherit as premise; this standalone study must rederive the switch, the seal, and the ratio from the text
2. **PRIMARY explanation is the tamid connection (answer counts in the tamid's own units), NOT encoding; word-order matches Genesis not the tamid service** (Source: dan-8-14-evening-mornings (prior study))
   - **Verify:** verify against Dan 8:13 + Ex 29:38-42 + Gen 1:5; keep tamid-primary and Genesis-allusion candidates live (focus 2, 4)
3. **the 1:1 ratio-formula lives ONLY at Num 14:34 + Ezek 4:6; Dan 8 is the application site, not the generator; satham (8:26) is load-bearingly distinct from chatham (9:24)** (Source: day-for-year-principle-grounding (prior study))
   - **Verify:** verify from Num 14:34 + Ezek 4:6 directly (focus 5); keep the seal-verb distinction (focus 3); do NOT ground day-year in Dan 8
4. **satham = block access (well-stopping); chatham (9:24) = authentication; sealing is temporary (preserve/entrust); Dan 9:24 as concealment would contradict the data** (Source: daniel-seal-unseal-visions (prior study))
   - **Verify:** verify satham base sense via Gen 26:15; verify chatham=authenticate at 9:24; treat as the TRAP (focus 3, 12)
5. **Dan 8:14 evening-morning order matches Genesis 1; both nouns singular = one unit; LXX/Theodotion read 2300 whole day-units (rules out 1150)** (Source: Bohr (Secrets Unsealed))
   - **Verify:** verify vs Gen 1:5 + hebrew_parser on Dan 8:14 + 8:26 singular; use as lead only (focus 2, 6)
6. **earlier interpreters (Josephus/Antiochus) could not decode the little-horn/time prophecy because they did not live in the time of the end** (Source: Bohr (Secrets Unsealed, KSBI L#1))
   - **Verify:** verify vs Dan 12:4,9-10 + Rev 22:10; balance concealment-half against preservation/authentication-half (focus 12)
7. **the sealed book = the portion of Daniel's prophecy relating to the last days** (Source: EGW (1MR 43.3 / 2SM 105.1))
   - **Verify:** verify vs Dan 8:26 + 12:4,9 directly; EGW is a lead to primary sources, NOT a historical/doctrinal authority (focus 8, 12)
8. **'erev boqer counts 2300 tamid half-day sacrifices = 1150 days, terminating with Antiochus IV; year-day rejected as a general rule; sealing = literary/pseudonymity convention** (Source: Collins / Goldingay / Montgomery / ABR-Lanser (critical + conservative))
   - **Verify:** represent fairly as the dominant academic reading; test the 1150-halving from grammar (focus 6) and the genre-convention counter (focus 3, 8, 9) — this is the critical counter that must be able to win

### Structural Constraints (from prior studies — verify and account for)

1. **Daniel uses yamim (H3117) for apocalyptic time periods within the same book and genre — 1290 yamim (Dan 12:11) and 1335 yamim (Dan 12:12), and 'many days' (leyamim rabbim) in the sealing verse itself (Dan 8:26) — all parser-verified.**
   - Established by: daniel-8-14 text (parser-verified in scoping)
   - Directive: verify_and_account_for
   - Implication: This is a text-level fact the study must account for from the passage: Daniel had and used yamim for apocalyptic durations, so the switch to 'erev boqer at 8:14 is grammatically marked, not vocabulary-forced. It supports (but does not alone prove) a deliberate word-choice; the concealment MOTIVE remains a separate calibrated inference.
2. **Dan 8:26 uses satham (H5640, 'stop up') on the vision, while Dan 9:24 uses chatham (H2856, 'affix a seal') — two DIFFERENT verbs, parser-verified from the lemmas (סתם vs חתם).**
   - Established by: daniel-8-14 / daniel-9 text (parser-verified in scoping)
   - Directive: verify_and_account_for
   - Implication: The study must keep the two seal-verbs distinct and derive each meaning from its own usage. Dan 9:24 sealing (chatham) must NOT be cited as concealment evidence; only satham (8:26; 12:4,9) supports the concealment reading.
3. **The day-for-year 1:1 ratio formula (yom lashanah) is stated at Num 14:34 and Ezek 4:6 — outside Daniel 8 — parser-verified as the reduplicated distributive-lamed construction.**
   - Established by: numbers-14 / ezekiel-4 text (parser-verified in scoping)
   - Directive: verify_and_account_for
   - Implication: The decoder pre-exists in Torah/Prophets; Daniel 8 is the application site, not the generator. The encoding claim depends on this pre-existence and must state it precisely; the study must NOT ground the day-year principle in Daniel 8 itself.

## Research Instructions

You are the Research Agent. Execute this study by:

1. Read the SKILL.md for full tool documentation and principles
2. Read your agent instructions at `agents/research-agent.md`
3. **Read ALL library entries listed in "Available Library Entries" above**
4. Follow the workflow from the skill
5. Write research files to this folder:
   - `01-topics.md` — Nave's topics and full entries (retrieve full entries for: DAY, DAILY OFFERING, SEAL, SANCTUARY, VISION, CREATION, BURNT OFFERING, PROPHECY, MESSIAH, NIGHT)
   - `02-verses.md` — All verse texts retrieved with context for:
     - **Crux passages** (Dan 8:13, Dan 8:14, Dan 8:26, Dan 9:24, Dan 9:25) — retrieve with FULL chapter context
     - **Negative-control durations (Daniel's yamim)** (Dan 12:11, Dan 12:12) — retrieve with FULL chapter context
     - **Day-for-year decoder precedents** (Num 14:34, Ezek 4:4-5, Ezek 4:6) — retrieve with FULL chapter context
     - **Genesis creation-day refrain** (Gen 1:5, Gen 1:8, Gen 1:31) — retrieve with FULL chapter context
     - **Tamid / daily offering** (Ex 29:38-42, Num 28:3-8, Dan 8:11, Dan 8:12) — retrieve with FULL chapter context
     - **Sealing economy and reversal** (Dan 12:4, Dan 12:9, Isa 29:11, Isa 8:16, Jer 32:10-14...)
     - **All additional verses from Nave's topic entries**
   - `04-word-studies.md` — Strong's research:
     - **FROM LIBRARY (read, don't re-derive):** H6153 ('ereb (evening)), H1242 (boqer (morning)), H3117 (yom / yamim (day/days)), H5640 (satham (stop up / shut up / seal)), H2856 (chatham (affix a seal / authenticate)), H2852 (chathak (cut off / determine — hapax)), H8548 (tamid (continual / the daily)), H4758 (mareh (appearance / vision-sight)), H2377 (chazon (vision)), H6663 (tsadaq (be just / vindicated)), H6944 (qodesh (holiness / sanctuary)), H4759 (marah (vision — fem. variant)), H2384 (chizzayon (vision))
     - **FRESH LOOKUPS (no library entry):** H2782 (charats (decree / determine)), H8141 (shanah (year))
   - `raw-data/` — Raw tool output organized by category
6. Do NOT write `03-analysis.md` or `CONCLUSION.md` — those are for the analysis agent

### Specific Research Directives

7. **Priority verses to retrieve with FULL CHAPTER context:**
   - Dan 8:1-27
   - Dan 9:20-27
   - Dan 12:1-13
   - Gen 1:1-2:3
   - Num 14:26-38
   - Ezek 4:1-8
   - Ex 29:38-46
   - Num 28:1-8

8. **Required Greek/Hebrew parsing:**
   - Dan 8:14 — confirm 'ereb + boqer both Noun.ms.Abs, asyndetic (no waw), no article; single cardinal 2300 scoping the pair; nitsdaq Niphal.Perf.3ms — CRUX morphology (already scoping-verified; re-run for research record)
   - Dan 8:26 — confirm ha-'erev we-ha-boqer articulated + waw (anaphoric, contrast with 8:14); satham Qal.Impv.2ms; le-yamim rabbim (yamim in the sealing verse); mareh Cst
   - Dan 9:24 — confirm nechtak Niphal.Perf.3ms lemma חתך = H2852 hapax; and lachtom = chatham √חתם (the authenticate trap); shavu'im shiv'im pair
   - Dan 12:11 — confirm yamim (Noun.mp.Abs) with 1290 — the negative control that Daniel uses days for apocalyptic periods
   - Dan 12:12 — confirm 1335 yamim — second negative control
   - Num 14:34 — confirm yom lashanah yom lashanah reduplicated distributive lamed — the day-year decoder witness 1
   - Ezek 4:6 — confirm yom lashanah — the day-year decoder witness 2
   - Gen 1:5 — confirm wayehi 'erev wayehi boqer yom — evening-first order, each joined with waw, paired with yom (contrast with bare asyndetic Dan 8:14)
   - Dan 8:13 — confirm ha-tamid as the question's subject; qodesh we-tsava trampled — grounds the tamid-primary candidate
   - Dan 12:4 — confirm satham + chatham together with 'time of the end' — the seal-verb distinction and unsealing horizon
   - Dan 9:26-27 — confirm charats used here (Daniel's ordinary decree-verb) — the contrast that makes chathak's choice at 9:24 marked

9. **Required cross-testament parallels** (run BOTH --hybrid-ot AND --hybrid-nt):
   - Dan 8:14 — OT parallels for the erev-boqer time unit and the nitsdaq terminus
   - Dan 8:26 — OT parallels for sealing a vision until many days (Isa 29:11; Isa 8:16; Jer 32; Hab 2:2-3)
   - Num 14:34 — parallels for the day-for-year formula (Ezek 4:6) and its portability
   - Dan 9:24 — parallels for the seventy-weeks and the cut-off vocabulary bridging to Dan 8
   - Gen 1:5 — parallels for the evening-morning creation refrain across the six days

10. **Required word traces:**
   - H2782 (charats (decree / determine)) — run search_strongs.py --lookup and --verses
   - H8141 (shanah (year)) — run search_strongs.py --lookup and --verses

11. **External corpus verification directives:**
   - 'erev boqer is a deliberately encoded counting unit, the visible fingerprint of the sealing act; the sealing command supplies the motive; already a PUBLISHED conclusion (sv-10 / sv-11 (prior study)) — TEST the chain defeasibly from Scripture — do NOT inherit as premise; this standalone study must rederive the switch, the seal, and the ratio from the text
   - PRIMARY explanation is the tamid connection (answer counts in the tamid's own units), NOT encoding; word-order matches Genesis not the tamid service (dan-8-14-evening-mornings (prior study)) — verify against Dan 8:13 + Ex 29:38-42 + Gen 1:5; keep tamid-primary and Genesis-allusion candidates live (focus 2, 4)
   - the 1:1 ratio-formula lives ONLY at Num 14:34 + Ezek 4:6; Dan 8 is the application site, not the generator; satham (8:26) is load-bearingly distinct from chatham (9:24) (day-for-year-principle-grounding (prior study)) — verify from Num 14:34 + Ezek 4:6 directly (focus 5); keep the seal-verb distinction (focus 3); do NOT ground day-year in Dan 8
   - satham = block access (well-stopping); chatham (9:24) = authentication; sealing is temporary (preserve/entrust); Dan 9:24 as concealment would contradict the data (daniel-seal-unseal-visions (prior study)) — verify satham base sense via Gen 26:15; verify chatham=authenticate at 9:24; treat as the TRAP (focus 3, 12)
   - Dan 8:14 evening-morning order matches Genesis 1; both nouns singular = one unit; LXX/Theodotion read 2300 whole day-units (rules out 1150) (Bohr (Secrets Unsealed)) — verify vs Gen 1:5 + hebrew_parser on Dan 8:14 + 8:26 singular; use as lead only (focus 2, 6)
   - earlier interpreters (Josephus/Antiochus) could not decode the little-horn/time prophecy because they did not live in the time of the end (Bohr (Secrets Unsealed, KSBI L#1)) — verify vs Dan 12:4,9-10 + Rev 22:10; balance concealment-half against preservation/authentication-half (focus 12)
   - the sealed book = the portion of Daniel's prophecy relating to the last days (EGW (1MR 43.3 / 2SM 105.1)) — verify vs Dan 8:26 + 12:4,9 directly; EGW is a lead to primary sources, NOT a historical/doctrinal authority (focus 8, 12)
   - 'erev boqer counts 2300 tamid half-day sacrifices = 1150 days, terminating with Antiochus IV; year-day rejected as a general rule; sealing = literary/pseudonymity convention (Collins / Goldingay / Montgomery / ABR-Lanser (critical + conservative)) — represent fairly as the dominant academic reading; test the 1150-halving from grammar (focus 6) and the genre-convention counter (focus 3, 8, 9) — this is the critical counter that must be able to win

12. **Grammar reference entries to read:**
   - `$GRAMMAR_REF/hebrew/asyndetic-noun-pair.md` — Asyndetic noun pair — Dan 8:14 'erev boqer as fused counted unit vs Dan 8:26 articulated anaphoric pair
   - `$GRAMMAR_REF/hebrew/apocalyptic-time-unit-grammar.md` — Apocalyptic time-unit grammar — counted-unit displacement of yamim; Dan 8:14/8:26/9:24/12:11 signal stack
   - `$GRAMMAR_REF/hebrew/day-year-formula.md` — Day-year formula — yom lashanah 1:1 conversion (Num 14:34; Ezek 4:6)
   - `$GRAMMAR_REF/hebrew/distributive-lamed-ratio.md` — Distributive lamed ratio — the broader construction behind yom lashanah; operator vs value
   - `$GRAMMAR_REF/hebrew/lamed-recipient-vs-destination.md` — Lamed senses — disambiguates the distributive/ratio lamed
   - `$GRAMMAR_REF/hebrew/stem-niphal.md` — Niphal stem — nitsdaq (Dan 8:14) and nechtak (Dan 9:24) are both Niphal
   - `$GRAMMAR_REF/hebrew/ben-adam-vocative-construct.md` — Ben-adam vocative — Gabriel's address to Daniel (Dan 8:17), the 8-to-9 bridge
   - `$GRAMMAR_REF/hebrew/syntax-compound-object-waw.md` — Compound object with waw — Dan 9:24 chazon we-nabi under lachtom; Dan 8:13 qodesh we-tsava
   - `$GRAMMAR_REF/hebrew/attributive-apposition-double-article.md` — Double article / apposition — Dan 8:26 ha-'erev we-ha-boqer articulation

### Additional Research Instructions

STANDALONE REDERIVATION (per CUSTOM-INSTRUCTIONS.md): every phase must build the argument from the biblical TEXT and cite Scripture, NOT prior conclusions. Prior studies (sv-series, evening-morning, seal, day-year) and all external corpus items are LEADS to test, never evidence. When a difficulty unit reads a prior CONCLUSION.md, record it as an external lead and reach an independent verdict from the passages.

The thesis MUST be able to lose. Keep FIVE axes distinct and do not collapse them: (1) terminology choice (yamim vs 'erev boqer), (2) Genesis-1 allusion, (3) day-for-year principle, (4) sealing/satham, (5) authorial-intent/motive. Cover each candidate referent category once in defeater coverage: cand-deliberate-concealment-cipher (thesis), cand-tamid-primary-natural, cand-genesis-allusion-driven, cand-literary-sealing-convention (the critical counter). All four stay live; reconcile, do not drop.

CALIBRATION CEILINGS: MEDIUM-HIGH that the 2300 specifically = years; authorial-motive ('Daniel chose X in order to conceal') is an inference rarely explicit with NO scholarly precedent — hold to a high bar and state as calibrated inference, never as text-statement; Dan 9 chathak is the STRONGEST confirmation among several (Num/Ezek ratio + apocalyptic genre + scope-demand), NOT the sole proof; 'cut off FROM the 2300' is a historicist inference, not a lexical necessity — flag as the most contestable load-bearing link.

THREE NON-NEGOTIABLE TRAPS: (a) satham (8:26 conceal) is a different verb from chatham (9:24 authenticate) — never cite 9:24 as concealment; (b) day-year is grounded in Num 14:34 + Ezek 4:6, NOT Dan 8; (c) do NOT drop the tamid-primary / Genesis-1 day-definition readings — 'erev boqer may be natural-to-topic, not obscure-by-design.

SHARPENED CLAIM (the study's genuinely new move, must be ARGUED not assumed): the days-vs-years UNIT-ambiguity may itself be part of the design (the corpus position is that the sealed target is the WHEN/starting-anchor). Argue this from the text and test it against the WHEN-only framing (focus 8).

STYLE: no loaded/system theological vocabulary in prose; quote KJV verbatim with Hebrew notes. Distinguish sharply what the text SAYS from what the encoding thesis INFERS. Do NOT use EGW as a historical/doctrinal authority — only as a lead to primary sources and to the biblical text. Represent the critical/Antiochus + 1150-day reading fairly as the dominant academic position, not a fringe view.

Parser scripts are at $TOOLS/hebrew/hebrew_parser.py and $TOOLS/greek/greek_parser.py (run with --verse "Book C:V"). Naves and Strong's tools are in $TOOLS/search/.

## Workflow
answer-question

---
*Scoped from prompt.json*
*Folder: daniel-8-14-erev-boqer-encoded-concealment/*