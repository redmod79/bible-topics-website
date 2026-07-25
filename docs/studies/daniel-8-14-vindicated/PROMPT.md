# Bible Study: In Daniel 8:14, is the Hebrew word translated 'cleansed' (KJV) more appropriately rendered 'vindicated'? Is 'vindicated' the proper response to the question posed in Daniel 8:13? And does the meaning 'vindicated' include cleansing?

## Question
In Daniel 8:14, is the Hebrew word translated 'cleansed' (KJV) more appropriately rendered 'vindicated'? Is 'vindicated' the proper response to the question posed in Daniel 8:13? And does the meaning 'vindicated' include cleansing?

**Prompt schema:** v2

## Prior Research Summary
10 prior studies read in full converge on: (1) 'vindicated' is the more accurate rendering — nitsdaq is Niphal Perfect 3ms of tsadaq (H6663), forensic; tsadaq is 54x always 'just/justify/righteous', never elsewhere 'cleanse'; LXX renders tsadaq with dikaioo/dikaios/krino, never katharizo; the 'cleansed' reading traces to Theodotion (katharizo) and the Vulgate (mundabitur), not the Hebrew. (2) It IS the proper response to 8:13 — 8:13 asks the duration of injustice (pesha/shamem/mirmac); 8:14 answers with justice (tsadaq); ad-matay/ad lock-and-key; qodesh flips from object-of-trampling (v.13) to subject-of-vindication (v.14). (3) It INCLUDES cleansing as inclusion-not-displacement: sv-19 (via Davidson JATS 1996) shows sdq in poetic parallel with taher/zakah/bor (Job 4:17 LXX katharos; Job 25:4; Psa 51:4), and the tame->tahor->tsadaq progression means you cannot skip the cleansing step but cleansing alone is not the goal. NOTE Strong's own gloss for H6663 lists 'cleanse, clear' among its senses. External: Bohr/Augsburger argue 'cleansed' is an acceptable translation because tsadaq's cultic sense includes purification (inclusion), contra Desmond Ford's 'mistranslation' objection. CRITICAL open item flagged by web research: the OG LXX vs Theodotion split (justify-verb vs cleanse-verb) at Dan 8:14 must be VERIFIED against the local LXX corpus — web sources report BOTH OG and Theodotion may read katharisthesetai (cleanse), contradicting the assumption that OG=justify. Do not assert the split until checked.

## Authorial Vernacular Audit

**Scope:** Daniel (primary), widening to the OT tsadaq corpus — Daniel, Job, Isaiah, Psalms, Leviticus, Zechariah, Malachi

### cat-daniel-ritual-cleansing-vocab-available: When Daniel/the OT names ritual cleansing or atonement directly (negative controls: Daniel HAD taher/kaphar but chose tsadaq)

**Candidate categories:** cand-cleansing-primary, cand-vindication-includes-cleansing

**Focus area:** 4

**Direct-label passages:**
- Lev 16:30: The DOA cleansing text uses taher (H2891) directly for the sanctuary/people being made clean — the standard cleansing vocabulary.
- Lev 16:19: taher used for cleansing the altar on the Day of Atonement — the ritual-purity register.

**Structural analogies:**
- Dan 9:24: kaphar + tsedeq paired in one verse

**Negative controls:**
- Dan 9:24: Daniel uses kaphar (H3722, atone) here, proving he had the atonement/cleansing vocabulary in his active lexicon.
- Lev 16:30: Moses' DOA law uses taher, not tsadaq, for the cleansing act.

**Required searches:**
- `python search_strongs.py --verses H2891 --scope "Dan,Lev"`
- `python search_strongs.py --verses H3722 --scope "Dan,Lev"`
- `python hebrew_parser.py --verse "Dan 9:24"`

### cat-tsadaq-parallel-with-cleansing: When tsadaq/sdq stands in poetic parallel with cleansing/purity words (structural analogies supporting inclusion)

**Candidate categories:** cand-vindication-includes-cleansing

**Focus area:** 5

**Direct-label passages:**
- Job 4:17: sdq (be righteous/pure before God) — Davidson notes the LXX renders the verb here with the katharos word-group, the same Greek family as Dan 8:14's Theodotion katharizo.
- Job 25:4: 'How can man be justified (tsadaq) with God? or how can he be clean (zakah)?' — tsadaq set in synonymous parallel with a purity/clean word.

**Structural analogies:**
- Job 4:17: sdq || purity term; LXX katharos
- Job 25:4: tsadaq || zakah (be clean/pure)
- Psa 51:4: tsadaq (be justified/clear when judged) in a purification-saturated psalm (v.7 purge/wash)

**Negative controls:**
- Job 9:2: 'how should man be just (tsadaq) with God?' — here tsadaq is purely forensic (standing in judgment) with no cleansing term nearby.

**Required searches:**
- `python search_strongs.py --verses H6663`
- `python cross_testament_parallels_v2.py --hybrid-ot "Job 4:17"`
- `python hebrew_parser.py --verse "Job 25:4"`

### cat-tsadaq-forensic-courtroom: When the OT uses tsadaq in forensic/courtroom contexts (direct label passages for the vindication sense)

**Candidate categories:** cand-vindication-includes-cleansing, cand-vindication-displaces-cleansing

**Focus area:** 6

**Direct-label passages:**
- Isa 43:9: 'let them be justified (tsadaq)' — courtroom summons of the nations; forensic verdict language.
- Isa 43:26: 'declare thou, that thou mayest be justified (tsadaq)' — legal self-defense before God.
- Isa 45:25: 'In the LORD shall all the seed of Israel be justified (tsadaq)' — corporate forensic vindication.
- Isa 50:8: 'He is near that justifieth (tsadaq) me' — the Servant's courtroom vindication scene.
- Psa 143:2: 'in thy sight shall no man living be justified (tsadaq)' — forensic verdict before the divine judge.

