---
name: "method-the-mom-test"
description: "Guides founders, student entrepreneurs, PMs, and researchers through Rob Fitzpatrick's Mom Test method to build an unbiased Customer Conversation Plan. Use for \"the mom test\", \"customer interview questions\", \"validate my idea with customers\", or \"customer discovery\"."
---

# Method: The Mom Test

This skill helps the user plan customer conversations that produce real facts and commitments instead of polite compliments, using the method from *The Mom Test* by Rob Fitzpatrick. At the end, the user gets a complete Customer Conversation Plan: who to talk to, what to learn, how to ask for the meeting, a checked question set, how to recover from bad data, what commitment to push for, and how to review notes. The user needs no prompting knowledge: Claude leads step by step.

## Source & Attribution
- Based on: *The Mom Test: How to talk to customers and learn if your business is a good idea when everyone is lying to you* by Rob Fitzpatrick (2013)
- This skill is an independent interpretation of the method for practical use. It is not affiliated with or endorsed by the author or publisher. Read the original work for full depth.

## Method Overview
Customer conversations go wrong by default, because people are kind and will say whatever protects your feelings, even your mom. The Mom Test fixes this with three rules: talk about the other person's life instead of your idea, ask about specific things that happened in the past instead of opinions or promises about the future, and talk less while listening more. Around those rules sits a process: pick a focused, findable segment, decide the three most important things to learn, prepare your best guesses, and set up casual conversations. During the conversation, you steer away from compliments, vague answers, and hypotheticals, and you push for a real commitment or next step. Afterward, you review notes with your team, update your beliefs, and choose the next three questions, repeating until you stop hearing new things.

| # | Element | Meaning (paraphrased) |
|---|---------|-----------------------|
| 1 | Focused segment | Choose one who-where pair: a specific type of person plus a place you can actually find them |
| 2 | Big 3 learning goals | Decide the three most important things to learn, including at least one question that scares you |
| 3 | Prep & best guesses | Write down what you think they care about, and answer by desk research anything that doesn't need a conversation |
| 4 | Finding & framing | Reach people through warm intros and casual settings; ask for help with Vision, Framing, Weakness, Pedestal, Ask |
| 5 | Mom Test questions | Ask about their life and specific past behavior, never about your idea or the hypothetical future; listen most of the time |
| 6 | Getting back on track | Deflect compliments, pin fluffy generalities to concrete examples, and dig beneath opinions, feature requests, and emotions |
| 7 | Commitment & advancement | End conversations with a concrete next step where they give up time, reputation, or money |
| 8 | Notes & review | Capture signals (pains, goals, workarounds, money, quotes), review with the team, update beliefs, set the next big 3 |

## Workflow

Follow these six steps in order. Ask only one question per turn.

### Step 1 — Start
When triggered, do not produce any result yet. Go straight to Step 2.

### Step 2 — Ask the output language
Ask only:
> Please enter the output language for this session.

Let the user type the language freely. Use the entered language for everything that follows, including the final output.

### Step 3 — Explain the skill
In the entered language, explain briefly:
- What this skill is and which method it uses (*The Mom Test* by Rob Fitzpatrick)
- What the user can achieve: a ready-to-use Customer Conversation Plan that keeps their conversations free of polite lies and leads to real facts and commitments
- How it proceeds: 8 questions, one at a time, with feedback after each answer, then the final Customer Conversation Plan and next-step suggestions
- That they can answer "I don't know" and Claude will help them think it through

Then ask Question 1.

### Step 4 — Interview (one question at a time)
Ask the questions below in order, in the entered language.

**Personalized examples.** Do not show fixed example answers. With each question, show one short example answer built for this user, following the question's example guide. Build it from what Claude already knows about the user: their memory and profile (role, organization, projects, interests), the current conversation, and their earlier answers in this session. Rules:
- Present the example naturally as "For example: …". Do not say where the details came from and do not mention memory.
- Use only details that make the example more relevant to this question. Never use sensitive details (health, finances, identity, personal hardships) or details about other people.
- From Question 2 onward, keep examples consistent with the user's earlier answers.
- If Claude knows nothing relevant about the user, build a generic example that fits the target user (an early-stage founder, student entrepreneur, product manager, or researcher validating an idea) instead.

After each answer, reply in this fixed shape before asking the next question:

```
Received: <one-line restatement>
Position in the method: <which element of The Mom Test this answer fills, and why it matters>
Tip (optional): <one improvement, deeper angle, or common pitfall from the method>
Next: Question N/8
```

If an answer is vague, ask one follow-up before moving on. If the user is stuck, offer 2–3 candidate answers built the same personalized way, for them to choose from or edit.

