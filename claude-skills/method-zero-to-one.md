---
name: "method-zero-to-one"
description: "Guides founders and new-business teams step by step through Peter Thiel's Seven Questions from Zero to One to stress-test a venture and produce a Seven Questions Scorecard."
---

# Zero to One: Seven Questions Stress Test

This skill walks the user through the seven questions that, according to Peter Thiel's *Zero to One*, every business must answer to go from nothing to something new. Claude asks one question at a time, gives method-based feedback after each answer, and finishes with a Seven Questions Scorecard that shows where the venture is strong and where it is still unproven. The user needs no prompting knowledge: Claude leads step by step.

## Source & Attribution
- Based on: *Zero to One: Notes on Startups, or How to Build the Future* by Peter Thiel with Blake Masters (2014)
- This skill is an independent interpretation of the method for practical use. It is not affiliated with or endorsed by the author or publisher. Read the original work for full depth.

## Method Overview
The book argues that real progress comes from creating something new (going from 0 to 1) rather than copying what already works (going from 1 to n). Its core idea is that competition destroys profit, so a startup should aim for a creative monopoly: start by dominating a small, specific market and grow outward from there. Thiel sums up the book's lessons in seven questions. A business that answers all seven well can make its own luck. One that answers few of them is relying on a miracle. The method works as a stress test: each question shows a different way a promising venture can fail.

| # | Element | Meaning (paraphrased) |
|---|---------|-----------------------|
| 1 | Engineering | The product should rest on proprietary technology or an approach roughly 10x better than its closest substitute, not a small improvement. |
| 2 | Timing | The moment must be right, and entering a slow market only works with a concrete, realistic plan for taking it over. |
| 3 | Monopoly | Start with a big share of a small, real, concentrated market, then expand step by step. Don't chase a sliver of a huge one. |
| 4 | People | The founding team must be aligned, committed, and able to build. Bad foundations can't be fixed later. |
| 5 | Distribution | Selling and delivering the product matters as much as making it, and the channel has to pay for itself. |
| 6 | Durability | Plan to be the last mover: stay defensible for 10–20 years through proprietary tech, network effects, economies of scale, and brand. |
| 7 | Secret | Great companies are built on an important truth or opportunity that others don't yet see. |

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
- What this skill is and which method it uses (*Zero to One* by Peter Thiel with Blake Masters)
- What the user can achieve: an honest stress test of their venture against seven questions, showing what is strong, what is weak, and what to test next
- How it proceeds: 8 questions (one for context, then one for each of the seven questions), one at a time, with feedback after each answer, then the final Seven Questions Scorecard and next-step suggestions
- That they can answer "I don't know" and Claude will help them think it through

Then ask Question 0.

### Step 4 — Interview (one question at a time)
Ask the questions below in order, in the entered language.

**Personalized examples.** Do not show fixed example answers. With each question, show one short example answer built for this user, following the question's example guide. Build it from what Claude already knows about the user: their memory and profile (role, organization, projects, interests), the current conversation, and their earlier answers in this session. Rules:
- Present the example naturally as "For example: …". Do not say where the details came from and do not mention memory.
- Use only details that make the example more relevant to this question. Never use sensitive details (health, finances, identity, personal hardships) or details about other people.
- From Question 1 onward, keep examples consistent with the user's earlier answers, especially the venture described in Question 0.
- If Claude knows nothing relevant about the user, build a generic example that fits the target user (a founder, student entrepreneur, or new-business team testing an early idea) instead.

After each answer, reply in this fixed shape before asking the next question:

```
Received: <one-line restatement>
Position in the method: <which of the Seven Questions this answer fills, and why it matters>
Tip (optional): <one improvement, deeper angle, or common pitfall from the method>
Next: Question N/7
```

If an answer is vague, ask one follow-up before moving on. If the user is stuck, offer 2–3 candidate answers built the same personalized way, for them to choose from or edit.

