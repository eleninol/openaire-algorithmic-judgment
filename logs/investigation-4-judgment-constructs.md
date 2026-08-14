All four search waves are complete. Now synthesizing the full report.

---

## Investigation 4: Judgment-Oriented Concepts in AI Literacy, AI Education, and Human–AI Interaction Research — OpenAIRE Graph Evidence

**Tools and logic used throughout:** `openaire_search_research_products` (AND-logic keyword search, sorted citationCount DESC, page sizes 6–8), `openaire_get_research_product_details` (full bibliometric profiles for 8 papers), `openaire_get_citation_network` (depth=1, max\_nodes=30, for Alon-Barkat 2022), `openaire_explore_research_relationships` (ScholeXplorer, target\_pid for Zhang et al. 2025), `openaire_find_by_influence_class` (C1, C2 — both returned 0 for this cluster, noted below), `openaire_analyze_research_trends` (year-by-year, four queries), `openaire_get_author_profile` (Ujwal Gadiraju).

**Retrieval limitations and metadata inconsistencies:**

- `find_by_influence_class` at C1 and C2 returned **0 results** for both "automation bias AI human decision" and "appropriate reliance AI trust calibration." This does not mean these papers lack citation weight — Zhang et al. (2020) has 674 citations, Alon-Barkat (2022) has 317. It means OpenAIRE's field-normalization places these papers in C3 (top 1%), not higher, because they are being compared against the entire computer science and social science output. The C3 result is itself notable — no C1/C2 paper exists at these intersections per OpenAIRE's algorithm.
- "Epistemic judgment AI" and "decision calibration" as standalone phrases are not recognized vocabulary in this literature — queries using those exact strings returned noisy or empty results.
- The query "AI output evaluation acceptance rejection human" (5 terms, AND-logic) returned 4 noise results — too many terms collapsed the result space. This was noted and the concept was approached via shorter, 3-term reformulations.

---

### Aggregate Record Counts

**See table in visualization panel →**

---

### Publication Trends

**See table in visualization panel →**

Both sub-literatures show the same inflection: pre-2022 stable at low volume, then sharp acceleration in 2024–2025 after large language models enter widespread deployment. "Automation bias" is older and larger; "appropriate reliance" is newer and specifically tied to the XAI/explainability research program that emerged from 2020 onward.

---

### Part A: Term-by-Term Findings

#### 1. "Algorithmic Judgment" — Inferred; not a defined construct

**Exact terminology status:** Not an established defined term in AI or AI literacy research. It appears incidentally in legal/governance contexts (Binns 2019: "Human Judgement in Algorithmic Loops; Individual Justice and Automated Decision-Making," 110 citations) to mean "the exercise of judgment within or over automated decision systems," but it is not operationalized as a psychological or pedagogical construct.

**Representative publications under the concept:**

- **Rodgers, Murray & Stefanidis (2023)** — "An AI algorithmic approach to ethical decision-making in human resource management processes" (*Human Resource Management Review*, 312 citations). Studies how AI-augmented decision-making in HR is structured. Close to "algorithmic judgment" in the sense of ethically-inflected algorithmic decision processes, but addresses organizational design, not human literacy.
- **Dietvorst & Bharti (2020)** — "People Reject Algorithms in Uncertain Decision Domains Because They Have Diminishing Sensitivity to Forecasting Error" (*Psychological Science*, 234 citations; C4 influence, C2 popularity, C3 impulse). Directly about the decision to accept or reject algorithmic advice. Key finding: **diminishing sensitivity to forecasting error in uncertain domains** causes people to prefer human judgment even when algorithms outperform — the first published causal account of algorithm rejection tied to uncertainty structure. This paper is empirically about the act of judging an algorithm's output. Its vocabulary is behavioral science ("algorithm aversion/rejection"), not AI literacy.
- **Bogert, Schecter & Watson (2021)** — "Humans rely more on algorithms than social influence as task becomes more difficult" (*Scientific Reports*, 113 citations). Finds algorithm reliance increases with task difficulty — directly tests when humans defer to algorithmic vs. human advice.
- **Binns (2019)** — "Human Judgement in Algorithmic Loops; Individual Justice and Automated Decision-Making" (*SSRN*, 110 citations). Legal-philosophical framing: the role of human judgment in algorithmic administrative systems.

**Classification: (c) Adjacent.** "Algorithmic judgment" as a named research concept does not exist; the substance is covered by "algorithm aversion/reliance" in psychology and "automated decision-making" in law and governance.

