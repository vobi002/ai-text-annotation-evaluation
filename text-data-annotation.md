# Text Data Annotation Project

## Project Overview

This project demonstrates practical text data annotation skills through the classification of customer-support messages.

Each text sample is assigned a predefined intent label based on the primary purpose of the message.

The project focuses on accurate classification, consistent labeling, and appropriate handling of ambiguous messages.

## Annotation Objective

The objective is to identify the main intent expressed in each customer message and assign the most appropriate category.

## Annotation Labels

| Label | Definition |
|---|---|
| Order Tracking | The customer wants to know the status or location of an order. |
| Refund Request | The customer wants money returned for a purchase or transaction. |
| Payment Issue | The customer reports a failed, declined, or problematic payment. |
| Account Update | The customer wants to change or update account information. |
| Technical Support | The customer reports a technical problem or needs help using a service or feature. |
| Lost or Stolen Item | The customer reports an item as lost or stolen. |

## Annotated Dataset

| ID | Customer Message | Intent Label | Annotation Rationale |
|---|---|---|---|
| 1 | Where is my package? It was supposed to arrive yesterday. | Order Tracking | The customer is asking about the location or status of an order. |
| 2 | I want my money back for the shoes I returned. | Refund Request | The customer explicitly requests a refund. |
| 3 | My card keeps getting declined when I try to pay. | Payment Issue | The message describes a failed payment. |
| 4 | I need to change the phone number on my account. | Account Update | The customer wants to update account information. |
| 5 | The app keeps crashing whenever I try to open it. | Technical Support | The customer reports a technical problem with the application. |
| 6 | Someone stole my phone and I cannot access my account. | Lost or Stolen Item | The primary issue involves a stolen device. |
| 7 | Can you tell me when my delivery will arrive? | Order Tracking | The customer is requesting delivery information. |
| 8 | I was charged twice for the same order. | Payment Issue | The message describes a problem involving a payment charge. |
| 9 | Please update the email address linked to my account. | Account Update | The customer wants to change account information. |
| 10 | I returned the product last week. When will I receive my refund? | Refund Request | The customer is asking about a refund after returning a product. |

## Ambiguous Case

### Example

> I can't use my card to pay for anything.

**Assigned Label:** Payment Issue

**Reasoning:** The message does not specify the exact cause of the problem, but the primary issue is an inability to complete payments. The available information supports a Payment Issue label.

The annotation does not assume a specific technical cause such as a damaged card, insufficient funds, or a blocked account.

## Annotation Principles

- Assign the label that best represents the primary intent of the message.
- Use only information supported by the text.
- Do not infer details that are not provided.
- When a message contains multiple issues, identify the primary issue based on the available context.
- Apply the same definitions consistently across all examples.
- Consider the meaning and context of the entire message rather than relying on individual keywords.
- When ambiguity exists, choose the best-supported label and document the reasoning.

## Quality Control

Annotations were reviewed against the label definitions to check for:

- Correct intent classification
- Consistent application of labels
- Unsupported assumptions
- Ambiguous language
- Appropriate use of context
- Clear annotation rationales

## Key Skill Demonstrated

This project demonstrates the ability to transform unstructured customer-support text into structured, consistently labeled data while documenting the reasoning behind annotation decisions.
