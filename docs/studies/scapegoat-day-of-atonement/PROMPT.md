# Bible Study: What does the scapegoat represent on the Day of Atonement?

## Question
What does the scapegoat represent on the Day of Atonement?

**Prompt schema:** v2

## Prior Research Summary
Five prior studies were read in full. doa-two-goats-referents (the closest match) and sanc-11-two-goats-typology answer the referent question directly with a three-axis framework (grammatical-object / functional-conceptual / material-subtype). Established findings: (1) Lev 16:10 lekapper alav = atonement made OVER/concerning the live goat, not BY it (same kipper-al construction as the altar, 16:18); (2) the live goat is presented ALIVE and NOT slain, and blood-atonement is completed (kalah, 16:20) BEFORE the live goat is handled; (3) referent verdict: NOT Christ (necessary inference, because NT keeps Christ's sin-bearing in the Godward priestly/Lamb register while the scapegoat goes wilderness-ward), and CORRESPONDS TO Satan bound (Rev 20:1-3) at reasonable-inference strength. The two mandated Rev-20 studies supply the eschatological correspondence and its limits. A tension exists between the H5799-azazel.md library entry ('goat of departure/removal', descriptive) and prior conclusions (BHSA PropN -> personal entity); the material_subtype axis must reconcile this. This study must re-verify from Scripture, build on prior work via structural_constraints, and NOT merely duplicate.

## Authorial Vernacular Audit

**Scope:** Priestly / Torah sacrificial vocabulary — Leviticus, Exodus, Numbers

### cat-blood-atonement-vs-live-goat: When Scripture makes atonement BY a slain animal (kaphar + blood) vs. the live goat which is NOT slain

**Candidate categories:** cand-removal-of-sin, cand-christ

**Focus area:** 3

**Direct-label passages:**
- Lev 16:15: The LORD's goat IS killed (shachat) and its blood brought within the veil = blood-atonement BY the animal.
- Lev 17:11: 'It is the blood that maketh an atonement for the soul' — atonement is predicated on blood/life.
- Lev 16:18: kipper-al applied to the altar (an object acted upon), the same construction as the live goat in 16:10.

**Structural analogies:**
- Lev 4:20: kaphar + blood -> salach (forgiveness)
- Lev 14:4-7: two-bird leper rite: one killed, one released alive (shalach)

**Negative controls:**
- Lev 16:10: The live goat is 'presented alive' (yaomad) and explicitly NOT slain; the atonement is made OVER it (lekapper alav), not BY its blood.
- Heb 9:22: 'Without shedding of blood is no remission' — forecloses the live goat (which sheds none) being the propitiation.

**Required searches:**
- `cd "$TOOLS/search" && python search_strongs.py --verses H3722 KJV`
- `cd "$TOOLS/search" && python search_strongs.py --verses H7819 KJV`

### cat-redemptive-sinbearer-vs-judicial-removal: When Scripture names a sin-bearer who atones redemptively (Christ) vs. a figure who bears sin as judicial removal (scapegoat)

**Candidate categories:** cand-christ, cand-satan, cand-removal-of-sin

**Focus area:** 5

**Direct-label passages:**
- Isa 53:11-12: The Servant 'shall bear (nasa/sabal) their iniquities' paired with intercession (paga Hiphil) = redemptive/priestly register.
- John 1:29: 'the Lamb of God, which taketh away (airo) the sin of the world' — Christ's sin-removal in the Lamb register.
- Heb 9:28: Christ 'was once offered to bear (anaphero) the sins of many' — priestly, God-ward direction.
- 1 Pet 2:24: 'bare our sins in his own body on the tree' (anaphero) — redemptive sin-bearing.

**Structural analogies:**
- Exo 28:38: priest bears (nasa) iniquity God-ward for acceptance
- Exo 34:7: God forgives (nasa) iniquity

**Negative controls:**
- Lev 16:22: The live goat 'shall bear (nasa) upon him all their iniquities unto a land not inhabited' — removal register, wilderness-ward.
- Lev 16:21: Sin is PLACED on the goat (natan al-rosh) by confession, not redemptively borne by voluntary self-offering.

**Required searches:**
- `cd "$TOOLS/search" && python search_strongs.py --verses H5375 KJV`
- `cd "$TOOLS/search" && python cross_testament_parallels_v2.py "Lev 16:22" --hybrid-nt`

### cat-cultic-dispatch-to-a-wilderness-being: When the Torah names cultic dispatch TO a wilderness/goat-being (a recipient) vs. mere disposal to an uninhabited place (a destination)

**Candidate categories:** cand-demon-destination, cand-removal-of-sin

**Focus area:** 9

**Direct-label passages:**
- Lev 17:7: The one Torah text that names Israel sacrificing 'unto devils' (la-se'irim, goat-demons of the open field) — the only Priestly vocabulary for cultic offering directed TO a wilderness goat-being. Tests whether Lev 16 uses the same recipient framing for Azazel.

**Structural analogies:**
- Lev 16:10: la-azazel ha-midbarah — lamed + Azazel + directional he to the wilderness

**Negative controls:**
- Lev 16:22: The goal is stated as erets gezerah, a 'land not inhabited' — an empty PLACE, with no offering-verb (zabach/qarab) directed at any being there.
- Lev 16:26: The man who leads the goat away is defiled and must wash — a contamination-transfer/disposal signal, not a propitiatory sacrifice to a deity.

**Required searches:**
- `cd "$TOOLS/search" && python search_strongs.py --verses H8163 KJV`
- `cd "$TOOLS/search" && python search_strongs.py --verses H5799 KJV`

## Identity Axes

- **Grammatical relationship of atonement to the live goat** (required): Is atonement made BY the goat or made OVER/concerning it? The Lev 16:10 crux: does lekapper alav ('to make atonement over/upon it') mark the goat as an object acted upon (like the altar in 16:18, kipper-al) rather than a co-propitiator? What verbs govern the live goat (shalach send away, nasa bear, natan al-rosh impute) vs. the LORD's goat (shachat slaughter)?
- **What the live-goat rite DOES functionally** (required): Does the live-goat rite atone (blood-propitiation), remove/dispose of confessed sin, or judicially consign it? Where does it fall in the ritual sequence relative to the completion (kalah, 16:20) of blood-atonement?
- **What Azazel is referentially** (required): Is Azazel (H5799) a proper name of a being, a place (rugged wilderness/cliff), or a common noun ('goat that departs' / 'complete removal')? Resolve the tension between the compound-etymology (ez+azal, descriptive) reading and the BHSA proper-noun parse + la-YHWH // la-Azazel parallelism (16:8).
- **Whether the goat redeems / bears sin sacrificially** (optional): Does the live goat redeem or bear sin sacrificially (contributing to salvation), or does it merely carry away / receive already-atoned guilt (a non-redemptive function)? Does the text ever call it a sacrifice (zabach)?
- **Typological referent (if any)** (optional): If the live goat is typological, does it point to Christ, to Satan, or to neither? What controls (direction of sin-bearing, blood vs. no-blood, killed vs. alive) decide the mapping?

## Available Library Entries

### Word Studies

- `$WORD_STUDIES/H5799-azazel.md` — azazel (scapegoat), H5799 — NOTE tension: leans 'goat of departure/removal' descriptive vs. prior-study PropN reading
- `$WORD_STUDIES/H8163-saiyr.md` — sa'ir (goat / hairy one / se'irim), H8163
- `$WORD_STUDIES/H5375-nasa.md` — nasa (bear/carry/forgive), H5375
- `$WORD_STUDIES/TR-nasa-airo.md` — Translation relationship nasa -> airo (LXX/NT)
- `$WORD_STUDIES/H3722-kaphar.md` — kaphar (atone/cover/expiate), H3722
- `$WORD_STUDIES/H3615-kalah.md` — kalah (complete/finish/make an end), H3615
- `$WORD_STUDIES/TR-kalah-synteleo.md` — Translation relationship kalah -> synteleo
- `$WORD_STUDIES/H7819-shachat.md` — shachat (slaughter), H7819
- `$WORD_STUDIES/TR-shachat-sphazo.md` — Translation relationship shachat -> sphazo
- `$WORD_STUDIES/H7971-shalach.md` — shalach (send away), H7971
- `$WORD_STUDIES/TR-shalach-apostello.md` — Translation relationship shalach -> apostello
- `$WORD_STUDIES/H3034-yadah.md` — yadah (confess/give thanks), H3034
- `$WORD_STUDIES/TR-yadah-exomologeo.md` — Translation relationship yadah -> exomologeo
- `$WORD_STUDIES/H5414-nathan.md` — nathan (give/put/place), H5414
- `$WORD_STUDIES/H6261-ittiy.md` — ittiy (fit/ready/timely) — ish itti, H6261
- `$WORD_STUDIES/H4057-midbar.md` — midbar (wilderness/desert), H4057
- `$WORD_STUDIES/H1509-gzerah.md` — gezerah (separation/solitary) — erets gezerah, H1509 (the flagged 'gap' entry EXISTS)
- `$WORD_STUDIES/H2403-chattaah.md` — chattaah (sin/sin-offering), H2403
- `$WORD_STUDIES/H5771-avon.md` — avon (iniquity), H5771
- `$WORD_STUDIES/H6588-pesha.md` — pesha (transgression/rebellion), H6588
- `$WORD_STUDIES/TR-avon-adikia.md` — Translation relationship avon -> adikia
- `$WORD_STUDIES/TR-chattaah-hamartia.md` — Translation relationship chattaah -> hamartia
- `$WORD_STUDIES/TR-kapporeth-hilasterion.md` — Translation relationship kapporeth -> hilasterion (mercy-seat)
- `$WORD_STUDIES/H7126-qarab.md` — qarab (bring near/present/offer), H7126

### Grammar References

- `$GRAMMAR_REF/passages/lev-16-20-22.md` — Lev 16:20-22 scapegoat-dispatch grammar (kalah completion + nasa removal)
- `$GRAMMAR_REF/passages/lev-16-21-sin-terms.md` — Lev 16:21 kol + avon/pesha/chattat sin triad
- `$GRAMMAR_REF/passages/lev-16-14-16.md` — Lev 16:14-16 blood-atonement grammar
- `$GRAMMAR_REF/passages/lev-16-30.md` — Lev 16:30 kaphar + taher (cleanse) grammar

### Missing Library Entries (generate)

- G399 anaphero — Christ's God-ward sin-bearing (Heb 9:28; 1 Pet 2:24) — no dedicated entry found; central to the direction argument
- G142 airo — Lamb 'taketh away' sin (John 1:29) — no dedicated entry found; Lamb register
- G2435 hilasterion — mercy-seat/propitiation (Rom 3:25) — TR-kapporeth-hilasterion exists but no standalone G2435 entry
- H8549 tamiym — unblemished/perfect — TR-tamiym-amomos referenced in 00-references but no standalone H8549 entry located in the ls output; verify
- natan al-rosh (imputation gesture) — The 'put upon the head' imputation construction has no dedicated grammar note; flagged in 00-references

### Strong's Numbers

| Strong's | Word | Relevance | Library Entry |
|----------|------|-----------|---------------|
| H5799 | azazel | The central disputed term; material_subtype axis; near-hapax in Lev 16 | yes |
| H8163 | sa'ir (goat) | Both goats are sa'ir; connects to se'irim/'devils' in Lev 17:7 | yes |
| H5375 | nasa (bear/carry) | Lev 16:22 sin-bearing; three registers; direction decides referent | yes |
| H3722 | kaphar (atone/cover) | The Lev 16:10 crux verb; spans blood-propitiation and removal | yes |
| H3615 | kalah (complete/finish) | Lev 16:20 completion marker; propitiation precedes elimination | yes |
| H7819 | shachat (slaughter) | Governs the LORD's goat (16:15); the live goat is NOT shachat | yes |
| H7971 | shalach (send away) | Governs the live goat (16:21); non-sacrificial dispatch | yes |
| H3034 | yadah (confess) | Lev 16:21 confession over the live goat's head | yes |
| H5414 | nathan (put/place) | natan al-rosh, imputation of sin onto the goat's head (16:21) | yes |
| H6261 | ittiy (fit/ready man) | ish itti hapax (16:21); nameless functional agent | yes |
| H4057 | midbar (wilderness) | Destination of the live goat; desolation motif | yes |
| H1509 | gezerah (separation/solitary) | erets gezerah, 'land not inhabited' (16:22); hapax destination | yes |
| H2403 | chattaah (sin/sin-offering) | Lev 16:5 'one sin offering'; sin triad member | yes |
| H5771 | avon (iniquity) | Sin triad in the confession (16:21) | yes |
| H6588 | pesha (transgression) | Sin triad in the confession (16:21) | yes |
| H8549 | tamiym (unblemished/perfect) | Blemish-free requirement (Lev 22:20-21); Christ-view argument | (missing) |
| H2891 | taher (cleanse) | Lev 16:30 'to cleanse you'; the day cleanses the sanctuary | (missing) |
| G399 | anaphero (bear up/offer) | Christ's God-ward sin-bearing (Heb 9:28; 1 Pet 2:24) vs. scapegoat's wilderness-ward | (missing) |
| G142 | airo (take away) | Christ the Lamb 'taketh away' sin (John 1:29); Lamb register | (missing) |
| G2435 | hilasterion (mercy-seat/propitiation) | LXX renders kapporeth; Rom 3:25 applies to Christ = LORD's-goat/mercy-seat bridge | (missing) |

## Discovered Scope

### Topics Found (from naves_semantic.py)

| Topic | Subtopic | Verse Count |
|-------|----------|-------------|
| AZAZEL | GENERAL | 1 |
| SCAPEGOAT | GENERAL | 1 |
| ATONEMENT | DAY OF / BY ANIMAL SACRIFICES / BY JESUS | 100 |
| GOAT | SACRIFICE | 20 |
| SANCTUARY | HOLY OF HOLIES | 10 |
| PRIEST | HIGH PRIEST | 30 |
| REDEMPTION | OF SOULS | 15 |
| LAMB OF GOD | GENERAL | 20 |
| FORGIVENESS | OF SIN | 20 |
| CONFESSION | OF SIN | 20 |
| SATAN | JUDGMENT/BINDING | 30 |
| WILDERNESS | TYPICAL OF SINNER'S STATE | 5 |
| SACRIFICES | GENERAL | 40 |
| BLOOD | ATONEMENT | 30 |

### Primary Verses (39 — full analysis required)

**The two-goat rite (Leviticus 16):**
_The primary passage — retrieve with full chapter context_
- Lev 16:5 — Two goats taken 'for a sin offering' (chattat) — does one chattat govern both goats (Christ-view basis)?
- Lev 16:7 — Both goats presented before the LORD at the door of the tabernacle prior to the casting of lots
- Lev 16:8 — Lots cast: 'one lot for the LORD, and the other lot for the scapegoat (Azazel)' — the la-YHWH // la-Azazel parallelism crux
- Lev 16:9 — The LORD's-lot goat is offered as a sin offering
- Lev 16:10 — THE crux: the Azazel goat is 'presented alive' (yaomad) to make atonement over/upon it (lekapper alav) and sent away to the wilderness
- Lev 16:11 — Aaron brings the bullock of the sin offering for himself — establishes the blood-atonement sequence
- Lev 16:14 — Blood of the bullock sprinkled on/before the mercy seat — blood-atonement mechanism
- Lev 16:15 — The LORD's goat KILLED (shachat); its blood brought within the veil — blood-atonement BY the slain goat
- Lev 16:16 — kaphar for the holy place because of the uncleanness/transgressions/sins of Israel — the sanctuary is cleansed
- Lev 16:17 — kaphar ba'ad (for/on behalf of) himself, his house, and the congregation — beneficiary construction contrast
- Lev 16:18 — kipper-al applied to the altar — same 'atone upon/over' construction as the live goat in 16:10 (object acted upon)
- Lev 16:19 — Cleanse and hallow the altar — completes the purgation phase
- Lev 16:20 — vekhillah mikapper (kalah): 'made an end of reconciling/atoning' BEFORE the live goat is brought — the completion marker
- Lev 16:21 — Aaron lays both hands on the live goat, confesses (yadah) all iniquities/transgressions/sins, putting them on its head (natan al-rosh); sent by a fit man (ish itti)
- Lev 16:22 — The goat shall BEAR (nasa) upon him all their iniquities to a land not inhabited (erets gezerah) — removal register, wilderness-ward
- Lev 16:23 — Aaron returns, changes garments — marks the live-goat rite as a distinct phase
- Lev 16:24 — kaphar for himself and the people via burnt offerings — further completion
- Lev 16:26 — The man who led away the goat 'for Azazel' must wash — third and final Azazel occurrence; ritual-impurity note on the handler
- Lev 16:27 — The sin-offering carcasses burned outside the camp — 'outside the camp' motif (cf. Heb 13:11-13)
- Lev 16:30 — 'on that day shall the priest make atonement (kaphar) for you, to cleanse (taher) you' — the day cleanses
- Lev 16:33-34 — kaphar for the sanctuary, priests, and all the people once a year — the annual scope of the day

**Blood-atonement and sacrificial-vocabulary controls:**
_What atonement BY blood looks like_
- Lev 17:11 — 'It is the blood that maketh an atonement for the soul' — atonement predicated on blood/life (the live goat sheds none)
- Lev 4:20 — The daily chattat: kaphar + blood -> salach (forgiveness); contrast Lev 16 where salach of the live goat is absent
- Lev 14:4-7 — Two-bird leper rite: one killed, one released alive (shalach) — the one-killed/one-released Levitical template

**nasa sin-bearing across registers:**
_Divine / priestly / removal registers_
- Exo 34:7 — God forgives (nasa) iniquity/transgression/sin — DIVINE register of nasa; establishes nasa is register-neutral
- Exo 28:38 — The priest BEARS (nasa) iniquity God-ward for acceptance — PRIESTLY register of nasa
- Isa 53:4-6 — The Servant bears our griefs/carries our sorrows; iniquity laid on him — sin-bearer language to test against the scapegoat
- Isa 53:11-12 — 'he shall bear (nasa/sabal) their iniquities' + intercession (paga) — redemptive/priestly sin-bearing register

**Christ the sin-bearer / High Priest (NT fulfillment):**
_Godward, Lamb, and priestly registers_
- John 1:29 — 'the Lamb of God, which taketh away (airo) the sin of the world' — Christ's sin-removal in the Lamb register, not the goat register
- Heb 9:7 — The high priest enters the second veil once a year with blood — DOA background applied to Christ
- Heb 9:11-12 — Christ enters by his own blood, obtaining eternal redemption — Christ = LORD's-goat + High-Priest role
- Heb 9:22 — 'without shedding of blood is no remission' — forecloses the live goat (bloodless) being the propitiation
- Heb 9:24-26 — Christ appears in God's presence for us and put away sin by the sacrifice of himself — Godward direction
- Heb 9:28 — Christ 'once offered to bear (anaphero) the sins of many' — priestly, God-ward bearing (not wilderness-ward)
- Heb 13:11-13 — 'the bodies... are burned without the camp'; Jesus suffered 'without the gate' — the 'outside the camp' motif and which goat it maps to
- 1 Pet 2:24 — 'bare (anaphero) our sins in his own body on the tree' — redemptive sin-bearing register for Christ
- Rom 3:24-26 — Christ set forth as a propitiation (hilasterion, LXX = kapporeth/mercy-seat) — the LORD's-goat/mercy-seat bridge
- Gal 3:13 — Christ 'made a curse for us' — a facet of Christ's sin-dealing beyond the two-goat type (guards against over-mapping)

**Adversary / judgment correspondence:**
_Satan bound; do NOT over-weight_
- Rev 20:1-3 — Satan bound alive, sealed in the abyss/desolation for a season — the correspondence tested against the six markers of the live-goat rite

### Supporting Verses (11 — retrieve for context, no individual analysis)

- Lev 22:20-21 — Sacrifices must be without blemish — the Christ-view's 'blemish-free excludes Satan' argument; test whether it applies to the live goat
- Lev 10:17 — The priest bears (nasa) the iniquity of the congregation to make atonement — priestly register
- Lev 23:27-32 — The Day of Atonement appointed: afflict souls, a day of kaphar
- Num 29:7-11 — DOA offerings prescribed — corroborates the annual rite's sacrificial structure
- Lev 17:7 — 'no more offer their sacrifices unto devils (se'irim)' — tests whether 'for Azazel' implies an offering to a being (it does not; goat is sent, not sacrificed)
- Zec 3:1-2 — Satan as accuser/adversary standing before the LORD — adversary background
- 1 John 3:8 — 'the devil sinneth from the beginning' — the 'originator of sin' framing (verify here, not in Lev 16)
- Rev 20:10 — Satan's final destruction in the lake of fire — shows Rev 20 EXCEEDS the type (release, lake of fire)
- Gen 3:15 — Protoevangelium — enmity/adversary framework, seed bruising the serpent
- Mat 27:15-26 — Barabbas/Jesus: two subjects, one released one condemned — an inverted historical echo of the two-goat pattern (guilty freed)
- Num 8:19 — Levites given to bear (nasa) / make atonement — priestly-bearing register control

