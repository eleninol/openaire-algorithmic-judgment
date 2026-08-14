I now have all the data I need. The Wave 4 results complete the falsification test. Here is the full Investigation 5 report.

---

# Investigation 5: Final Falsification Test — Are the Three Traditions Weakly Connected?

## Overview of the Test

This investigation tests whether three research traditions — (T1) AI literacy and competency frameworks, (T2) human-AI judgment and reliance research, and (T3) mathematical/statistical/probabilistic/model-based reasoning about uncertainty — are weakly connected or genuinely integrated. The test was conducted by searching for every meaningful bridge combination, examining the citation networks of anchor papers, and explicitly seeking counter-evidence that would falsify the fragmentation hypothesis. Searches were executed across four waves with 40+ parallel OpenAIRE calls.

---

## Tools, Queries, and Record Counts

**Primary tool:** `openaire_search_research_products` — used with AND-logic, sorted by `citationCount DESC`, `detail="standard"`.

**Citation network tools:** `openaire_get_citation_network` — applied to Long & Magerko (2020) [1975 citations, 80 citing nodes sampled] and Bhatt et al. (2020) "Explainable ML in Deployment" [439 citations, 50 citing nodes sampled; used as a proxy for XAI/deployment literature accessible to the T2 tradition].

**Trend tool:** `openaire_analyze_research_trends` — used for "algorithm aversion AI literacy education" (2018–2025).

**Bibliometric detail tool:** `openaire_get_research_product_details` — used for five candidate bridge papers.

**Key AND-logic constraint:** OpenAIRE requires all query terms to co-occur. Multi-tradition queries with 5–6 terms collapsed to 0 results throughout; all genuine bridge queries were limited to 3–4 terms. Where collapse occurred, shorter reformulations were retried and results compared.

---

## Bridge 1: T1 + T2 — AI Literacy with Appropriate Reliance or Trust Calibration

**Queries and results:**

- "AI literacy appropriate reliance trust" → **21 records**; top hit = Hua et al. (2024), "AI acceptability in medical imaging," 90 citations, *Artificial Intelligence in Medicine* — a clinical AI adoption paper, not the HCI appropriate reliance tradition
- "AI literacy appropriate reliance framework" → **2 noise records**
- "AI competency framework reliance calibration" → **1 noise record** (medical education deskilling paper)
- "Trust calibration AI literacy data reasoning students" → **2 noise records**

**Citation network evidence — Long & Magerko (2020), 80 citing papers:**

Examined all 80 citing papers for any connection to the HCI appropriate reliance or trust calibration traditions. Every citing paper is within the AI literacy education field: curriculum design, AI literacy scale development, generative AI adoption studies, critical AI literacy discourse, AI tool pedagogy, and K-12 computing education. **Zero citing papers** come from the appropriate reliance or trust calibration research community. Authors such as Yin, Lee, Bansal, Schemmer, Rechkemmer, or Vodrahalli — the researchers who publish on appropriate reliance at CHI, CSCW, and AAAI — do not appear anywhere in the 80-node citation network.

**Citation network evidence — XAI/deployment literature (50 citing papers):**

The 50 papers citing the landmark XAI-in-deployment paper (FAccT 2020) cite exclusively within: XAI methods literature, medical AI deployment, software engineering, NLP, AI fairness and governance, and JAMA-style clinical informatics. **Zero papers** from AI literacy education venues (CAEAI, BJET, Computers & Education, Educational Technology Research and Development) appear in this network.

**Verdict for Bridge 1:** No citation bridge and no terminological bridge exist. The terms "appropriate reliance" and "trust calibration" — the operational vocabulary of T2 — are absent from AI literacy competency framework literature and from any publication that also uses the vocabulary of T1. The 21 records returned by the loosest bridge query ("AI literacy appropriate reliance trust") represent papers about either clinical AI adoption (where "appropriate" is an adjective modifying clinical decision-making, not the HCI construct) or general technology trust — not genuine integration of the two research traditions.

---

