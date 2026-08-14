I now have all the evidence needed. Let me compile the complete structured analysis.

---

## AI Literacy and Epistemic Competencies: An OpenAIRE Graph Evidence Report

---

### I. Methodology: Tools, Filters, and Query Logic

All searches used `openaire_search_research_products` with `type=["publication"]` and `sort_by="citationCount DESC"`. The OpenAIRE API applies **AND logic** by default — more terms produce fewer results but with higher topical specificity. Pagination `total` fields give approximate record counts. For the two landmark papers (Long & Magerko 2020; Ng et al. 2021) and two key adjacent papers (Almatrafi et al. 2024; Kozyreva et al. 2019), `openaire_get_research_product_details` retrieved full abstracts and all four bibliometric class scores. No external databases, bioRxiv, or medRxiv were used.

**Queries run and record counts returned:**

**See table in visualization panel →**

**Critical interpretive warning:** High record counts for "critical thinking" and "decision making" co-occurring with "AI literacy" do not indicate that the AI literacy field *researches* these as epistemic competencies. OpenAIRE's AND logic picks up any paper in which all query terms appear anywhere — including a paper on ChatGPT in healthcare that tags "critical thinking" as a general concern. The *top-ranked* results, abstracts, and bibliometric classes were examined to discriminate genuine focus from incidental mention.

---

### II. Concept-by-Concept Analysis

---

#### 1. Critical Thinking — *Explicitly present; instrumentally framed*

**Record count:** \~2,223 (AI literacy + critical thinking)

**Explicit occurrence in titles/abstracts/keywords:**

The clearest explicit case is **Walter (2024)** — *"Embracing the future of AI in the classroom: the relevance of AI literacy, prompt engineering, and critical thinking in modern education"* (DOI: `10.1186/s41239-024-00448-3`, **786 citations, C2 influence, C1 popularity, C1 impulse**). Critical thinking is literally in the title and is framed as one of three equal pillars of AI literacy for the ChatGPT era. The abstract defines it as "enhanced critical thinking skills" needed to evaluate personalized AI outputs and resist pedagogical substitution. This is the highest-impact paper that makes critical thinking structurally central.

A second explicit entry: **Federiakin, Molerov & Zlatkin-Troitschanskaia (2024)** — *"Prompt engineering as a new 21st century skill"* (89 citations, *Frontiers in Education*) frames prompt design as requiring iterative reasoning and reflective evaluation of AI responses — implicitly a critical thinking exercise.

**Almatrafi, Johri & Lee (2024)** — *"A systematic review of AI literacy conceptualization, constructs, and implementation (2019–2023)"* (DOI: `10.1016/j.caeo.2024.100173`, **203 citations, C3 influence, C2 popularity**) synthesizes six constructs of AI literacy: Recognize, Know and Understand, Use and Apply, **Evaluate**, Create, and Navigate Ethically. "Evaluate" explicitly encompasses critical assessment of AI outputs. This is a systematic review paper; it confirms that critical evaluation *appears in the definitional literature* as a named construct.

**Inferred conceptual relevance:** The majority of the 2,223 records use "critical thinking" as a desired educational outcome associated with AI integration, not as a researched AI literacy dimension. Papers on ChatGPT in nursing, dentistry, and healthcare mention critical thinking as a normative value without operationalizing it as an AI literacy skill.

**Assessment:** Critical thinking is *declaratively present* in frameworks and explicitly researched in a small cluster of high-citation papers. It is more consistently mentioned than studied — the gap between declaration and operationalization is significant.

---

#### 2. Reasoning — *Largely inferred; one substantive strand via "AI Thinking"*

**Record count:** \~806 (AI literacy + reasoning)

**Explicit occurrence:** The 806 results are heavily contaminated by papers about AI *systems'* reasoning (knowledge graph reasoning, Bayesian inference in ML) rather than human reasoning *about* AI. Genuinely relevant papers in this count are sparse.

The strongest explicit case is **How & Hung (2019)** — *"Educing AI-Thinking in Science, Technology, Engineering, Arts, and Mathematics (STEAM) Education"* (DOI: `10.3390/educsci9030184`, **107 citations, C3 influence, C3 popularity**). The abstract is substantively important: it explicitly teaches STEAM learners to use "Naïve Bayes" and "semi-supervised Bayesian" approaches to "educe AI-assisted human-centric reasoning," enabling "what-if scenario" thinking. The keyword list includes "AI Thinking," "Bayesian," and "explainable AI." This paper directly targets inferential/probabilistic reasoning as an AI literacy outcome — using AI as a scaffold for reasoning rather than just a tool to use.

