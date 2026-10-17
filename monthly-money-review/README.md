# Monthly Money Review

An Agent Skill for reviewing a monthly bank statement, balance sheet, or transaction list. It helps an AI agent summarize money in and out, report balances when the data supports them, separate identifiable transfers, group spending cautiously, note uncertainty, and suggest a few optional budgeting ideas.

The skill is for understanding supplied financial records. It does not make transactions, change accounts, request credentials, or provide professional financial, investment, tax, or legal advice.

## Folder structure

```text
monthly-money-review/
├── SKILL.md
├── README.md
├── LICENSE
└── sample-statement.txt
```

- `SKILL.md` contains the skill metadata and the instructions an agent follows.
- `README.md` explains the skill and how to install and validate it.
- `LICENSE` contains the MIT license. Replace `Skill Author` with the copyright holder's name before distribution.
- `sample-statement.txt` is fictional example data for trying the skill. One transaction is intentionally unclear so the agent can demonstrate how it handles uncertainty.

## Install

Copy the `monthly-money-review` folder into the skills directory used by your agent or application. Follow that agent's documentation for the exact skills directory and whether it needs a restart or reload to discover new skills.

## Validate

Install the reference validator and validate this skill folder from its parent directory:

```powershell
pip install skills-ref
skills-ref validate .\monthly-money-review
```

The validator checks the skill against the Agent Skills specification. Also review the skill instructions for fit with your agent and intended use.
