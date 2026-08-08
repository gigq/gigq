# Read Privacy Policy

Effective: August 8, 2026

Read is a feed reader for iPhone, iPad, and Mac. This policy explains how Read handles
information when you use the app.

## Information Read handles

Read stores your accounts, feeds, article metadata and content, saved searches, labels,
and reading state in a SQLite database on your device. Provider usernames and server URLs
are stored with the local account record. Passwords and API tokens are stored in the
device Keychain.

When you configure a feed-provider account, Read sends the credentials and library
requests needed to use that account directly to the provider you selected. Read does not
route that traffic through a developer-operated server. Your relationship with that
provider, and its handling of your account information, is governed by the provider's
terms and privacy policy.

Read also connects directly to feed, article, image, audio, and website servers when it
loads content you request. Those server operators may receive ordinary network request
information, such as your IP address, under their own privacy policies. The developer does
not receive a copy of those requests.

Read can place article titles, summaries, feed names, and identifiers needed to reopen
articles in your private system Spotlight index and Handoff activity. Apple may transfer
Handoff activity between your nearby devices under its privacy terms; the developer does
not receive it.

When you choose to save an article image on iPhone or iPad, Read requests add-only
permission and writes that image to your Photos library; it does not read your photo
library. On Mac, Read writes the image to your Downloads folder.

## iCloud

When iCloud is available, Read syncs feeds, article metadata, saved searches, labels, and
read, starred, and read-later state through your private CloudKit database in Apple's
`iCloud.com.gigq.read` container. Article bodies and media are not stored in CloudKit.
Read can also sync app preferences through Apple's iCloud key-value storage and register
with Apple's push-notification service for private CloudKit change notifications.

This information is associated with your Apple Account and is handled by Apple under its
terms and privacy policy. Read does not create a separate developer-operated account, and
the developer does not receive or retain your private CloudKit records.

## Data collection and tracking

The developer does not collect your data through Read. Read contains no advertising,
third-party analytics, or tracking technology. The developer does not sell or share your
information, and Read does not track you across apps or websites.

If you contact support, the developer receives your email address and anything you choose
to include. That information is used only to respond to your request. Read can generate a
diagnostics report on your device; it leaves the device only when you deliberately copy or
share it. The report does not intentionally include stored credentials or account
usernames, but it can include provider or iCloud error messages; review it before sharing.

If you enable Apple's **Share With App Developers** option, Apple may provide the
developer with diagnostics or usage information under Apple's privacy terms. Read itself
does not add analytics or tracking to that information.

## Your choices

You can remove provider accounts and delete or clear library data from within Read.
Removing a provider account also deletes its saved password or API token. You can manage
Read's iCloud access and data through your Apple Account and system iCloud settings.

Removing Read from an iPhone or iPad removes its local database and App Group data from
that device, but passwords and API tokens stored in Keychain can remain after uninstall.
Remove provider accounts inside Read before uninstalling if you want Read to delete those
credentials. On Mac, moving Read to the Trash does not automatically remove data from its
sandboxed Application Support or App Group containers, credentials from Keychain, or
entries from the system Spotlight index.

Data held by a feed provider remains subject to that provider's controls. Exported files,
device backups, and synced iCloud data are separate copies and remain until you delete
them through the service or system that stores them.

## Changes

If Read's data practices change, this policy will be updated before the changed version
is released. The effective date above identifies the current policy.

## Contact

For privacy questions, email
[justin@gigq.com](mailto:justin@gigq.com?subject=Read%20Privacy).
