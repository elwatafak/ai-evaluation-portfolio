# AI Response Comparison

## Goal

Compare two plausible AI-generated answers and select the stronger one using explicit criteria.

## Example task

**User prompt**

> I have 30 minutes to study before an exam. Give me a simple plan with three steps.

### Response A

> First, spend 10 minutes reviewing the topics most likely to appear on the exam. Then spend 15 minutes answering practice questions without notes. Use the final 5 minutes to review mistakes and memorize the most important corrections.

### Response B

> Studying effectively requires understanding your learning style, sleep schedule, course structure, previous grades, and long-term academic goals. You should create a comprehensive study calendar, organize all of your notes, identify the best learning resources, and begin with the chapters you find most difficult.

## Evaluation

**Preferred response:** Response A.

### Reasoning

| Criterion | Response A | Response B |
| --- | --- | --- |
| Follows the three-step request | Yes | No |
| Fits the 30-minute constraint | Yes | No clear timing |
| Relevance | High | Low to medium |
| Actionability | High | Medium |
| Unnecessary information | Minimal | Significant |

Response B contains generally reasonable study advice, but it does not satisfy the immediate constraints of the prompt. Response A is stronger because it follows the requested structure and converts the full 30 minutes into concrete actions.

## Key lesson

The "best" response is not necessarily the longest or most detailed one. It is the response that most accurately satisfies the user's request while remaining correct, clear, and useful.