### Focus Areas

1. **The Lev 16:8 lots and the la-YHWH // la-Azazel parallelism:**
This is the single most-cited grammatical argument in the identity dispute. READ $WORD_STUDIES/H5799-azazel.md and NOTE its stated tension: the entry frames Azazel via ez+azal ('goat of departure', descriptive) and observes KJV/Septuagint (apopompaios) treat it descriptively, while modern translations transliterate as a proper name. Prior studies (sanc-11, doa-two-goats) report the BHSA parses azazel as PropN.ms.Abs at each of the four attestations and that la-YHWH // la-azazel (16:8) is the only place in Scripture a non-divine entity receives the same lamed+noun framing as the divine name. The research agent must RECONCILE the compound-etymology reading with the BHSA proper-noun parse rather than assume either. Run hebrew_parser.py on Lev 16:8 to confirm the morphological parse of azazel and the lamed constructions. Test the counter-argument: does the same lamed in 16:10 (la-azazel ha-midbarah, 'for Azazel to the wilderness') mark a DESTINATION rather than a recipient? Retrieve Lev 16:7-10 with full context. The material_subtype axis turns on this; state the result as 'PropN parse PRESSURES but does not PROVE a personal referent' (prior-study calibration).
**Verses:** Lev 16:7, Lev 16:8, Lev 16:9, Lev 16:10, Lev 16:26
**Strong's:** H5799, H8163, H1486