The adjacent **Kozyreva, Lewandowsky & Hertwig (2019)** — *"Citizens Versus the Internet: Confronting Digital Challenges With Cognitive Tools"* (DOI: `10.31234/osf.io/ky4x8`, **339 citations, C3 influence, C2 popularity**) is not an AI literacy paper per se but is directly relevant. Its abstract explicitly addresses "boosting competences of reasoning and resilience to manipulation" as interventions for citizens facing "AI-assisted information architectures." It frames reasoning as a learnable civic competency in AI environments. It appears in OpenAIRE searches on "AI literacy reasoning" because it co-indexes with AI literacy discussions in citing literature.

**Inferred relevance:** Every major AI literacy framework includes "understanding how AI makes decisions" as a core competency — which implicitly requires reasoning about probabilistic patterns, training data effects, and model limitations. But this is *conceptualized* rather than *taught as reasoning practice* in most studies.

**Assessment:** Reasoning is peripheral as an explicit research focus. The "AI Thinking" label from How & Hung has not proliferated — the "AI thinking STEAM inference" query returned **0 records**, confirming the concept has not spawned a research strand.

---

#### 3. Decision-Making — *Conceptually embedded but empirically in professional, not educational, contexts*

**Record count:** \~2,032 (AI literacy + decision making)

**Explicit occurrence in AI literacy research:** The top results for "AI literacy decision making" are dominated by papers about AI-assisted clinical decision-making in healthcare (health literacy for patients, clinical decision support literacy for professionals). These are not AI literacy *education* papers in the standard sense.

One genuinely relevant entry: **Romeo & Conti (2025)** — *"Exploring automation bias in human-AI collaboration: a review and implications for explainable AI"* (DOI: `10.1007/s00146-025-02422-7`, **78 citations**, *AI & Society*). Subjects: "Automation bias · Trust calibration · Explainable AI (XAI) · Hybrid intelligence · Anchoring effect." This paper directly addresses the phenomenon where humans uncritically defer to AI decision recommendations — the decision-making failure that AI literacy is designed to prevent. It is not an AI literacy curriculum paper but provides the psychological grounding for why decision-making judgment matters.

**Dong, Jiang & Xu (2025)** — *"From simplification to sophistication: Secondary students' conceptual change in understanding machine learning model decision making"* (2 citations, *British Journal of Educational Technology*) explicitly tracks students' evolving interpretive understanding of how ML models decide — a form of epistemic development directly relevant to decision-making literacy.

**Inferred relevance:** The "Evaluate" dimension in Ng et al.'s four-part model and in Almatrafi et al.'s six-construct synthesis presupposes decision-making: a learner must judge whether an AI output is reliable, contextualize that judgment, and decide how to act. But this is mostly implicit.

**Assessment:** Decision-making as a *human* AI literacy competency is peripherally researched in the education strand. The concept appears heavily in professional/clinical contexts (where AI decision-support is high-stakes), and is inferred but not operationalized in general AI literacy education research.

---

#### 4. Interpretation — *Marginally present; primarily in domain-specific and XAI contexts*

**Record count:** \~25 (AI literacy + interpretation + explainability)

**Explicit occurrence:** The 25 records are dominated by dental/oral AI curriculum and radiology safety papers — professional domains where interpreting AI outputs is a clinical skill. **Schwendicke, Chaurasia & Wiegand (2023)** — *"Artificial intelligence for oral and dental healthcare: Core education curriculum"* (108 citations, *Journal of Dentistry*) is the highest-cited entry in this cluster; it develops a curriculum where dentists must interpret AI-generated diagnoses.

Beyond domain-specific cases, the **Bobek et al. (2025)** *"Dataset resulting from user study on comprehensibility of explainable AI algorithms"* (5 citations, *Scientific Data*) provides empirical data on how users interpret XAI outputs — relevant to interpretation as a competency but not framed as AI literacy education research.

**Inferred relevance:** Interpretation is inherent in the "Use and Apply" and "Evaluate and Create" dimensions of Ng et al.'s framework — using AI requires interpreting its outputs. But as a named object of study in AI literacy, it is sparse.

