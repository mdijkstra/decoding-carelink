## START logs/ReadHistoryData-page-12.data
#### STOPPING DOUBLE NULLS @ 253, found 1 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0x6e 0x8f 0x8e 0x06 0x10 0xcd 0x59 0x12    n.....Y.
    0008   0x05 0x00 0x00 0x07 0x70 0x01 0xd4 0x19    ....p...
    0010   0x05 0x9c 0x4b 0x00 0xbc 0x00 0x64 0x00    ..K...d.
    0018   0xb0 0x03 0x18 0x01 0x70 0x01 0x02 0x02    ....p...
##### DEBUG DECIMAL
            110  143  142    6   16  205   89   18
              5    0    0    7  112    1  212   25
              5  156   75    0  188    0  100    0
            176    3   24    1  112    1    2    2
#### RECORD 0 UnabsorbedInsulinBolus unknown head[17], body[0] op[0x5c]
###### DECODED
```python
[{'age': 61, 'amount': 2.0, 'curve': 128},
 {'age': 91, 'amount': 2.5, 'curve': 128},
 {'age': 15, 'amount': 1.7, 'curve': 144},
 {'age': 25, 'amount': 0.9, 'curve': 144},
 {'age': 215, 'amount': 0.5, 'curve': 144}]
```
    op hex (17)
    0000   0x5c 0x11 0x50 0x3d 0x80 0x64 0x5b 0x80    \.P=.d[.
    0008   0x44 0x0f 0x90 0x24 0x19 0x90 0x14 0xd7    D..$....
    0010   0x90                                       .
    decimal
             92   17   80   61  128  100   91  128
             68   15  144   36   25  144   20  215
            144
    datetime (unknown)

    body (0)

#### RECORD 1 Bolus (2002, 0, 0, 24, 0, 0) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.2, 'dual_component': '??', 'programmed': 0.0, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x02 0x00 0x02                        ....
    decimal
              1    2    0    2
    datetime ((2002, 0, 0, 24, 0, 0))
    0000   0x00 0x00 0x38 0x00 0x82                   ..8..
    body (0)
    YEAR BITS: [1, 0, 0, 0]
#### RECORD 2 Base (2000, 0, 2, 27, 14, 15) head[2], body[0] op[0x71]

    op hex (2)
    0000   0x71 0x4b                                  qK
    decimal
            113   75
    datetime ((2000, 0, 2, 27, 14, 15))
    0000   0x0f 0x0e 0x7b 0x02 0x80                   ..{..
    body (0)
    YEAR BITS: [1, 0, 0, 0]
#### RECORD 3 Base (2000, 0, 6, 24, 14, 15) head[2], body[0] op[0x40]

    op hex (2)
    0000   0x40 0x0c                                  @.
    decimal
             64   12
    datetime ((2000, 0, 6, 24, 14, 15))
    0000   0x0f 0x0e 0x18 0x06 0x00                   .....
    body (0)

#### RECORD 4 Ian0B 2014-09-15T12:17:26 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x65 0x3f                             .e?
    decimal
             11  101   63
    datetime (2014-09-15T12:17:26)
    0000   0x9a 0x51 0x4c 0xaf 0x8e                   .QL..
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [1, 0, 1] YEAR BITS: [1, 0, 0, 0]
#### RECORD 5 Bolus (2012, 0, 0, 0, 1, 60) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 6.0, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x00 0x3c 0x00                        ..<.
    decimal
              1    0   60    0
    datetime ((2012, 0, 0, 0, 1, 60))
    0000   0x3c 0x01 0xc0 0x00 0xac                   <....
    body (0)
    YEAR BITS: [1, 0, 1, 0]
#### RECORD 6 Base (2008, 0, 0, 1, 14, 15) head[2], body[0] op[0x51]

    op hex (2)
    0000   0x51 0x4c                                  QL
    decimal
             81   76
    datetime ((2008, 0, 0, 1, 14, 15))
    0000   0x0f 0x0e 0x01 0x00 0x78                   ....x
    body (0)
    YEAR BITS: [0, 1, 1, 1]
#### RECORD 7 Base (2004, 1, 11, 0, 44, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x78                                  .x
    decimal
              0  120
    datetime ((2004, 1, 11, 0, 44, 0))
    0000   0x00 0x6c 0x00 0x8b 0x54                   .l..T
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [1, 0, 0] YEAR BITS: [0, 1, 0, 1]
#### RECORD 8 Base (2000, 0, 8, 0, 1, 14) head[2], body[0] op[0x4d]

    op hex (2)
    0000   0x4d 0x0f                                  M.
    decimal
             77   15
    datetime ((2000, 0, 8, 0, 1, 14))
    0000   0x0e 0x01 0x00 0x08 0x00                   .....
    body (0)

#### RECORD 9 ChangeBasalProfile 2013-08-14T05:00:12 head[2], body[44] op[0x08]

    op hex (2)
    0000   0x08 0x00                                  ..
    decimal
              8    0
    datetime (2013-08-14T05:00:12)
    0000   0x8c 0x00 0xa5 0x6e 0x4d                   ...nM
    body (44)
    hex
    0000   0x0f 0x0e 0x0b 0x65 0x2f 0xa3 0x6f 0x4d    ...e/.oM
    0008   0xaf 0x8e 0x0b 0x73 0x00 0xa3 0x47 0x4f    ...s..GO
    0010   0xaf 0x0e 0x0a 0x59 0xa1 0x4e 0x31 0x6f    ...Y.N1o
    0018   0x0e 0x3f 0x0b 0xa1 0x4e 0x31 0x6f 0x0e    .?..N1o.
    0020   0x70 0x41 0x96 0x0a 0x2d 0x90 0x78 0x51    pA..-.xQ
    0028   0x0f 0x0e 0x5b 0x2d                        ..[-
    decimal
             15   14   11  101   47  163  111   77
            175  142   11  115    0  163   71   79
            175   14   10   89  161   78   49  111
             14   63   11  161   78   49  111   14
            112   65  150   10   45  144  120   81
             15   14   91   45
    DAY BITS: [0, 1, 1] YEAR BITS: [0, 1, 0, 0]
#### RECORD 10 Base (2000, 1, 4, 14, 47, 17) head[2], body[0] op[0xa3]

    op hex (2)
    0000   0xa3 0x78                                  .x
    decimal
            163  120
    datetime ((2000, 1, 4, 14, 47, 17))
    0000   0x11 0x6f 0x0e 0x64 0x90                   .o.d.
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 1, 1] YEAR BITS: [1, 0, 0, 1]
#### RECORD 11 Base (2008, 0, 0, 12, 56, 25) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0xc8                                  ..
    decimal
              0  200
    datetime ((2008, 0, 0, 12, 56, 25))
    0000   0x19 0x38 0xec 0x00 0xc8                   .8...
    body (0)
    HOUR BITS: [0, 0, 1] YEAR BITS: [1, 1, 0, 0]
#### RECORD 12 Base (2012, 0, 14, 20, 0, 0) head[2], body[0] op[0xf8]

    op hex (2)
    0000   0xf8 0x00                                  ..
    decimal
            248    0
    datetime ((2012, 0, 14, 20, 0, 0))
    0000   0x00 0x00 0xb4 0x4e 0x5c                   ...N\
    body (0)
    DAY BITS: [0, 1, 0] YEAR BITS: [0, 1, 0, 1]
#### RECORD 13 ChangeTime (2000, 2, 22, 24, 16, 2) head[2], body[0] op[0x17]

    op hex (2)
    0000   0x17 0x08                                  ..
    decimal
             23    8
    datetime ((2000, 2, 22, 24, 16, 2))
    0000   0x02 0x90 0x78 0x16 0x90                   ..x..
    body (0)
    HOUR BITS: [1, 0, 0] YEAR BITS: [1, 0, 0, 1]
#### RECORD 14 Base (2000, 8, 16, 28, 16, 16) head[2], body[0] op[0x2c]

    op hex (2)
    0000   0x2c 0x52                                  ,R
    decimal
             44   82
    datetime ((2000, 8, 16, 28, 16, 16))
    0000   0x90 0x10 0x5c 0x90 0x00                   ..\..
    body (0)
    DAY BITS: [1, 0, 0]
#### RECORD 15 Base (2010, 6, 4, 16, 44, 16) head[2], body[0] op[0x70]

    op hex (2)
    0000   0x70 0x92                                  p.
    decimal
            112  146
    datetime ((2010, 6, 4, 16, 44, 16))
    0000   0x50 0xac 0x90 0x64 0xca                   P..d.
    body (0)
    HOUR BITS: [1, 0, 1] DAY BITS: [0, 1, 1] YEAR BITS: [1, 1, 0, 0]
#### RECORD 16 Base (2015, 2, 18, 0, 0, 3) head[2], body[0] op[0x90]

    op hex (2)
    0000   0x90 0x7b                                  .{
    decimal
            144  123
    datetime ((2015, 2, 18, 0, 0, 3))
    0000   0x03 0x80 0x40 0x12 0x0f                   ..@..
    body (0)
    HOUR BITS: [1, 0, 0]
#### RECORD 17 Base (2008, 0, 1, 1, 0, 24) head[2], body[0] op[0x0e]

    op hex (2)
    0000   0x0e 0x24                                  .$
    decimal
             14   36
    datetime ((2008, 0, 1, 1, 0, 24))
    0000   0x18 0x00 0x01 0x01 0x18                   .....
    body (0)
    YEAR BITS: [0, 0, 0, 1]
#### RECORD 18 Bolus (2015, 2, 17, 24, 35, 0) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 2.4, 'dual_component': '??', 'programmed': 0.0, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x18 0x00 0x00                        ....
    decimal
              1   24    0    0
    datetime ((2015, 2, 17, 24, 35, 0))
    0000   0x00 0xa3 0x78 0x51 0x6f                   ..xQo
    body (0)
    HOUR BITS: [1, 0, 1] DAY BITS: [0, 1, 0] YEAR BITS: [0, 1, 1, 0]
#### RECORD 19 Base (2000, 1, 16, 0, 16, 0) head[2], body[0] op[0x0e]

    op hex (2)
    0000   0x0e 0x01                                  ..
    decimal
             14    1
    datetime ((2000, 1, 16, 0, 16, 0))
    0000   0x00 0x50 0x00 0x50 0x00                   .P.P.
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 0]
#### RECORD 20 ChangeTimeDisplay 2014-09-15T19:04:17 head[2], body[0] op[0x64]

    op hex (2)
    0000   0x64 0x00                                  d.
    decimal
            100    0
    datetime (2014-09-15T19:04:17)
    0000   0x91 0x44 0x53 0x0f 0x0e                   .DS..
    body (0)
    HOUR BITS: [0, 1, 0]
#### RECORD 21 BasalProfileStart 2014-09-15T20:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x04                                  {.
    decimal
            123    4
    datetime (2014-09-15T20:00:00)
    0000   0x80 0x40 0x14 0x0f 0x0e                   .@...
    body (3)
    hex
    0000   0x28 0x1d 0x00                             (..
    decimal
             40   29    0
    HOUR BITS: [0, 1, 0]
#### RECORD 22 Ian0B 2014-09-15T20:03:45 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x73 0x00                             .s.
    decimal
             11  115    0
    datetime (2014-09-15T20:03:45)
    0000   0xad 0x43 0x54 0xaf 0x0e                   .CT..
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [1, 0, 1]
#### RECORD 23 Ian0B 2014-09-15T20:22:31 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x73 0x00                             .s.
    decimal
             11  115    0
    datetime (2014-09-15T20:22:31)
    0000   0x9f 0x56 0x54 0xaf 0x0e                   .VT..
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [1, 0, 1]
#### RECORD 24 BasalProfileStart 2014-09-16T00:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x00                                  {.
    decimal
            123    0
    datetime (2014-09-16T00:00:00)
    0000   0x80 0x40 0x00 0x10 0x0e                   .@...
    body (3)
    hex
    0000   0x00 0x14 0x00                             ...
    decimal
              0   20    0
    HOUR BITS: [0, 1, 0]
#### RECORD 25 MResultTotals 2014-09-16T00:00:00 head[5], body[0] op[0x07]

    op hex (5)
    0000   0x07 0x00 0x00 0x07 0x70                   ....p
    decimal
              7    0    0    7  112
    datetime (2014-09-16T00:00:00)
    0000   0x8f 0x8e                                  ..
    body (0)
    HOUR BITS: [1, 0, 0]
`end logs/ReadHistoryData-page-12.data: 26 records`
