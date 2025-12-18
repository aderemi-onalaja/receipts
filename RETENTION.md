🗂️ Receipts — Data Retention & Lifecycle

This document explains how Receipts manages receipt data over time, balancing legal compliance, merchant needs, and customer control.

Receipts is designed to retain data only as long as necessary, while preserving the integrity of receipts as records of truth.

⸻

Retention principles

Receipts follows four core principles:
	1.	Purpose‑driven retention — data is kept only for defined business or legal reasons
	2.	Configurable by merchants — retention varies by region and obligation
	3.	Consumer control — customers can delete receipts at any time
	4.	Integrity preserved — retention actions never compromise receipt authenticity

⸻

Merchant retention (system of record)

Merchants rely on receipts for:
	•	Accounting and tax records
	•	Returns and refunds
	•	Dispute resolution
	•	Warranty validation

Default policy
	•	6 years rolling retention per receipt
	•	Aligns with common accounting and tax record expectations

Configurable options

Merchants can configure retention per store or region:
	•	3 years
	•	6 years (default)
	•	7 years
	•	10 years

Longer retention is supported where legally required.

⸻

Consumer retention (wallet & vault)

From the customer’s perspective:
	•	Receipts live inside Apple Wallet / Google Pay
	•	Receipts can also appear in a lightweight receipt vault (if enabled)

Customer controls
	•	Delete receipts at any time
	•	Enable optional auto‑purge windows (e.g. 1–6 years)
	•	Export receipts before deletion

Customer deletion does not affect merchant records.

⸻

Anonymisation after expiry

When merchant retention periods expire:
	•	Personally identifiable information (PII) is anonymised
	•	Receipt structure and totals are preserved
	•	Aggregate and statistical data remains available

This allows:
	•	Reporting continuity
	•	Trend analysis
	•	Compliance with data minimisation requirements

Receipt authenticity remains verifiable.

⸻

Legal holds & exceptions

In certain cases, deletion may be paused:
	•	Ongoing disputes
	•	Active chargebacks
	•	Legal or regulatory investigations

When a legal hold is applied:
	•	Data deletion is suspended
	•	Receipt integrity remains unchanged
	•	Normal deletion resumes once the hold is lifted

⸻

Regional compliance support

Receipts supports region‑specific retention needs, including:
	•	VAT / tax record retention
	•	Consumer protection requirements
	•	Data protection regulations

Merchants are guided via:
	•	Clear retention templates
	•	In‑dashboard explanations
	•	Region‑aware defaults

Receipts does not provide legal advice but enables compliant configurations.

⸻

Security during retention

Throughout the retention lifecycle:
	•	Data remains encrypted at rest
	•	Access controls remain enforced
	•	Audit logs remain immutable

Anonymisation never weakens security or verification.

⸻

Summary

Receipts provides:
	•	Sensible defaults
	•	Merchant flexibility
	•	Customer control
	•	Long‑term trust and verifiability

Receipts are retained only as long as needed — and no longer.

⸻

© 2025 Aderemi Onalaja. All rights reserved.
