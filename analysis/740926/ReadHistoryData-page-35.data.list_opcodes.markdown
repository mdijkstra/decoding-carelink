## START logs/ReadHistoryData-page-35.data
#### STOPPING DOUBLE NULLS @ 158, found 1 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0x04 0x00 0x00 0x00 0x01 0x00 0x00 0x0b    ........
    0008   0x73 0x00 0x91 0x34 0x40 0xa7 0x0e 0x0a    s..4@...
    0010   0x5d 0x80 0x38 0x20 0x67 0x0e 0x3f 0x0b    ].8 g.?.
    0018   0x80 0x38 0xa0 0x67 0x0e 0x70 0x41 0x96    .8.g.pA.
##### DEBUG DECIMAL
              4    0    0    0    1    0    0   11
            115    0  145   52   64  167   14   10
             93  128   56   32  103   14   63   11
            128   56  160  103   14  112   65  150
#### RECORD 0 Bolus (2002, 0, 0, 0, 0, 20) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 2.0, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x00 0x14 0x00                        ....
    decimal
              1    0   20    0
    datetime ((2002, 0, 0, 0, 0, 20))
    0000   0x14 0x00 0x00 0x00 0x92                   .....
    body (0)
    YEAR BITS: [1, 0, 0, 1]
#### RECORD 1 Base (2008, 0, 5, 11, 14, 6) head[2], body[0] op[0x30]

    op hex (2)
    0000   0x30 0x54                                  0T
    decimal
             48   84
    datetime ((2008, 0, 5, 11, 14, 6))
    0000   0x06 0x0e 0x0b 0x65 0xc8                   ...e.
    body (0)
    DAY BITS: [0, 1, 1] YEAR BITS: [1, 1, 0, 0]
#### RECORD 2 Base (2000, 6, 1, 14, 38, 21) head[2], body[0] op[0x99]

    op hex (2)
    0000   0x99 0x10                                  ..
    decimal
            153   16
    datetime ((2000, 6, 1, 14, 38, 21))
    0000   0x55 0xa6 0x0e 0x01 0x00                   U....
    body (0)
    HOUR BITS: [1, 0, 1]
#### RECORD 3 ChangeBasalProfile (2002, 0, 0, 16, 0, 8) head[2], body[44] op[0x08]

    op hex (2)
    0000   0x08 0x00                                  ..
    decimal
              8    0
    datetime ((2002, 0, 0, 16, 0, 8))
    0000   0x08 0x00 0x10 0x00 0xa2                   .....
    body (44)
    hex
    0000   0x14 0x55 0x06 0x0e 0x0a 0xec 0xac 0x13    .U......
    0008   0x36 0x66 0x0e 0x3f 0x1d 0xac 0x13 0x96    6f.?....
    0010   0x66 0x0e 0x70 0x41 0x96 0x5b 0x83 0x92    f.pA.[..
    0018   0x14 0x16 0x66 0x0e 0x00 0x90 0x00 0x8c    ..f.....
    0020   0x19 0x38 0x54 0x00 0x00 0x00 0x00 0x08    .8T.....
    0028   0x00 0x4c 0x4e 0x5c                        .LN\
    decimal
             20   85    6   14   10  236  172   19
             54  102   14   63   29  172   19  150
            102   14  112   65  150   91  131  146
             20   22  102   14    0  144    0  140
             25   56   84    0    0    0    0    8
              0   76   78   92
    YEAR BITS: [1, 0, 1, 0]
#### RECORD 4 ChangeBasalProfile (2000, 2, 28, 20, 0, 62) head[2], body[44] op[0x08]

    op hex (2)
    0000   0x08 0x08                                  ..
    decimal
              8    8
    datetime ((2000, 2, 28, 20, 0, 62))
    0000   0x3e 0x80 0x14 0x5c 0x80                   >..\.
    body (44)
    hex
    0000   0x01 0x00 0x28 0x00 0x28 0x00 0x08 0x00    ..(.(...
    0008   0x92 0x14 0x56 0x66 0x0e 0x7b 0x00 0x80    ..Vf.{..
    0010   0x00 0x00 0x07 0x0e 0x00 0x14 0x00 0x07    ........
    0018   0x00 0x00 0x03 0x14 0x86 0x0e 0x00 0x00    ........
    0020   0x00 0x6e 0x86 0x0e 0x06 0x00 0x93 0x42    .n.....B
    0028   0xec 0x04 0x00 0x00                        ....
    decimal
              1    0   40    0   40    0    8    0
            146   20   86  102   14  123    0  128
              0    0    7   14    0   20    0    7
              0    0    3   20  134   14    0    0
              0  110  134   14    6    0  147   66
            236    4    0    0
    HOUR BITS: [1, 0, 0] DAY BITS: [0, 1, 0] YEAR BITS: [1, 0, 0, 0]
#### RECORD 5 Prime (2015, 1, 0, 10, 8, 1) head[5], body[0] op[0x03]
###### DECODED
```python
{'amount': 5.8, 'fixed': 0.1, 'type': 'fixed'}
```
    op hex (5)
    0000   0x03 0x14 0x01 0xcc 0x3a                   ....:
    decimal
              3   20    1  204   58
    datetime ((2015, 1, 0, 10, 8, 1))
    0000   0x01 0x48 0x2a 0x00 0x1f                   .H*..
    body (0)
    HOUR BITS: [0, 1, 0] YEAR BITS: [0, 0, 0, 1]
#### RECORD 6 Base (2000, 0, 0, 0, 52, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0xb0                                  ..
    decimal
              0  176
    datetime ((2000, 0, 0, 0, 52, 0))
    0000   0x00 0x34 0x00 0x00 0x00                   .4...
    body (0)
    HOUR BITS: [0, 0, 1]
#### RECORD 7 ChangeTimeDisplay (2014, 0, 0, 5, 0, 2) head[2], body[0] op[0x64]

    op hex (2)
    0000   0x64 0x01                                  d.
    decimal
            100    1
    datetime ((2014, 0, 0, 5, 0, 2))
    0000   0x02 0x00 0x05 0x00 0xae                   .....
    body (0)
    YEAR BITS: [1, 0, 1, 0]
#### RECORD 8 Base (2002, 3, 0, 8, 62, 0) head[2], body[0] op[0x11]

    op hex (2)
    0000   0x11 0x53                                  .S
    decimal
             17   83
    datetime ((2002, 3, 0, 8, 62, 0))
    0000   0x00 0xfe 0x28 0x00 0x02                   ..(..
    body (0)
    HOUR BITS: [1, 1, 1]
`end logs/ReadHistoryData-page-35.data: 9 records`
