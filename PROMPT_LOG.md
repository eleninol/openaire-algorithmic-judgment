# Prompt Log and Investigation Sequence

This file records the five main prompts used in the Alien/OpenAIRE MCP exploration. The sequence was deliberately adaptive: later prompts were chosen in response to earlier findings rather than fixed in advance.

## Investigation 1 - Map the home field

**Prompt**

> Map the main research strands associated with AI literacy. Identify influential publications, recurring authors, and the major concepts used to define AI literacy. Focus on research products indexed in the OpenAIRE Graph and explain the connections you identify.

**Decision after output:** The broad mapping showed that critical evaluation already appears structurally in leading AI-literacy frameworks. The exploration therefore shifted from asking whether reasoning is absent to asking how reasoning/evaluation are operationalised.

## Investigation 2 - Test reasoning, interpretation, judgment and uncertainty

**Prompt**

> Within the OpenAIRE Graph literature on AI literacy, identify research products that explicitly address reasoning, interpretation, critical evaluation, decision-making, judgment, uncertainty, or probabilistic reasoning. For each concept, distinguish between explicit occurrence in titles/abstracts/keywords and inferred conceptual relevance. Report representative publications, recurring authors, and approximate record counts where possible. Explain whether these concepts appear central or peripheral to AI literacy research. Use OpenAIRE Graph evidence only, and state the tools, filters, and query logic used. Also identify counter-evidence that would challenge the claim that reasoning and judgment are underdeveloped in AI literacy.

**Decision after output:** Critical evaluation was present in frameworks but appeared less developed as an empirical object; uncertainty/probabilistic reasoning appeared particularly sparse. The next step tested whether mathematical/statistical/model-based reasoning provided the missing connection.

## Investigation 3 - Trace mathematical/statistical/model-based reasoning

**Prompt**

> Using the OpenAIRE Graph, trace explicit and implicit connections between AI literacy and mathematical reasoning, mathematical literacy, model-based reasoning, statistical reasoning, probabilistic reasoning, and uncertainty. Identify publications, authors, citation relationships, projects, or disciplinary clusters where these traditions intersect. Distinguish direct conceptual links from adjacent or inferred links. Report approximate record counts, representative publications, and whether any stable research cluster exists. Also search for counter-evidence: established strands where mathematical or probabilistic reasoning is already integrated into AI literacy education or assessment. State the OpenAIRE tools, filters, and query logic used.

**Decision after output:** The evidence suggested disconnected currents rather than a stable cluster. Because AI-literacy frameworks use "critical evaluation" without necessarily specifying accept/reject behaviour, the exploration moved into HCI and psychology where judgment is operationalised experimentally.

## Investigation 4 - Locate judgment-oriented constructs in adjacent fields

**Prompt**

> Using the OpenAIRE Graph, investigate whether “algorithmic judgment”, “epistemic judgment”, “AI output evaluation”, “trust calibration”, “automation bias”, “decision calibration”, and “judgment under uncertainty” appear as established concepts in AI literacy, AI education, or human-AI interaction research. Distinguish: (a) exact terminology, (b) conceptually equivalent but differently named constructs, and (c) merely adjacent concepts. Identify representative publications, recurring authors, citation relationships, and research clusters. Pay particular attention to studies in which humans must decide whether to accept, reject, revise, or qualify an AI-generated output. Then test whether these judgment-oriented studies connect bibliographically or conceptually to mathematical, statistical, probabilistic, data, or model-based reasoning. Search explicitly for counter-evidence showing that a mature reasoning-and-judgment strand already exists within AI literacy. Report approximate record counts, the OpenAIRE tools used, filters/query logic, and any metadata inconsistencies or retrieval limitations encountered.

**Decision after output:** "Algorithmic judgment" was not an established construct, while trust calibration, appropriate reliance, automation bias and algorithm aversion were established in adjacent research. The final step therefore attempted to falsify the emerging fragmentation interpretation.

## Investigation 5 - Final falsification test

**Prompt**

> Using the OpenAIRE Graph only, perform a final falsification test of the emerging finding that three research traditions remain weakly connected: (1) AI literacy and competency frameworks - especially Long & Magerko, Ng et al., Chiu and related work; (2) human-AI judgment and reliance research - including trust calibration, appropriate reliance, automation bias, algorithm aversion, adherence and override; (3) mathematical, statistical, probabilistic and model-based reasoning about uncertainty. Test whether there are meaningful citation, co-citation, author, project, venue, or conceptual links connecting these three traditions. Specifically search for publications that combine: AI literacy with appropriate reliance or trust calibration; AI literacy with automation bias or algorithm aversion; statistical/probabilistic reasoning with trust calibration or AI reliance; model-based reasoning with AI output evaluation; mathematical/data literacy with accept/reject/override decisions about AI outputs. For each possible bridge, distinguish genuine integration from incidental keyword co-occurrence. Actively search for counter-evidence that would falsify the claim of disciplinary fragmentation. If a mature bridge exists, identify it. If it does not, report the strongest partial bridges and explain exactly what remains disconnected. Report the OpenAIRE tools used, approximate record counts, citation or relationship evidence, query limitations, and any indexing or metadata problems encountered.

**Stopping rule:** Stop when new searches no longer change the structural interpretation and the main claim has survived explicit counter-searches. Investigation 5 met this stopping rule.