2. **The Lev 16:10 crux — lekapper alav: atonement BY the goat or OVER the goat?:**
The crux of the whole study. READ $WORD_STUDIES/H3722-kaphar.md and $GRAMMAR_REF/passages/lev-16-20-22.md (and lev-16-14-16.md if present). Prior work (doa-two-goats) established that lekapper alav uses the same kipper-al construction applied to the ALTAR in 16:18 — an inanimate object acted upon — not the kipper-ba'ad (for/on behalf of) beneficiary construction of 16:17. Run hebrew_parser.py on Lev 16:10, 16:16, 16:17, and 16:18 to display the al vs ba'ad prepositional contrast. Note the verb yaomad (Hophal, 'is presented/made to stand') marks the goat as passive. Because the live goat sheds no blood and Heb 9:22 predicates remission on blood, the 'atonement' associated with the live goat cannot be a second blood-propitiation. State the grammatical-object axis result: atonement is made OVER/concerning the goat, and the goat is the terminus of a disposal act, not a propitiator. This forecloses cand-christ's strongest grammatical claim if confirmed.
**Verses:** Lev 16:10, Lev 16:16, Lev 16:17, Lev 16:18, Lev 17:11
**Strong's:** H3722, H3725, H5975

3. **Killed vs. alive: shachat, blood, and the no-blood control (Heb 9:22):**
The negative control for the audit. READ $WORD_STUDIES/H7819-shachat.md (+ TR-shachat-sphazo.md) and $WORD_STUDIES/H8163-saiyr.md. Lev 16:15 governs the LORD's goat with shachat (slaughter) and brings its blood within the veil; Lev 16:10/21-22 govern the live goat with 'presented alive' (yaomad), shalach (send away), and nasa (bear), never shachat or zabach. Run hebrew_parser.py on Lev 16:15 to confirm shachat and on Lev 16:10 to confirm the live goat is NOT slain. Establish from Lev 17:11 ('the blood... maketh atonement') and Heb 9:22 ('without shedding of blood is no remission') that the bloodless live goat cannot be the propitiation — foreclosing the notion that the live goat atones by sacrifice. This grounds redemptive_action = the live goat does NOT redeem/atone sacrificially. Note the two goats belong to ONE chattat (16:5) yet perform mutually exclusive acts — address the Christ-view's 'one sin offering' argument here: does one chattat designation unify their FUNCTION, or does the ritual divide labor (one pays by death, one removes)?
**Verses:** Lev 16:5, Lev 16:15, Lev 16:9, Lev 17:11, Heb 9:22
**Strong's:** H7819, H8163, H2403, H1818

