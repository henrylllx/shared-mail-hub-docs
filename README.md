# Shared Mail Hub

Shared Mail Hub is a personal, locally operated Gmail integration for MCP-compatible AI clients. It is intended for its owner's own account, rather than public signup or a hosted email service.

The application lets the owner search and read Gmail messages, review conversations, create and update drafts, and download selected incoming attachments. Sending an existing draft requires an explicit instruction from the owner. Files sent to other people use the owner's existing file-link delivery workflow.

Google authorization requests two Gmail permissions: read-only access to messages and settings (`gmail.readonly`), and management of drafts and sending (`gmail.compose`). The application does not provide tools to permanently delete messages, change forwarding settings, or administer the account.

The service runs on the owner's Mac and is accessible only through local MCP connections. Google OAuth credentials are stored in the Mac's Keychain. This public repository contains only the application description and privacy policy; it does not host the mail service, credentials, or mailbox content.

See the [Privacy Policy](PRIVACY.md) for data handling, connected AI clients, and revocation details.

For technical questions about this documentation, use this repository's issue tracker. Do not post emails, attachments, OAuth tokens, or other private account data in public issues.