**Assessment:** Interpretation is peripheral as an explicit concept in the OpenAIRE AI literacy corpus. It is researched under domain-specific labels (radiology literacy, dental AI education) rather than as a generalizable AI literacy competency.

---

#### 5. Judgment — *Peripheral and primarily in ethics framing*

**Record count:** \~134 (AI literacy + judgment + evaluation)

**Explicit occurrence:** The most relevant paper is **Brauner, Hick & Philipsen (2023)** — *"What does the public think about artificial intelligence? A criticality map to understand bias in the public perception of AI"* (DOI: `10.3389/fcomp.2023.1113903`, **119 citations**, *Frontiers in Computer Science*). Subjects include "Technology Acceptance" and the paper constructs a "criticality map" — a taxonomy of how critically or credulously members of the public engage with AI. This is genuinely relevant to judgment as an AI literacy competency, though it is diagnostic rather than educational.

The clinical contexts dominate the 134 entries: judgment in nursing, radiology, and medical education about when to follow or override AI recommendations. These are judgment-as-professional-practice papers, not AI literacy education papers.

The **Almatrafi et al.** systematic review (abstract quoted above) is the strongest evidence that judgment is present *definitionally*: their "Evaluate" construct includes "critically assess AI outputs and make judgments about their reliability."

**Inferred relevance:** Ethical judgment — knowing when AI recommendations are biased or harmful — is consistently present in the ethics strand (Ma, Ng & Liu 2025 on K-12 AI ethics; Usher & Barak 2024 on AI ethics for engineers). But this is ethics *of* AI, not epistemological judgment *about* AI outputs.

**Assessment:** Judgment is peripheral as an epistemic skill in AI literacy education. It is more present as an ethical than as an epistemological concept.

---

#### 6. Uncertainty and Probabilistic Reasoning — *Nearly absent*

**Record count:** \~18 (AI literacy + uncertainty + probabilistic)

**Explicit occurrence:** This is the starkest finding of the entire investigation. In 18 records, only two are directly relevant:

- **Pramartha, Hendriyanto & Muhaimin (2026)** — *"AI-thinking in secondary mathematics education: A design-based research on Bayesian-based probabilistic reasoning"* (DOI: `10.24042/ijsme.v9i1.30923`, 0 citations). This paper explicitly targets Bayesian probabilistic reasoning as the mechanism by which AI thinking is educated in mathematics students. But it has no citation traction yet.
- **Córdova & Nóbrega (2025)** — *"Medicine, artificial intelligence and uncertainty: Why is statistical thinking fundamental?"* (DOI: `10.47626/2237-6089-2025-1069`, 0 citations). This argues directly for statistical/probabilistic thinking as a prerequisite for meaningful AI literacy in medical contexts. Again, zero citations.

The How & Hung (2019) "AI Thinking" paper implicitly covers this via its Bayesian framing, but it is located in the "reasoning" searches and is not explicitly framed under "uncertainty."

**Inferred relevance:** Understanding AI uncertainty is implied by knowing that "AI can be wrong" — a concept taught in K-12 programs. But teaching students *how* probabilistic outputs should inform epistemic confidence (calibrated credences, confidence intervals, error rates) is essentially unrepresented in the indexed literature.

**Assessment:** Uncertainty and probabilistic reasoning are **overwhelmingly peripheral** — this is the largest gap in the field as revealed by OpenAIRE evidence. The gap is real, not an artifact of search strategy, since three different query formulations all converge on <20 records with near-zero citation weight.

---

### III. Recurring Authors Across These Concepts

**See table in visualization panel →**

The small size of the recurring-author list for these concepts is itself evidence: the same few names appear, whereas the broader AI literacy field features dozens of active research groups.

---

### IV. Centrality vs. Peripherality Assessment

**See table in visualization panel →**

---

### V. Counter-Evidence: Challenging the Claim That Reasoning and Judgment Are Underdeveloped

The claim that reasoning and judgment are underdeveloped in AI literacy research faces **several genuine challenges** from OpenAIRE evidence, which must be stated fairly.

