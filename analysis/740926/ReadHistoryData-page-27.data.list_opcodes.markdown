## START logs/ReadHistoryData-page-27.data
#### STOPPING DOUBLE NULLS @ 144, found 2 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0x38 0x4e 0x5c 0x11 0x8c 0x6d 0x80 0x28    8N\..m.(
    0008   0x8b 0x80 0x38 0x9f 0x80 0x3c 0xb3 0x80    ..8..<..
    0010   0xf4 0xbd 0x80 0x01 0x00 0x64 0x00 0x64    .....d.d
    0018   0x00 0x0c 0x00 0x8c 0x1b 0x57 0x73 0x0e    .....Ws.
##### DEBUG DECIMAL
             56   78   92   17  140  109  128   40
            139  128   56  159  128   60  179  128
            244  189  128    1    0  100    0  100
              0   12    0  140   27   87  115   14
#### RECORD 0 UnabsorbedInsulinBolus unknown head[14], body[0] op[0x5c]
###### DECODED
```python
[{'age': 31, 'amount': 1.0, 'curve': 128},
 {'age': 51, 'amount': 1.4, 'curve': 128},
 {'age': 71, 'amount': 1.5, 'curve': 128},
 {'age': 81, 'amount': 6.1, 'curve': 128}]
```
    op hex (14)
    0000   0x5c 0x0e 0x28 0x1f 0x80 0x38 0x33 0x80    \.(..83.
    0008   0x3c 0x47 0x80 0xf4 0x51 0x80              <G..Q.
    decimal
             92   14   40   31  128   56   51  128
             60   71  128  244   81  128
    datetime (unknown)

    body (0)

#### RECORD 1 Bolus (2008, 4, 0, 16, 0, 56) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 12.0, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x00 0x78 0x00                        ..x.
    decimal
              1    0  120    0
    datetime ((2008, 4, 0, 16, 0, 56))
    0000   0x78 0x00 0x90 0x00 0xb8                   x....
    body (0)
    YEAR BITS: [1, 0, 1, 1]
#### RECORD 2 ChangeRemoteID (2004, 4, 0, 1, 14, 51) head[2], body[0] op[0x27]

    op hex (2)
    0000   0x27 0x55                                  'U
    decimal
             39   85
    datetime ((2004, 4, 0, 1, 14, 51))
    0000   0x73 0x0e 0x01 0x00 0x14                   s....
    body (0)
    YEAR BITS: [0, 0, 0, 1]
#### RECORD 3 Base (2010, 3, 5, 0, 60, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x14                                  ..
    decimal
              0   20
    datetime ((2010, 3, 5, 0, 60, 0))
    0000   0x00 0xfc 0x00 0xa5 0x2a                   ....*
    body (0)
    HOUR BITS: [1, 1, 1] DAY BITS: [1, 0, 1] YEAR BITS: [0, 0, 1, 0]
#### RECORD 4 Base (2014, 0, 20, 0, 33, 14) head[2], body[0] op[0x55]

    op hex (2)
    0000   0x55 0x13                                  U.
    decimal
             85   19
    datetime ((2014, 0, 20, 0, 33, 14))
    0000   0x0e 0x21 0x00 0x94 0x2e                   .!...
    body (0)
    HOUR BITS: [0, 0, 1] DAY BITS: [1, 0, 0] YEAR BITS: [0, 0, 1, 0]
#### RECORD 5 Base (2000, 0, 0, 0, 3, 14) head[2], body[0] op[0x15]

    op hex (2)
    0000   0x15 0x13                                  ..
    decimal
             21   19
    datetime ((2000, 0, 0, 0, 3, 14))
    0000   0x0e 0x03 0x00 0x00 0x00                   .....
    body (0)

#### RECORD 6 Base (2011, 0, 14, 19, 53, 48) head[2], body[0] op[0x6a]

    op hex (2)
    0000   0x6a 0x98                                  j.
    decimal
            106  152
    datetime ((2011, 0, 14, 19, 53, 48))
    0000   0x30 0x35 0x13 0x0e 0x7b                   05..{
    body (0)
    HOUR BITS: [0, 0, 1] YEAR BITS: [0, 1, 1, 1]
#### RECORD 7 Base (2008, 0, 14, 19, 21, 51) head[2], body[0] op[0x04]

    op hex (2)
    0000   0x04 0x93                                  ..
    decimal
              4  147
    datetime ((2008, 0, 14, 19, 21, 51))
    0000   0x33 0x15 0x13 0x0e 0x28                   3...(
    body (0)
    YEAR BITS: [0, 0, 1, 0]
#### RECORD 8 Base (2005, 0, 0, 5, 0, 3) head[2], body[0] op[0x1d]

    op hex (2)
    0000   0x1d 0x00                                  ..
    decimal
             29    0
    datetime ((2005, 0, 0, 5, 0, 3))
    0000   0x03 0x00 0x05 0x00 0x05                   .....
    body (0)

#### RECORD 9 Base (2000, 0, 26, 14, 19, 21) head[2], body[0] op[0x81]

    op hex (2)
    0000   0x81 0x33                                  .3
    decimal
            129   51
    datetime ((2000, 0, 26, 14, 19, 21))
    0000   0x15 0x13 0x0e 0x1a 0x00                   .....
    body (0)

#### RECORD 10 Base (2001, 0, 26, 14, 19, 21) head[2], body[0] op[0x97]

    op hex (2)
    0000   0x97 0x36                                  .6
    decimal
            151   54
    datetime ((2001, 0, 26, 14, 19, 21))
    0000   0x15 0x13 0x0e 0x1a 0x01                   .....
    body (0)

#### RECORD 11 Base (2004, 0, 27, 14, 19, 21) head[2], body[0] op[0xb0]

    op hex (2)
    0000   0xb0 0x36                                  .6
    decimal
            176   54
    datetime ((2004, 0, 27, 14, 19, 21))
    0000   0x15 0x13 0x0e 0x7b 0x04                   ...{.
    body (0)
    DAY BITS: [0, 1, 1]
#### RECORD 12 Base (2013, 0, 8, 14, 19, 21) head[2], body[0] op[0xb0]

    op hex (2)
    0000   0xb0 0x36                                  .6
    decimal
            176   54
    datetime ((2013, 0, 8, 14, 19, 21))
    0000   0x15 0x13 0x0e 0x28 0x1d                   ...(.
    body (0)
    DAY BITS: [0, 0, 1] YEAR BITS: [0, 0, 0, 1]
#### RECORD 13 Base (2003, 10, 22, 16, 51, 42) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x0a                                  ..
    decimal
              0   10
    datetime ((2003, 10, 22, 16, 51, 42))
    0000   0xaa 0xb3 0x10 0x36 0x73                   ...6s
    body (0)
    HOUR BITS: [1, 0, 1] DAY BITS: [0, 0, 1] YEAR BITS: [0, 1, 1, 1]
#### RECORD 14 Base (2003, 2, 22, 16, 51, 21) head[2], body[0] op[0x0e]

    op hex (2)
    0000   0x0e 0x3f                                  .?
    decimal
             14   63
    datetime ((2003, 2, 22, 16, 51, 21))
    0000   0x15 0xb3 0x10 0x56 0x73                   ...Vs
    body (0)
    HOUR BITS: [1, 0, 1] DAY BITS: [0, 1, 0] YEAR BITS: [0, 1, 1, 1]
#### RECORD 15 Base (2008, 6, 5, 11, 22, 1) head[2], body[0] op[0x0e]

    op hex (2)
    0000   0x0e 0x70                                  .p
    decimal
             14  112
    datetime ((2008, 6, 5, 11, 22, 1))
    0000   0x41 0x96 0x0b 0x65 0xc8                   A..e.
    body (0)
    HOUR BITS: [1, 0, 0] DAY BITS: [0, 1, 1] YEAR BITS: [1, 1, 0, 0]
#### RECORD 16 Base (2000, 6, 27, 14, 51, 23) head[2], body[0] op[0xaf]

    op hex (2)
    0000   0xaf 0x19                                  ..
    decimal
            175   25
    datetime ((2000, 6, 27, 14, 51, 23))
    0000   0x57 0xb3 0x0e 0x5b 0x00                   W..[.
    body (0)
    HOUR BITS: [1, 0, 1] DAY BITS: [0, 1, 0]
#### RECORD 17 Base (2000, 1, 20, 14, 51, 23) head[2], body[0] op[0x8c]

    op hex (2)
    0000   0x8c 0x1b                                  ..
    decimal
            140   27
    datetime ((2000, 1, 20, 14, 51, 23))
    0000   0x17 0x73 0x0e 0x14 0x90                   .s...
    body (0)
    HOUR BITS: [0, 1, 1] YEAR BITS: [1, 0, 0, 1]
#### RECORD 18 Base (2008, 0, 0, 0, 56, 25) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x8c                                  ..
    decimal
              0  140
    datetime ((2008, 0, 0, 0, 56, 25))
    0000   0x19 0x38 0x00 0x00 0x38                   .8..8
    body (0)
    HOUR BITS: [0, 0, 1] YEAR BITS: [0, 0, 1, 1]
`end logs/ReadHistoryData-page-27.data: 19 records`