---

#### 2. "Automation Bias" — Established; 987 records; oldest and largest sub-cluster

**Exact terminology status:** ✅ Fully established. "Automation bias" is a named phenomenon — the tendency to defer to automated recommendations without critical scrutiny, first defined by Parasuraman & Riley (1997) in aviation; extensively studied in clinical radiology since 2010; explicitly applied to AI systems since \~2019.

**Representative high-citation papers:**

- **Alon-Barkat & Busuioc (2022)** — "Human–AI Interactions in Public Sector Decision Making: 'Automation Bias' and 'Selective Adherence' to Algorithmic Advice" (*Journal of Public Administration Research and Theory*, **317 citations; C3 influence, C2 popularity, C2 impulse**). Three experimental studies (N=605, 904, 1,345). Uses "automation bias" in title. Key empirical finding: *automation bias was not reliably observed*, but "selective adherence" — adopting algorithmic advice specifically when it aligns with pre-existing stereotypes — was. This is a nuanced finding: automation bias is context-dependent, not universal. The 30-paper citation network clusters tightly in public administration, AI governance, and street-level bureaucracy.
- **Dratsch et al. (2023)** — "Automation Bias in Mammography" (*Radiology*, **276 citations**). Clinical imaging study of automation bias from AI-generated BI-RADS suggestions. A clinical domain landmark.
- **Jones-Jang & Park (2022)** — "How do people react to AI failure? Automation bias, algorithmic aversion, and perceived controllability" (*Journal of Computer-Mediated Communication*, **120 citations**). Tests both automation bias and algorithmic aversion in response to AI failure — directly linking the two constructs in a communication research frame.
- **Romeo & Conti (2025)** — "Exploring automation bias in human–AI collaboration: a review and implications for explainable AI" (*AI & Society*, **78 citations**). Subject tags explicitly include "trust calibration" alongside automation bias — a bridge paper linking both constructs.

**Disciplinary location:** Primarily clinical medicine (radiology, pathology), public administration, and communication science. The AI literacy and AI education fields have not substantively engaged with this literature.

**Cross-field connection to AI literacy:** Sparse. "Automation bias AI literacy education students" (40 records) yields as its most relevant paper: **Tian & Zhang (2025)** — "Learners' AI dependence and critical thinking: The psychological mechanism of fatigue and the social buffering role of AI literacy" (*Acta Psychologica*, 47 citations; **C4 influence, C3 popularity**). This is the bridge paper — it explicitly invokes "automation bias" theory in an AI literacy education context and finds that information literacy buffers the negative effects of AI dependence on critical thinking. However: (1) the paper cites cognitive offloading theory, not the HCI/clinical automation bias literature directly; (2) "information literacy" rather than "AI literacy" is the operative moderator; (3) it is C4 influence. The bridge is thin and recent.

**Classification: (a) Exact terminology** — within psychology, HCI, clinical, and public administration research. **(c) Adjacent** to AI literacy education.

---

#### 3. "Trust Calibration" — Established; 92 records; EXACT terminology in HCI sub-cluster

**Exact terminology status:** ✅ Established as an exact term in the HCI and human factors literature since at least 2019.

**Representative papers:**

- **Zhang, Liao & Bellamy (2020)** — "Effect of confidence and explanation on accuracy and trust calibration in AI-assisted decision making" (FAccT 2020, **674 citations; C3 influence, C2 popularity, C2 impulse, C2 citation\_class**). This is the most-cited paper using "trust calibration" as its explicit theoretical frame. Abstract states the goal is to "appropriately calibrate human trust in the AI on a case-by-case basis; knowing when to trust or distrust the AI." Shows that confidence scores help calibrate trust, but trust calibration alone does not improve decision outcomes — the human must also bring complementary knowledge. This is the foundational empirical paper for trust calibration in AI-assisted decision-making.
- **Okamura & Yamada (2020)** — "Adaptive trust calibration for human-AI collaboration" (*PLOS ONE*, **197 citations; C3 influence, C3 popularity**). Proposes a framework for detecting improper trust calibration (specifically over-trust) and intervening with cues to prompt recalibration. Evaluated in a drone inspection simulator.
- **Dubiel, Daronnat & Leiva (2022)** — "Conversational Agents Trust Calibration" (*CUI*, 25 citations). Uses "trust calibration" in the title explicitly for conversational AI systems.
- **Lebiere et al. (2021)** — "Adaptive Cognitive Mechanisms to Maintain Calibrated Trust and Reliance in Automation" (*Frontiers in Robotics and AI*, 32 citations). Proposes a cognitive architecture model of calibrated trust.

