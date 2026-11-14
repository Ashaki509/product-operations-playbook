# Product Operations Prompt Library

Ready-to-use prompts for common Product Operations work. Replace the text in [brackets] with your own details before running them.

**Before you use these:** follow your organization's policy on what data can be shared with AI tools. Remove customer names, confidential financials, and personal information unless your tool is approved for them. Treat every output as a first draft and check the facts before sharing it.

---

## Planning

### 1. Turn raw intake into themes

```
Below is a list of [number] product requests from [sources, e.g. Sales, Support, customers].
Group them into 5 to 8 themes. For each theme, give: a short name, a one-sentence
description of the underlying need, the number of requests in it, and two representative
examples. List separately any requests that fit no theme.

[paste requests]
```

### 2. Pressure-test a draft roadmap

```
Act as a skeptical executive reviewing this quarterly roadmap. Our top objectives are
[objectives]. Our capacity is [teams and size]. Identify: items that do not clearly support
an objective, likely dependency conflicts, signs the plan is over capacity, and the three
questions you would ask before approving it.

[paste roadmap]
```

### 3. Improve a set of OKRs

```
Review these draft OKRs. For each Key Result, say whether it measures an outcome or a task,
whether it has a baseline and a target, and whether it can be tracked without a meeting.
Rewrite any weak Key Result in the form "[verb] [metric] from [baseline] to [target] by
[date]". Use placeholders where a number is unknown. Do not invent numbers.

[paste OKRs]
```

---

## Communication

### 4. Write an executive update

```
Write an executive update from the notes below. Lead with the decision or action needed
and the date it is needed by. Follow with status in one sentence, then the two or three
facts that support it. Keep it under 150 words. Use plain language and no jargon.

Audience: [role]
Notes: [paste notes]
```

### 5. Prepare a product review pre-read

```
Turn these notes into a one-page pre-read with these sections: decision needed, context,
options considered (with benefit, cost, and risk for each), recommendation, impact on the
roadmap, and open questions. Flag any section where the notes do not give enough
information, and do not fill the gap with assumptions.

[paste notes]
```

### 6. Explain a "not now" decision

```
Write a short message to [requester role] explaining that their request, [request], was
not prioritized this quarter. Include what was prioritized and why, what would change the
decision, and when it will be reviewed again. The tone should be direct and respectful.
```

---

## Analysis

### 7. Summarize customer feedback

```
Summarize the customer feedback below for a product team. Give the top five themes ranked
by frequency, a representative paraphrase for each, the customer segment it came from if
stated, and whether it describes a missing capability, a usability problem, or a
reliability problem. Note anything that appears only once but looks severe.

[paste feedback]
```

### 8. Find risks in a launch plan

```
Review this launch plan and list the risks across engineering, go-to-market, support, and
legal. For each risk, give the likelihood (low, medium, high), the impact, an early warning
sign, and a mitigation. Then list anything a launch plan normally includes that is missing
here.

[paste plan]
```

### 9. Draft a post-launch review

```
Using the data and notes below, draft a post-launch review with these sections: what we
planned, what happened, results against targets, what worked, what did not, and three
specific changes for the next launch. Keep observations factual and avoid assigning blame
to individuals or teams.

[paste data and notes]
```

---

## Process

### 10. Document a process from a conversation

```
Below is a transcript or set of notes describing how [process] works today. Write it up as
a process document with: purpose, trigger, steps in order with the owner of each, inputs
and outputs, decision points, and known gaps. List any step where the notes are unclear as
a question for the process owner.

[paste notes]
```

### 11. Build a RACI from a description

```
Based on the description below, draft a RACI matrix for [process or program]. Use these
roles: [roles]. Make sure each activity has exactly one Accountable. After the matrix, list
any activity where accountability is ambiguous in the description.

[paste description]
```

### 12. Assess a meeting cadence

```
Here is our list of recurring meetings with purpose, frequency, length, and attendees.
Identify meetings with overlapping purposes, meetings with no stated decision or output,
and attendees who appear in most of them. Suggest which to merge, shorten, or replace with
a written update, and explain the reasoning for each suggestion.

[paste meeting list]
```

---

## Tips for Better Results

- Give the audience and the purpose. "For an executive deciding on funding" produces a different draft from "for the engineering team."
- Ask the tool to flag gaps instead of filling them. This reduces invented details.
- Paste examples of the format you want when you have them.
- Review every number and name in the output against your source.

---

## Related

- [AI Tools for PMs & PgMs](https://github.com/Ashaki509/pmpgaiassistant): interactive assistants and a broader prompt library
