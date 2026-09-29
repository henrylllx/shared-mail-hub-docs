# Privacy Policy — Shared Mail Hub

Effective date: September 28, 2026.

## Purpose and operator

Shared Mail Hub is operated locally by its owner for that owner's personal Gmail account. It is not a public mailbox service and does not offer third-party signup. This public documentation site does not connect to Gmail or display mailbox information.

## Data accessed and used

After explicit Google OAuth consent, the local application can access the Gmail account address and mailbox counts, message identifiers, senders and recipients, subjects, labels, message bodies, threads, draft content, and attachments requested by the owner. It uses these data to provide user-directed search, reading, drafting, sending, and incoming-attachment download features.

The requested scopes are `https://www.googleapis.com/auth/gmail.readonly` and `https://www.googleapis.com/auth/gmail.compose`. The application does not request Gmail account administration or permanent message-deletion access.

## Storage and recipients

OAuth client credentials and refresh authorization are stored in the owner's macOS Keychain. Access tokens are kept in process memory. Drafts and sent messages remain in Gmail. Downloaded incoming attachments are saved locally on the owner's Mac. Normal service logs do not intentionally include message bodies or tokens.

Requested results are returned to the MCP client selected by the owner. If that client uses a cloud AI provider, selected message data may be processed by that provider under its applicable terms and the owner's account settings. A local MCP interface does not mean that a connected AI client is entirely local. The owner controls which clients connect and which mail tasks they perform.

The public documentation host does not receive OAuth credentials or Gmail message contents from this application. The application does not sell Gmail data, use it for advertising, or perform model training. It does not include a third-party analytics service.

## Google API data commitments

Shared Mail Hub's use and transfer of information received from Google APIs will adhere to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements. Access is used for the user-facing mail features described here. Connected clients must be configured and used consistently with those requirements; Google user data must not be used to train general-purpose AI models.

## Control, retention, and revocation

The owner may disconnect a client, stop the local service, or revoke Google access through [Google Account connections](https://myaccount.google.com/connections). Revocation prevents further authorized API access, but does not automatically delete existing Gmail messages, drafts, local attachments, or data already handled by a connected client. Those items remain subject to their respective local, Gmail, or provider retention controls.

The owner manages credential retention in macOS Keychain. No mailbox database is maintained by this local gateway. The application does not automatically send messages; sending requires an explicit owner instruction to an authorized client.

## Contact and updates

Questions about this application or policy may be raised through the issue tracker of this documentation repository. Do not include private email content, attachments, or credentials in a public issue. Material changes to data access or handling will be reflected in an updated policy and, where required, new Google consent.
