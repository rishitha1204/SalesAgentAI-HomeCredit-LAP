# Voice Agent Testing Scenarios

## Project
Home Credit Loan Against Property Eligibility Voice Agent

## Purpose
To test whether the Retell AI voice agent handles eligible customers, ineligible customers, and special requests according to the assignment requirements.

## Tests Performed

| Scenario | Expected behavior | Observed result |
|---|---|---|
| Eligible customer | Collect all seven details, confirm the summary, and refer to a senior loan expert | Passed |
| Agricultural property | Politely disqualify the customer | Passed |
| Cash-only income | Politely disqualify the customer | Passed |
| Original documents unavailable | Politely disqualify the customer | Passed |
| Tenure below 3 years | Reject the requested tenure | Passed |
| Tenure above 15 years | Reject the requested tenure | Passed |
| Existing loan on the property | Refer the customer to a loan-transfer specialist | Passed |
| Request to reduce existing EMI | Refer the customer to a loan-transfer specialist | Passed |
| Loan request above ₹75 lakh | Explain the maximum offer and ask whether the customer wishes to continue at ₹75 lakh | Tested |

## Successful Eligibility Test
The agent collected the property type, ownership, original-document availability, requested amount, occupation and income method, estimated property market value, and preferred tenure. It summarized the information for confirmation and explained that a senior loan expert would discuss the next steps and exact interest rates.

## Limitations
The agent performs initial screening only. Final approval, document verification, and applicable interest rates are determined by the lending team.