**Structural analogies:**
- Isa 53:11: the Servant tsadaq (justify) many by bearing iniquity

**Negative controls:**
- Isa 43:9: The nations' 'justification' is a legal verdict of being in the right, with zero ritual-purity content.

**Required searches:**
- `python search_strongs.py --verses H6663 --scope "Isa,Psa,Job"`
- `python hebrew_parser.py --verse "Isa 50:8"`

## Identity Axes

- **Grammatical object/subject of nitsdaq** (required): What is nitsdaq predicated of — qodesh (the sanctuary)? What receives the action, and how does the Niphal (divine passive) identify the unnamed agent (God) who does the vindicating?
- **Functional-conceptual identity of the word** (required): Does nitsdaq name a forensic verdict (vindication/justification), a restoration/setting-right, or a ritual purification — and does that concept include cleansing?
- **Material Niphal-stem force of a hapax stem-form** (required): Given Dan 8:14 is the sole Niphal of tsadaq in the OT, what is the precise passive force — 'be vindicated/declared righteous' vs 'be put right/restored to rightful state' — and how is that nuance established from the Niphal's normal passive/tolerative sense and Niphal-adjacent controls?
- **Violated norm named by 8:13 that 8:14's word must answer** (optional): What problem does Dan 8:13 name — injustice/trampling/usurpation (pesha, shamem, mirmac/ramas) or ritual defilement — and does an injustice-problem demand a justice-answer (vindicate) rather than a purity-answer (cleanse)? This is the 'proper response to 8:13' axis.
- **Relation to the Day-of-Atonement process (kaphar/taher)** (optional): Does nitsdaq connect to the DOA process (kaphar/taher) as the declared RESULT of a completed atonement/cleansing process (inclusion), or as a distinct category set against it (displacement)?

## Available Library Entries

### Word Studies

- `$WORD_STUDIES/H6663-tsadaq.md` — tsadaq (be/make right, vindicate, justify), H6663 — the central term
- `$WORD_STUDIES/H2891-taher.md` — taher (be clean, cleanse), H2891 — ritual-cleansing contrast term
- `$WORD_STUDIES/H3722-kaphar.md` — kaphar (make atonement, cover), H3722 — atonement contrast term
- `$WORD_STUDIES/H6942-qadash.md` — qadash (sanctify, be holy), H6942 — cognate of qodesh (sanctuary)
- `$WORD_STUDIES/H8548-tamid.md` — tamid (continual), H8548 — the tamid taken away in Dan 8:11-13
- `$WORD_STUDIES/TR-tsadaq-dikaioo.md` — Translation relationship tsadaq -> dikaioo (righteousness/justification chain)
- `$WORD_STUDIES/TR-taher-katharizo.md` — Translation relationship taher -> katharizo (cleansing/purification chain)
- `$WORD_STUDIES/TR-tame-akathartos.md` — Translation relationship tame -> akathartos (defilement/uncleanness)
- `$WORD_STUDIES/TR-mishpat-krima.md` — Translation relationship mishpat -> krima (judgment/verdict)
- `$WORD_STUDIES/WG-cleansing.md` — Word group: cleansing
- `$WORD_STUDIES/WG-judgment.md` — Word group: judgment
- `$WORD_STUDIES/WG-atonement.md` — Word group: atonement
- `$WORD_STUDIES/WG-hebrew-righteousness.md` — Word group: Hebrew righteousness terms
- `$WORD_STUDIES/WG-righteousness.md` — Word group: righteousness
- `$WORD_STUDIES/WG-sanctification.md` — Word group: sanctification

### Grammar References

- `$GRAMMAR_REF/hebrew/stem-niphal.md` — Niphal stem — passive/reflexive/tolerative; the stem of nitsdaq

### Missing Library Entries (generate)

- H6664 tsedeq — Righteousness noun paired with kaphar in Dan 9:24; no dedicated H-entry found (TR-tsedeq-dikaiosyne exists but not a canonical H6664 study)
- H2135 zakah — 'be clean/pure' — parallel with tsadaq in Job 25:4; no library entry
- H4823 mirmac — 'trampling' in Dan 8:13; no library entry (TR-ramas-katapateo exists for the verb)
- H6588 pesha — 'transgression' in Dan 8:13; no library entry
- G2511 katharizo — Greek cleanse-verb at Dan 8:14 Theodotion; no dedicated G-entry (TR-taher-katharizo covers the chain only)
- G1344 dikaioo — Greek justify-verb rendering tsadaq; no dedicated G-entry (TR-tsadaq-dikaioo covers the chain only)
- Hebrew prophetic perfect / waw-consecutive with Niphal — The venitsdaq form's certainty-not-speed nuance; no dedicated grammar entry beyond stem-niphal

### Strong's Numbers

