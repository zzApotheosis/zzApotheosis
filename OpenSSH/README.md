The provided file `zzApotheosisSSH.pub` is my public OpenSSH key.

## Verifying your downloaded data
If you're like me and you care about digital security, the smart thing to do would be to not just blindly trust that my OpenSSH key is actually my public key and not some arbitrary malware. To be certain, use your own trusted and preferred anti-virus method to scan `zzApotheosisSSH.pub` and verify it is safe.

Additionally, I would recommend verifying the data you receive is indeed the exact same data that you think you downloaded. This goes for pretty much anything you download; it is always recommended to digitally verify the data you receive if you care about digital security. This is done by locally calculating checksums and/or hash values. On GNU/Linux/Unix-like systems, you can use this to verify my OpenSSH key:
```
$ cat zzApotheosisSSH.pub | sha512sum
```
You may visually verify the locally calculated hash value is the same as the one contained in `zzApotheosisSSH.pub.sha512`:
```
$ cat zzApotheosis.pub.sha512
```

