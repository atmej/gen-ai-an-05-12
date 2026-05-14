# Pay-Me Link Glossary

This glossary defines the main business terms used in the Pay-Me Link feature requirements.

| Term | Definition |
| --- | --- |
| Pay-Me Link | A unique, shareable link created by a HappyBank user to request a payment from another person. |
| Generate Pay-Me Link | The action of creating a new Pay-Me Link by entering an amount and, optionally, a short description. |
| Pay-Me Link Request | A payment request represented by a Pay-Me Link. It contains the requested amount, requester details, and optional description. |
| Requester | The user who creates the Pay-Me Link and expects to receive the money. |
| Payer | The person who receives the Pay-Me Link and completes the payment. |
| Requested Amount | The amount of money the requester asks the payer to send. |
| Description | Optional short text attached to a Pay-Me Link request, such as "for pizza". |
| Payment Confirmation Screen | The pre-filled screen shown after the payer opens the Pay-Me Link in the HappyBank app and before they confirm payment. |
| Single-Use Link | A Pay-Me Link that can be successfully used only once. After payment, it becomes invalid. |
| Expired Pay-Me Link | A Pay-Me Link that is no longer valid because its allowed lifetime has passed. |
| Active Pay-Me Link | A Pay-Me Link that is valid, not yet used, and still within its allowed lifetime. |
| Cancelled Pay-Me Link | A Pay-Me Link that was intentionally invalidated before payment. |
| Shareable Link | A Pay-Me Link that can be copied or sent using standard sharing features. |
| Deep Link Opening | Behavior where clicking the Pay-Me Link opens the HappyBank mobile app directly to the relevant payment flow. |
| Authentication Reuse | The payer completes the flow using their existing logged-in app session without a separate login step. |
| Happy Path | The ideal end-to-end scenario in which the Pay-Me Link is generated, opened, confirmed, and paid without errors. |
| MVP | The minimum demo scope needed to show the core Pay-Me Link flow, even if backend processing is simulated. |