## Bridge 2: T1 + T2 — AI Literacy with Automation Bias or Algorithm Aversion

**Queries and results:**

- "AI literacy automation bias algorithm aversion" → **0 records** (AND-logic collapse on four terms)
- "Automation bias education students AI literacy" → **40 records**; top hit = Tian & Zhang (2025), 47 citations
- "Algorithm aversion appreciation human education" → **4 records**; top hits = Kaufmann (2021), 19 citations, and Laupichler et al. (2025), 1 citation
- "Algorithm aversion AI literacy education" trend (2018–2025) → 0/0/0/0/0/0/0/**2** — two papers in all of 2025

This bridge query produced the only genuine cross-tradition papers found in the entire investigation. Three papers merit close attention:

**Kaufmann (2021)**, "Algorithm appreciation or aversion? Comparing in-service and pre-service teachers' acceptance of computerized expert models," *Computers and Education: Artificial Intelligence*, 19 citations, C4 influence and popularity. This paper uses the behavioral science term "algorithm aversion" (from Dietvorst et al. 2015) in an AI education venue. The study examines whether teachers prefer human vs. algorithmic advice on student recommendations. It is a genuine terminological bridge between T2's behavioral science wing and T1's education context. However, it does not engage with the AI literacy competency framework tradition (no mention of Long & Magerko, Ng et al., Chiu, or Almatrafi); it is not cited by AI literacy framework papers; and it explicitly finds that numeracy does NOT predict algorithm acceptance, which actively undercuts any hypothesis that quantitative reasoning is the relevant moderating variable. This paper sits in an education venue without inhabiting the theoretical structure of either T1 or T3.

**Laupichler, Knoth, Schleiss & Raupach (2025)**, "Algorithm aversion revisited: The role of AI literacy and attitudes towards AI in shaping perceptions of AI-generated texts," *British Journal of Educational Technology*, 1 citation, C5 influence and impulse. This is the most direct bridge paper found across all five investigations. The abstract explicitly integrates algorithm aversion (T2 behavioral science vocabulary) with AI literacy (T1 vocabulary), examines when students trust or reject AI-generated text, and uses validated AI literacy instruments. Theoretically, this is exactly the kind of paper the bridge should look like. But it was published in late 2025, has 1 citation, and has C5 influence — placing it at the very bottom of the bibliometric hierarchy. It is an isolated research foray, not evidence of a mature strand. Critically, the paper frames the evaluation question in terms of attitude and belief, not statistical or probabilistic reasoning: students judge text credibility based on whether it is labeled "AI-generated" or "human-written," not by evaluating the reliability or confidence of the content itself. The T3 quantitative reasoning tradition remains absent.

**Tian & Zhang (2025)**, "Learners' AI dependence and critical thinking: The psychological mechanism of fatigue and the social buffering role of AI literacy," *Acta Psychologica*, 47 citations, C4. This paper sits partly in the T1/T2 bridge zone by connecting AI dependence (a behavioral analog of automation bias) with critical thinking and AI literacy. It was published in a psychology journal, invokes automation bias implicitly, and uses AI literacy as a protective factor. It is the most-cited bridge paper across both investigations 4 and 5. However: the journal is psychology, not AI literacy education or HCI; it does not cite T1 framework papers (Long & Magerko, Ng et al.); it does not invoke HCI reliance constructs (appropriate reliance, trust calibration); and it contains no quantitative or probabilistic reasoning component.

**Trend assessment:** 0→0→0→0→0→0→0→2 for "algorithm aversion AI literacy education" across 2018–2025. Two papers appearing in 2025 represent not a developing research community but an emergent fringe. For comparison, "AI literacy" as a standalone query returned 1,000+ records per year by 2024–2025.

**Verdict for Bridge 2:** An embryonic bridge exists, consisting of three papers published in 2024–2025, all at C4–C5 bibliometric influence. The bridge is real in the sense that some researchers are explicitly combining the vocabulary of both traditions. It is not a mature bridge in the sense of having citation mass, theoretical depth, or consistent engagement with the competency framework literature of T1. The behavioral science wing of T2 (algorithm aversion) has weakly penetrated AI education venues; the HCI wing of T2 (appropriate reliance, trust calibration) has not penetrated at all. The three bridge papers do not reference each other or form a cluster.

---

## Bridge 3: T2 + T3 — Statistical/Probabilistic Reasoning with Trust Calibration or AI Reliance

**Queries and results:**

- "Probabilistic reasoning trust calibration AI uncertainty" → **9 records**, all noise (student science journals, pseudoscience theses, quantum AI books)
- "Statistical reasoning AI reliance decision making" → **24 records**, all off-topic (LLM benchmarking, clinical AI evaluation, Applied Psychometrics textbooks)
- "AI output evaluation Bayesian probabilistic reasoning humans" → **2 noise records**
- "Trust calibration statistical reasoning probability uncertainty" (from Investigation 4) → **3 noise records**

This is the hardest evidence of fragmentation found across the entire investigation. T2 and T3 are not just weakly connected — they appear to have no connection whatsoever in the OpenAIRE-indexed literature. The trust calibration and appropriate reliance research community (which operates within HCI, focusing on behavioral and design factors that affect over- or under-reliance) does not draw on statistical or probabilistic reasoning traditions. Researchers who study appropriate reliance typically manipulate XAI explanations or confidence displays and measure reliance behavior; they do not theorize from Bayesian or probability theory frameworks. Conversely, educational researchers studying statistical literacy or probabilistic reasoning focus on human reasoning about data and uncertainty in general — they do not apply those frameworks to the specific question of human evaluation of AI outputs.

**Verdict for Bridge 3:** No bridge. The quantitative reasoning tradition and the HCI reliance tradition are operating in entirely separate theoretical and empirical spaces. There is no paper in OpenAIRE that uses both "trust calibration" (or "appropriate reliance") and "statistical reasoning" (or "probabilistic reasoning") in a meaningful way.

---

## Bridge 4: Model-Based Reasoning + AI Output Evaluation

**Query:** "model-based reasoning AI output evaluation human" → **123 records**.

This is a case of false abundance produced by AND-logic matching individual terms across unrelated contexts. The 123 records are predominantly XAI evaluation papers (methods for explaining ML models to end users), LLM benchmarking studies, and clinical AI performance assessment. "Model-based reasoning" in these papers refers to how the AI system itself reasons (internal model processes), not to humans reasoning from models in the epistemological sense (how a person reasons about uncertainty using explicit probabilistic or causal models). The top hits — Abdulnour et al. (2025) on clinical supervision of AI use (11 citations) and Qazi et al. (2025) on automation bias in LLM-assisted diagnosis (9 citations) — are clinical medicine papers entirely within T2's clinical wing. They do not engage with T3 (mathematical/statistical reasoning) or T1 (AI literacy competency frameworks).

**Verdict for Bridge 4:** 123 records are noise. The epistemological meaning of "model-based reasoning" — applying explicit probabilistic or causal models to evaluate AI outputs — does not exist as a research construct in the indexed literature. The 0 records at the intersection of "probabilistic reasoning + AI output evaluation + human judgment" confirm this.

---

## Bridge 5: Mathematical/Data Literacy + Accept/Reject/Override Decisions About AI Outputs

**Queries and results:**

- "Data literacy AI decision accept reject override" → **1 noise record**
- "Mathematical literacy uncertainty AI judgment" → **0 records**
- "AI literacy competency overreliance dependence human" → **0 records**
- "Critical thinking AI evaluation numerical reasoning probability" → **4 noise records**

Complete absence. No paper in OpenAIRE combines data literacy or mathematical literacy with the behavioral question of whether to accept, reject, revise, or override an AI-generated output. This is the most profound gap: the capacity that is arguably most needed for appropriate reliance on AI systems — the ability to reason quantitatively about what an AI output means and how reliable it is — is nowhere studied as a competency to be developed or measured.

**Verdict for Bridge 5:** Zero bridge. This specific conceptual combination — quantitative reasoning skills applied to the human act of evaluating and deciding whether to follow AI recommendations — does not exist as an organized area of study.

---

## Author and Venue Overlap Analysis

**Author overlap:** Across all 40+ searches and the two citation networks examined, no single researcher appears in publications belonging to more than one of the three traditions. The AI literacy framework authors (Long, Magerko, Ng, Chiu, Almatrafi) publish exclusively in AI education venues. The appropriate reliance researchers (Yin, Lee, Bansal, Schemmer) publish exclusively at CHI, CSCW, and AAAI. The statistical/probabilistic reasoning researchers (Karaali on quantitative literacy, How & Hung on AI-Thinking) publish in mathematics education and STEAM venues. No author straddles traditions.

**Venue overlap:** Zero papers appear across all three of: (a) AI literacy education journals (CAEAI, BJET, Computers & Education), (b) HCI reliance venues (CHI, CSCW, AAAI, Human Factors), and (c) mathematical/statistical reasoning education journals (Educational Studies in Mathematics, Mathematical Thinking and Learning). The three communities publish in non-overlapping journals with no evidence of editorial cross-referencing or co-citation links.

**One noteworthy partial exception:** The 2026 CHI-adjacent paper "Rethinking Human-AI Collaboration in Information Seeking: Why Epistemic Incompatibility Demands New Design Paradigms" (Shah 2026, CHIIR 2026 proceedings, 0 citations) cites Long & Magerko. This is a genuine cross-citation from the HCI information retrieval community to the AI literacy tradition. However, it has 0 citations and no abstract in OpenAIRE, so its content and contribution to bridging cannot be verified. It represents one researcher who noticed the relevance of AI literacy concepts in an HCI-adjacent context — not a stable cross-community connection.

---

## Genuine Integration vs. Incidental Co-occurrence: Diagnostic Criteria Applied

To distinguish genuine integration from incidental keyword co-occurrence, four criteria were applied:

1. **Theoretical engagement:** Does the paper cite and engage with the theoretical constructs of both traditions (not just mention both topics in passing)?
2. **Methodological inheritance:** Does the paper use research designs or instruments drawn from both traditions?
3. **Citation mass:** Does the paper have more than 50 citations and C3 or better bibliometric influence?
4. **Community formation:** Do multiple papers cite each other on the cross-tradition topic, indicating a developing subfield?

**Assessment results:**

**See table in visualization panel →**

No candidate bridge paper passes all four criteria. The strongest (Laupichler et al., 2025) passes one criterion partially.

---

## Final Verdict: Falsification Test Result

**The hypothesis of disciplinary fragmentation is confirmed, not falsified.**

The three research traditions remain weakly connected by any bibliometric standard. The specific evidence:

**T1 ↔ T2 (AI literacy ↔ appropriate reliance/trust calibration):** No citation connections. The HCI constructs of appropriate reliance and trust calibration do not appear in AI literacy framework literature and vice versa. The T2 behavioral science wing (algorithm aversion) has produced three nascent bridge papers in 2025, all at C4–C5 influence, with a combined citation count below 50 and no mutual citation network.

**T2 ↔ T3 (appropriate reliance ↔ probabilistic/statistical reasoning):** Zero connection in the indexed literature. No paper bridges the HCI behavioral study of reliance behavior with quantitative or probabilistic reasoning frameworks.

**T1 ↔ T3 (AI literacy ↔ mathematical/statistical reasoning):** As established in Investigation 3, the "AI literacy + probabilistic reasoning uncertainty" intersection contains approximately 6 records with no C3+ papers. The trend is rising sharply in 2025 but from a near-zero baseline.

**T1 ↔ T2 ↔ T3 (all three):** No paper was found that addresses AI literacy competencies AND human-AI judgment/reliance AND mathematical or statistical reasoning together. The triple intersection does not exist in the indexed literature.

**Strongest partial bridges, in order of strength:**

1. **Laupichler et al. (2025)** — T1+T2 behavioral wing: algorithm aversion + AI literacy in one BJET paper, 1 citation. The field's best current bridge is a single uncited 2025 paper.
2. **Tian & Zhang (2025)** — T1+T2 behavioral wing: AI dependence (≈automation bias) + AI literacy + critical thinking, 47 citations, C4. Published in psychology, not AI literacy or HCI.
3. **Kaufmann (2021)** — T2 behavioral wing → education: algorithm aversion in teacher education, 19 citations, C4. No engagement with T1 competency frameworks; numeracy (T3 proxy) explicitly found to be non-predictive.

**What remains disconnected:**

The most critical gap is structural: no tradition has yet formulated the problem of how humans should use quantitative reasoning (probability, confidence intervals, base rates, model error rates) when deciding whether to accept, revise, or override an AI output. This problem belongs conceptually at the intersection of all three traditions, but the three communities — AI literacy educators, HCI appropriate reliance researchers, and mathematics/statistics educators — have not yet identified each other's work as relevant to their own.

The AI literacy tradition defines the competencies needed to critically evaluate AI; it does not specify what cognitive operations "critical evaluation" consists of when an AI output carries quantified uncertainty. The appropriate reliance tradition studies the conditions under which people over- or under-rely on AI; it does not connect those conditions to the learnable reasoning skills that would make better reliance possible. The mathematical reasoning tradition studies how people reason about data and uncertainty; it has not applied that lens to the specific challenge of reasoning about AI outputs.

**Bibliometric authority of the fragmentation finding:**

The finding rests not on the absence of any connection whatsoever (which would be too strong a claim and would be trivially falsified by individual papers) but on the absence of citation mass, theoretical integration, and community formation at any of the three possible bridges. The evidence is quantified: the annual trend count for "algorithm aversion AI literacy education" reached 2 in 2025; "probabilistic reasoning AI education uncertainty" reached 7 in 2025; "statistical reasoning AI education literacy" reached 15 in 2025. In contrast, "AI literacy" alone yields thousands of records annually. The T1 tradition is orders of magnitude more active than any of the bridges connecting it to T2 or T3.

---

## Metadata Limitations and Indexing Caveats

Several limitations constrain the confidence of these findings:

1. **ScholeXplorer citation coverage is partial.** The citation networks examined (Long & Magerko, 80 citing papers; Bhatt et al., 50 citing papers) underrepresent total citations (1975 and 439 respectively). Papers outside ScholeXplorer's indexed range would not appear. However, the qualitative uniformity of all 130 retrieved citing papers — all firmly within their home traditions — makes sampling bias an unlikely explanation for the complete absence of cross-tradition papers.
2. **Algorithm aversion foundational papers underindexed.** Dietvorst et al. (2015, *Journal of Experimental Psychology*) and Logg, Minson & Moore (2019, *Organizational Behavior and Human Decision Processes*) were not reliably retrieved in OpenAIRE searches, likely due to incomplete journal indexing. The behavioral science core of T2's algorithm aversion strand is somewhat underrepresented.
3. **Very recent papers (2025–2026) underrepresent nascent bridging.** OpenAIRE citation data for papers published in late 2025 and 2026 is sparse; citation accumulation lags by months. The bridge papers identified may have more citations than recorded, though this would not change the order-of-magnitude difference from the established traditions.
4. **AND-logic query collapse.** Any multi-term query crossing traditions collapsed to 0–6 records. This makes it impossible to confirm with certainty that the 0 or near-0 record counts represent genuine absence rather than retrieval failure. The reformulation strategy (disaggregating to 3-term queries, confirming results with trend data and citation networks) provides convergent evidence that the absences are real.
5. **The "appropriate reliance" construct.** This specific HCI term may appear in papers indexed in databases OpenAIRE does not fully cover (e.g., ACM Digital Library direct full-text). However, ACM paper metadata — including titles, authors, and citation counts — is generally covered in OpenAIRE via CrossRef and ScholeXplorer.

---

## Summary Table

**See table in visualization panel →**