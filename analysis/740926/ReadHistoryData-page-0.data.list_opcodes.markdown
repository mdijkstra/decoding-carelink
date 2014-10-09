## START logs/ReadHistoryData-page-0.data
#### STOPPING DOUBLE NULLS @ 146, found 0 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0x84 0x4e 0x5c 0x08 0x0c 0xf3 0x80 0x18    .N\.....
    0008   0x2f 0x90 0x01 0x00 0x48 0x00 0x48 0x00    /...H.H.
    0010   0x00 0x00 0xa2 0x9f 0x40 0x09 0x0e 0x0a    ....@...
    0018   0x46 0x9f 0xa6 0x20 0x69 0x0e 0x3f 0x08    F.. i.?.
##### DEBUG DECIMAL
            132   78   92    8   12  243  128   24
             47  144    1    0   72    0   72    0
              0    0  162  159   64    9   14   10
             70  159  166   32  105   14   63    8
#### RECORD 0 Bolus (2010, 0, 0, 12, 0, 12) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 1.2, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x00 0x0c 0x00                        ....
    decimal
              1    0   12    0
    datetime ((2010, 0, 0, 12, 0, 12))
    0000   0x0c 0x00 0x0c 0x00 0xba                   .....
    body (0)
    YEAR BITS: [1, 0, 1, 1]
#### RECORD 1 Base (2000, 0, 19, 11, 14, 8) head[2], body[0] op[0xa4]

    op hex (2)
    0000   0xa4 0x54                                  .T
    decimal
            164   84
    datetime ((2000, 0, 19, 11, 14, 8))
    0000   0x08 0x0e 0x0b 0x73 0x00                   ...s.
    body (0)
    DAY BITS: [0, 1, 1]
#### RECORD 2 Base (2003, 6, 11, 14, 40, 22) head[2], body[0] op[0xa6]

    op hex (2)
    0000   0xa6 0x97                                  ..
    decimal
            166  151
    datetime ((2003, 6, 11, 14, 40, 22))
    0000   0x56 0xa8 0x0e 0x0b 0x73                   V...s
    body (0)
    HOUR BITS: [1, 0, 1] YEAR BITS: [0, 1, 1, 1]
#### RECORD 3 Base (2011, 9, 14, 8, 22, 42) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x92                                  ..
    decimal
              0  146
    datetime ((2011, 9, 14, 8, 22, 42))
    0000   0xaa 0x56 0xa8 0x0e 0x7b                   .V..{
    body (0)
    HOUR BITS: [0, 1, 0] YEAR BITS: [0, 1, 1, 1]
#### RECORD 4 Base (2000, 8, 14, 9, 0, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x80                                  ..
    decimal
              0  128
    datetime ((2000, 8, 14, 9, 0, 0))
    0000   0x80 0x00 0x09 0x0e 0x00                   .....
    body (0)

#### RECORD 5 SelectBasalProfile (2004, 0, 2, 0, 0, 7) head[2], body[0] op[0x14]

    op hex (2)
    0000   0x14 0x00                                  ..
    decimal
             20    0
    datetime ((2004, 0, 2, 0, 0, 7))
    0000   0x07 0x00 0x00 0x02 0xd4                   .....
    body (0)
    YEAR BITS: [1, 1, 0, 1]
#### RECORD 6 IanA8 2000-09-04T08:52:50 head[10], body[0] op[0xa8]

    op hex (10)
    0000   0xa8 0x0e 0x00 0x00 0x00 0x6e 0xa8 0x0e    .....n..
    0008   0x06 0x10                                  ..
    decimal
            168   14    0    0    0  110  168   14
              6   16
    datetime (2000-09-04T08:52:50)
    0000   0xb2 0x74 0x28 0x04 0x00                   .t(..
    body (0)
    HOUR BITS: [0, 1, 1]
#### RECORD 7 Base (2001, 12, 1, 20, 1, 20) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x02                                  ..
    decimal
              0    2
    datetime ((2001, 12, 1, 20, 1, 20))
    0000   0xd4 0x01 0xd4 0x41 0x01                   ...A.
    body (0)
    DAY BITS: [0, 1, 0]
#### RECORD 8 Base (2000, 0, 24, 0, 27, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x23                                  .#
    decimal
              0   35
    datetime ((2000, 0, 24, 0, 27, 0))
    0000   0x00 0x1b 0x00 0x18 0x00                   .....
    body (0)

#### RECORD 9 Ian50 (2001, 0, 1, 24, 0, 0) head[2], body[34] op[0x50]

    op hex (2)
    0000   0x50 0x00                                  P.
    decimal
             80    0
    datetime ((2001, 0, 1, 24, 0, 0))
    0000   0x00 0x00 0x98 0x01 0x01                   .....
    body (34)
    hex
    0000   0x00 0x02 0x00 0xa2 0x0b 0x59 0x00 0x20    .....Y. 
    0008   0x28 0x00 0x05 0x00 0x00 0x00 0x02 0x01    (.......
    0010   0x00 0x00 0x02 0x00 0x00 0x0b 0x73 0x00    ......s.
    0018   0x9c 0x92 0x40 0xa9 0x0e 0x0a 0x4c 0xa1    ..@...L.
    0020   0x92 0x20                                  . 
    decimal
              0    2    0  162   11   89    0   32
             40    0    5    0    0    0    2    1
              0    0    2    0    0   11  115    0
            156  146   64  169   14   10   76  161
            146   32

#### RECORD 10 Ian69 (2000, 0, 18, 1, 9, 63) head[2], body[2] op[0x69]

    op hex (2)
    0000   0x69 0x0e                                  i.
    decimal
            105   14
    datetime ((2000, 0, 18, 1, 9, 63))
    0000   0x3f 0x09 0xa1 0x92 0x80                   ?....
    body (2)
    hex
    0000   0x69 0x0e                                  i.
    decimal
            105   14
    DAY BITS: [1, 0, 0] YEAR BITS: [1, 0, 0, 0]
#### RECORD 11 Base (2015, 9, 1, 0, 27, 22) head[2], body[0] op[0x70]

    op hex (2)
    0000   0x70 0x41                                  pA
    decimal
            112   65
    datetime ((2015, 9, 1, 0, 27, 22))
    0000   0x96 0x5b 0x00 0xa1 0x9f                   .[...
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [1, 0, 1] YEAR BITS: [1, 0, 0, 1]
#### RECORD 12 Base (2010, 0, 0, 16, 57, 14) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x09                                  ..
    decimal
              0    9
    datetime ((2010, 0, 0, 16, 57, 14))
    0000   0x0e 0x39 0x90 0x00 0xaa                   .9...
    body (0)
    HOUR BITS: [0, 0, 1] YEAR BITS: [1, 0, 1, 0]
#### RECORD 13 Base (2000, 0, 0, 4, 0, 0) head[2], body[0] op[0x1c]

    op hex (2)
    0000   0x1c 0x38                                  .8
    decimal
             28   56
    datetime ((2000, 0, 0, 4, 0, 0))
    0000   0x00 0x00 0x84 0x00 0x00                   .....
    body (0)

`end logs/ReadHistoryData-page-0.data: 14 records`