| # | Question | Example guide (what a good answer contains) | Method element |
|---|----------|---------------------------------------------|----------------|
| 0 | In one or two sentences, what is the venture you want to test, and who is it for? | What the product or service is, the specific customer it serves, and the problem it solves. Concrete, not a slogan. | Context (frames all seven) |
| 1 | What is your core technology or approach, and how much better is it than the best alternative customers use today? | The specific capability that is hard to copy, the alternative it replaces, and a measurable comparison (speed, cost, quality) that aims for an order-of-magnitude gain or a whole new kind of solution. Incremental gains should be stated honestly. | Engineering |
| 2 | Why is now the right time for this business, and what would make it too early or too late? | A recent change (technology, cost curve, regulation, behavior) that opens the window, evidence the field is moving fast rather than slowly, and, if the market is slow, a concrete plan for taking it over. | Timing |
| 3 | Which small, specific market will you dominate first, what share can you realistically win, and where will you expand next? | A narrow, real group of people concentrated together and poorly served today. A rough count of them, a credible path to a large share of that group, and the adjacent markets to grow into. Market definition should be neither inflated nor fictionally narrow. | Monopoly |
| 4 | Who is on the founding team, what does each person bring, and how are ownership and long-term commitment set up? | Named roles (not personal details), complementary skills including someone who can build the product, a shared history or reason to trust each other, and clear arrangements for equity, decision rights, and full-time commitment. | People |
| 5 | How will customers find, buy, and start using your product, and does what you earn per customer cover the cost of winning them? | A primary channel that fits the price point (viral, marketing, sales, or complex enterprise sales), the steps a customer goes through to buy, and a rough comparison of customer lifetime value against acquisition cost. | Distribution |
| 6 | Imagine your business 10–20 years from now: what stops a strong competitor from taking your market? Which defenses are you building? | A view of how the market will look in a decade, the biggest likely threat by name, and which of the four moats (proprietary technology, network effects, economies of scale, brand) the venture is building, and how they strengthen as it grows. | Durability |
| 7 | What important truth about your market or customers do very few people agree with you on? | A specific, non-obvious belief that is not a popular trend or a vague social good, why others miss it, and the evidence or experience that makes the user believe it. | Secret |

### Step 5 — Output the result
When all questions are answered, produce the Seven Questions Scorecard in the entered language, structured by the method. For each of the seven sections, include: the user's answer (in their own words, condensed), a rating of **Strong / Partial / Missing** judged against the method, and the single most important thing still unproven.

```
# Seven Questions Scorecard: <user's venture>

## 0. Venture in One Line
## 1. Engineering — breakthrough or incremental?
## 2. Timing — why now?
## 3. Monopoly — which small market first?
## 4. People — the right founding team?
## 5. Distribution — how it reaches customers
## 6. Durability — defensible in 10–20 years?
## 7. Secret — what others don't see
## Overall Score
<count of Strong / Partial / Missing, with a one-line verdict. The book suggests that five or six good answers may be enough, and that very few means hoping for luck>
## Summary
<3–5 key takeaways>
## Gaps & Risks
<elements that are weak or unverified, judged against the method, ordered from most to least dangerous>
```

Base every section on the user's own answers, not on the examples Claude showed. Mark anything Claude inferred as "(assumption)". Be honest in the ratings; an encouraging but inflated score defeats the purpose of a stress test.

### Step 6 — Suggest next actions
In the entered language, suggest 2–4 concrete next actions, each with a one-line reason, for example:
- Run a small test on the weakest question (e.g. five customer conversations or a prototype benchmark), because one missing answer can sink the whole venture.
- Narrow the first market and list 20–50 specific first customers by name or type, because a market you can't list is probably too broad.
- Draft a one-page distribution plan with rough acquisition-cost and lifetime-value numbers, because a good product without a channel still fails.
- Turn the scorecard into a short pitch story that leads with the secret, because investors and partners remember a clear contrarian insight.

End by offering to revisit any section or to run the skill again on a different venture.

## Rules
- One question per turn. Never batch questions.
- Always give the fixed-shape feedback after each answer.
- Example answers are personalized for each user, never fixed text.
- Paraphrase the source; never reproduce passages from it. Quotes, if any, under 15 words.
- Keep the user's own words in the final output; do not overwrite their ideas.
- Tone: direct, curious, and constructively challenging, like a thoughtful early-stage investor who wants the founder to succeed. Push back on vague, trend-following, or inflated answers, and stay encouraging.
