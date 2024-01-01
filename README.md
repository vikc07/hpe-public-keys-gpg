# HPE Public Keys in GPG format
## Overview
These are gpg versions of pub files available at https://downloads.linux.hpe.com/SDR/keys.html. 

On Debian, download the gpg files, and move them to `/etc/apt/trusted.gpg.d/`

## Why do you need these?
In order to install HPE utilities, you need the keys.

The original instructions provided by HPE use `apt-key` which is deprecated.

Utilizing the pub files meant, converting those to gpg, and then manually importing those into the keystore.

The gpg files are readily available to use, avoiding the need to convert pub files again.