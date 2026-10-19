# Baseline — proposed privacy policy

> **Proposal for review. Not an effective privacy notice.** These are proposed commitments, not a claim that every safeguard is currently implemented. This proposal has no effective date. Operator contact information, service locations, and verification of the commitments are required before adoption. It should not be submitted as an active privacy notice.

## 1. Purpose and scope

Baseline is designed to help people review their sleep, recovery, and training-load history through long-term charts and summaries. The current policy scope is a personal pilot. Coach access, athlete rosters, and public sharing are not enabled. Future coaching would require specific athlete authorization and an updated notice before use.

If adopted, this policy would permit Baseline to process information only to provide functions the user requests, maintain their security and reliability, handle authorized support requests, and meet specific legal obligations. It would not grant ownership of the information or permission for unrelated uses.

## 2. Minimum information

After WHOOP authorization, Baseline would retrieve cycle, recovery, and sleep records and save only the dated measurements needed for the dashboard: sleep duration, recovery score, strain, heart-rate variability, and resting heart rate. WHOOP responses may contain more detail than is saved. Complete raw responses would not be kept as a separate archive.

Necessary supporting information would include a local account identifier and configured display name; encrypted access and refresh tokens, their expiry and permissions; sync status and error categories; and limited sign-in and authorization records. Those records would include hashed session identifiers, authorization-state records, and hashed connection-address identifiers used to limit repeated login attempts. A hashed address identifier would not be treated as anonymous.

Support contact details and messages would be used only to resolve the user's request. Users should not send passwords, authorization tokens, or unnecessary health records to support.

Baseline would not request WHOOP profile, body-measurement or workout endpoints, location tracks, contacts, or continuous raw sensor streams. It would not collect a WHOOP password. Its own sign-in password would be checked against a salted password hash rather than stored as plaintext by the application.

## 3. Authorization and history

Before an import, the user would expressly authorize fetching and storing historical measurements for their requested charts. Declining an unrelated optional use would not block the core dashboard.

Long-term charts need dated historical measurements. Background updates need a refresh token so synchronization can continue when the dashboard is closed. Permissions would be limited to `read:cycles`, `read:recovery`, `read:sleep`, and `offline`, with no permission to change WHOOP records. Historical availability and storage would remain subject to WHOOP's API and applicable terms.

Authorized history would be kept only for the chosen dashboard until the user deletes it, disconnects, or the pilot ends, subject to any requirement for earlier deletion. Inactivity alone would not cause valuable history to be erased. Baseline would not promise an independent permanent archive of WHOOP data.

## 4. Prohibited uses and sharing

Baseline would not sell, rent, license, or trade health data. It would not use health data for advertising, marketing profiles, data brokerage, insurance or employment decisions, or an unrelated research dataset. These restrictions would also cover derived and de-identified copies.

Health records would not be sent to AI services or used to create, train, test, fine-tune, or improve AI models or systems.

Coaches, employers, insurers, other athletes, and other users would receive no automatic access. Any future sharing feature would require a separate, specific choice identifying the recipient and information shared. Sharing would be off by default and could not be enabled by accepting a general policy update.

## 5. Access, providers, and security

The dashboard would remain private. Authorized administrators could access underlying records only when necessary for a support request the user authorizes, a specific security incident, or a binding legal obligation. Access would be limited to the information needed. Individual health histories would not be routinely read for product development.

Health records, authorization tokens, and backups would be encrypted at rest and transmitted over appropriate encrypted connections, with restricted access. The server would still process readable measurements to calculate charts. This would not be end-to-end encryption that excludes the operator, and no system can guarantee protection against every incident.

WHOOP handles authorization and API requests under its own policies. Hosting and networking providers may process technical information needed to operate the service. Providers receiving health data, their roles, and relevant service locations would be identified before adoption or before a new health-data disclosure.

The public policy page is separate from the health application and would not receive its session cookie or database records. GitHub Pages hosts this static documentation and logs visitors' IP addresses for security under GitHub's own privacy practices. The page contains no forms, advertising pixels, analytics, session-replay tools, or third-party tracking scripts.

The dashboard would use no advertising or behavioral tracking. An essential sign-in cookie would expire after eight hours or be invalidated at sign-out. Device password managers and downloaded files would remain under the user's control.

Legally compelled disclosures would be assessed and limited to what is required, with user notice when legally permitted. Users affected by a security incident would be notified promptly with the known impact and protective steps, as required by applicable law.

## 6. Export, disconnection, and deletion

The dashboard would provide monthly-summary CSV downloads. Users could also request a machine-readable copy of stored daily measurements through the privacy contact established before adoption. A monthly CSV would not be presented as a complete daily-data export.

**Disconnect WHOOP** would stop future synchronization and remove the saved WHOOP tokens, imported health records, and associated sync jobs from the active database. In-flight jobs would not be allowed to restore a deleted connection's history. Disconnection would remain separate from ending a browser session with **Sign out**.

Disconnecting Baseline would not delete information held by WHOOP and would not automatically revoke WHOOP's authorization grant. Users would also need to revoke access through WHOOP's connected-app controls. Revocation at WHOOP would prevent further authorized imports, but would not alone be treated as a request to erase existing Baseline copies; users would use Disconnect or the privacy contact for that purpose.

Deleted information could remain in encrypted disaster-recovery backups for no more than seven days. Backup copies would be isolated from normal use and expire automatically. Recovery would apply deletion requests before returning the service to use, so deleted records and connections would not reappear. Minimal deletion markers could be retained only as necessary to enforce this protection, without health measurements or reusable credentials.

Operational security records would be removed within seven days of expiry or resolution, unless a specific legal obligation or documented active security investigation required longer retention. Exceptions would be limited to necessary records and end with their reason. There would be no general business-purposes exception for keeping health histories.

Support correspondence would be deleted within 30 days after resolution unless the user requested longer retention or a specific legal obligation required it. Health information volunteered in a support message would receive the same restricted-use treatment as imported records.

Users could request access, correction, or deletion through the privacy contact. Identity checks would not require emailing passwords or tokens. Responses would be provided within 30 days or a shorter applicable deadline. Corrections to WHOOP-source information might need to be made in WHOOP and then synchronized. Statutory rights would not be limited by this policy.

## 7. Changes and closure

Users would receive notice before material privacy changes. A policy update or continued use would not authorize a new purpose for previously collected health data. Broader collection, sharing, or use would require a separate affirmative choice and must also be allowed by WHOOP's terms and applicable law.

If the pilot closed, users would receive notice and an export opportunity where practicable, followed by deletion of active health records and tokens. Backup copies would expire within the same seven-day limit. Health histories would not be transferred to a buyer or successor as business assets.

---

**Status:** public proposal only. No effective date or public privacy-contact channel has been established here. Adoption requires a complete, accurate notice and verified implementation of its commitments. This document is not a claim of regulatory compliance or a substitute for legal review.
