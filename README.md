# Marketplacer Operator Onboarding Hub

This static prototype contains developed Operator guidance for Content Sprints 1 through 11, plus approved enhancements to the Commercials and Product and Catalogue sections.

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

Testing and Go-Live and Resources and Support retain representative content or placeholders for later sprints.

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
- `js/content-sprint-1.js` through `js/content-sprint-11.js` developed content
- `assets/` Marketplacer logos, favicons and illustrations

## Typography

The Hub uses Manrope with Arial as fallback.
