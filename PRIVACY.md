# Privacy Policy

This application is a private, single-user integration between the account owner and their own
Google account. It is not offered to the public and has exactly one user: the person who
authorises it.

## What data is accessed

- Gmail messages, headers and metadata belonging to the authorising account.
- Google Calendar events belonging to the authorising account.
- No other Google data is requested, and the credential does not carry scopes for Drive,
  Sheets, Docs or contacts.

## Where the data goes

Data is processed locally, on the account owner's own computer, by Hermes Agent running on that
machine. It is not transmitted to any server operated by this application, because there is no
such server. There is no analytics, no advertising, no profiling, and no data sale.

## Storage

- Message headers and short body excerpts are cached locally under `~/.hermes/` on the owner's
  machine to avoid re-reading the same mail.
- OAuth tokens are stored locally in `~/.hermes/google_token.json` with file permissions `0600`.

## Sharing

None. No data is shared with, sold to, or made available to any third party.

## Retention and deletion

The owner controls all local data and may delete it at any time. Access can be revoked at any
moment at https://myaccount.google.com/permissions, after which this application can no longer
read or modify anything. The application itself never deletes mail or calendar data.

## Contact

buiquocviet99@gmail.com