| Strong's | Word | Relevance | Library Entry |
|----------|------|-----------|---------------|
| H6663 | tsadaq | The central disputed term (nitsdaq form); forensic vindicate/justify — library entry exists | yes |
| H2891 | taher | The ritual-cleansing contrast verb Daniel did NOT use in 8:14 — library entry exists | yes |
| H3722 | kaphar | The atonement verb Daniel used in 9:24 but NOT 8:14 — negative control; library entry exists | yes |
| H6664 | tsedeq | The noun 'righteousness' paired with kaphar in Dan 9:24 (tsedeq olamim) | (missing) |
| H6666 | tsedaqah | Righteousness/justice noun from the same root; forensic register | (missing) |
| H6662 | tsaddiq | The adjective 'righteous/just' — same root, courtroom sense | (missing) |
| H2135 | zakah | 'be clean/pure' — stands in parallel with tsadaq (Job 25:4); tests the inclusion overlap | (missing) |
| H4823 | mirmac | 'trampling' in Dan 8:13 — the injustice-word the vindication answers | (missing) |
| H6588 | pesha | 'transgression/rebellion' in Dan 8:13 — the violated norm | (missing) |
| H4941 | mishpat | 'judgment/verdict' — the forensic frame collocating with tsadaq | (missing) |
| H1780 | din (Aramaic) | 'judgment' in Dan 7:10,22,26 — the courtroom that 8:14 compresses | (missing) |
| G1344 | dikaioo | The LXX/NT rendering of tsadaq (justify) — the Greek side of the translation-history argument — audit all local LXX occurrences and classify which Hebrew source terms dikaioo renders, to confirm the tsadaq->dikaioo bridge and test whether dikaioo ever renders cleansing vocabulary. | (missing) |
| G2511 | katharizo | The Theodotion/LXX rendering at Dan 8:14 (cleanse) — the disputed Greek verb | (missing) |
| G2643 | katallage/hilasterion cluster | atonement/propitiation in Rom 3:25 grounding the justifying verdict | (missing) |
| G1342 | dikaios | 'righteous/just' in Rev 15-19 — cosmic vindication of God's judgments | (missing) |

### Required LXX Occurrence Audits

- **G1344 (dikaioo)** — inventory every joined local LXX occurrence, classify its grammatical target, and preserve the complete audit in research JSON

## Discovered Scope

### Topics Found (from naves_semantic.py)

| Topic | Subtopic | Verse Count |
|-------|----------|-------------|
| SANCTUARY | GENERAL | 15 |
| ATONEMENT | DAY OF / BY JESUS | 60 |
| RIGHTEOUSNESS | GENERAL | 40 |
| RIGHTEOUS | GENERAL | 30 |
| JUDGMENT | THE GENERAL | 25 |
| JUSTICE | GENERAL | 20 |
| PURIFICATION | RITUAL/FIGURATIVE | 25 |
| INJUSTICE | GENERAL | 18 |
| SCAPEGOAT | GENERAL | 1 |
| VERDICT | GENERAL | 6 |
| SELF-RIGHTEOUSNESS | GENERAL | 20 |
| ACCUSATION, FALSE | GENERAL | 8 |

### Primary Verses (29 — full analysis required)

**Crux passage — Daniel 8:**
_The attack-question-answer unit; retrieve with full chapter context_
- Dan 8:9-14 — The full attack-question-answer unit: little horn's fourfold assault, the 'how long' question (v.13), and nitsdaq answer (v.14) — the crux passage
- Dan 8:11-12 — tamid taken away, truth cast down, host given over (natan) — the injustice the vindication reverses
- Dan 8:13 — The question nitsdaq answers — names pesha (transgression), shamem (desolation), mirmac (trampling); the 'violated norm' axis
- Dan 8:14 — The verse itself — nitsdaq qodesh; the term whose rendering is disputed

**The forensic frame — Daniel 7 and 9:24:**
_The judgment scene and the kaphar+tsedeq bridge_
- Dan 7:9-10 — The judgment scene (thrones set, books opened) that Dan 8:14 compresses — the forensic/courtroom frame
- Dan 7:22 — 'judgment was given to the saints' — vindication of the persecuted, parallel to 8:14
- Dan 7:26 — 'the judgment shall sit' — the verdict against the horn; forensic answer to usurpation
- Dan 9:24 — The only OT verse pairing kaphar (atone) with tsedeq (righteousness); Daniel HAD the atonement word and used it here, not in 8:14 — key negative control

**Ritual-cleansing negative controls:**
_The taher/kaphar vocabulary Daniel had available_
- Lev 16:19 — taher (H2891) used to cleanse the altar on the Day of Atonement — the ritual-cleansing register Daniel did NOT use
- Lev 16:30 — 'ye shall be clean (taher)' — the DOA cleansing text; the standard cleansing vocabulary for this exact context
- Mal 3:3 — 'purify (taher)... refine' — shows taher is NOT restricted/narrow (guards against overreach); Levites purified for right offerings

**tsadaq forensic + parallelism corpus:**
_Courtroom uses and parallels with cleansing terms_
- Job 4:17 — sdq in parallel with purity; LXX renders with katharos word-group — Davidson's load-bearing inclusion proof
- Job 9:2 — 'how should man be just (tsadaq) with God?' — pure forensic use, no cleansing term; negative control for the base sense
- Job 25:4 — tsadaq set in synonymous parallel with zakah (be clean/pure) — righteousness word || cleanness word
- Job 40:8 — 'wilt thou condemn me, that thou mayest be righteous (tsadaq)?' — explicit courtroom vindication contrast
- Isa 43:9 — 'let them be justified (tsadaq)' — courtroom summons of the nations; forensic verdict
- Isa 43:26 — 'declare thou, that thou mayest be justified (tsadaq)' — legal self-defense before God
- Isa 45:25 — 'in the LORD shall all the seed of Israel be justified (tsadaq)' — corporate forensic vindication
- Isa 50:8 — 'he is near that justifieth (tsadaq) me' — the Servant's courtroom vindication
- Isa 53:11 — the Servant shall justify (tsadaq) many by bearing iniquity — links verdict to sin-bearing/atonement
- Psa 51:4 — 'be justified (tsadaq) when thou judgest' in a purification psalm (purge/wash v.7) — verdict + cleansing coupled
- Psa 143:2 — 'in thy sight shall no man living be justified (tsadaq)' — forensic verdict before the divine judge
- Deut 25:1 — judges 'justify (tsadaq) the righteous and condemn the wicked' — the plainest forensic/courtroom use of tsadaq

