<h2> s0md3v Repositories <img src="https://media.giphy.com/media/mGcNjsfWAjY5AEZNw6/giphy.gif" width="50"></h2>

*[learning hacking](https://github.com/s0md3v/be-a-hacker) and [programming](https://s0md3v.medium.com/learn-to-code-in-less-than-a-week-8f3da5e0ab29).*

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Index</summary>

[Arjun](/Arjun/#README.md)

[Blazy](/Blazy/#README.md)

[Bolt](/Bolt/#README.md)

[Breacher](/Breacher/#README.md)

[Cloak](/Cloak/#README.md)

[Corsy](/Corsy/#README.md)

[CyberChef](/CyberChef/#README.md)

[Decodify](/Decodify/#README.md)

[Diggy](/Diggy/#README.md)

[Entropy](/Entropy/#README.md)

[fonetic-go](/fonetic-go/#README.md)

[goop](/goop/#README.md)

[hardcodes](/hardcodes/#README.md)

[Hash-Buster](/Hash-Buster/#README.md)

[hashid](/hashid/#README.md)

[huepy](/huepy/#README.md)

[JShell](/JShell/#README.md)

[Locky](/Locky/#README.md)

[meta](/meta/#README.md)

[nano](/nano/#README.md)

[Orbit](/Orbit/#README.md)

[ote](/ote/#README.md)

[Parth](/Parth/#README.md)

[Photon](/Photon/#README.md)

[proxify](/proxify/#README.md)

[Quark](/Quark/#README.md)

[ReconDog](/ReconDog/#README.md)

[rewise](/rewise/#README.md)

[shades](/shades/#README.md)

[Shiva](/Shiva/#README.md)

[Silver](/Silver/#README.md)

[Smap](/Smap/#README.md)

[sqlmate](/sqlmate/#README.md)

[Striker](/Striker/#README.md)

[uro](/uro/#README.md)

[velocity](/velocity/#README.md)

[XSStrike](/XSStrike/#README.md)

[Zen](/Zen/#README.md)

[zetanize](/zetanize/#README.md)
</details>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Decodify</summary>
  
# Decodify
It can detect and decode encoded strings, recursively.\
Lets take this string : `s0md3v` and encode it in Base 64
```
czBtZDN2
```
Now lets encode it in hex
```
637a42745a444e32
```
And now again in Base 64
```
NjM3YTQyNzQ1YTQ0NGUzMg==
```
Now lets supply it to **Decodify**

<img src='https://i.imgur.com/bsiEyiM.png' />

Boom! Thats what <b>Decodify</b> does. It automatically detects the encoding and decodes it and it does that recursively.

### Supported Encodings and Encryptions
- Caesar ciphers
- Hex
- Decimal
- Binary
- Base64
- URL
- FromChar
- MD5
- SHA1
- SHA2

**Warning:** Decodify uses third party web services for MD5, SHA1 & SHA2 hash lookups. If you are dealing with sensitive data, you are advised to use the `-s` option which will prevent Decodify to use these services.

### Usage
Download Decodify with the following command:
```
git clone https://github.com/UltimateHackers/Decodify
```
Now switch to Decodify directory and run the installer with this command:
```
make install
```
Now you can run decodify by entering `dcode <string to decode>` in your terminal.

To remove Decodify run the uninstaller with this command
```
make uninstall
```

#### Decoding Caesar Cipher
You can supply the offest by `--rot` option or you can tell Decodify to decode for 1-26 offest by using `--rot all`.\
Using `-rot all` option on the string `bpgkta xh qtiitg iwpc sr` gives the following output:

![rot all demo](https://i.imgur.com/4mqxpBU.png)

#### Reversing a String
You can reverse a string by using the `-rev` option.

### Contribution
If you encounter a valid encoded string which wasn't correctly processed by Decodfiy, please open an issue including the string.<br>
You can also contribute by adding support for more encodings or by fixing my poorly writting code.
  
</details>
  
[![Twitter Follow](https://img.shields.io/twitter/follow/s0md3v?style=social)](https://twitter.com/s0md3v)
