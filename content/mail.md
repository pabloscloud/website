+++
author = "pabloscloud"
title = "Contact me via email"
date = "2024-03-16"
lastmod = "2024-03-16"
tags = [
  "PGP",
  "Encryption",
  "Privacy",
]
categories = []
featured = false

+++
<div class="alert">
  <i class="fas fa-info-circle"></i> <strong>Note:</strong> I highly recommend using Threema or Signal to contact me instead of relying on email. Emails are not encrypted by default and even if you choose to use pgp, metadata will not be encrypted.
</div>

## Sending an unencrypted email
[hey@pablos.cloud](mailto:hey@pablos.cloud?body=Hey%20Pablo%2C%0D%0A%0D%0A)

## Sending an encrypted email

I recommend to use [Thunderbird](https://www.thunderbird.net) if you are on a PC.

Firstly you'll need to create a keypair for yourself. And later on we'll import my public key.
1. Open Thunderbird
2. Go to 'Account Settings' from the menu bar
3. Open up 'End-To-End Encryption'
4. Hit 'Add Key...' and click continue to create a new pgp key
5. Click Generate Key


You'll also need a program that manages your keys. For macOS there is [GPG Suite](https://gpgtools.org)and for Windows you'd need [Gpg4win](https://gpg4win.de).

Open my public key with the desired program. You can find it here: [keys.openpgp.org](https://keys.openpgp.org/vks/v1/by-fingerprint/C512E45E7235A6904C4A76844165BE9C6E5DC8FF).


Now you should be able to send an email to hey@pablos.cloud, but remember it's always better to use modern software like Signal or Threema which can protect metadata.

## Receiving an encrypted email

Firstly you'll need to create a keypair.

1. Open Thunderbird
2. Go to 'Account Settings' from the menu bar
3. Open up 'End-To-End Encryption'
4. Hit 'Add Key...' and click continue to create a new pgp key
5. Click Generate Key

Upload the key to a keyserver so your friend can send you an encrypted mail.

Two popular key-servers are [keys.openpgp.org](https://keys.openpgp.org) and [keyserver.ubuntu.com](https://keyserver.ubuntu.com/)