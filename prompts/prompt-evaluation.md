# Prompt Evaluation and Improvement

## Goal

Identify ambiguity in a prompt and improve it without changing the user's underlying intent.

## Original prompt

> Tell me about the best marketing strategy.

## Problems

The prompt is underspecified because it does not define:

- the business or industry;
- the target customer;
- the objective;
- the budget;
- the market or location;
- the time horizon;
- what "best" means.

A model answering immediately may make assumptions that the user did not provide.

## Improved prompt

> Propose three low-budget digital marketing strategies for a small local coffee shop in Mexico that wants to increase weekday visits from customers aged 18–30 during the next three months. For each strategy, explain the objective, implementation steps, estimated effort, and one metric to track.

## Why the improved prompt is stronger

It preserves the original marketing intent but adds enough context to produce a more relevant and measurable answer. It also defines the requested output structure instead of relying on the model to guess what level of detail the user wants.

## Evaluation principle

A strong prompt should provide enough context and constraints to reduce avoidable ambiguity while leaving room for the model to solve the task.
