🧾 Receipts

Instant, secure, wallet-native receipts for modern commerce.

Receipts replaces paper receipts with tamper‑proof, branded receipts delivered automatically to Apple Wallet and Google Pay the moment a contactless payment succeeds.

Built to save merchants time, money, and labour, while giving customers a zero‑friction post‑purchase experience.

⸻

🚀 Core Idea

Payment → Receipt. No extra steps.

As soon as a tap‑to‑pay transaction is approved:
	•	A receipt is generated server‑side
	•	Digitally signed and verified
	•	Instantly pushed to the customer’s wallet

No QR scans. No SMS links. No email chasing.

⸻

🧠 Why Receipts Exists (Merchant View)

Paper receipts:
	•	Get lost
	•	Cost money (printers, rolls, ink)
	•	Slow down checkout
	•	Create customer service overhead

Receipts removes this entirely.

Merchant Benefits
	•	Lower costs — no printers, paper, ink, or maintenance
	•	Faster checkout — no printing or hand‑offs
	•	Reduced labour — fewer “lost receipt” disputes
	•	Fraud reduction — receipts cannot be edited or faked
	•	Sustainability — paperless by default

Pitch line:
“Every receipt, secured and delivered instantly to your customer’s phone — no paper, no hassle, no fraud.”

⸻

✨ Features
	•	Instant wallet receipts
Generated automatically after contactless payment
	•	Apple Wallet & Google Pay native
No app install required for customers
	•	Tamper‑proof by design
Cryptographically signed receipts with server verification
	•	Branded receipts
Merchant logo included (uploaded or auto‑fetched from the web)
	•	Returns‑ready
Staff scan the wallet receipt to instantly verify authenticity
	•	Configurable retention
Default 6‑year merchant retention, adjustable per region

⸻

🔐 Trust & Security

Receipts are designed as records of truth.
	•	Digital signatures per receipt
	•	Unique receipt serials tied to merchant + transaction
	•	Server‑side verification (screenshots are not valid)
	•	Encrypted in transit and at rest
	•	No PAN storage (only token references / last‑4)

This ensures receipts cannot be altered, duplicated, or forged.

⸻

🗂️ Retention Model
	•	Merchants (default): 6 years
	•	Configurable: 3 / 6 / 7 / 10 years by region
	•	After expiry: PII anonymised, aggregates retained
	•	Consumers: Can delete receipts anytime or enable auto‑purge

Legal holds override deletion where required.

⸻

🔌 API Overview (Conceptual)

POST /v1/receipts
→ Creates receipt + returns Apple/Google Wallet pass URLs

GET /v1/receipts/{id}
→ Fetch receipt details

POST /v1/receipts/{id}/refunds
→ Issue refund + update wallet pass

	•	OAuth2 / client credentials
	•	HMAC‑signed payloads
	•	Idempotent receipt creation

⸻

⚙️ High‑Level Architecture
	•	POS / Payment Provider → Receipts API
	•	Receipt Service → generates signed wallet passes
	•	Wallet Issuers → Apple Wallet / Google Wallet
	•	Merchant Dashboard → branding, analytics, retention

Wallet updates are pushed for refunds, notes, or status changes.

⸻

🛣️ Roadmap
	•	POS & payment processor integrations
	•	Refund & return workflows
	•	Expense‑tool exports (Xero, Expensify, etc.)
	•	Multi‑region data residency
	•	Enterprise SSO & audit exports

⸻

🤝 Contributing

Pull requests are welcome.

For major changes, please open an issue first to discuss what you’d like to change.

⸻

📜 License

See LICENSE.

© 2025 Aderemi Onalaja. All rights reserved.
