# Instruction-Following Evaluation

## Goal

Check whether an AI response follows every explicit constraint in the user's request.

## Example task

**User prompt**

> Explain what an API is in exactly three sentences. Do not use technical jargon.

**Candidate response**

> An API lets two programs communicate with each other. It acts like a messenger that takes a request from one program and brings back a response. Developers often use REST endpoints and HTTP methods to implement APIs. This makes different software services easier to connect.

## Evaluation

**Verdict:** Does not fully follow instructions.

### Issues identified

1. The user requested **exactly three sentences**, but the response contains four.
2. The user requested **no technical jargon**, but the response introduces "REST endpoints" and "HTTP methods."
3. The first two sentences are clear and appropriate for the requested audience.

## Improved response

> An API is a way for two programs to communicate with each other. It works like a messenger that carries a request from one program and brings the answer back. This allows different apps and services to work together.

## Key lesson

A response can be generally correct and still fail the task if it ignores explicit formatting, length, tone, or audience constraints.