**Cleansing-within-vindication model:**
_Zechariah 3 courtroom scene_
- Zech 3:4 — filthy garments removed (cleansing) + festival robes conferred (vindication/positive standing) — one event, both dimensions; the inclusion model

**kaphar->tsadaq bridge into the NT:**
_Atonement grounds the verdict; katharizo tension_
- Rom 3:24-26 — hilasterion + God 'just (dikaios) and the justifier (dikaioo)' — NT antitype: atonement grounds the justifying verdict; the kaphar->tsadaq bridge
- Heb 9:22-23 — 'without shedding of blood is no remission'; heavenly things purified (katharizo) — the katharizo tension; broader tsadaq encompasses narrower katharizo

**Cosmic vindication:**
_God's judgments declared just/true_
- Rev 15:3-4 — 'just (dikaios) and true are thy ways... thy judgments (dikaioma) are made manifest' — cosmic vindication of God's character
- Rev 16:5-7 — 'thou art righteous (dikaios)... true and righteous are thy judgments' — the verdict declaring God right; vindication theme
- Rev 19:2 — 'true and righteous (dikaios) are his judgments' — final vindication; the answer to the horn's accusation

### Supporting Verses (8 — retrieve for context, no individual analysis)

- Dan 8:26 — back-reference to 8:14 (the evening-morning vision) with definite articles — confirms 8:14 as the answer clause
- Lev 17:11 — blood makes atonement (kaphar) — the atonement mechanism underlying DOA
- Psa 51:7 — 'purge me... wash me' — the cleansing dimension paired with the justifying verdict of v.4
- Zech 3:1-5 — The courtroom scene: Satan the accuser, the high priest defended, garments changed — cleansing-within-vindication in narrative form
- Ezek 36:25 — 'clean water... ye shall be clean (taher)' — taher used broadly for covenant renewal; guards the inclusion argument against shrinking taher
- Dan 12:10 — 'many shall be purified (barar), and made white, and tried' — purification language in Daniel's own end-time frame (not taher, not in ch.8)
- Lev 23:27-30 — Day of Atonement as a day of judgment ('cut off'), not merely ceremony — DOA-as-judgment bridge supporting the forensic reading
- Prov 17:15 — 'he that justifieth (tsadaq) the wicked... abomination' — tsadaq as a forensic verdict (declaring in the right)

### Focus Areas

1. **Morphology and lexical range of nitsdaq / tsadaq (H6663) — is 'vindicated' the more accurate rendering?:**
READ `$WORD_STUDIES/H6663-tsadaq.md` in full for the canonical data (Septuagint rendering pattern dikaioo, PMI, collocations mishpat/shaphat/rasha, and that Dan 8:14 is the only Niphal). Run `python hebrew_parser.py --verse "Dan 8:14"` to confirm the morphology (Niphal Perfect 3ms + waw, divine passive) and `python search_strongs.py --verses H6663` to build the full Hebrew tsadaq concordance and confirm KJV renders it 'just/justify/righteous' in all ~54 occurrences EXCEPT Dan 8:14. IMPORTANT nuance to handle honestly: Strong's own gloss for H6663 lists 'cleanse, clear' among its senses — do not misstate that the lexicon knows nothing of a cleansing sense; the argument is about the PRIMARY/forensic core versus a KJV rendering unique to this verse. Contrast the Niphal's normal passive/tolerative force (READ `$GRAMMAR_REF/hebrew/stem-niphal.md`) to establish whether the hapax stem means 'be vindicated/declared righteous' or 'be put right/restored'. Conclude on sub-question 1: is 'vindicated' more accurate than 'cleansed', and with what calibration given the hapax uncertainty.
**Verses:** Dan 8:14, Job 9:2, Isa 43:9, Deut 25:1, Prov 17:15
**Strong's:** H6663, H6662, H6666, H6664

2. **The question of Daniel 8:13 — is it an injustice problem or a defilement problem?:**
Run `python hebrew_parser.py --verse "Dan 8:13"` and on 8:11-12 to extract every operative verb/noun. Confirm the controlling imagery is trampling (mirmac H4823 / ramas), casting down, magnifying, and giving-over (natan) — usurpation and assault, NOT ritual defilement. Run `python search_strongs.py --verses H2891` and for tame across Daniel to VERIFY purity vocabulary is absent from Dan 8 (a key datum: an injustice question naturally takes a justice answer). Establish the ad-matay (8:13) / ad (8:14) syntactic lock-and-key and the semantic inversion — qodesh is object of trampling in v.13 and subject of vindication in v.14. Tie back to Dan 8:12 tinnaten: what God gave over, God vindicates. Conclude whether tsadaq is the fitting answer-word to the specific problem 8:13 names.
**Verses:** Dan 8:9-14, Dan 8:13, Dan 8:11-12, Dan 8:26
**Strong's:** H4823, H6588, H8074, H5414

3. **The forensic frame of Daniel 7 and the judgment as the vindication event:**
Retrieve Dan 7:9-14 and 7:22-27 with full chapter context. Show the parallel: horn attacks (7:8,21,25) -> court sits, books opened (7:9-10) -> judgment given FOR the saints and AGAINST the horn (7:22,26) — a forensic verdict that vindicates the persecuted. Argue that Dan 8:14's single justice-word nitsdaq compresses what Dan 7 expands into a full courtroom. Run `python cross_testament_parallels_v2.py` on Dan 7:9-10 to surface the wider judgment-scene network (Rev 15/16/19, the Ancient of Days). This establishes the STRUCTURAL constraint (see structural_constraints) that Dan 7 and Dan 8:14 name one judgment event.
**Verses:** Dan 7:9-10, Dan 7:22, Dan 7:26, Dan 8:14
**Strong's:** H1780, H1779, H6663

