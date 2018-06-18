
### How to Use

1. Xcode --> General --> Linked Fameworks and libraries. 

	Just drop lib files in to listView.

2. Xcode --> Build Settings -> Search Paths.

	Double click the right of Header Search Paths,
drop header files folder into ListView;

 	Double click the right of Library Search Paths,drop lib folder into ListView。

3. Enjoy!

---

###  1.sqlite3 3.22.0

iPhoneOS iPhoneSimulator  MacOSX

```c
#define SQLITE_VERSION        "3.22.0"
#define SQLITE_VERSION_NUMBER 3022000
#define SQLITE_SOURCE_ID      "2018-01-22 18:45:57 0c55d179733b46d8d0ba4d88e01a25e10677046ee3da1d5b1581e86726f2171d"
```
### 2.libssh2 1.8.0

iPhoneOS iPhoneSimulator  MacOSX

```c
#define LIBSSH2_VERSION "1.8.0"
#define LIBSSH2_TIMESTAMP "Tue Oct 25 06:44:33 UTC 2016"

```


### 3.Openssl 1.1.0g 

iPhoneOS iPhoneSimulator  MacOSX

```c
# define OPENSSL_VERSION_NUMBER  0x1010007fL
# ifdef OPENSSL_FIPS
#  define OPENSSL_VERSION_TEXT    "OpenSSL 1.1.0g-fips  2 Nov 2017"
# else
#  define OPENSSL_VERSION_TEXT    "OpenSSL 1.1.0g  2 Nov 2017"
# endif
```

Pull a request,if you want to share you compiled  library.


### 4.Openssl 0.9.8  Apple used

MacOSX

	libcrypto.0.9.8.dylib libssl.0.9.8.dylib
	
You can find this two files at /usr/lib,but without openssl at /usr/include









