# Hasher (Firefox WebExtension)

A Firefox-friendly fork of https://github.com/s12v/hasher

99% of the credit goes to the original developer; I liked it so much I "ported" it to a WebExtension when I switched back to Firefox.

This extension is used to compute cryptographic hashes and do common conversions. It might be useful for programmers and system administrators. It's entirely implemented in JavaScript, all calculations are performed on client side, so it's safe.

* <b>Hash</b>: MD5, SHA-1, SHA-2 (224, 256, 384, 512), SHA-3, RIPEMD-160, MD4, Whirlpool
* <b>HMAC:</b> MD5, SHA-1, SHA-2 (224, 256, 384, 512), RIPEMD-160, MD4
* <b>CRC:</b> CRC-8, CRC-16, FCS-16, FCS/CRC-32
* <b>Cipher</b> <i>(interoperable with OpenSSL)</i>: AES-256, DES, Triple DES, Rabbit, RC4, RC4Drop. CBC/Pkcs7 is used.
* <b>Net:</b> Subnet calculator, Ip ↔ Dec, Ip → Bin, Ip → Hex
* <b>Time:</b> Unix ↔ Datetime, Unix ↔ RFC-1123, Unix ↔ ISO 8601
* <b>Numbers:</b> Dec ↔ Hex, Dec ↔ Bin, Dec ↔ Roman
* <b>Strings:</b> ASCII ↔ Hex, UTF-8 ↔ Hex, UTF-16 ↔ Hex
* <b>Encode:</b> Base64, ROT-13, JavaScript encodeURI(), encodeURIComponent(), HTML special chars encode/decode
