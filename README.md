# resources
Resources for manage sfos-ja

## How do we manage the resources

The private file will shares by the owner. At that time, owner encrypts with other member's gpg public key.

```
gpg --encrypt --armor --recipient <member's gpg key id> <private file>
```

Shared members can read the file with decrypt by self gpg private key.

```
gpg --decrypt <private file>
```
