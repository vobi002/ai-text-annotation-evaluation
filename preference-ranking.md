# AI Preference Ranking

## Project Overview

This project demonstrates the evaluation and ranking of two AI-generated responses to the same user prompt.

The goal is to determine which response better satisfies the user's request by comparing accuracy, relevance, instruction following, clarity, helpfulness, and factual consistency.

## Evaluation Task

### User Prompt

> I am a university student in Nigeria with a ₦5,000 budget. Suggest three affordable lunch options and briefly explain why each is suitable.

---

## Response A

> Here are three affordable lunch options:
>
> 1. **Jollof rice and egg** — A common Nigerian meal that can provide carbohydrates and protein while staying within a modest budget.
> 2. **Beans and plantain** — Filling and relatively affordable, with beans providing protein and plantain providing carbohydrates.
> 3. **Noodles and egg** — Quick to prepare and usually inexpensive, making it convenient for a student on a budget.

---

## Response B

> Here are some Nigerian foods you can try:
>
> 1. **Jollof rice and chicken** — Very delicious and popular.
> 2. **Pounded yam and egusi soup** — A traditional Nigerian meal.
> 3. **Fried rice and fish** — A tasty and nutritious option.
>
> These meals are great choices for lunch and can be enjoyed by students.

---

## Preference Decision

**Preferred Response: Response A**

Response A is preferred because it more directly addresses the user's budget and student context. It provides three specific lunch options and briefly explains why each option is suitable.

Response B provides three Nigerian meals, but it does not demonstrate that the options are affordable or suitable for a ₦5,000 budget. Some of the suggested meals may also be less likely to fit the stated budget depending on location and portion size.

---

## Evaluation Comparison

| Criterion | Response A | Response B |
|---|---:|---:|
| Accuracy | 5/5 | 4/5 |
| Relevance | 5/5 | 3/5 |
| Instruction Following | 5/5 | 3/5 |
| Clarity | 5/5 | 5/5 |
| Helpfulness | 5/5 | 3/5 |
| Factual Consistency | 5/5 | 4/5 |

---

## Ranking

**1st — Response A**

**2nd — Response B**

---

## Evaluator Rationale

Response A better satisfies the user's requirements because it considers the student's limited budget, provides exactly three options, and briefly explains why each meal is suitable.

Response B follows the requested number of options but does not adequately address the ₦5,000 budget. It also provides limited explanations for why the meals would be suitable for the user.

The ranking is therefore based on how well each response satisfies the complete user request rather than on personal preference.

---

## Key Evaluation Insight

A response does not need to be completely incorrect to rank lower.

Response B contains reasonable Nigerian meal suggestions, but it is less effective because it does not sufficiently address the user's specific constraints.

This demonstrates the importance of evaluating AI responses against the **full prompt and its requirements**, rather than judging responses only on whether the information sounds generally correct.

## Conclusion

Response A is the preferred response because it demonstrates stronger instruction following, relevance, and helpfulness while directly addressing the user's stated budget and situation.
