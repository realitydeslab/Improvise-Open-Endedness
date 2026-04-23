# Deep Think: CHI 2027 Strategy

*Written after completing CHI requirements research, literature review, related works analysis, expansion strategy, venue analysis, and research plan.*

---

## What Is the ONE Strongest Angle for CHI?

After reading everything, the strongest angle is:

**"Design principles for open-ended co-creative systems, grounded in improvisation expertise"**

Not the formal OE mapping (save that for ALIFE). Not the interview findings alone (too thin for CHI main track). The winning move is the SYNTHESIS: expert knowledge about how improvisation sustains creative novelty, translated through OE theory into actionable design principles for the HCI community.

Why this wins:
1. **CHI wants design implications.** This gives them 8 concrete, well-grounded design principles.
2. **CHI values interdisciplinary bridging.** This bridges three fields (improv, OE, HCI) in a way no existing paper does.
3. **The author has credibility.** Amber's CHI 2026 paper (GravField) demonstrates the principles in practice. This isn't armchair theorizing.
4. **The timing is right.** Co-creative AI is exploding. LLMs are entering creative domains. But the theoretical foundation for WHY some co-creative interactions sustain novelty (and others collapse into repetition) is missing. This paper provides it.

---

## What Contribution Type Fits Best?

**Primary: Theoretical/Conceptual** — the IOE (Improvisational Open-Endedness) framework

But wrapped in:
- **Empirical** — interview study with 10-12 improvisation experts
- **Design** — actionable design implications with system exemplars

This multi-layered contribution is what CHI rewards. Pure theory is risky at CHI. Theory + empirical grounding + design implications is the sweet spot.

The framework's power: it doesn't just describe — it **generates**. Given any co-creative system, you can use the IOE framework to:
1. Diagnose why it does/doesn't sustain creative novelty
2. Identify which improvisational qualities are present/absent
3. Generate specific design modifications to enhance open-endedness

That's a tool, not just a taxonomy.

---

## Mock Reviewer Simulation: Three CHI Reviewers

### Reviewer A: The Champion (loves it)

> **Rating: 4.0 — Accept**
>
> "This is exactly the kind of interdisciplinary theoretical contribution CHI needs. The paper bridges improvisation theory, open-endedness, and co-creative AI design in a way I haven't seen before. The interview data is rich, the framework is well-structured, and — crucially — the design implications are genuinely actionable. I particularly appreciate that the author has a CHI 2026 paper (GravField) that demonstrates these principles in practice; this grounds the theoretical contribution in real design experience.
>
> The IOE framework's three-layer structure (attentional, relational, generative) elegantly maps improvisation concepts to OE mechanisms to design principles. I could immediately see how to apply DI3 (Productive Uncertainty) and DI5 (Structure-Surprise Balance) to my own work on interactive narrative systems.
>
> Minor suggestions: The OE background could be trimmed — assume less ALife knowledge. And I'd love a worked example applying the full framework to one system (GravField would be perfect).
>
> Best Paper potential if the validation section is strengthened."

### Reviewer B: The Skeptic (mixed)

> **Rating: 2.5 — Revise**
>
> "Interesting and ambitious, but I have concerns:
>
> 1. **Sample size and diversity:** 10-12 participants is adequate for a qualitative study, but the framing as a 'framework paper' raises the bar. Are 10-12 interviews enough to generate a theoretical framework? The paper needs to be more careful about the scope of its claims.
>
> 2. **Framework validation:** The retrospective analysis of existing systems is useful but doesn't constitute rigorous validation. How do we know the framework actually helps designers build better co-creative systems? At minimum, I'd want to see a design exercise where the framework is used generatively, with some comparison to design without it.
>
> 3. **Relationship to COFI:** The paper positions against COFI but doesn't demonstrate that the IOE framework captures something COFI misses in a systematic way. A direct analytical comparison (applying both frameworks to the same systems) would be much more convincing.
>
> 4. **The OE connection feels forced in places.** Some of the improvisation themes (e.g., empathy, care) don't map cleanly onto OE mechanisms. The paper should be honest about where the mapping works and where it breaks down.
>
> The core idea is solid but the execution needs tightening. Resubmit with stronger validation and more careful claims."

### Reviewer C: The Hostile (doesn't like it)

> **Rating: 1.5 — Reject**
>
> "I'm not convinced this paper makes a meaningful contribution to CHI.
>
> 1. **'Open-endedness' is not an HCI concept.** This reads like an ALife paper wearing an HCI costume. The connection between ALife's formal OE (unbounded evolutionary complexity) and HCI's informal open-endedness (users doing unexpected things with systems) is asserted but never rigorously justified. These are categorically different phenomena.
>
> 2. **The interviews tell us what we already know.** Improvisers value listening, surprise, trust, and flow. This is well-established in the improvisation literature (Sawyer, Nachmanovitch, Borgo). The 'insight' is reporting known findings and attaching new labels from a different field.
>
> 3. **Design implications are generic.** 'Design for Active Listening' and 'Design for Productive Uncertainty' could come from any interaction design textbook. Where is the specificity that comes from the improvisation-OE bridge? What can I do with this framework that I can't do with existing co-creative design guidelines?
>
> 4. **No system, no evaluation, no evidence of impact.** The author cites their own CHI 2026 system but doesn't formally use the framework to analyze it. This is a theory paper without sufficient rigor to stand as pure theory.
>
> Recommend: alt.chi or workshop paper. Not ready for main track."