4. **The kalah completion sequence — propitiation precedes elimination:**
The sequencing pillar. READ $WORD_STUDIES/H3615-kalah.md (+ TR-kalah-synteleo.md) and $GRAMMAR_REF/passages/lev-16-20-22.md. Lev 16:20 opens 'And when he hath made an end (vekhillah, Piel of kalah H3615) of reconciling (mikapper) the holy place...' THEN 'he shall bring the live goat.' Run hebrew_parser.py on Lev 16:20 to display the Piel kalah + min-kaphar construction. Establish the three ordered phases: cleanse the sanctuary by blood (16:15-19) -> CLOSE/complete atonement (16:20) -> dispose of sin via the live goat (16:21-22). Because the live-goat rite is explicitly sequenced AFTER completion, it is a distinct terminal act, not part of the propitiation. Verify Bohr's three-point structure (kalah-sequence + no-blood/not-a-sacrifice + Rev 20 alive-on-desolate-earth) as a research directive against Lev 16:20, Heb 9:22, Rev 20:1-3. Note salach (forgiveness) is ABSENT from Lev 16 (contrast the daily rite, Lev 4:20 kaphar->salach): the day CLEANSES the sanctuary (kaphar + taher, 16:30), it does not itself pronounce individual forgiveness — a further sign the live goat is disposal, not remission.
**Verses:** Lev 16:19, Lev 16:20, Lev 16:21, Lev 16:30, Lev 4:20
**Strong's:** H3615, H3722, H2891, H5545