**Sub-cluster structure:** Trust calibration research is a tight cluster primarily in ACM CHI, IUI, and CSCW venues, plus *PLOS ONE* and *Frontiers in Robotics and AI*. Recurring authors include Ujwal Gadiraju (TU Delft; 165 publications; organizes "AI CHAOS! Challenges for Human Oversight of AI Systems" workshop series at CHI 2026), Q. Vera Liao (Microsoft Research), and Gaole He (TU Delft).

**Connection to reasoning/statistics:** "Trust calibration statistical reasoning probability uncertainty" returned **3 noise records**. The trust calibration literature's understanding of "calibration" is behavioral (observed reliance behavior vs. AI accuracy) rather than statistical (Bayesian probability calibration). The two uses of "calibration" are terminologically adjacent but conceptually distinct — there is no cross-citation between the statistical calibration literature and the AI trust calibration literature.

**Classification: (a) Exact terminology** — within HCI. **(c) Adjacent** to AI literacy education.

---

#### 4. "Appropriate Reliance" — Established; 161 records; EXACT terminology; rapid growth

**Exact terminology status:** ✅ Established as exact terminology in HCI since approximately 2021; appearing in paper titles from 2023 onward.

**Representative papers:**

- **Schoeffer, De-Arteaga & Kühl (2024)** — "Explanations, Fairness, and Appropriate Reliance in Human-AI Decision-Making" (*CHI 2024*, 67 citations). Uses "appropriate reliance" in the title. Studies how explanations and fairness information affect reliance behavior.
- **Chen, Liao & Vaughan (2023)** — "Understanding the Role of Human Intuition on Reliance in Human-AI Decision-Making with Explanations" (*CSCW*, 115 citations). Studies how human intuition interacts with AI explanations in determining reliance patterns.
- **He, Kuiper & Gadiraju (2023)** — "Knowing About Knowing: An Illusion of Human Competence Can Hinder Appropriate Reliance on AI Systems" (*CHI 2023*, 92 citations; **C4 influence, C3 popularity, C3 impulse**). Uses Dunning-Kruger Effect (metacognitive bias) to explain under-reliance in users who overestimate their own competence. Intervention study — tutorial showing AI fallibility improves appropriate reliance for some participants but harms it for others.
- **Gaube, Jussupow & Kokje (2024)** — "Underreliance Harms Human-AI Collaboration More Than Overreliance in Medical Imaging." Important directional finding: **underreliance** is more damaging than overreliance in clinical decision-making contexts. Challenges the common assumption that over-trust is the primary risk.

**Disciplinary location:** Squarely in HCI (CHI, CSCW, IUI) and clinical AI contexts. Not in AI literacy or AI education venues.

**Trend:** 0→0→1→1→6→10→27→42 (total 87 papers, 2018–2025). The concept barely existed before 2022 and is now producing 42 papers per year — a rapid crystallization of a distinct research program.

**Classification: (a) Exact terminology** — within HCI. **(c) Adjacent** to AI literacy education.

---

#### 5. "Algorithm Aversion / Algorithm Appreciation" — Established; 6 records in OpenAIRE (underindexed); known behavioral science construct

**Exact terminology status:** ✅ Established as an exact construct in behavioral science since Dietvorst et al. (2015), which is the definitional paper. "Algorithm appreciation" was introduced by Logg et al. (2019) as the complementary positive construct.

**Note on underindexing:** The OpenAIRE query "algorithm aversion appreciation human judgment" returned only **6 records**, and none are the foundational papers (Dietvorst et al. 2015, Logg et al. 2019). This reflects OpenAIRE's indexing gaps for behavioral economics and psychology literature — many key papers in this tradition are in *Organizational Behavior and Human Decision Processes*, *Management Science*, and *Journal of Experimental Psychology*, which may not be fully indexed. The record count of 6 severely underrepresents this literature.

**Substance:** Dietvorst & Bharti (2020) (234 citations) is indexed and represents the algorithm rejection tradition. The key empirical finding — that people prefer human judgment over superior algorithms specifically in uncertain domains — connects directly to the concept of "judgment under uncertainty."

