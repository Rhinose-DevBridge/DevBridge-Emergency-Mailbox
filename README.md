# DevBridge Emergency Mailbox

This public repository is an issue-only emergency control mailbox for the DevBridge watchdog.

Do not post source code, secrets, tokens, credentials, private URLs, logs, or personal data.
Emergency request issues may contain only the protocol fields `schemaVersion`, `requestId`,
`requestedAt`, `action`, and `expectedCommit`. The watchdog accepts only bounded status
and exact-commit restart requests authored by the repository owner.