---

## Defending Against Each Reviewer

### Against Reviewer B's concerns:
1. **Sample size:** Frame as "framework development" study, not "framework validation" study. The interviews generate the framework; validation is a separate concern addressed through retrospective analysis. Cite Braun & Clarke on the adequacy of 6-15 participants for thematic analysis aimed at framework development.
2. **Validation:** Add a concrete comparative analysis: apply both IOE and COFI to LuminAI and GravField. Show what IOE reveals that COFI misses (relational dynamics, temporal sustainment of novelty).
3. **COFI comparison:** Include systematic side-by-side in Table format.
4. **Mapping limits:** Add a "Where the Mapping Breaks Down" subsection. Honesty strengthens the paper.

### Against Reviewer C's concerns (the hardest):
1. **OE is not HCI:** Explicitly bridge with HCI language. Don't import ALife jargon wholesale. Frame: "HCI has long valued open-endedness in design (Gaver et al., 2003; Sengers & Gaver, 2006). We provide formal mechanisms — drawn from open-endedness research — that explain HOW designs achieve sustained novelty." The connection is: HCI's informal OE can be understood through ALife's formal OE.
2. **Known findings:** The contribution isn't the findings — it's the FRAMEWORK that connects them to OE mechanisms and generates design principles. The themes are the input, not the output.
3. **Generic implications:** Make each DI ultra-specific. Not "Design for Active Listening" but "Design for Multi-Timescale Responsiveness: systems should respond at three timescales — micro (50-200ms for gesture mirroring), meso (5-30s for movement phrase completion), macro (session-level pattern evolution) — because improvisation research shows responsiveness at only one timescale collapses creative novelty."
4. **No system:** Reference GravField formally as design exemplar. Include a worked analysis section: "Analyzing GravField Through the IOE Framework" showing specific insights the framework generates.

---

## What Would Make This a Best Paper Contender?

1. **A formal validation that generates surprise.** Apply the framework to an existing system and discover something non-obvious — e.g., "COFI classifies LuminAI as turn-taking co-creation; IOE reveals that its open-endedness depends on a relational trust dynamic that neither the designers nor COFI recognized."

2. **Ultra-specific, counter-intuitive design implications.** Not "design for surprise" but something practitioners wouldn't have thought of: e.g., "In co-creative AI systems, introducing 3-5 seconds of silence/non-response after unexpected user input increases creative novelty by 40% — because improvisation research shows that 'active not-doing' (holding space) is essential to open-ended interaction."

3. **A beautiful, memorable visual framework.** The IOE diagram should be instantly comprehensible and frequently cited. Think of COFI's framework diagram or Höök's soma design qualities — one image that captures the whole contribution.

4. **A deeply reflexive methodology section** that positions Amber's unique perspective (improviser + AI researcher + system designer) as a methodological asset, not a bias. Research-through-design meets qualitative inquiry meets interdisciplinary theory-building.

5. **Engagement with power and culture.** Improvisation has deep cultural roots (jazz improvisation's African American origins, contact improv's counter-cultural roots, raga's millennia of tradition). A thoughtful engagement with whose improvisation we're studying and what that means for the framework's applicability would impress CHI reviewers.

---

## Honest Assessment: Is This Ready for CHI 2027?

**Yes, with significant work.** Here's my honest breakdown:

| Dimension | Current Readiness | By September 2026? |
|-----------|------------------|---------------------|
| Empirical base | 60% (6 participants → need 10-12) | 90% if recruitment starts now |
| Theoretical framework | 40% (theme list → need formal framework) | 85% with focused development |
| Design implications | 20% (none currently) | 80% with systematic development |
| CHI lit engagement | 30% (ALife-focused) | 90% (done in this research) |
| Writing quality | 30% (WIP format) | 85% with dedicated writing time |
| Validation | 0% | 70% (retrospective analysis + comparison) |

**Overall: ~35% ready now → 85% by September 2026.**

85% is submittable. The remaining 15% gap is normal for any submission. The key risks are:
- Participant recruitment (if it stalls, the empirical base is thin)
- Framework development (if it feels forced or too abstract)
- Reviewer C (hostile reviewers who don't see OE as relevant to HCI)

**Recommendation: Submit to CHI 2027 main track.**
- It's ambitious but feasible
- The worst case (reject) still produces a strong paper for DIS 2027 or C&C 2027
- The best case (accept, possible honorable mention) establishes Amber as the person who brought OE theory to HCI co-creative design

**Alternative if timeline is too tight:** Submit to TEI 2027 (deadline ~August 2026, Lisbon) with a more embodied/somaesthetic framing, then expand for CHI 2028.

---

## The Killer Sentence

The paper's core claim, in one sentence:

> "We show that the practices expert improvisers use to sustain creative novelty — active listening, productive uncertainty, relational trust, and structure-surprise balance — correspond to formal mechanisms of open-endedness, and we translate these correspondences into eight design principles for building co-creative AI systems that sustain genuinely open-ended interaction."

If reviewers walk away remembering that sentence, the paper has done its job.