5. **nasa across three registers — direction decides the referent:**
The load-bearing argument for cand-christ elimination. READ $WORD_STUDIES/H5375-nasa.md (+ TR-nasa-airo.md), $WORD_STUDIES/H4057-midbar.md, and $WORD_STUDIES/H1509-gzerah.md (the erets gezerah / 'land not inhabited' destination — the flagged 'gap' entry actually EXISTS; use it). Establish nasa's three registers from tool output: DIVINE (God forgives iniquity, Exo 34:7), PRIESTLY (priest bears God-ward for acceptance, Exo 28:38; Lev 10:17), and REMOVAL (scapegoat carries away to desolation, Lev 16:22). Isa 53:11-12 pairs nasa/sabal with intercession (paga Hiphil) = priestly register; John 1:29 uses airo (Lamb register); Heb 9:28 and 1 Pet 2:24 use anaphero (God-ward priestly). Run cross_testament_parallels_v2.py on Lev 16:22 --hybrid-nt to surface how the NT renders sin-bearing. Because nasa itself is neutral, DIRECTION decides: the scapegoat goes wilderness-ward (banishment to erets gezerah, a solitary land), while Christ bears sin God-ward (Heb 9:24). Conclude: Christ occupies the LORD's-goat + High-Priest roles, NOT the scapegoat. Resolve Lev 17:7 (se'irim/'devils') — the goat is SENT (shalach)/BEARS (nasa), never SACRIFICED (zabach), so 'for Azazel' is a destination for dispatched sin, not an offering to a being.
**Verses:** Lev 16:22, Isa 53:11-12, Exo 28:38, Exo 34:7, John 1:29, Heb 9:28, 1 Pet 2:24
**Strong's:** H5375, H4057, H1509, G399, G142

6. **Confession and imputation — natan al-rosh vs. voluntary self-offering:**
Distinguishes the mode of sin-transfer. READ $WORD_STUDIES/H3034-yadah.md (+ TR-yadah-exomologeo.md), $WORD_STUDIES/H5414-nathan.md, $WORD_STUDIES/H6261-ittiy.md, and $GRAMMAR_REF/passages/lev-16-21-sin-terms.md (the kol + avon/pesha/chattat triad). Run hebrew_parser.py on Lev 16:21 to display the two-handed gesture, the confession verb yadah (Hithpael), and natan al-rosh ('put upon the head'). Note the sin triad avon (H5771)/pesha (H6588)/chattat (H2403) — the full inventory of confessed sin. Contrast this imputation-onto-a-recipient with Christ's voluntary self-offering (Heb 9:14, 'offered himself'). The scapegoat does not consent or intercede; sin is placed ON it. The handler is an ish itti (H6261, hapax, 'fit/ready man', not a priestly title). This supports a judicial/removal reading and pressures the 'originator receives sin back' (Satan) framing — but verify the 'originator of sin' claim against 1 John 3:8, NOT against Lev 16 which does not state it. Guard: natan al-rosh is imputation of guilt onto a bearer, which the text presents without specifying the bearer's identity.
**Verses:** Lev 16:21, Lev 16:22, Lev 16:26
**Strong's:** H3034, H5414, H6261, H5771, H6588, H2403

7. **The 'one sin offering', blemish-free, and 'outside the camp' — the Christ-view's biblical case:**
Engage cand-christ's biblical case directly. READ $WORD_STUDIES/H2403-chattaah.md. Retrieve Lev 16:5 and 16:27 with context. Verify Answering Adventism's claim that Lev 16:5 makes both goats 'one sin offering' (chattat): run hebrew_parser.py on Lev 16:5 — is chattat singular governing both, and does shared designation entail shared FUNCTION, or division of labor (one dies to pay, one is sent to remove)? Test the blemish-free argument (Lev 22:20-21): does Lev 16 require the LIVE goat to be unblemished, and if so does that bear on identity? Critically examine the 'outside the camp' motif: Heb 13:11-13 says the sin-offering BODIES are burned outside the camp and Jesus suffered outside the gate — run cross_testament_parallels_v2.py on Lev 16:27 and check whether Hebrews maps 'outside the camp' onto the SLAIN goat's carcass (16:27) or the LIVE goat's banishment (16:21-22); these are different rites. Verify Heb 9:26 ('put away sin by the sacrifice of himself') keeps Christ's sin-removal in the sacrificial/God-ward register. Weigh the patristic two-goat typology (Barnabas 7; Justin, Dial. 40) as ancient interpretation, NOT Scripture — verify only what Lev 16 states.
**Verses:** Lev 16:5, Lev 16:27, Lev 22:20-21, John 1:29, Heb 9:24-26, Heb 13:11-13
**Strong's:** H2403, H8549, G266

8. **The six-marker correspondence to Rev 20:1-3 — and its limits:**
Calibrate the Satan correspondence. Do NOT over-weight Rev 20 — this study is Leviticus-first. Retrieve Rev 20:1-3 (and 20:7, 20:10 for limits). The prior Rev-20 studies established a SIX-element correspondence with Lev 16:20-22: (1) after completed atonement (16:20 // Rev 20 post-cross era); (2) living creature not killed, goes alive (16:10 // Satan bound alive); (3) nameless functional agent (ish itti, 16:21 // the angel with the key); (4) desolate destination (erets gezerah, 16:22 // the abyss); (5) sin imputed not redemptively borne (natan al-rosh, 16:21); (6) removal from community into confinement. Run cross_testament_parallels_v2.py on Rev 20:1-3 to see lexical overlap. STATE THE LIMITS explicitly: Lev 16 never says 'Azazel is Satan'; Rev 20 never cites Lev 16; the abyss (abyssos/tehom) is not lexically the wilderness (midbar/eremos); Rev 20's 'little season' release and lake-of-fire (20:10) EXCEED the type (the scapegoat does not return). Conclude at reasonable-inference strength: NOT Christ (necessary inference), CORRESPONDS TO Satan (strong canonical inference). GUARD THE REDEMPTIVE CONTROL: any Satan identification is JUDICIAL (accountability/removal), never a contribution to salvation — Christ alone atones/redeems (Heb 9:11-12; Rom 3:25; John 1:29).
**Verses:** Lev 16:20, Lev 16:21, Lev 16:22, Rev 20:1-3, Rev 20:10
**Strong's:** H1509, H6261, G12, G1210

9. **Beckworth's goat-vs-Azazel distinction and the ANE elimination-rite reading:**
Handle the two freshest scholarly leads. Beckworth (Southern Adventist, 2024) argues 'a distinction needs to be made between the goat and the scapegoat (Azazel)' so the goat's symbolic identity is separate from Azazel's — potentially letting both major positions coexist (goat -> sin-bearer object; Azazel -> destination/recipient). Test this against the syntax of Lev 16:10, 16:22, 16:26: the goat is 'la-azazel' (for/to Azazel) — is Azazel grammatically the DESTINATION the goat is sent toward, distinct from what the goat itself represents? This bears directly on material_subtype (Azazel = destination/recipient) vs. functional_conceptual (the goat = removal act). Separately, verify Milgrom/Wright's ANE 'elimination vehicle' framing: does Lev 16 ever call the live goat a sacrifice (zabach, qorban)? Run search_strongs.py to check whether sacrificial vocabulary is ever applied to the live goat (it is not — only shalach/nasa/natan). If the live goat is a disposal vehicle sent TO a destination, then cand-removal-of-sin and cand-demon-destination/cand-satan describe DIFFERENT referents (the act vs. the destination), which the identity_axes must keep distinct rather than collapse. Conclude whether the text supports Beckworth's separation or treats goat-and-destination as one dispatch.
**Verses:** Lev 16:8, Lev 16:10, Lev 16:22, Lev 16:26, Lev 17:7
**Strong's:** H5799, H7971, H8163, H2077

10. **Etymology and the material_subtype resolution — name, place, or common noun:**
The explicit tension-resolution focus area. READ $WORD_STUDIES/H5799-azazel.md in full and note its Core Data: root given as ez (H5795, goat) + azal (H235, go away) = 'goat of departure', with BDB suggesting 'complete removal', and the note that KJV + Septuagint (apopompaios, 'one sent away') treat it descriptively while ESV/NASB/NIV transliterate as a proper name. Lay out the four scholarly options: (a) proper name of a being/demon (azaz+el, 'El is fierce'; 1 Enoch/4Q180; Angelini's theophoric-correction thesis); (b) a place (rugged cliff/wilderness; b. Yoma 67b; later Septuagint revisers); (c) a common noun/abstraction ('goat that departs' / 'complete removal'; Strong's, BDB, Tyndale's 'escape goat', Philo); (d) a deity demoted below YHWH. Report the BHSA parse (PropN.ms.Abs at each of the four attestations) that prior studies rely on. Give a CALIBRATED verdict for material_subtype: the morphology + la-YHWH parallelism PRESSURE a proper-name/personal reading, but the descriptive etymology and Septuagint descriptive rendering keep the common-noun reading live; the text underdetermines a single lexical class. Crucially, note that the FUNCTIONAL conclusion (the live goat = removal of confessed sin after completed atonement; NOT Christ) holds INDEPENDENTLY of how material_subtype resolves — uncertainty about the WORD does not weaken the stronger conclusion about the ACT. This is the three-axis independence principle from doa-two-goats.
**Verses:** Lev 16:8, Lev 16:10, Lev 16:26
**Strong's:** H5799, H5795, H235

### External Corpus Leads (from 00-references.md)

1. **Azazel is a proper name representing the devil/Satan (Syriac 'the angel who revolted'; oldest Hebrew/Christian opinion)** (Source: EGW/Haskell)
   - **Verify:** verify against BHSA parse + Lev 16:8 grammar; state as lexical-tradition lead, not proof; the material_subtype axis adjudicates
2. **The high priest places the borne sins on the scapegoat only AFTER finishing the sanctuary work** (Source: EGW)
   - **Verify:** verify against the kalah completion sequence (Lev 16:20)
3. **Satan bears the 'final penalty' as instigator, then is destroyed** (Source: EGW/Bohr)
   - **Verify:** distinguish JUDICIAL bearing from REDEMPTIVE atonement; verify 'originator' framing against 1 John 3:8, not Lev 16
4. **Three-point structure: kalah-sequence (16:20) + no-blood/not-a-sacrifice (Heb 9:22) + Rev 20:1-3 alive on a desolate planet** (Source: Bohr (Secrets Unsealed))
   - **Verify:** verify each point against Lev 16:20, Heb 9:22, Rev 20:1-3
5. **'Scapegoat' is a misleading English term; Satan is to blame as originator, not an innocent scapegoated party** (Source: Bohr)
   - **Verify:** note the English-word history (Tyndale 'escape goat'); do not build doctrine on the English gloss
6. **Azazel = azaz+el ('El is fierce'); Masoretic spelling may be a theological correction erasing a theophoric element; four-way dispute (deity/place/common-noun/demon)** (Source: Angelini (TheTorah.com))
   - **Verify:** verify etymology against HALOT/BDB/TDOT and the H5799 library entry; adjudicate on material_subtype axis
7. **'for YHWH / for Azazel' contrasts two divine figures; wilderness = demonic territory; the high priest is NOT sacrificing TO Azazel — sin is dispatched to its domain** (Source: Heiser (drmsh.com))
   - **Verify:** verify the parallelism forces a personal being; confirm the goat neither atones nor is offered to Azazel (test against shalach/nasa, non-sacrificial)
8. **Lev 16:5 makes both goats 'one sin offering'; blemish-free (Lev 22:20-21) excludes Satan; John 1:29; Heb 9:26 = Christ view** (Source: Answering Adventism)
   - **Verify:** verify Lev 16:5 chattat governs both goats and whether shared designation entails shared function; test the blemish-free argument on the live goat
9. **Distinguish the GOAT (sin-bearer object) from AZAZEL (recipient/destination); both Christ-symbol and Satan/demon readings can operate on different referents** (Source: Beckworth (Southern Adventist, 2024))
   - **Verify:** test whether the syntax of la-azazel (16:10, 22, 26) separates the goat's symbol from its destination
10. **The live goat is a non-sacrificial ANE 'elimination vehicle'; the day's primary goal is purgation of the sanctuary; the goat removes rather than atones by blood** (Source: Milgrom / Wright)
   - **Verify:** verify Lev 16 never applies sacrificial vocabulary (zabach/qorban) to the live goat; confirm purgation-of-sanctuary emphasis (16:16, 33)
11. **Ancient two-goat Christ typology (Barnabas 7; Justin Dial. 40; Tertullian; Origen; Jerome; Cyril) applied the scapegoat to Christ** (Source: Moscicke / patristics)
   - **Verify:** treat as ancient interpretation, NOT Scripture; verify only what Lev 16 states

### Structural Constraints (from prior studies — verify and account for)

1. **Lev 16:10 lekapper alav = atonement made OVER/concerning the live goat (kipper-al, same as the altar in 16:18, an object acted upon), not BY it as a co-propitiator**
   - Established by: doa-two-goats-referents, sanc-11-two-goats-typology
   - Directive: verify_and_account_for
   - Implication: If confirmed, the live goat is not an atoning agent; the Christ-view's strongest grammatical claim fails, and the goat's role is disposal after atonement.
2. **Blood-atonement (kaphar) is completed (kalah, Lev 16:20) BEFORE the live goat is handled; the live goat is presented ALIVE and NOT slain (Lev 16:10) and sheds no blood**
   - Established by: doa-two-goats-referents, rev-20-1-3-scapegoat-day-of-atonement, atone-19-sin-path-two-goats
   - Directive: verify_and_account_for
   - Implication: The live-goat rite is a terminal disposal phase, not part of the propitiation; per Heb 9:22 the bloodless goat cannot remit sin.
3. **nasa is register-neutral; the scapegoat carries sin WILDERNESS-ward (removal), whereas Christ bears sin GOD-ward (anaphero, Heb 9:28) and Lamb-ward (airo, John 1:29) — so the scapegoat is NOT Christ**
   - Established by: doa-two-goats-referents, sanc-11-two-goats-typology, rev-20-scapegoat-satan-bound
   - Directive: verify_and_account_for
   - Implication: Direction, not the neutral verb, decides the referent; the scapegoat's Godward-absence forecloses the Christ identification (necessary inference).
4. **Referent verdict from prior work: the scapegoat is NOT Christ (necessary inference) and CORRESPONDS TO Satan bound (Rev 20:1-3) at reasonable-inference strength — a JUDICIAL (accountability/removal) correspondence, never redemptive; language is 'corresponds to', never 'is'**
   - Established by: doa-two-goats-referents, rev-20-1-3-scapegoat-day-of-atonement, rev-20-scapegoat-satan-bound
   - Directive: verify_and_account_for
   - Implication: Re-verify from Scripture, do not assume; calibrate the Satan correspondence at reasonable-inference strength and note where Rev 20 exceeds the type; keep the redemptive control (Christ alone atones).
5. **Material_subtype of Azazel is underdetermined by the lexicon: the H5799 library entry leans 'goat of departure/complete removal' (descriptive) while prior conclusions rely on the BHSA PropN parse + la-YHWH parallelism (personal entity)**
   - Established by: sanc-11-two-goats-typology, doa-two-goats-referents
   - Directive: verify_and_account_for
   - Implication: The material_subtype axis must reconcile these openly; the FUNCTIONAL conclusion (removal after completed atonement; not Christ) holds independently of how the word's lexical class resolves.

## Research Instructions

You are the Research Agent. Execute this study by:

1. Read the SKILL.md for full tool documentation and principles
2. Read your agent instructions at `agents/research-agent.md`
3. **Read ALL library entries listed in "Available Library Entries" above**
4. Follow the workflow from the skill
5. Write research files to this folder:
   - `01-topics.md` — Nave's topics and full entries (retrieve full entries for: AZAZEL, SCAPEGOAT, ATONEMENT, GOAT, SANCTUARY, PRIEST, REDEMPTION, LAMB OF GOD, FORGIVENESS, CONFESSION, SATAN, WILDERNESS, SACRIFICES, BLOOD)
   - `02-verses.md` — All verse texts retrieved with context for:
     - **The two-goat rite (Leviticus 16)** (Lev 16:5, Lev 16:7, Lev 16:8, Lev 16:9, Lev 16:10...) — retrieve with FULL chapter context
     - **Blood-atonement and sacrificial-vocabulary controls** (Lev 17:11, Lev 4:20, Lev 14:4-7, Lev 22:20-21) — retrieve with FULL chapter context
     - **nasa sin-bearing across registers** (Exo 34:7, Exo 28:38, Lev 10:17, Isa 53:4-6, Isa 53:11-12...)
     - **Christ the sin-bearer / High Priest (NT fulfillment)** (John 1:29, Heb 9:7, Heb 9:11-12, Heb 9:22, Heb 9:24-26...) — retrieve with FULL chapter context
     - **Adversary / judgment correspondence** (Rev 20:1-3, Rev 20:10, Zec 3:1-2, 1 John 3:8, Gen 3:15...)
     - **All additional verses from Nave's topic entries**
   - `04-word-studies.md` — Strong's research:
     - **FROM LIBRARY (read, don't re-derive):** H5799 (azazel), H8163 (sa'ir (goat)), H5375 (nasa (bear/carry)), H3722 (kaphar (atone/cover)), H3615 (kalah (complete/finish)), H7819 (shachat (slaughter)), H7971 (shalach (send away)), H3034 (yadah (confess)), H5414 (nathan (put/place)), H6261 (ittiy (fit/ready man)), H4057 (midbar (wilderness)), H1509 (gezerah (separation/solitary)), H2403 (chattaah (sin/sin-offering)), H5771 (avon (iniquity)), H6588 (pesha (transgression))
     - **FRESH LOOKUPS (no library entry):** H8549 (tamiym (unblemished/perfect)), H2891 (taher (cleanse)), G399 (anaphero (bear up/offer)), G142 (airo (take away)), G2435 (hilasterion (mercy-seat/propitiation))
   - `raw-data/` — Raw tool output organized by category
6. Do NOT write `03-analysis.md` or `CONCLUSION.md` — those are for the analysis agent

### Specific Research Directives

7. **Priority verses to retrieve with FULL CHAPTER context:**
   - Lev 16:1-34
   - Lev 17:1-16
   - Lev 4:1-35
   - Lev 14:1-9
   - Isa 53:1-12
   - Heb 9:1-28
   - Heb 13:10-16
   - Rev 20:1-10

8. **Required Greek/Hebrew parsing:**
   - Lev 16:8 — Parse azazel (PropN?) and the la-YHWH // la-azazel lamed constructions
   - Lev 16:10 — lekapper alav (kipper-al) + yaomad (Hophal, presented alive) — the crux
   - Lev 16:15 — shachat governing the LORD's goat — the blood-atonement contrast
   - Lev 16:17 — kaphar ba'ad (beneficiary construction) vs. kipper-al
   - Lev 16:18 — kipper-al applied to the altar (object) — parallel to 16:10
   - Lev 16:20 — vekhillah mikapper (Piel kalah + min-kaphar) — completion marker
   - Lev 16:21 — yadah (Hithpael confession), natan al-rosh (imputation), ish itti
   - Lev 16:22 — nasa (bear) + erets gezerah destination — removal register
   - Isa 53:12 — nasa/sabal + paga (intercession) — priestly/redemptive register
   - Heb 9:28 — anaphero — Christ's God-ward sin-bearing

9. **Required cross-testament parallels** (run BOTH --hybrid-ot AND --hybrid-nt):
   - Lev 16:22 — OT and NT parallels for the goat 'bearing' sin to a solitary land
   - Lev 16:21 — Parallels for laying-on-of-hands + confession + imputation
   - Lev 16:27 — 'Outside the camp' — parallels to Heb 13:11-13
   - Isa 53:11-12 — Sin-bearing Servant parallels; nasa in redemptive register
   - Rev 20:1-3 — Structural correspondence to the live-goat rite (Lev 16:20-22)

10. **Required word traces:**
   - H8549 (tamiym (unblemished/perfect)) — run search_strongs.py --lookup and --verses
   - H2891 (taher (cleanse)) — run search_strongs.py --lookup and --verses
   - G399 (anaphero (bear up/offer)) — run search_strongs.py --lookup and --verses
   - G142 (airo (take away)) — run search_strongs.py --lookup and --verses
   - G2435 (hilasterion (mercy-seat/propitiation)) — run search_strongs.py --lookup and --verses

11. **External corpus verification directives:**
   - Azazel is a proper name representing the devil/Satan (Syriac 'the angel who revolted'; oldest Hebrew/Christian opinion) (EGW/Haskell) — verify against BHSA parse + Lev 16:8 grammar; state as lexical-tradition lead, not proof; the material_subtype axis adjudicates
   - The high priest places the borne sins on the scapegoat only AFTER finishing the sanctuary work (EGW) — verify against the kalah completion sequence (Lev 16:20)
   - Satan bears the 'final penalty' as instigator, then is destroyed (EGW/Bohr) — distinguish JUDICIAL bearing from REDEMPTIVE atonement; verify 'originator' framing against 1 John 3:8, not Lev 16
   - Three-point structure: kalah-sequence (16:20) + no-blood/not-a-sacrifice (Heb 9:22) + Rev 20:1-3 alive on a desolate planet (Bohr (Secrets Unsealed)) — verify each point against Lev 16:20, Heb 9:22, Rev 20:1-3
   - 'Scapegoat' is a misleading English term; Satan is to blame as originator, not an innocent scapegoated party (Bohr) — note the English-word history (Tyndale 'escape goat'); do not build doctrine on the English gloss
   - Azazel = azaz+el ('El is fierce'); Masoretic spelling may be a theological correction erasing a theophoric element; four-way dispute (deity/place/common-noun/demon) (Angelini (TheTorah.com)) — verify etymology against HALOT/BDB/TDOT and the H5799 library entry; adjudicate on material_subtype axis
   - 'for YHWH / for Azazel' contrasts two divine figures; wilderness = demonic territory; the high priest is NOT sacrificing TO Azazel — sin is dispatched to its domain (Heiser (drmsh.com)) — verify the parallelism forces a personal being; confirm the goat neither atones nor is offered to Azazel (test against shalach/nasa, non-sacrificial)
   - Lev 16:5 makes both goats 'one sin offering'; blemish-free (Lev 22:20-21) excludes Satan; John 1:29; Heb 9:26 = Christ view (Answering Adventism) — verify Lev 16:5 chattat governs both goats and whether shared designation entails shared function; test the blemish-free argument on the live goat
   - Distinguish the GOAT (sin-bearer object) from AZAZEL (recipient/destination); both Christ-symbol and Satan/demon readings can operate on different referents (Beckworth (Southern Adventist, 2024)) — test whether the syntax of la-azazel (16:10, 22, 26) separates the goat's symbol from its destination
   - The live goat is a non-sacrificial ANE 'elimination vehicle'; the day's primary goal is purgation of the sanctuary; the goat removes rather than atones by blood (Milgrom / Wright) — verify Lev 16 never applies sacrificial vocabulary (zabach/qorban) to the live goat; confirm purgation-of-sanctuary emphasis (16:16, 33)
   - Ancient two-goat Christ typology (Barnabas 7; Justin Dial. 40; Tertullian; Origen; Jerome; Cyril) applied the scapegoat to Christ (Moscicke / patristics) — treat as ancient interpretation, NOT Scripture; verify only what Lev 16 states

12. **Grammar reference entries to read:**
   - `$GRAMMAR_REF/passages/lev-16-20-22.md` — Lev 16:20-22 scapegoat-dispatch grammar (kalah completion + nasa removal)
   - `$GRAMMAR_REF/passages/lev-16-21-sin-terms.md` — Lev 16:21 kol + avon/pesha/chattat sin triad
   - `$GRAMMAR_REF/passages/lev-16-14-16.md` — Lev 16:14-16 blood-atonement grammar
   - `$GRAMMAR_REF/passages/lev-16-30.md` — Lev 16:30 kaphar + taher (cleanse) grammar

### Additional Research Instructions

This is a schema_version 2 disputed-identity study. Keep the THREE identity axes independent (three-axis framework imported from doa-two-goats-referents): uncertainty about material_subtype (what the WORD Azazel is) must NOT weaken the stronger grammatical_object and functional_conceptual conclusions (what the RITE does). Keep two questions distinct throughout (Beckworth's distinction): (A) what does the LIVE GOAT represent/do (grammatical_object + functional_conceptual), and (B) what is Azazel — the word/destination/recipient (material_subtype). Do not collapse them. Represent the identity axes as distinct levels, NOT as mutually exclusive documentary models. GUARD THE REDEMPTIVE CONTROL wherever the referent is discussed: Christ alone atones/redeems (Heb 9:11-12; Rom 3:25; John 1:29); any Satan identification is JUDICIAL (accountability/removal/final punishment), never a contribution to salvation. Use 'corresponds to' / 'points to', never 'is', for the Satan correspondence. Treat EGW/Haskell/Bohr and all patristic/scholarly sources as LEADS to primary sources, not as historical or exegetical authorities — verify every claim against the Hebrew/Greek text. This study is LEVITICUS-FIRST: do not over-weight Rev 20. Build on the five prior studies via structural_constraints (verify_and_account_for) — re-verify, do not merely duplicate.

## Workflow
answer-question

---
*Scoped from prompt.json*
*Folder: scapegoat-day-of-atonement-represents/*