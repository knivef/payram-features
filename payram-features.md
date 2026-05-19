# PayRam Features

PayRam is a full-stack crypto payments infrastructure for businesses that want to accept, manage, and send funds across chains without building the infrastructure themselves. From no-code payment links to developer APIs, everything runs from one dashboard.

---

## Contents

- [Payment Links](#payment-links)
- [Payment APIs](#payment-apis)
- [Multi-Currency and Multi-Chain Support](#multi-currency-and-multi-chain-support)
- [SmartSweep](#smartsweep)
- [Customer Deposit Wallets](#customer-deposit-wallets)
- [Multi-Brand Setup](#multi-brand-setup)
- [User Management](#user-management)
- [Analytics and Reporting](#analytics-and-reporting)
- [Payouts](#payouts)
- [Card-to-Crypto Fiat Onramp](#card-to-crypto-fiat-onramp)
- [Shopify Plugin](#shopify-plugin)

---

## Payment Links

**Accept crypto payments in seconds. No code, no checkout page, no friction.**

Send a link. Get paid. PayRam Payment Links let you collect crypto payments through a shareable URL that works on any device, any browser, in any channel. Customers pick their preferred token and chain, confirm, and you're done.

**Who it's for:** Freelancers, sales teams, support teams, event organizers, creators, and any business that needs to collect payment fast without building a checkout flow.

**What you get:**
- Instant link generation from your dashboard with no technical setup
- Customers select their preferred cryptocurrency and blockchain at checkout
- Share via email, SMS, WhatsApp, QR code, or embed in invoices
- Real-time status tracking per link: Pending, Successful, Cancelled
- Full transaction history with customer info, amounts, networks, and timestamps

**The business case:** Every step you remove from a payment flow increases conversion. Payment Links cut out the manual invoice back-and-forth and give customers a clean, one-click experience. Fewer abandoned transactions, faster cash flow.

---

## Payment APIs

**Automate your entire payment workflow with a single integration.**

PayRam's Payment APIs give your backend full programmatic control over payment creation, management, and monitoring. If you're building a platform, marketplace, SaaS product, or any application that needs to process crypto payments at scale, the API is your foundation.

**Who it's for:** Engineering teams, product builders, platforms, and any business automating crypto payment flows.

**What you get:**
- Full API access to create and manage payments programmatically
- Webhook support for real-time event-driven payment notifications
- API key management per project: create, rotate, and deactivate without disrupting other projects
- Custom logic hooks before payment initiation
- Architecture that fits into any existing backend

**The business case:** Manual payment handling does not scale. The API removes humans from routine payment operations, reducing errors and cutting overhead. One integration, every payment automated.

---

## Multi-Currency and Multi-Chain Support

**Meet your customers wherever they hold their funds.**

PayRam supports the most widely-used cryptocurrencies across the most important blockchain networks, and the list keeps growing. Whether your customers hold BTC, USDT on Tron, or USDC on Base, they can pay you without converting to a token they don't have.

**Currently supported:**

| Asset | Networks |
|-------|----------|
| Bitcoin (BTC) | Bitcoin |
| Ethereum (ETH) | Ethereum, Base |
| Tether (USDT) | Ethereum, Tron, Polygon |
| USD Coin (USDC) | Ethereum, Base, Polygon |
| Tron (TRX) | Tron |
| Coinbase Wrapped BTC (cbBTC) | Base |
| Polygon (POL) | Polygon |

**Coming soon:** Solana (SOL/USDC) and TON.

**What you get:**
- Single API manages all currencies and networks with no separate integrations
- Settle in stablecoins (USDC, USDT) or native crypto assets, your choice
- Reduce checkout abandonment caused by unsupported tokens
- Platform expands as new chains are added

**The business case:** Unsupported payment methods are silent revenue leaks. Every customer who can't pay in their preferred token is a lost transaction. Broad chain and currency coverage captures more revenue from the global crypto user base without you building or maintaining the infrastructure.

---

## SmartSweep

**Automated fund consolidation. No manual work, no private key exposure.**

SmartSweep automatically moves funds from your customer deposit wallets into a designated cold wallet using smart contracts. No manual transfers, no private key handling, no missed consolidations. Your treasury stays organized and secure.

**Who it's for:** Any business running customer deposit wallets at volume: exchanges, platforms, wallets, and high-transaction merchants.

**What you get:**
- Fully automated consolidation triggered by amount, address count, or time interval
- Smart contract execution keeps private keys out of the sweep process entirely
- Real-time monitoring of all deposit wallet balances
- Complete transaction logs and audit trails for every sweep
- Reduced network fees through consolidated transfers instead of individual movements

**How triggers work:**
- **Amount-based:** Sweep when a single wallet or batch total reaches a threshold
- **Address-based:** Sweep when a set number of addresses have received funds
- **Time-based:** Sweep on a predetermined schedule

**The business case:** Manual fund consolidation is expensive to operate and a security liability. SmartSweep removes both problems, automating work that would otherwise require a person and cutting out the private key exposure that comes with manual transfers. Your cold wallet stays funded. Your team stays focused on other things.

---

## Customer Deposit Wallets

**Give every customer a permanent, dedicated deposit address.**

Customer Deposit Wallets assign a unique blockchain address to each customer at onboarding. Customers can deposit any supported token at any time with no need to request a new address and no confusion about where to send funds. PayRam tracks everything automatically and credits the right account every time.

**Who it's for:** Platforms, exchanges, wallets, subscription businesses, and any merchant managing ongoing customer balances.

**What you get:**
- Persistent, customer-specific addresses across multiple tokens and networks
- Automatic transaction monitoring and balance attribution to the correct customer account
- Internal ledger tracks every customer's balance with no manual reconciliation
- Configurable confirmation requirements before crediting deposits
- Collision-resistant address uniqueness and full audit trails
- Error handling for token or network mismatches

**The business case:** Deposit friction kills retention. When customers have to ask for a new address every time they want to fund their account, some of them don't bother. Permanent deposit wallets remove that barrier, making it as easy to add funds as it is to use the product.

---

## Multi-Brand Setup

**Run multiple brands, stores, or business units from one PayRam account.**

Multi-Brand Setup lets you create independent projects under a single PayRam account, each with its own branding, API keys, webhooks, and reporting. One login, full separation where it matters.

**Who it's for:** Multi-brand companies, agencies managing multiple clients, regional operations, enterprises with separate divisions, and businesses running parallel products.

**What you get:**
- Separate logos, website URLs, and API keys per project
- Isolated webhook endpoints and audit trails per brand
- Unified payout accounts and wallet balances across all projects
- Dropdown navigation to switch between projects instantly
- Role-based access control at the project level via User Management
- Independent settings for payment options and wallet configuration

**The business case:** Spinning up a new brand or market usually means new infrastructure, new accounts, and new overhead. Multi-Brand Setup compresses all of that into a settings panel. New concept? Launch it in minutes. Regional expansion? Clone and localize.

---

## User Management

**Give your team exactly the access they need, and nothing more.**

PayRam's User Management lets you invite teammates, assign roles, and control access at the project level. Finance sees what finance needs. Ops sees what ops needs.

**Who it's for:** Any team larger than one: operators, finance, developers, support, and referral managers.

**Available roles:**

| Role | What They Can Do |
|------|-----------------|
| Admin | Full organizational access across all projects and payments |
| Project Lead | Creates and updates projects, manages team-level access |
| Project Manager | View-only project oversight and reporting |
| Project Ops | Monitors payment and customer data |
| Platform Referral Admin | Manages referral APIs and program configuration |

**What you get:**
- Invite teammates directly from the dashboard
- One role per user with clean, unambiguous permissions
- Project-level assignments so access is scoped correctly
- Only Admins and Owners can modify roles
- Credential security maintained without sharing dashboard access broadly

**The business case:** Shared credentials are a compliance risk and an operational mess. Role-based access means you can bring contractors, finance teams, and support staff into the platform without exposing everything. It's the minimum viable internal control structure for any serious operation.

---

## Analytics and Reporting

**See exactly how your payments business is performing.**

PayRam's Analytics dashboard gives you a full picture of revenue, customer behavior, and payment health in one place. No spreadsheet exports, no manual reconciliation, just the numbers you need to make decisions.

**Who it's for:** Finance teams, growth teams, operators, and founders who need clear visibility into payment performance.

**Three dashboard views:**

**Revenue Insights**
Total and net revenue, growth rates, average order value, top-performing products, and revenue breakdown by network and payment method. Filter by time period to measure campaigns or regional performance.

**Customer Analytics**
New vs. returning customer rates, churn patterns, ARPU, and high-value segment identification. Understand whether new payment options are actually improving retention.

**Transaction Health**
Payment success rates, decline reasons, popular networks, processing times, and settlement lag by region. Get alerted when performance dips on specific tokens or chains before it becomes a problem.

**What you get:**
- Real-time dashboard with no lag, no stale data
- Exportable reports for accounting systems and team sharing
- Modular views so each team focuses on what's relevant to them
- Cross-network performance comparison to optimize your payment stack

**The business case:** Most crypto payment tools give you a transaction log and call it analytics. PayRam gives you the context: why payments succeed or fail, which networks perform best, which customers are worth retaining. Data you can actually act on.

---

## Payouts

**Send funds to any wallet, on any chain, with full control and audit trails.**

PayRam Payouts makes outbound crypto payments as structured as inbound ones. Whether you're paying suppliers, running payroll, or processing refunds, every payout goes through a controlled approval flow with complete documentation.

**Who it's for:** Finance teams, operations teams, and any business making regular outbound crypto payments.

**What you get:**
- Multi-chain payouts from a single dashboard with no custom integrations per chain
- Address Book to pre-verify recipient wallets and prevent misdirected funds
- Role-based approval flow: only Admins can authorize payout execution
- API-based automation to reduce manual work and processing fees at scale
- Complete audit trails and exportable records for reconciliation
- OTP verification via SMTP for an additional security layer on every payout

**Common use cases:** Vendor and supplier payments, cross-border payroll, and customer refunds across chains.

**The business case:** Crypto payouts without controls are a liability. A wrong address, a wrong network, and the funds are gone. PayRam's payout workflow builds the guardrails in: pre-verified addresses, network matching checks, admin approval gates. Your finance team can move fast without moving recklessly.

---

## Card-to-Crypto Fiat Onramp

**Let anyone pay with a card. You still settle in crypto.**

PayRam's Fiat Onramp bridges traditional payment methods with crypto settlement. Customers pay with what they have: credit cards, debit cards, Apple Pay, Google Pay, bank transfers, and local payment methods. You receive crypto. No custodial risk, no additional fees from PayRam.

**Who it's for:** Merchants targeting customers who don't already hold crypto, platforms onboarding new Web3 users, and any business that wants to reach fiat-paying customers without giving up crypto settlement.

**What you get:**
- 175+ payment methods across 190+ countries
- Supports credit/debit cards, Apple Pay, Google Pay, bank transfers, and RevolutPay
- Non-custodial crypto settlements with funds going directly to your wallet
- No KYC/KYB requirements for merchant activation
- Customers auto-generate self-custody wallets with one-time KYC
- Optional gas fee sponsorship for a smoother customer experience
- Multi-project control: enable or disable per brand from dashboard settings
- Zero additional fees from PayRam

**Setup:** Enable the Base blockchain in your settings, activate Cards under Payment Channels, and you're live.

**The business case:** The biggest barrier to crypto commerce is not merchant adoption, it's customer readiness. Most people don't hold crypto yet. The Fiat Onramp removes that barrier, turning any card-carrying customer into a crypto payment without them needing to buy crypto first. Your addressable market becomes anyone with a card.

---

## Shopify Plugin

**Add crypto checkout to your Shopify store without touching your existing payment setup.**

The PayRam Shopify Plugin connects your PayRam account to your Shopify store so customers can pay with crypto at checkout. It runs as a standalone server alongside your existing infrastructure and takes no dependency on your main PayRam instance.

**Who it's for:** Shopify merchants who want to accept crypto payments without replacing their current checkout or payment provider.

**How it works:**

PayRam appears as a custom payment method at checkout. When a customer selects it, they complete the transaction on the post-order Thank You page through a PayRam payment link. No redirects mid-checkout, no disruption to your existing payment flow.

**What you get:**
- Crypto checkout added to any Shopify store
- Runs as an independent server: no conflict with your existing setup
- Configurable with your PayRam Project API Key and payment method name
- Custom branding on the checkout page
- Full PayRam payment link flow post-order, including token and chain selection
- Test mode to verify the integration before going live

**Setup overview:**
1. Run the installation script from the PayRam GitHub repository on your server
2. Configure HTTPS on port 2798 via nginx or direct server config
3. Authenticate with your Shopify credentials and enter your store URL
4. Add your PayRam Base URL and Project API Key
5. In Shopify, create a custom manual payment method labeled PayRam
6. Add the PayRam app block to your Thank You page
7. Run a test transaction to confirm the flow

**The business case:** Crypto-native customers expect crypto checkout options. Adding PayRam to Shopify takes a few hours to set up and opens your store to a buyer segment that would otherwise look elsewhere. No changes to your existing checkout, no new payment provider contract.

---

## Why PayRam

Every feature above runs from one account, one dashboard, one integration. PayRam is built for businesses that want to operate in crypto without building crypto infrastructure from scratch and without giving up the controls, visibility, and flexibility that serious operations need.

**Accept payments. Manage customers. Pay out globally. All from one place.**
