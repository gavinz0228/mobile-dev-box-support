# Security Policy

## Reporting a vulnerability

Please do not open a public issue for security or privacy problems.

For now, open a minimal [support issue](https://github.com/gavinz0228/mobile-dev-box-support/issues/new)
requesting a private reporting channel, without disclosing the vulnerability
or any sensitive information. Wait for a private channel before sharing
reproduction details. Private vulnerability reporting is not currently enabled
for this repository.

## Scope

DevBoxMobile stores server credentials and SSH keys in Apple Keychain and
connects only to servers the user configures. Reports about credential
handling, transport security, data stored on the device, or the app's handling
of remote commands are all in scope.

Reports about a third-party server, service, or package that DevBoxMobile
connects to should go to that project's own security contact.