4. **Negative controls — Daniel possessed taher and kaphar but chose tsadaq (authorial vocabulary audit):**
This is the authorial-vernacular negative-control category. Run `python search_strongs.py --verses H2891 --scope "Dan,Lev"` and `python search_strongs.py --verses H3722 --scope "Dan,Lev"` to show taher and kaphar are the standard cleansing/atonement verbs (Lev 16:19,30 taher for the sanctuary/altar/people; kaphar 16x in Lev 16). Run `python hebrew_parser.py --verse "Dan 9:24"` to confirm Daniel himself uses kaphar (to make reconciliation for iniquity) one chapter after 8:14 — proving he HAD the atonement vocabulary. READ `$WORD_STUDIES/H2891-taher.md`, `$WORD_STUDIES/H3722-kaphar.md`, `$WORD_STUDIES/TR-taher-katharizo.md`. The deliberate departure to tsadaq is the pivot: it means either 'more than cleansing' (inclusion) or 'not cleansing at all' (displacement). GUARD AGAINST OVERREACH: do not argue taher is restricted/narrow — Mal 3:3, Ezek 36:25 show taher's breadth; the inclusion case must rest on tsadaq's breadth, not on shrinking taher.
**Verses:** Lev 16:19, Lev 16:30, Dan 9:24, Lev 17:11, Mal 3:3, Ezek 36:25
**Strong's:** H2891, H3722, H6663, H6664

5. **Poetic parallelism of sdq with cleansing/purity words — does vindication INCLUDE cleansing?:**
Test the inclusion thesis at its strongest point. Run `python hebrew_parser.py --verse "Job 25:4"` (tsadaq || zakah be-clean) and `python cross_testament_parallels_v2.py --hybrid-ot "Job 4:17"` to surface the parallel of sdq with a purity term, and to check the LXX Greek — Davidson claims LXX renders tsadaq at Job 4:17 with the katharos (clean) word-group, the same family as Dan 8:14's Theodotion katharizo. VERIFY this against the local LXX corpus rather than asserting it. Add Psa 51:4 (be justified when judged) inside a purification-saturated psalm (v.7 purge/wash). Then argue the tame->tahor->tsadaq progression: you cannot skip the cleansing step but cleansing alone is not the goal — tsadaq is the larger category that encompasses it. Contrast with the pure-forensic controls (Job 9:2) where no purity term appears, to show cleansing is an INCLUDED facet in cultic/relational contexts, not the base meaning. Conclude on sub-question 3.
**Verses:** Job 4:17, Job 25:4, Psa 51:4, Psa 51:7, Job 9:2
**Strong's:** H6663, H2891, H2135, H1249

