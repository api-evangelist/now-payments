# NOWPayments

NOWPayments is a crypto payment gateway that enables businesses to accept 300+ cryptocurrencies, create payment invoices, process recurring subscriptions, and manage merchant mass payouts. Founded in 2019, the platform processes over 30 million transactions monthly with 99.99% uptime and supports automatic coin conversion and fiat settlements.

## APIs

- **Payment API** — Core REST API for accepting cryptocurrency payments, creating invoices, checking payment status, and managing transaction history with IPN webhooks.
- **Mass Payouts API** — Bulk payout API for initiating thousands of transactions in a single call for payroll and affiliate distributions (no service fee).
- **Recurring Payments API** — Subscription-based billing automation for SaaS and membership platforms.
- **Custody API** — Off-chain fund management with sub-account support for platform operators.

## Pricing

- Monocurrency payments: 0.5% service fee
- Conversion payments: 1.0% service fee
- Mass payouts: 0% service fee (network fees only)
- Volume discounts available for high-throughput merchants

## Developer Resources

- [API Documentation](https://nowpayments.io/help/api)
- [Postman Collection](https://documenter.getpostman.com/view/7907941/S1a32n38)
- [Sandbox Environment](https://sandbox.nowpayments.io)
- [Pricing](https://nowpayments.io/pricing)
- [Blog](https://nowpayments.io/blog)

## Authentication

Requires an `x-api-key` header with your API key from your NOWPayments merchant account. JWT bearer tokens are required for payout and payment list endpoints (valid 5 minutes, obtained from `POST /v1/auth`).

## Base URL

- Production: `https://api.nowpayments.io/v1`
- Sandbox: `https://api.sandbox.nowpayments.io/v1`

## Contact

- Support: support@nowpayments.io
- Partnerships: partners@nowpayments.io