**CE-1: The foundational frameworks explicitly include "Evaluate" as a core competency.** Both Long & Magerko (2020, 1,975 citations) — whose abstract states users need to "critically evaluate AI" — and Ng et al. (2021, 1,241 citations) — whose abstract names "evaluate and create" as one of four pillars — structurally embed critical evaluation. Almatrafi et al.'s (2024) six-construct synthesis confirms this is a *consensus position* across 47 reviewed studies. At the level of framework design, evaluation/judgment is not marginal — it is foundational. Any claim that it is "underdeveloped" applies to *empirical research and pedagogy*, not to the definitional architecture.

**CE-2: The Walter (2024) paper makes critical thinking structurally central with high citation impact.** With 786 citations, C2 influence, and C1 popularity and impulse — all confirmed by OpenAIRE bibliometrics — this paper is the fastest-rising in the field. It places critical thinking on equal footing with AI literacy knowledge and prompt engineering as a triple-pillar model. Its rapid citation accumulation suggests the field is *actively moving toward* critical thinking as a central concern.

**CE-3: How & Hung (2019) provides a published, pedagogically implemented probabilistic reasoning intervention.** The "AI Thinking" paper (107 citations, C3 influence) is the only indexed paper to explicitly teach Bayesian probabilistic reasoning as an AI literacy skill — and it does so with a concrete STEAM curriculum. The follow-on paper by Pramartha et al. (2026) suggests this strand is continuing. The low citation count of the latter reflects recency, not absence of the concept.

**CE-4: Kozyreva et al. (2019) provides a 339-citation theoretical foundation for reasoning interventions in AI-information environments.** Classified by OpenAIRE as C3 influence and C2 popularity, this *Psychological Science in the Public Interest* paper explicitly addresses "boosting competences of reasoning and resilience to manipulation" as responses to AI-assisted information architectures. It is a foundational theoretical contribution to the reasoning-in-AI-environments strand, even if not labeled "AI literacy."

**CE-5: The professional and domain-specific literature has operationalized judgment.** In healthcare, radiology, dentistry, and nursing AI literacy programs (Schwendicke et al. 2023, 108 citations; Kwak et al. 2022, 218 citations), judgment — when to override AI recommendations, how to interpret model confidence — is explicitly taught and in some cases assessed. The claim "judgment is underdeveloped" is less accurate within professional AI literacy than within general education AI literacy.

**CE-6: The Brauner et al. "criticality map" (119 citations) shows the field has a diagnostic framework for public criticality toward AI.** While not a curriculum paper, it is evidence that researchers *are* studying how critically people engage with AI — a precondition for understanding what judgment-development interventions should target.

---

### VI. The Genuine Evidential Case for the "Underdeveloped" Claim

Notwithstanding the counter-evidence above, three structural findings from OpenAIRE data sustain the claim at the level of *empirical operationalization*:

1. **The declarative/empirical gap is confirmed by record counts.** "AI literacy critical thinking" yields 2,223 records, but "critical thinking evaluating AI output students" yields only **18 records** — showing that while critical thinking is widely *mentioned* alongside AI literacy, it is rarely the *research subject* of a study.
2. **Probabilistic/uncertainty reasoning has near-zero empirical presence.** Three separate queries converge on **<20 records** with near-zero citation weight. The two most directly relevant papers (Pramartha 2026; Córdova 2025) have **0 citations**. This is not a retrieval artifact — it reflects a genuine absence of established research.
3. **The "Evaluate" dimension in frameworks has not generated a corresponding empirical research strand.** Searching "evaluate create AI literacy competency" returns 18 records, dominated by the Ng et al. foundational paper itself and its citations — not follow-on empirical studies that teach, measure, or assess evaluative reasoning as a specific AI literacy skill. The dimension is named but not yet operationalized in published research indexed in OpenAIRE.

The most accurate characterization of the OpenAIRE evidence is therefore: **critical evaluation and judgment are structurally present in AI literacy frameworks (counter-evidence is real) but remain empirically underdeveloped as distinct research objects — and probabilistic/uncertainty reasoning is substantively absent at any level of the literature.**

---

*Self-check: OpenAIRE added genuine value unavailable elsewhere — bibliometric classes (C2/C3 influence, C1 popularity) confirmed which papers carry field-level authority; record counts from pagination totals provided quantitative evidence of conceptual density/absence; ScholeXplorer citation data was not needed here since the investigation was concept-level, not network-level. bioRxiv and medRxiv were correctly excluded — this topic is education/social science, not life sciences. I explicitly evaluated both null and non-null results and distinguished AND-logic noise from genuine signal in every query.*