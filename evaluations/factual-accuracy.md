# Factual Accuracy Evaluation

## Goal

Evaluate whether an AI response contains factual errors, unsupported claims, or misleading certainty.

## Example task

**User prompt**

> What is the capital of Australia, and is it the country's largest city?

**Candidate response**

> Sydney is the capital of Australia and also its largest city.

## Evaluation

**Verdict:** Incorrect.

### Issues identified

- The response incorrectly states that **Sydney is the capital of Australia**.
- Australia's capital is **Canberra**.
- Sydney is commonly identified as Australia's largest city by population, but that does not make it the capital.
- Because the first claim is wrong, the response should not be rated as fully correct even though part of it may be true.

## Improved response

> Canberra is the capital of Australia. Sydney is the country's largest city by population, but it is not the capital.

## Why this matters

A fluent answer can still be unreliable. Factual evaluation requires checking each meaningful claim separately instead of judging the response by confidence or writing quality.
