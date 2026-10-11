# SalesAgentAI – Home Credit LAP Eligibility Voice Agent

## Project Overview
This project is an AI voice agent built using Retell AI for a Home Credit Loan Against Property (LAP) eligibility screening assignment. The agent speaks with existing customers, collects relevant property and financial information, and determines whether the customer meets the initial screening criteria.

## Objectives
- Conduct a natural and professional customer conversation.
- Collect the information needed for initial LAP eligibility screening.
- Identify ineligible cases and explain the reason politely.
- Direct existing property-loan or EMI-reduction requests to the appropriate specialist.
- Refer eligible customers to a senior loan expert for further discussion.

## Technology Used
- Retell AI – voice agent creation, conversation flow, and testing.

## Eligibility Screening
The agent collects these seven details:
1. Property type.
2. Property ownership.
3. Availability of original property documents.
4. Requested loan amount.
5. Occupation and income receipt method.
6. Estimated current property market value.
7. Preferred loan tenure.

## Screening Rules
- Eligible property types: residential, commercial, and industrial.
- Sole and joint ownership are accepted for initial screening.
- Original property documents must be available for verification.
- The maximum requested loan amount for this offer is ₹75 lakh.
- Income must be received through a bank account.
- Loan tenure must be between 3 and 15 years, inclusive.
- The agent does not invent a minimum property value or guarantee loan approval.
- Agricultural property, unavailable original documents, cash-only income, and tenure outside the accepted range result in disqualification from the standard flow.
- Existing loans on the property or requests to reduce an existing EMI are referred to a loan-transfer specialist.

## Conversation Flow
1. Greet the customer and verify their identity.
2. Ask the eligibility questions one at a time.
3. Process customer answers and clarify ambiguous information.
4. Disqualify cases that fail the screening criteria.
5. Summarize the collected information for confirmation.
6. Refer eligible customers to a senior loan expert for further steps and exact interest-rate details.

## Testing
The agent was tested with eligible and ineligible scenarios, including agricultural property, cash-only income, unavailable original documents, invalid tenure, requests above ₹75 lakh, and existing property loans.

## Deliverables
The assignment evidence folder contains the system prompt, call transcript, call recording, and call history export.

## Important Note
This agent performs initial screening only. Final loan approval, verification, and applicable interest rates are determined by the lending team.
