
# c4ptur3-th3-fl4g
## A beginner level CTF challenge


### Task 1

#### 1 - c4n y0u c4p7u23 7h3 f149?

```
Pretty straight foward. :D
```

#### 2 - 01101100 01100101 01110100 01110011 00100000 01110100 01110010 01111001 00100000 01110011 01101111 01101101 01100101 00100000 01100010 01101001 01101110 01100001 01110010 01111001 00100000 01101111 01110101 01110100 00100001

```
Decoding as binary.
```

Decode - [cyberchef](https://gchq.github.io/CyberChef/#recipe=From_Binary('Space'))


#### 3 - MJQXGZJTGIQGS4ZAON2XAZLSEBRW63LNN5XCA2LOEBBVIRRHOM======

```
Its Base32 :D 
```

Decode - [cyberchef](https://gchq.github.io/CyberChef/#recipe=From_Base32('A-Z2-7%3D',true))

#### 4 - RWFjaCBCYXNlNjQgZGlnaXQgcmVwcmVzZW50cyBleGFjdGx5IDYgYml0cyBvZiBkYXRhLg==

```
Its Base64 :D 
```

Decode - [cyberchef](https://gchq.github.io/CyberChef/#recipe=From_Base64('A-Za-z0-9%2B/%3D',true))

#### 5 - 68 65 78 61 64 65 63 69 6d 61 6c 20 6f 72 20 62 61 73 65 31 36 3f

```
Each pair of numbers represents a letter/number(Hexadecimal).
```

Decode - [cyberchef](https://gchq.github.io/CyberChef/#recipe=From_Hex('Auto'))

#### 6 - Ebgngr zr 13 cynprf!

```
Rot13 :D
```

Decode - [cyberchef](https://gchq.github.io/CyberChef/#recipe=ROT13(true,true,13))

#### 7 - *@F DA:? >6 C:89E C@F?5 323J C:89E C@F?5 Wcf E:>6DX

```
Rot47. (I took a while to get this)
```

Decode - [cyberchef](https://gchq.github.io/CyberChef/#recipe=ROT47(47))

#### 8 - - . .-.. . -.-. --- -- -- ..- -. .. -.-. .- - .. --- -. / . -. -.-. --- -.. .. -. --.

```
Bip Bip Bop (Morse code :D)
```

Decode - [cyberchef](https://gchq.github.io/CyberChef/#recipe=From_Morse_Code('Space','Forward%20slash'))

#### 9 - 85 110 112 97 99 107 32 116 104 105 115 32 66 67 68

```
Using the ASCII table, you can convert each decimal number to a letter.
```

Decode - [cyberchef](https://gchq.github.io/CyberChef/#recipe=From_Decimal('Space',false))

#### 10 - LS0tLS0gLi0tLS0gLi0tLS0gLS0tLS0gLS0tLS0gLi0tLS0gLi (...)

```
Base64 -> Morse Code -> Decode binary -> Rot47 -> Decode decimal
```

Decode - [cyberchef](https://gchq.github.io/CyberChef/#recipe=From_Base64('A-Za-z0-9%2B/%3D',true)From_Morse_Code('Space','Line%20feed')From_Binary('Space')ROT47(47)From_Decimal('Space',false))


### Task 2

#### 1 - 39d4a2ba07e44421c9bedd54dc4e1182

```
MD2
```

Decode - [md5hashing.net](https://md5hashing.net/hash/md2)

#### 2 - e0418e7c6c2f630c71b2acabbcf8a2fb

```
MD4
```

Decode - [md5hashing.net](https://md5hashing.net/hash/md4)

#### 3 - efbd448a935421a54dda43da43a701e1

```
MD5
```

Decode - [md5hashing.net](https://md5hashing.net/hash/md5)

#### 4 - 11FE61CE0639AC2A1E815D62D7DEEC53

```
NTLM
```

Decode - [md5decrypt.net](https://md5decrypt.net/en/Ntlm/)

#### 5 - a361f05487b879f25cc4d7d7fae3c7442e7849ed15c94010b389faafaf8763f0dd022e52364027283d55dcb10974b09e7937f901584c092da65a14d1aa8dc4d8

```
SHA512
```
	
Decode - [md5hashing.net](https://md5hashing.net/hash/sha512)

#### 6 - d48a2f790f7294a4ecbac10b99a1a4271cdc67fff7246a314297f2bca2aaa71f

```
SHA256
```

Decode - [md5hashing.net](https://md5hashing.net/hash/sha256)

#### 7 - a34e50c78f67d3ec5d0479cde1406c6f82ff6cd0

```
SHA1
```

Decode - [md5hashing.net](https://md5hashing.net/hash/sha1)

### Task 3

#### 1 - Download the file

```
Use the command  *spek filename* to see spectogram.
```

### Task 4

#### 1 - Decode the image to reveal the answer.

```
Use the command *steghide extract -sf filename* to extract the answer.
```

### Task 5

#### 1 - Download and get 'inside' the file. What is the first filename & extension?

```
Use the command *binwalk -W filename* to see the hexdump. If you look closely you can see one filename :D 
```

#### 2 - Get inside the archive and inspect the file carefully. Find the hidden text.

```
You can see the hidden text using the command from task 5.1 ( last one! ).
```

