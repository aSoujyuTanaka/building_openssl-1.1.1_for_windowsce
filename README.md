# openssl-1.1.1_windowsce

This is the instruction to build OpenSSL 1.1.1 for Windows CE.
https://qiita.com/souju/items/94117c024862f57459c3

wince_openssl-1.1.1b.patch: patch for OpenSSL 1.1.1b

### How to patch
mv to the top of original OpenSSL directory and
```bash
$ patch -s -p0 < ../wince_openssl-1.1.1b.patch
```
