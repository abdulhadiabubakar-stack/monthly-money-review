---
name: monthly-money-review
description: Reviews a person's monthly bank statement, balance sheet, or transaction list, summarizes where money came from and went, and offers practical optional ways to manage spending. Use it when someone says “Review my bank statement,” “Where did my money go this month,” or “Help me understand and manage my monthly spending.” It is not for making transactions, changing accounts, professional financial, investment, tax, or legal advice, or guessing unclear transaction meanings.
license: MIT
---

# Monthly Money Review

## When to use

Use this skill when someone wants a clear, non-judgmental summary of a monthly statement, account balance sheet, or transaction list and a few practical budgeting ideas. It can also help with a shorter or longer period if the user asks, but label the period accurately.

## Gather first

- Ask the user to provide or paste the relevant statement or transaction data if it is not already available. Accept text, tables, or supported files.
- Ask which account(s), currency, and period to include if the data does not make these clear. Do not assume a currency or that multiple accounts belong to the same person.
- Ask whether the data is complete, whether it includes pending transactions, and whether opening and closing balances are available when those details affect the review.
- Invite the user to redact names, addresses, account identifiers, and other personal details before sharing. Never request passwords, PINs, security codes, or full account numbers.
- Ask a focused follow-up when an ambiguity materially affects totals or classification. Otherwise, proceed and label the uncertainty.

## Process

1. **Check coverage.** Identify the date range, account(s), currency, and records provided. Note missing dates, pages, entries, or other signs the data may be incomplete. Do not imply a full-month review if only part of the month is supplied.
2. **Read the figures carefully.** Extract dates, descriptions, and amounts as given. Distinguish credits from debits using the source's signs or labels. Do not fill missing values, silently correct apparent errors, or assume how a transaction was funded.
3. **Calculate supported totals.** Sum money in and money out from the supplied records, keeping currencies separate. State the included period and any exclusions. If the source has balances, report opening and closing balances as shown. Check whether opening balance plus inflows minus outflows agrees with closing balance when the data supports that check; report any difference rather than forcing a reconciliation.
4. **Separate transfers where possible.** Treat an item as a transfer only when its description or user confirmation supports that classification. Report identified transfers separately from income and spending where possible, and explain whether totals are gross or exclude identified transfers. Do not assume an ambiguous payment is an internal transfer.
5. **Categorize spending cautiously.** Use clear transaction descriptions and the user's context. Summarize totals by useful categories, and group unclear items under “Unclear / unclassified” rather than inventing a merchant, purpose, or category. Label inferred categories as estimates and surface uncertain entries.
6. **Look for useful patterns.** Point out notable recurring or unusually large items, fees, and changes visible in the supplied data. Do not call something unusual without a comparison or context that supports it. Avoid inferring the user's income stability, debts, household situation, or financial priorities.
7. **Offer practical options.** Give a few specific, low-pressure ideas grounded in the reviewed data, such as checking a recurring charge or setting a spending limit for a category. Frame them as optional possibilities, not instructions or professional advice.
8. **Protect privacy and agency.** Analyze only; do not initiate payments, make transactions, contact providers, or change accounts or settings. Do not shame, pressure, or make decisions for the user.

## Output format

Keep the report concise and use the following sections. Omit a figure that the data cannot support, and explain why rather than estimating it.

### Monthly money review
- **Period and data reviewed:** dates, account(s) as identified, currency, records included, and any coverage limitations.
- **Money in and out:** total inflows and outflows, with the basis of calculation; state whether identified transfers are included or excluded.
- **Balances:** opening and closing balances if shown in the source; include any reconciliation difference if checked.
- **Transfers:** identified incoming and outgoing transfers, separated from income and spending where possible; state uncertainty.
- **Spending by category:** category totals, plus an unclear / unclassified total when applicable. Mark estimates and uncertain classifications.
- **Notable items:** supported patterns, recurring items, fees, and relevant large transactions.
- **Optional ideas:** a few practical money-management options tied to the observations.

Use the source's currency notation consistently. Never combine unlike currencies into one total without a user-provided conversion basis. Make clear when totals are based only on posted items or otherwise exclude transactions.

## Do not

- Make transactions, change account settings, or claim to have done so.
- Ask for or repeat passwords, PINs, security codes, or full account numbers.
- Invent transaction meanings, missing amounts, dates, balances, or financial circumstances. Do not present a guess as fact.
- Hide incomplete data, uncertain classifications, arithmetic discrepancies, or assumptions that affect the result.
- Shame the user or describe spending in moralizing terms.
- Present suggestions as professional financial, investment, tax, or legal advice, or guarantee an outcome.
- Apply local financial, tax, or legal rules unless the user asks for that context and the relevant jurisdiction and reliable information are available; clearly state limitations.
