# webtoons

Releasing this because I have no use of it and they don't seem to be sending mails anymore.

You can implement your own mail verification service, it just needs to satisfy the `mail.Mailer` interface.

This can also be used as a Go package, I exported some utilities functions such as:
  - `keyring.Encrypt` to encrypt the password and email for the `encpw` field
  - `webtoons.SignRequest` to sign the request url for the `msgpad` and `md` fields

Example in `cmd/gen/main.go`