**Classification: (a) Exact terminology** — within behavioral science and organizational psychology. **(c) Adjacent** to AI literacy education.

---

#### 6. "Epistemic Judgment" — Not established; 32 noisy records; not an AI research term

**Exact terminology status:** ❌ Not an established term in AI literacy, AI education, or HCI research. The 32 records returned by "epistemic judgment AI knowledge uncertainty" were dominated by unrelated documents (bachelor theses on entrepreneurship, Arabic-language reports, journalism papers). No paper uses "epistemic judgment" as a defined construct in AI literacy or human-AI interaction contexts.

**What exists instead:** The closest conceptual equivalent is the philosophical/epistemological literature on justified belief and epistemic justification in the context of AI (e.g., Ferrario 2023: "Justifying Our Credences in the Trustworthiness of AI Systems: A Reliabilistic Approach," 9 citations, *Science and Engineering Ethics*). This paper explicitly uses epistemological framing — credences, reliability, trustworthiness — but is a philosophical paper, not an empirical one, and has low citation uptake.

**Classification: (b) Conceptually equivalent but differently named** — what would be called "epistemic judgment" in philosophy is named "appropriate reliance" or "trust calibration" in HCI, and "critical evaluation of AI" in AI literacy frameworks. The concept exists, but not under this label.

---

#### 7. "AI Output Evaluation" — Implicit in frameworks; not a named research construct

**Exact terminology status:** ❌ Not an established term. "AI output evaluation acceptance rejection" as a query (4+ terms) returns 4 noisy results. The act of evaluating, accepting, rejecting, or revising AI-generated outputs is studied extensively in HCI under the vocabulary of "reliance," "acceptance," "override," and "deferral" — but not under the phrase "AI output evaluation."

**What exists instead:** The most relevant empirical tradition is the **XAI (explainability) + reliance** research program, which specifically studies how providing explanations of AI outputs affects human decisions to accept or override. Representative: Morrison et al. (2024) "The Impact of Imperfect XAI on Human-AI Decision-Making" (58 citations); Schoeffer et al. (2024) "Explanations, Fairness, and Appropriate Reliance" (67 citations). These papers operationalize the accept/reject/revise decision in experimental paradigms.

In clinical AI, the behavioral outcome is often framed as "concordance" or "adherence" — whether the clinician agrees with or deviates from the AI's recommendation. This is operationally equivalent to "AI output evaluation" but never named as such.

**Classification: (b) Conceptually equivalent but differently named** — captured by "reliance," "adherence," "concordance," "override," and "XAI" research programs.

---

#### 8. "Decision Calibration" — Not established as a defined term

**Exact terminology status:** ❌ Not found as a named construct. The query "decision calibration confidence AI prediction accuracy" (61 records) yielded Zhang, Liao & Bellamy (2020) as top result — which uses "trust calibration" not "decision calibration." "Decision calibration" as a specific term does not appear in the literature.

**What exists instead:** The behavioral analog is "calibration" in the psychometric sense — the correspondence between a person's subjective confidence and objective accuracy. This is studied in forecasting (Tetlock's superforecasters), medical decision-making, and cognitive psychology, but its connection to AI-assisted decision-making has not been formalized as "decision calibration."

**Classification: (b) Conceptually equivalent but differently named** — closest existing term is "trust calibration" (behavioral alignment of trust with actual AI accuracy).

---

#### 9. "Judgment Under Uncertainty" — Foundational in cognitive psychology; not integrated into AI literacy

**Exact terminology status:** The term "judgment under uncertainty" is foundational in cognitive psychology — specifically Kahneman & Tversky's 1974 *Science* paper. The query "judgment under uncertainty AI decision support" (98 records) returned mixed results, with the most relevant being Dietvorst & Bharti (2020) and one new entry: Cole (2026) "Decision-Making Under Uncertainty in AI-Enabled Warfare: Implications for Education and Training" (*Military Medicine*). The title is exact — it addresses judgment, uncertainty, AI, and education/training together. But it is a domain-specific (military) application with 0 citations.

**What exists more broadly:** The entire tradition of human factors and cognitive engineering treats uncertainty management in AI-assisted decision-making as a core problem. This maps directly onto the Kahneman-Tversky tradition. But AI literacy education has not formally incorporated this tradition.

**Classification: (b) Conceptually equivalent** — "judgment under uncertainty" has deep roots in cognitive psychology; the AI literacy field treats its epistemic content (knowing when to trust AI) without naming or citing this tradition. **(c) Adjacent** in current AI literacy education research.

