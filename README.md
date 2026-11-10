# BERT Model Inventory Audit

Tracking repository for the quarterly open-models report's BERT subsection and follow-up audit items.

## Scope

- `google-bert/bert-base-uncased` — canonical BERT model, custody-checked against the Hugging Face Hub (task, library, license).
- Follow-up audit items are tracked as issues in this repository.

## Hub sanity-check results (verified)

| Field | Expected | Hub current | Status |
|---|---|---|---|
| pipeline task | fill-mask | fill-mask | ✅ Confirmed |
| library | transformers | transformers | ✅ Confirmed |
| license | apache-2.0 | apache-2.0 | ✅ Confirmed |
