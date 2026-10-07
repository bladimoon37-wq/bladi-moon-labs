# FREE INVOICE CHASER V0 — COMPLETE PACKAGE

Open `index.html` to use the product.
Open `tests.html` to run the 16 deterministic tests.

Architecture:
UI -> validation -> deterministic decision engine -> template engine -> result.

Decision rules live in `assets/engine.js`.
No AI API, database, login, payment, email sending, analytics, or external network request is included.
CSP uses `connect-src 'none'`.
User-entered invoice/customer data remains in browser memory and disappears on refresh.

Release process:
1. Browser flow
2. `tests.html` = 16 PASS / 0 FAIL
3. Mobile visual check
4. Security review
5. Static deployment + smoke test
6. STOP. No V1 without usage evidence.