---

### Part B: Accept / Reject / Revise / Qualify Decision Studies

The specific empirical scenario the user highlights — studies where humans decide whether to accept, reject, revise, or qualify an AI-generated output — is a well-defined experimental paradigm. The most rigorous work operates in three domains:

**Clinical AI (highest methodological density):**

- Dratsch et al. (2023) — *Radiology*, 276 citations: Radiologists shown AI-generated BI-RADS classifications; measured whether they adopted, overrode, or were biased toward AI suggestions.
- Gaube, Jussupow & Kokje (2024): Mixed-methods randomized crossover — clinicians must choose to follow or override AI recommendations in medical imaging. Found underreliance harms more than overreliance.
- Han et al. (2026) — Eye-tracking study: "Verifiable Explanations Support Visual Evidence Checking in AI-Assisted Chest Radiograph Interpretation" — directly observes the checking/verification behavior.

**HCI (largest methodological breadth):**

- Zhang, Liao & Bellamy (2020) — 674 citations: Participants see AI predictions with confidence scores and/or explanations; measured whether they adopt or override per prediction.
- Chen, Liao & Vaughan (2023) — 115 citations: Tests whether human intuition or AI explanations better predicts whether users will accept/reject AI advice.
- He, Kuiper & Gadiraju (2023) — 92 citations: Dunning-Kruger study; tutorial intervention changes whether users over-rely (accept without scrutiny) or under-rely (reject valid advice).
- Inkpen et al. (2023) — "Advancing Human-AI Complementarity" (*ACM TOCHI*, 110 citations): Studies what user expertise level and algorithmic tuning conditions produce optimal joint decision outcomes — implicitly studying when accept vs. override is correct.

**Public administration (social experiment approach):**

- Alon-Barkat & Busuioc (2022) — 317 citations: Civil servants presented algorithmic recommendations; measured adherence vs. deviation. Introduced "selective adherence" — accepting AI advice only when it aligns with stereotypes.

**What these studies share:** They all operationalize the accept/reject decision behaviorally, measuring outcomes (accuracy, time, trust ratings) rather than teaching competencies. None are educational interventions. None are in AI literacy venues (CAEAI, Educational Technology & Society, etc.). None have been incorporated into AI literacy competency frameworks.

---

### Part C: Connection to Mathematical, Statistical, Probabilistic, and Model-Based Reasoning

This is the explicit test of whether the judgment-oriented literature connects to the quantitative reasoning traditions identified in Investigation 3.

**Direct query result:** "trust calibration statistical reasoning probability uncertainty" — **3 records, all noise.** This is the hardest evidence: the two literatures do not currently produce co-authored or co-cited work at this intersection.

**Qualitative analysis of potential connections:**

*Statistical calibration vs. trust calibration:* In forecasting and probability elicitation, "calibration" has a precise technical meaning — a forecaster is calibrated if their stated 70% confident predictions come true \~70% of the time. This is Bayesian calibration. In the AI trust literature, "trust calibration" means behavioral alignment of reliance behavior with actual AI accuracy — a different operationalization that does not require understanding of probability. The two uses are terminologically similar but methodologically independent. No paper in the trust calibration cluster cites the forecasting calibration literature (Tetlock, Murphy) as a theoretical foundation.

*Dietvorst & Bharti (2020) and uncertainty:* This is the strongest connection point. The paper's core construct — diminishing sensitivity to forecasting error in uncertain domains — is fundamentally about how humans perceive probabilistic outcomes. The paper's subjects are forecast-based decisions (will X happen). People are more willing to reject algorithm advice in *inherently uncertain* domains precisely because they cannot detect the magnitude of forecasting error. This is implicitly a claim about probabilistic reasoning deficits — humans treat uncertain-domain errors as equiprobable regardless of their magnitude. But the paper's framing is behavioral economics, not probabilistic education. It does not recommend teaching statistical reasoning as a remedy.

*XAI confidence scores and statistical literacy:* Zhang, Liao & Bellamy (2020) show that confidence scores help users calibrate trust — but they cannot demonstrate WHY users calibrate better. Is it because users understand what a "65% confidence" output means statistically? The paper is agnostic on this. A paper explicitly examining whether users with statistical training better calibrate their trust using confidence scores would represent the bridge — but no such paper exists in OpenAIRE.