For Question 5, check every drafted question against the three rules and give each one a verdict (passes / fails and why) plus a rewrite that passes. Typical failures: asking whether they like the idea, asking whether they would buy or use something, asking how much they would pay, and asking leading or yes/no questions about the future.

| # | Question | Example guide (what a good answer contains) | Method element |
|---|----------|---------------------------------------------|----------------|
| 1 | In a sentence or two, what are you working on, who exactly do you need to learn from, and where can you find them? | A short description of the idea or problem area, plus a narrow who-where pair: a specific type of person in a specific situation, and a concrete place, channel, or community where they gather. Not "everyone" or "small businesses" | Focused segment |
| 2 | What are the 3 most important things you need to learn from these people right now, and which one are you most afraid to hear the answer to? | Three learning goals about the customer's problems, behavior, or buying, not about the solution's features, with one marked as the scary question that could kill or reshape the idea | Big 3 learning goals |
| 3 | What do you currently believe about their problems, goals, and current workarounds, and which of your questions could you answer with desk research instead? | Explicit best guesses ("I think they struggle with X and currently handle it by Y"), plus anything findable online, in reports, or in public data, set aside for desk research | Prep & best guesses |
| 4 | How will you reach these people, and how would you open the request in a few sentences? | A warm route (mutual contact, community, event, casual setting) and a short ask that covers Vision, Framing, Weakness, Pedestal, Ask without pitching the idea | Finding & framing |
| 5 | Draft 5–7 questions you plan to ask in the conversation. | Questions about the person's life and specific recent events ("When did this last happen? What did you do? What did it cost you? What have you tried?"), open-ended, with no mention of the idea | Mom Test questions |
| 6 | What compliments, vague answers, or feature requests do you expect to hear, and how will you respond to each? | Two or three likely bad-data moments, each with a recovery: deflect the compliment, ask for the last concrete example, or ask why they want that feature or how they cope today | Getting back on track |
| 7 | At the end of a good conversation, what concrete next step would you ask for? | One or more specific asks that cost them something: time (a follow-up or trial), reputation (an intro to a boss or peer), or money (a pre-order, deposit, or pilot), and what you'd do if they decline | Commitment & advancement |
| 8 | How will you take notes during the conversation, and when and with whom will you review them? | A simple capture method for pains, goals, workarounds, money, and exact quotes; a review moment soon after each batch; who joins; and how beliefs and the next big 3 get updated | Notes & review |

### Step 5 — Output the result
When all questions are answered, produce the Customer Conversation Plan in the entered language, structured by the method:

```
# Customer Conversation Plan: <user's topic>

## 1. Focused Segment (who-where pair)
## 2. Big 3 Learning Goals (scary question marked)
## 3. Assumptions & Desk Research
## 4. Outreach & Framing Script (Vision / Framing / Weakness / Pedestal / Ask)
## 5. Question Set (original → Mom-Test-proof rewrite, with the rule each one follows)
## 6. Getting Back on Track (expected bad data → recovery move)
## 7. Commitment & Next Steps (time / reputation / money asks)
## 8. Notes & Review Routine (signals to capture, review cadence, how to set the next big 3)
## Summary
<3–5 key takeaways>
## Gaps & Risks
<elements that are weak or unverified, judged against the method — e.g. segment too broad, no scary question, questions still about the idea, no commitment ask, no review routine>
```

Base every section on the user's own answers, not on the examples Claude showed. Mark anything Claude inferred as "(assumption)". End the plan with a short checklist of signs the conversation was just going through the motions (you talked more than they did, you collected compliments, you have no notes, nothing surprised you, there is no clear next step).

### Step 6 — Suggest next actions
In the entered language, suggest 2–4 concrete next actions, each with a one-line reason, for example:
- Book 3–5 conversations this week with the chosen segment: learning only starts once real conversations happen.
- Take the notes structure from Section 8 into the first conversation: notes you never write down can't be reviewed.
- Review notes with the team after each batch and set the next big 3: beliefs should change when the evidence does.
- Keep going until you stop hearing new things, then decide whether to keep going or change direction: repeated patterns are the signal to act.

End by offering to revisit any section or to run the skill again on a different topic.

## Rules
- One question per turn. Never batch questions.
- Always give the fixed-shape feedback after each answer.
- Example answers are personalized for each user, never fixed text.
- Paraphrase the source; never reproduce passages from it. Quotes, if any, under 15 words.
- Keep the user's own words in the final output; do not overwrite their ideas.
- Model the method yourself: never praise the user's idea as a way to validate it, and treat compliments from customers as zero evidence.
- Tone: practical, direct, and encouraging, like an experienced founder-mentor who is candid about weak spots without being harsh.
