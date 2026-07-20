# Marketplacer Operator Onboarding Hub

This static prototype contains developed Operator guidance for Content Sprints 1 through 12, plus approved cross-sprint enhancements to wholesale pricing governance, promotions, Orders, refunds, reporting and integrations.

## Developed sections

1. Your Onboarding Journey
2. Marketplace Decisions
3. Marketplacer Foundations
4. Platform and Environment Setup
5. Commercials, Tax and Marketplace Finance
6. Marketplace Structure
7. Seller Strategy and Onboarding
8. Product and Catalogue Management
9. Shipping, Orders and Fulfilment
10. Cancellations, Returns and Refunds
11. Reporting, Performance and Marketplace Operations
12. Integrations and Data Flow
13. Testing and Go-Live

Resources and Support retains representative content or placeholders for a later sprint.

## Sprint 12 additions

- Testing Strategy
- Marketplace Configuration Testing
- Catalogue Testing
- End-to-End Testing
- Seller Launch Readiness
- Production Readiness
- Go-Live
- Controlled Sandbox and Production testing guidance, evidence, defect and exit criteria
- Commission and wholesale test coverage across pricing, promotions, Orders, refunds, remittance and reporting
- Soft launch, hypercare, first-transaction monitoring, incident response and transition to business as usual

## Cross-sprint wholesale pricing revision

- Clarified that the Operator controls or approves the customer-facing website retail price for wholesale products
- Clarified that Wholesale Price is the Seller entitlement basis and commission does not normally apply
- Clarified that Seller RRP is reference only and may differ from the website retail price
- Clarified that wholesale promotional price is a temporary supplier cost and does not automatically change the customer Sale price
- Added integration overwrite controls, model-specific refund recovery, finance reporting and end-to-end testing

## Sprint 11 additions

- Integration Architecture
- APIs
- Webhooks
- Source-of-Truth Planning
- Integration Troubleshooting
- Detailed guidance for system boundaries, data flow, identifiers, authentication, scopes, retries, duplicate prevention, Webhook security, event ordering, reconciliation, troubleshooting and Support escalation

## Product and Catalogue revision

- Replaced the existing **MConnect** page with one authoritative 30-section guide under Product and Catalogue Management
- Added connector selection, Seller and Operator responsibilities, product scope, Category source, field ownership, price, inventory, Seller Invoice and fulfilment synchronisation, supported cancellation and return flows, monitoring, single-record recovery, fatal failures, change control, offboarding and end-to-end testing
- Removed the duplicate MConnect Integrations submenu from Integrations and Data Flow

## Previous enhancements

- Added **Promotions and Campaign Management** under Commercials, Tax and Marketplace Finance
- Expanded **Golden Records and Central Product Database**, including explicit Operator responsibility for buy-box ranking in the storefront or orchestration layer

## Open locally

Open `index.html` in a modern browser. No build step or database is required.

## Structure

- `index.html` application shell
- `css/styles.css` responsive visual system
- `js/app.js` navigation and interface behaviour
- `js/content-sprint-1.js` through `js/content-sprint-12.js` developed content
- `assets/` Marketplacer logos, favicons and illustrations

## Typography

The Hub uses Manrope with Arial as fallback.
