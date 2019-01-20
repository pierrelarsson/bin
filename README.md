Scripts for your "bin"
======================
A couple of simple, but handy scripts written in whatever language seemed fit.

cnum
----
Tries to **c**onvert the input string as any of the most common computer **num**eral systems
(decimal, hexadecimal, octal and binary) and then outputs the number again in those formats,
aswell as bit-length.
Helpful when you reverse engineer protocols etc.
```
$ cnum 40
hex: 0x40 (7)
  dec: 64
  oct: 0o100
  bin: 0b1000000

dec: 40 (6)
  hex: 0x28
  oct: 0o50
  bin: 0b101000

oct: 0o40 (6)
  hex: 0x20
  dec: 32
  bin: 0b100000
```

ctime
-----
**C**converts input string according to a couple of different date-time formats,
and outputs them again, aswell as unix-timestamp.
```
$ ctime
2019-01-20 23:46:31 (1548024391) [Sun]
1970-01-18 23:00:24 (1548024) [Sun]
```
