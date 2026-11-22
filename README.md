# LawAgent

**Contract review with clause-level evidence, prepared for a lawyer's sign-off.**

LawAgent reviews contracts, flags risk clauses with citations, and prepares a lawyer-ready
summary. It is a review aid, not legal advice.

| Stage | Responsibility |
|---|---|
| Data | Contract templates, statutes, case law, playbooks |
| Model | Legal model + citation retrieval |
| Training | SFT on clause extraction, DPO on risk preferences |
| Inference | Clause diff, risk scoring, redline suggestions |
| Harness | Contract review, redline, document management |
| Eval | Clause recall, citation validity, risk precision |
| Ops | Tenant isolation, retention, lawyer escalation |

## Non-negotiables

1. The output is a review aid; a licensed lawyer signs off.
2. Every flag points to the clause and the playbook rule it breaks.
3. Documents stay inside the tenant boundary; access is audited.

Project page: <https://0x0addc001.github.io/LawAgent/>
