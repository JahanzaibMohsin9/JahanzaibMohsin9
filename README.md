# Jahanzeb Mohsin

I'm a full-stack developer in Pakistan. I build AI-powered web apps with Next.js and Postgres, offline-first mobile apps with Flutter, and the odd desktop tool in Rust or Electron. I'm looking for a developer role, remote or abroad.

## Things I've built

[**ScopeSignal**](https://github.com/JahanzaibMohsin9/scopesignal) reads an agency's signed proposal, watches the client's Slack channels, and warns the account manager when a request looks like work nobody agreed to. Before choosing defaults I benchmarked two PDF parsers and two OpenAI models. The smaller model matched the larger one's 90% accuracy at about 40% of the cost, so it became the default. The numbers are in [docs/evaluation.md](https://github.com/JahanzaibMohsin9/scopesignal/blob/main/docs/evaluation.md).

[**AI Support Ops Copilot**](https://github.com/JahanzaibMohsin9/ai-support-ops-copilot) answers support tickets from a company's own docs and FAQs, cites the passages it used, and pulls the customer's Stripe details into the ticket. It never sends anything on its own. Every reply is a draft until a person approves it.

[**Ops Automation Hub**](https://github.com/JahanzaibMohsin9/ops-automation-hub) runs two pipelines. New leads are enriched, scored and synced to HubSpot. Uploaded invoices, onboarding forms and agreements go through OCR and structured extraction, then wait in a review queue before anything is exported. The OCR runs in a separate Python service.

[**Dukaan Book**](https://github.com/JahanzaibMohsin9/dukaan-book) is a ledger for small shops that run on cash, EasyPaisa and JazzCash. The typical user has one Android phone and patchy internet, so everything works offline and syncs to Supabase when the connection comes back. Money is stored in whole paisa to avoid rounding errors.

[**LAN Messenger**](https://github.com/JahanzaibMohsin9/lan-messenger) lets computers on the same office network find each other and chat with no internet and no server. It does direct and group messages, file transfer and screen sharing. Messages are encrypted with AES-256 and authenticated with an HMAC.

[**Notes Vault**](https://github.com/JahanzaibMohsin9/notes-vault) is an encrypted Markdown vault for the passwords, API keys and server commands developers tend to leave in plain text files. Each note is encrypted with AES-256-GCM using a key derived from your master password with Argon2id. The key lives only in the Rust side of the app and is wiped when the vault locks.

I've also built [InvoCenter](https://github.com/JahanzaibMohsin9/invocenter) (invoicing for desktop, web and mobile), [ShiftMate Pay](https://github.com/JahanzaibMohsin9/shiftmate-pay) (shift calendar and pay calculator), [Quiz Circle](https://github.com/JahanzaibMohsin9/quiz-circle), [LeadMiner](https://github.com/JahanzaibMohsin9/leadminer), [WooCommerce WhatsApp Pro](https://github.com/JahanzaibMohsin9/woocommerce-whatsapp-pro) and [SubTrack](https://github.com/JahanzaibMohsin9/subtrack).

## What I work with

Most of my work is in TypeScript (Next.js, React, Node) and Dart (Flutter), on top of PostgreSQL with pgvector, Supabase or SQLite. For AI features I use the OpenAI API for retrieval, classification and drafting, and I test prompts and models against fixed examples before trusting them. I've also written Rust (Tauri and a napi-rs module), Python (FastAPI), PHP for WordPress, and Electron apps.

## Contact

You can email me at [jahanzaibbaloch9@gmail.com](mailto:jahanzaibbaloch9@gmail.com) or find me on [LinkedIn](https://www.linkedin.com/in/jahanzeb-mohsin-a52990162/). My portfolio site is [jahanzaib-portfolio.pages.dev](https://jahanzaib-portfolio.pages.dev/).
