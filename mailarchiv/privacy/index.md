---
title: "Privacy Policy – MailArchiv"
lang: en
---

[MailArchiv](../) · [Help](../support/) · [Privacy](../privacy/) · [Legal notice](../impressum/) · [Deutsch](../datenschutz/)

# MailArchiv Privacy Policy

Last updated: November 23, 2026

## In short

MailArchiv works entirely on your Mac. Your emails, credentials and archive only leave your
Mac towards services you set up yourself (your email provider and, if you choose, your cloud
folder). **We, the developer, receive none of your data.** There is no account with us, no
server of ours, no advertising, no analytics or tracking tools, and the app does not send
crash reports by itself.

## 1. Controller

Roger Becker
Oberfeldstrasse 30
8586 Riedt b. Erlen
Switzerland
Email: erdwind@live.de

## 2. Data MailArchiv processes on your Mac

MailArchiv runs inside the macOS App Sandbox. All of the following data stays on your Mac:

| Data | Purpose | Location |
|---|---|---|
| Account details: account name, server, port, encryption type, user name or email address, selected folders | Connecting to your mailbox | Settings file in the app container (`~/Library/Containers/de.rogerbecker.mailarchiv/`) |
| Passwords or app-specific passwords and, if used, sign-in tokens (refresh tokens) | Signing in to your email provider | Encrypted in the settings file; the key is kept in the macOS keychain |
| Emails and attachments | Building your archive | As PDFs and, if enabled, original files (.eml) and extracted attachments in the folder you choose |
| Search index: subject, sender, recipients, date, message text, attachment names, file paths | Full-text search | Database in the app container |
| Settings, log of archiving runs, access permission for the chosen folder | Running the app | App container |

MailArchiv only reads from your mail server. It never deletes, moves or flags messages there.

## 3. Internet connections

MailArchiv only makes these connections:

**a) To your email provider (IMAP).** To fetch your messages, MailArchiv connects to the
server you entered or picked from a preset and signs in with your credentials. The
connection is encrypted (TLS or STARTTLS) unless you explicitly turn encryption off in the
account settings. As with any mail app, your provider sees your IP address and the access.
Your provider's privacy policy applies to this.

**b) Sign-in with Google or Microsoft (only if available in your version).** With browser
sign-in, you sign in directly with Google or Microsoft in your default browser; MailArchiv
never sees your password. MailArchiv receives permission to read your mailbox via IMAP and
your email address. The sign-in token is stored encrypted on your Mac and is only ever sent
to that provider. You can revoke the permission at any time in your Google or Microsoft
account.
MailArchiv's use of information received from Google APIs adheres to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the Limited Use requirements: the data is used solely on your Mac to create your
archive, is not transferred to us or third parties, is not used for advertising, and is not
read by any human.

**c) External images (off by default).** Many newsletters load images from third-party
servers, often including tracking pixels. MailArchiv blocks such content when creating PDFs.
Only if you turn on "Load external images" in the settings does MailArchiv download these
images. Those servers then learn your IP address and the time of access and may conclude
that the message was opened.

**d) Links.** When you click a link in the app, macOS opens it in your default browser. From
then on, the terms of that website apply.

**e) Cloud folders.** If you choose a folder in iCloud Drive, Dropbox, Google Drive, OneDrive
or a network drive as the storage location, MailArchiv only writes the files to that folder
on your Mac. Uploading is handled by that service's own software under its terms and
privacy policy.

## 4. What we don't do

- We run no servers for MailArchiv and receive no emails, credentials, search queries or
  usage data.
- MailArchiv contains no advertising, no analytics or tracking services, and no third-party
  software that sends data to third parties.
- We do not sell data or build profiles.

## 5. Apple and the App Store

Purchase, download and updates are handled by the Mac App Store. Apple is responsible for
this, and Apple's privacy policy applies. If you agreed in the macOS settings to "share with
app developers", Apple provides us with anonymized crash reports and statistics (such as the
number of installations). We cannot identify you from them.

## 6. Contacting us by email

If you write to us, we process your email address and the content of your message in order
to reply (Art. 31 Swiss FADP; where the GDPR applies, Art. 6(1)(b) or (f) GDPR). We delete the correspondence once it is resolved,
unless statutory retention obligations apply. Please don't send us passwords and, where
possible, no complete emails with confidential content.

## 7. Retention and deletion

All data stays on your Mac until you delete it:

- **Remove account** (in the app under "Accounts"): deletes the account details including
  the encrypted password or sign-in token.
- **Delete the app**: move MailArchiv to the Trash. Settings and the search index are kept in
  the container `~/Library/Containers/de.rogerbecker.mailarchiv/`, which you can delete as
  well.
- **Archive**: the PDF, EML and attachment files you created are yours and stay in the folder
  you chose until you delete them yourself.

## 8. Security

MailArchiv runs in the App Sandbox and can only access folders you grant it. Credentials are
stored encrypted, protected by the macOS keychain. PDFs are created without JavaScript;
scripts and active content are removed from emails beforehand.

## 9. Children

MailArchiv is not specifically directed at children and does not collect data about
children.

## 10. Your rights

Under the Swiss Federal Act on Data Protection (FADP) and, where applicable, the GDPR you have
the right of access, rectification and erasure, and under the GDPR also the right to
restriction of processing, data portability and objection. Since we receive no data from
you apart from support requests, these rights in practice only concern your correspondence
with us. You may also lodge a complaint with a data protection supervisory authority, for
example the Swiss Federal Data Protection and Information Commissioner (FDPIC) or, in the EU,
the authority in your country of residence.

## 11. This website

These pages are served by GitHub Pages (GitHub, Inc., 88 Colin P. Kelly Jr. Street,
San Francisco, CA 94107, USA). When you visit them, GitHub processes technically necessary
data such as your IP address in server logs to deliver the pages and protect against abuse
(legitimate interest, Art. 6(1)(f) GDPR). GitHub is certified under the EU-U.S. and the
Swiss-U.S. Data Privacy Framework. Details:
[GitHub General Privacy Statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement).
We do not use cookies or analytics tools on these pages.

## 12. Changes

If the app changes in a way that involves processing different data, we will update this
policy and show the new date at the top.
