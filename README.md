# Marketplacer Operator Onboarding Hub

The Marketplacer Operator Onboarding Hub is a live, static onboarding and enablement resource for Marketplacer Operators, implementation partners and Marketplacer delivery teams.

It brings end-to-end marketplace guidance into one structured experience, from early marketplace decisions and platform setup through Seller onboarding, testing, launch and transition to business as usual.

## Live Hub

[Open the Marketplacer Operator Onboarding Hub](https://marketplacersuccess.github.io/marketplacer-operator-hub/)

## What the Hub covers

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
14. Resources and Support

The Resources and Support area also includes Marketplacer Services, Operator resources, training resources, Seller resources, Marketplacer resources and guidance for obtaining Support.

## How the Hub is used

The Hub is the guidance layer for Operator onboarding. It helps teams understand:

- what needs to be decided
- how responsibilities should be assigned
- what needs to be configured
- what evidence should be collected
- how Seller, integration and operational readiness should be assessed
- how testing, Production Readiness, Go-Live and Hypercare should be managed

It is designed to be used alongside the shared onboarding workbook provided by the Marketplacer Delivery team.

## Shared onboarding workbook

The Hub includes a preview of the Marketplacer Operator Onboarding Control Workbook.

Each Operator receives a dedicated working copy from their Marketplacer Delivery team, with known marketplace details, contacts, scope and initial onboarding records pre-filled.

The shared workbook acts as the joint delivery control centre for:

- implementation activities, owners and dates
- marketplace decisions and approvals
- platform configuration
- Seller readiness
- integrations and data dependencies
- testing and evidence
- risks, assumptions, issues and changes
- Production Readiness
- Go-Live and Hypercare

The public template is a preview only and should not be used as the live project workbook.

## Marketplacer Seller Playbook

The Hub links contextually to the Marketplacer Seller Playbook across the Seller lifecycle:

- **Recruit** for Seller strategy, pipeline development, qualification and onboarding preparation
- **Integrate** for Seller Portal, CSV, M-Connect, API and channel-manager options
- **Succeed** for Seller training, support, Product management, Orders, promotions and performance

The Seller Playbook remains the authoritative collection of Seller-facing and Operator-facing Seller resources. The Hub explains when and why to use them.

## Marketplacer Services

The Marketplacer Services area explains available service options and how they can support onboarding, implementation, Seller growth, integrations, enablement and ongoing marketplace operations.

## Project structure

- `index.html` application shell
- `css/styles.css` responsive visual system
- `js/app.js` navigation, search and interface behaviour
- `js/content-sprint-1.js` through `js/content-sprint-13.js` developed Hub content
- `assets/` Marketplacer logos, favicons and approved illustrations
- `resources/` supporting templates and downloadable resources where a separate working file is still useful

## Content maintenance

Content is organised by sprint-specific JavaScript files. Updates should be made in the file that owns the relevant section rather than creating duplicate content elsewhere.

The Hub should maintain one authoritative resource for each purpose:

- Hub pages for guidance and explanations
- the shared onboarding workbook for delivery tracking, decisions, actions and evidence
- the Seller Playbook for Seller recruitment, integration and success resources
- separate downloads only where a standalone template, worksheet or formal artefact is genuinely required

## Open locally

Open `index.html` in a modern browser. No build step, package installation or database is required.

Keep the full folder structure intact so scripts, assets and downloadable resources continue to work.

## Deployment

The Hub is deployed through GitHub Pages.

Changes are made by updating the relevant source files, committing them to the repository and allowing GitHub Pages to redeploy the site.

## Resource and data handling

Do not store passwords, API secrets, MFA recovery codes, bank credentials, unrestricted Production exports or unnecessary personal information in the public Hub or downloadable templates.

Project-specific evidence and working records should be stored in the Operator's approved project workspace and linked from the shared onboarding workbook where appropriate.

## Typography

The Hub uses Manrope with Arial as the fallback font.
