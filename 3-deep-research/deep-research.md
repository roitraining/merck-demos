# Deep Research

## Time Required
30 minutes

## Overview
In this lab, you will use Gemini Enterprise Deep Research to analyze the current Alzheimer's drug market for a Merck strategy use case.

You will start broad, then narrow to competitor therapies, evidence strength, and market dynamics. Finally, you will turn the findings into a concise strategy brief.

### You learn how to:
- Frame a strong Deep Research request.
- Ask follow-up questions that improve source quality and answer depth.
- Compare competitors in a structured, evidence-based format.

## Scenario

<p align="left">
  <img src="images/merck-logo.png" width="70%" alt="Merck logo" />
</p>

Merck's Market Intelligence team needs a current view of the Alzheimer's treatment landscape. Leadership wants to understand the major approved and late-stage competitor therapies, where evidence is strongest, and where unmet need still exists.

Your job is to use Gemini Enterprise Deep Research to build a source-backed landscape review and convert it into a short strategic recommendation.


## Lab Instructions

### Task 1: Start with a Broad Research Brief

Begin broad so Deep Research can map the therapeutic and market landscape.

1. Open Gemini Enterprise and start a new chat.

2. From the **Tools** list, select **Deep Research**.

   <p align="left">
     <img src="images/deep-research.png" width="75%" alt="Deep Research" />
     <br>
     <em>Deep Research</em>
   </p>

3. Paste the following prompt:

```text
You are supporting Merck's Market Intelligence team.

Research the current global market for Alzheimer's disease drugs.

Return:
1. Major treatment categories and mechanisms in use today
2. Key approved therapies and their developers
3. Notable late-stage pipeline therapies (Phase 3 or registration stage)
4. Top 3 market trends in the next 2-3 years
5. Top 3 unmet needs in patients or care delivery
6. A one-sentence summary of where the market is heading

Use reliable sources and cite where each claim comes from.
```

4. Wait for Deep Research to generate a research plan. Review the plan. A good plan should cover approvals, pipeline, efficacy/safety themes, market access, and unmet need. If the plan is too narrow or too broad, ask Deep Research to adjust it before proceeding.

5. Scroll to the bottom of the plan and click **Start research**.

### Task 2: Compare Competitors

Now narrow the research to direct competitor comparison.

1. Ask this follow-up prompt:

```text
Now compare the leading Alzheimer's drug competitors relevant to Merck.

Build a comparison table with one row per therapy and these columns:
- Drug name
- Company
- Mechanism of action
- Regulatory status (approved, submitted, Phase 3, etc.)
- Patient population / stage focus
- Key efficacy signal (high-level only)
- Notable safety or monitoring considerations
- Source links

Return:
1. The table
2. A short summary: where competitors appear strongest
3. A short summary: where gaps remain

Use only evidence from reliable sources. If something cannot be verified, label it Unverified.
```

2. If the response is too generic, ask this follow-up:

```text
For each therapy, add specific dates and source-backed status updates. Replace broad claims with concrete source-backed statements, or label them Unverified.
```

### Bonus Task 3: Apply Deep Research to Your Own Work

Choose a research question that is relevant to your organization — something you would normally spend hours investigating manually. Use Deep Research to do the first pass.

Here are some ideas to get you started:

| Scenario | Example question |
|----------|-----------------|
| **Therapy area scan** | What are the most important pipeline and approval shifts in [therapy area] over the next 2-3 years? |
| **Competitor analysis** | Which competitors are strongest in [therapy area], and where are their evidence or access gaps? |
| **Access and reimbursement** | What payer and health system barriers most affect uptake in [market/region]? |
| **Regulatory landscape** | What pending regulatory events in [therapy area] could change market dynamics? |
| **Partnership scouting** | Which biotech or platform partners appear most strategic based on current evidence and trajectory? |

1. Open a new Gemini Enterprise chat and select **Deep Research**.

2. Write a prompt that gives Deep Research your role, your organization's context, and the specific question you want answered. Ask it to return findings with citations.

3. When the research plan appears, check that it covers the right scope — not too broad, not too narrow. Adjust it if needed before clicking **Start research**.

4. Review the output. Ask at least one follow-up prompt to push for more specific evidence or to clarify a claim that looks too general.

## Congratulations

In this lab, you have:
- Used Gemini Enterprise Deep Research to map the Alzheimer's drug market and key competitors.
- Refined research output by forcing source quality, specificity, and verification.