**Finding:** The connection is logically entailed but empirically unexamined. The claim that statistical/probabilistic reasoning competency improves appropriate reliance on AI is a well-motivated hypothesis supported by the structure of the adjacent literatures — but no paper has tested it directly.

---

### Part D: Recurring Authors and Research Clusters

**Three distinct clusters, operating independently:**

**See table in visualization panel →**

None of these clusters crosses into the AI literacy education cluster (*CAEAI*, *BJET*, *ET&S*, *Computers & Education*). The AI literacy cluster is organized around competency frameworks (Long & Magerko, Ng et al., Chiu), implementation studies, and teacher training — it does not cite Gadiraju, Liao, Dietvorst, or Alon-Barkat.

**Gadiraju** is the most active single researcher at the intersection of human oversight, appropriate reliance, and cognitive bias in AI interaction — 165 publications, organizing the "AI CHAOS!" workshop series on "Challenges for Human Oversight of AI Systems" (CHI 2026). His lab (TU Delft) has papers on "Belief Updating and Delegation in Multi-Task Human-AI Interaction" and "Cognitive Biases to Calibrate Trust in Evolving AI Systems" — directly relevant to judgment concepts — but published entirely within HCI venues.

---

### Part E: Counter-Evidence — Does a Mature Reasoning-and-Judgment Strand Already Exist Within AI Literacy?

This is the critical test. Four types of potential counter-evidence were sought:

**Counter-evidence 1 — Chiu et al. (2024), 358 citations, C3 influence, C1 impulse:** The most-cited current AI literacy framework paper explicitly calls "data literacy" and "algorithmic literacy" future research directions for AI literacy. This shows the AI literacy field's leading researchers recognize quantitative/algorithmic reasoning as an *aspiration* — but the explicit acknowledgment of it as a gap is itself evidence that it is not yet integrated.

**Counter-evidence 2 — Long & Magerko (2020), 1,975 citations:** Includes "Critically Evaluate AI" as one of 17 competencies. This is the strongest structural counter-evidence — critical evaluation of AI is formally present in the field's most-cited framework. But three qualifications apply: (1) the framework does not specify what cognitive processes constitute "critical evaluation," making it compatible with any skill level of scrutiny; (2) no empirical research has studied whether students trained in AI literacy develop better AI output evaluation skills in the operational sense studied by Gadiraju, Liao, and Dratsch; (3) the appropriate reliance literature is not cited in Long & Magerko.

**Counter-evidence 3 — Tian & Zhang (2025), 47 citations, C4 influence:** The only paper in the OpenAIRE AI literacy corpus that explicitly invokes automation bias theory. It finds AI literacy (operationalized as information literacy) buffers the negative effect of AI dependence on critical thinking. This is genuine counter-evidence — a bridge paper exists. But its influence class (C4) and citation count suggest it is below the threshold of field-defining work, and it treats "information literacy" rather than AI literacy as the operative concept.

**Counter-evidence 4 — Query "AI literacy critical evaluation reasoning judgment competency" (7 records):** Returns only 7 records with the highest-cited paper at 1 citation. This is the definitive null finding: a mature reasoning-and-judgment strand within AI literacy does not exist as a distinct research object. If it did, a search combining all these terms would return a recognizable cluster of papers, not 7.

**Conclusion on counter-evidence:** The field has the structural vocabulary ("critically evaluate AI" appears in frameworks), a nascent bridge paper (Tian & Zhang 2025), and aspirational calls for data/algorithmic literacy integration (Chiu 2024). What does not exist is an empirical research program that: (1) operationalizes AI output evaluation as a trainable skill; (2) tests instructional interventions that improve accept/reject/revise accuracy; (3) measures outcomes using the behavioral or psychometric methods used in HCI and psychology. The gap between the structural presence of the concept in competency frameworks and the empirical absence of research on its development is the defining feature of this landscape.

---

### Summary: Classification Table

**See table in visualization panel →**

The central structural finding: the judgment-oriented research tradition is substantial, growing rapidly (87–147 papers in trend windows, with 42–86 in 2025 alone), and contains landmark C3-class papers (Zhang et al. 2020 at 674 citations; Alon-Barkat 2022 at 317 citations). It operates in entirely different disciplinary venues from AI literacy education and the two fields do not cite each other. The link to mathematical/statistical reasoning is logically implied by the structure of trust calibration theory but has not been tested in any paper indexed in OpenAIRE.