6. **The forensic/courtroom corpus of tsadaq (Isaiah, Job, Psalms) — direct label passages for vindication:**
Retrieve Isa 43:9,26; 45:25; 50:8 (the Servant's 'he is near that justifieth me') and Psa 143:2 and Job 40:8 — the passages where tsadaq unambiguously means a courtroom verdict of being in the right. Run `python hebrew_parser.py --verse "Isa 50:8"` for the parsing. These fix the forensic core of tsadaq. Then add Isa 53:11 (the Servant justifies many BY bearing iniquity) as the structural analogy that links the justifying verdict to the atoning work — the verdict is the declared result of a completed sin-bearing, which is exactly how vindication can encompass the atonement/cleansing it presupposes. READ `$WORD_STUDIES/TR-tsadaq-dikaioo.md` for the Hebrew->LXX->NT chain into Rom 3:24-26.
**Verses:** Isa 43:9, Isa 43:26, Isa 45:25, Isa 50:8, Isa 53:11, Psa 143:2, Job 40:8
**Strong's:** H6663, H6666, H4941

7. **The Zechariah 3 model — cleansing and vindication as two aspects of one event:**
Retrieve Zech 3:1-5 with context. Map the two movements: iniquity/filthy garments taken away = the cleansing (taher) dimension; festival robes and mitre conferred = the vindication (tsadaq) dimension conferring positive standing. Argue these are not competing descriptions but two aspects of one judicial event — the accuser (Satan) is rebuked and the accused is vindicated. This is the clearest OT model for the inclusion hierarchy. Connect to Dan 7 (accuser/verdict) and Dan 8:14 (the sanctuary/host vindicated after being trampled). Note the same accuser-court-verdict shape recurs in Job (accuser, accusation, verdict).
**Verses:** Zech 3:4, Zech 3:1-5, Dan 7:22
**Strong's:** H2891, H6663, H7760

8. **The kaphar->tsadaq bridge and the katharizo tension (Dan 9:24; Rom 3; Heb 9):**
Build the redemptive-action axis. Dan 9:24 uniquely pairs kaphar (atone) with tsedeq (everlasting righteousness) — the bridge verse. Run `python greek_parser.py --verse "Rom 3:26"` to show God is 'just (dikaios) and the justifier (dikaioo)' — the atonement (hilasterion, v.25) GROUNDS the justifying verdict. Then handle the recurring objection: Heb 9:23 says the heavenly things are purified (katharizo) — run `python greek_parser.py --verse "Heb 9:23"`. Carry the settled corpus resolution: the broader category (tsadaq) encompasses the narrower one (taher/katharizo); a cleansing word appearing for the heavenly sanctuary does not refute the vindication reading because vindication includes the cleansing/atonement it declares complete. READ `$WORD_STUDIES/TR-tsadaq-dikaioo.md` and `$WORD_STUDIES/TR-taher-katharizo.md`.
**Verses:** Dan 9:24, Rom 3:24-26, Heb 9:22-23, Isa 53:11, Lev 16:30
**Strong's:** H3722, H6663, H6664, G2643, G1344, G2511

9. **Adjudicating the Bohr/Augsburger (inclusion) vs Desmond Ford (displacement) translation dispute:**
Transform the external leads into biblical tests. Bohr/Augsburger (GPOT2V1 Lesson #14 pp.442-449) argue 'cleansed' is ACCEPTABLE because tsadaq's cultic sense includes purification — test this against the parallelism data (focus area 5) and the DOA-as-judgment bridge (Lev 23:27-30). Desmond Ford objects that 'cleansed' is a mistranslation (Hebrew=tsadaq/vindicate, not taher/cleanse) — test the strong form (cleansing EXCLUDED) against Dan 9:24, Zech 3, and Job 25:4. The study should name where it agrees with Ford (tsadaq is the more precise word; 'cleansed' alone under-translates) and where it agrees with Bohr (cleansing is included, not displaced). Present the resolution as ONE coherent claim: vindication is the larger category that includes cleansing (so 'vindicated is better' and 'includes cleansing' are not in tension — a hierarchy, not a contradiction). Use EGW's 'the cleansing of the sanctuary is the work of judgment' (BR-ASI9 156.5) only as a lead pointing to the primary sources, not as authority.
**Verses:** Dan 8:14, Dan 9:24, Lev 23:27-30, Zech 3:4, Job 25:4
**Strong's:** H6663, H2891, H3722

10. **VERIFY the LXX (Old Greek) vs Theodotion text of Daniel 8:14 against the local corpus:**
This is a MANDATORY verification, not an assumption. Query the local LXX corpus (search the LXX index for Dan 8:14 / Daniel 8:14 in both the Old Greek and Theodotion recensions if the corpus distinguishes them) to establish the actual Greek verb. Do NOT assert the OG=justify vs Theodotion=cleanse split until the local text confirms it — web sources report both recensions may read katharisthesetai (cleanse). Then contrast with how the LXX renders tsadaq elsewhere (dikaioo/dikaios, per `$WORD_STUDIES/TR-tsadaq-dikaioo.md`), so the study can state accurately whether Dan 8:14's Greek is an outlier cleansing-rendering of a normally-justify word. This sharpens (and may correct) the 'cleansed traces to the Greek, not the Hebrew' claim. Report exactly what the local corpus shows and calibrate the conclusion to it.
**Verses:** Dan 8:14, Isa 45:25, Job 4:17
**Strong's:** H6663, G1344, G2511

11. **Cosmic vindication of God's character (Revelation) — the widest referent of the verdict:**
Retrieve Rev 15:3-4; 16:5-7; 19:2. Run `python greek_parser.py --verse "Rev 15:3"` for dikaios/dikaioma. Show these songs declare God's judgments righteous/vindicated — the cosmic dimension of what nitsdaq begins: the sanctuary vindicated, the people vindicated, and ultimately God's character and government vindicated before the watching universe (the five-beneficiary structure from sv-18). This demonstrates that 'vindicated' reaches meanings 'cleansed' cannot carry, reinforcing that tsadaq is the larger category — while never denying the cleansing it includes.
**Verses:** Rev 15:3-4, Rev 16:5-7, Rev 19:2, Dan 7:9-10
**Strong's:** G1342, G1345, H6663

### External Corpus Leads (from 00-references.md)

1. **'cleansed' is an ACCEPTABLE translation because tsadaq's cultic sense INCLUDES the purification dimension (inclusion, not because tsadaq means 'cleanse')** (Source: Bohr/Augsburger (SU GPOT2V1 Lesson #14 pp.442-449))
   - **Verify:** verify against the parallelism data (Job 4:17,25:4; Psa 51:4) and DOA-as-judgment (Lev 23:27-30); this is the pro-inclusion external voice for sub-question 3
2. **'cleansed' is a MISTRANSLATION; Hebrew=tsadaq/vindicate not taher/cleanse, so cleansing is displaced/excluded** (Source: Desmond Ford (via Bohr's framing))
   - **Verify:** test the strong displacement form against Dan 9:24, Zech 3, Job 25:4; agree that tsadaq is the more precise word, decide whether cleansing is truly EXCLUDED
3. **sdq stands in poetic parallelism with taher/zakah/bor; LXX renders tsadaq with katharos at Job 4:17; tsadaq is the larger category that includes cleansing** (Source: Richard M. Davidson, JATS 7/1 (1996))
   - **Verify:** verify the parallelisms and the Job 4:17 LXX rendering against the local corpus (focus areas 5,10) — the load-bearing inclusion proof
4. **nitsdaq answers the trampling/usurpation of 8:13 with restoration-to-rights that includes cultic setting-right** (Source: Martin Probstle, 'Truth and Terror' (Andrews diss. 2006))
   - **Verify:** verify the 8:9-13 verb inventory (usurpation vs defilement) supports an injustice->justice answer (focus area 2)
5. **nitsdaq = 'restored to its rightful state'; broadly away from ritual cleansing toward restore/vindicate (referent = Antiochus, a separable question)** (Source: Critical scholarship (Collins Hermeneia; Goldingay WBC))
   - **Verify:** note the convergence with the historicist lexical conclusion (both move away from 'cleanse'); keep the MEANING question distinct from the REFERENT question
6. **'the cleansing of the sanctuary is the work of judgment' — her 'cleansing' language already carries the judgment/verdict content** (Source: EGW (BR-ASI9 156.5))
   - **Verify:** use as a LEAD pointing to primary sources (Davidson/Augsburger), NOT as historical/analytical authority; supports that 'cleansed' and 'vindicated' name one judicial event
7. **the assumption OG=justify vs Theodotion=cleanse may be wrong; both recensions may read katharisthesetai (cleanse)** (Source: Web research (Old Greek/Theodotion textual question))
   - **Verify:** MANDATORY verification against the local LXX corpus (focus area 10); do not assert the split until confirmed

### Structural Constraints (from prior studies — verify and account for)

1. **nitsdaq in Dan 8:14 is forensic (tsadaq, 'vindicate/justify'), NOT the ritual-cleansing verb taher; 'vindicated' is the more accurate rendering of the Hebrew.**
   - Established by: daniel-8-14-cleansed-hebrew-meaning, sv-18-vindication-meaning, sanc-25-daniel-8-14-vindicated, daniel-8-14-cleansed-word-study, sv-19-righteousness-defilement-vindication
   - Directive: verify_and_account_for
   - Implication: If confirmed, sub-question 1 is answered yes; the study's rendering must be tsadaq-forensic and any retention of 'cleansed' must be justified as an included facet, not the primary sense.
2. **Vindication INCLUDES cleansing but exceeds it (inclusion, not displacement): tsadaq is the larger category that encompasses the narrower taher/katharizo; you cannot skip the cleansing step (tame->tahor->tsadaq) but cleansing alone is not the goal.**
   - Established by: dan-8-14-vindication-meaning, sanc-25-daniel-8-14-vindicated, sv-19-righteousness-defilement-vindication
   - Directive: verify_and_account_for
   - Implication: If confirmed, sub-question 3 is answered yes-as-inclusion; the study must reject BOTH the displacement reading (Ford) and the cleansing-primary reading, and state the inclusion hierarchy as one coherent claim so 'vindicated is better' and 'includes cleansing' are not in tension.
3. **Daniel 8:13 poses a duration-of-injustice question (pesha/shamem/mirmac trampling), and Daniel 8:14 answers with a justice word; qodesh flips from object-of-trampling (v.13) to subject-of-vindication (v.14) via the ad-matay/ad lock-and-key.**
   - Established by: daniel-8-14-cleansed-hebrew-meaning, sv-17b-vindication-as-process, daniel-8-14-cleansed-word-study
   - Directive: verify_and_account_for
   - Implication: If confirmed, sub-question 2 is answered yes: an injustice problem takes a justice answer, so 'vindicated' is the fitting response to 8:13 (and 'cleansed' answers a defilement problem the text does not primarily pose).

## Research Instructions

You are the Research Agent. Execute this study by:

1. Read the SKILL.md for full tool documentation and principles
2. Read your agent instructions at `agents/research-agent.md`
3. **Read ALL library entries listed in "Available Library Entries" above**
4. Follow the workflow from the skill
5. Write research files to this folder:
   - `01-topics.md` — Nave's topics and full entries (retrieve full entries for: SANCTUARY, ATONEMENT, RIGHTEOUSNESS, RIGHTEOUS, JUDGMENT, JUSTICE, PURIFICATION, INJUSTICE, SCAPEGOAT, VERDICT, SELF-RIGHTEOUSNESS, ACCUSATION, FALSE)
   - `02-verses.md` — All verse texts retrieved with context for:
     - **Crux passage — Daniel 8** (Dan 8:9-14, Dan 8:11-12, Dan 8:13, Dan 8:14, Dan 8:26) — retrieve with FULL chapter context
     - **The forensic frame — Daniel 7 and 9:24** (Dan 7:9-10, Dan 7:22, Dan 7:26, Dan 9:24) — retrieve with FULL chapter context
     - **Ritual-cleansing negative controls** (Lev 16:19, Lev 16:30, Lev 17:11, Lev 23:27-30, Mal 3:3...)
     - **tsadaq forensic + parallelism corpus** (Job 4:17, Job 9:2, Job 25:4, Job 40:8, Isa 43:9...)
     - **Cleansing-within-vindication model** (Zech 3:4, Zech 3:1-5) — retrieve with FULL chapter context
     - **kaphar->tsadaq bridge into the NT** (Rom 3:24-26, Heb 9:22-23) — retrieve with FULL chapter context
     - **Cosmic vindication** (Rev 15:3-4, Rev 16:5-7, Rev 19:2)
     - **All additional verses from Nave's topic entries**
   - `04-word-studies.md` — Strong's research:
     - **FROM LIBRARY (read, don't re-derive):** H6663 (tsadaq), H2891 (taher), H3722 (kaphar)
     - **FRESH LOOKUPS (no library entry):** H6664 (tsedeq), H6666 (tsedaqah), H6662 (tsaddiq), H2135 (zakah), H4823 (mirmac), H6588 (pesha), H4941 (mishpat), H1780 (din (Aramaic)), G1344 (dikaioo), G2511 (katharizo), G2643 (katallage/hilasterion cluster), G1342 (dikaios)
   - `raw-data/` — Raw tool output organized by category
6. Do NOT write `03-analysis.md` or `CONCLUSION.md` — those are for the analysis agent

### Specific Research Directives

7. **Priority verses to retrieve with FULL CHAPTER context:**
   - Dan 8:1-27
   - Dan 7:9-27
   - Dan 9:20-27
   - Lev 16:1-34
   - Job 25:1-6
   - Zech 3:1-10
   - Rom 3:19-31
   - Heb 9:1-28

8. **Required Greek/Hebrew parsing:**
   - Dan 8:14 — Confirm nitsdaq = Niphal Perfect 3ms of tsadaq (sole Niphal in OT); divine passive; qodesh as subject
   - Dan 8:13 — Parse pesha/shamem/mirmac and the ad-matay 'how long' question structure
   - Dan 9:24 — Confirm kaphar and tsedeq both present — the bridge verse
   - Job 25:4 — tsadaq || zakah parallelism — the inclusion overlap
   - Job 4:17 — sdq form and its LXX rendering (katharos?) — verify Davidson's claim
   - Isa 50:8 — tsadaq in the Servant's courtroom vindication
   - Psa 51:4 — tsadaq 'be justified when judged' in a purification psalm
   - Rom 3:26 — dikaios kai dikaiounta — atonement grounding the verdict
   - Heb 9:23 — katharizo for the heavenly sanctuary — the standing objection
   - Rev 15:3 — dikaios/dikaioma — cosmic vindication

9. **Required cross-testament parallels** (run BOTH --hybrid-ot AND --hybrid-nt):
   - Dan 8:14 — OT/NT parallels for the sanctuary being set right/vindicated
   - Dan 7:9-10 — The judgment-scene network (Rev 15/16/19)
   - Job 4:17 — sdq || purity parallelism and its LXX rendering
   - Zech 3:4 — cleansing-within-vindication courtroom model
   - Dan 9:24 — kaphar->tsadaq bridge parallels into Rom 3

10. **Required word traces:**
   - H6664 (tsedeq) — run search_strongs.py --lookup and --verses
   - H6666 (tsedaqah) — run search_strongs.py --lookup and --verses
   - H6662 (tsaddiq) — run search_strongs.py --lookup and --verses
   - H2135 (zakah) — run search_strongs.py --lookup and --verses
   - H4823 (mirmac) — run search_strongs.py --lookup and --verses
   - H6588 (pesha) — run search_strongs.py --lookup and --verses
   - H4941 (mishpat) — run search_strongs.py --lookup and --verses
   - H1780 (din (Aramaic)) — run search_strongs.py --lookup and --verses
   - G1344 (dikaioo) — run search_strongs.py --lookup and --verses
   - G2511 (katharizo) — run search_strongs.py --lookup and --verses
   - G2643 (katallage/hilasterion cluster) — run search_strongs.py --lookup and --verses
   - G1342 (dikaios) — run search_strongs.py --lookup and --verses

**Required deterministic LXX occurrence audits:**
- G1344 (dikaioo) — run `python "$SKILL_DIR/lxx_inventory.py" G1344`; copy every row and corpus field, then add the required target classifications

11. **External corpus verification directives:**
   - 'cleansed' is an ACCEPTABLE translation because tsadaq's cultic sense INCLUDES the purification dimension (inclusion, not because tsadaq means 'cleanse') (Bohr/Augsburger (SU GPOT2V1 Lesson #14 pp.442-449)) — verify against the parallelism data (Job 4:17,25:4; Psa 51:4) and DOA-as-judgment (Lev 23:27-30); this is the pro-inclusion external voice for sub-question 3
   - 'cleansed' is a MISTRANSLATION; Hebrew=tsadaq/vindicate not taher/cleanse, so cleansing is displaced/excluded (Desmond Ford (via Bohr's framing)) — test the strong displacement form against Dan 9:24, Zech 3, Job 25:4; agree that tsadaq is the more precise word, decide whether cleansing is truly EXCLUDED
   - sdq stands in poetic parallelism with taher/zakah/bor; LXX renders tsadaq with katharos at Job 4:17; tsadaq is the larger category that includes cleansing (Richard M. Davidson, JATS 7/1 (1996)) — verify the parallelisms and the Job 4:17 LXX rendering against the local corpus (focus areas 5,10) — the load-bearing inclusion proof
   - nitsdaq answers the trampling/usurpation of 8:13 with restoration-to-rights that includes cultic setting-right (Martin Probstle, 'Truth and Terror' (Andrews diss. 2006)) — verify the 8:9-13 verb inventory (usurpation vs defilement) supports an injustice->justice answer (focus area 2)
   - nitsdaq = 'restored to its rightful state'; broadly away from ritual cleansing toward restore/vindicate (referent = Antiochus, a separable question) (Critical scholarship (Collins Hermeneia; Goldingay WBC)) — note the convergence with the historicist lexical conclusion (both move away from 'cleanse'); keep the MEANING question distinct from the REFERENT question
   - 'the cleansing of the sanctuary is the work of judgment' — her 'cleansing' language already carries the judgment/verdict content (EGW (BR-ASI9 156.5)) — use as a LEAD pointing to primary sources (Davidson/Augsburger), NOT as historical/analytical authority; supports that 'cleansed' and 'vindicated' name one judicial event
   - the assumption OG=justify vs Theodotion=cleanse may be wrong; both recensions may read katharisthesetai (cleanse) (Web research (Old Greek/Theodotion textual question)) — MANDATORY verification against the local LXX corpus (focus area 10); do not assert the split until confirmed

12. **Grammar reference entries to read:**
   - `$GRAMMAR_REF/hebrew/stem-niphal.md` — Niphal stem — passive/reflexive/tolerative; the stem of nitsdaq

### Additional Research Instructions

This study unifies THREE sub-questions in order (better rendering -> proper response to 8:13 -> includes cleansing) into ONE coherent thesis; the inclusion finding must NOT read as walking back the 'vindicated is better' finding — resolve via the hierarchy vindication contains cleansing. THREE mandatory adjudications: (1) decide inclusion vs displacement vs cleansing-primary among the three candidate categories, with calibrated language given nitsdaq is a hapax stem-form; (2) VERIFY the Old Greek LXX vs Theodotion text of Dan 8:14 against the local corpus before asserting any dikaioo/katharizo split (focus area 10) — web research warns the assumed split may be wrong; (3) engage Bohr/Augsburger (inclusion) vs Ford (displacement) head-to-head, naming agreements with each. GUARD against overreach on taher (do not argue it is narrow/restricted — Mal 3:3, Ezek 36:25 show its breadth); rest the inclusion case on tsadaq's breadth (Davidson's parallelisms). Carry the settled Heb 9:23 katharizo resolution (broader tsadaq encompasses narrower katharizo) rather than re-deriving it. Treat EGW/Bohr as leads to primary sources, not authorities.

## Workflow
answer-question

---
*Scoped from prompt.json*
*Folder: daniel-8-14-vindicated-response-includes-cleansing/*