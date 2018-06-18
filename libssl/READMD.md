


#### Link Error

#### "_OPENSSL_ia32cap_P", referenced from:_AES_cbc_encrypt in libcrypto.a(aes-x86_64.o)



at Openssl file cryptlib.c

```c
unsigned long  OPENSSL_ia32cap_P=0;
unsigned long *OPENSSL_ia32cap_loc(void) { return &OPENSSL_ia32cap_P; }

```

just add this code

```c
extern unsigned long  OPENSSL_ia32cap_P=0;
```
 at you source, recompile。 












