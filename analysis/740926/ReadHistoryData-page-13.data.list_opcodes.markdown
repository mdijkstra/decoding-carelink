## START logs/ReadHistoryData-page-13.data
#### STOPPING DOUBLE NULLS @ 53, found 1 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0x6e 0x8d 0x8e 0x06 0x40 0xd9 0x9b 0xbf    n...@...
    0008   0x03 0x00 0x00 0x04 0xb2 0x01 0xd4 0x27    .......'
    0010   0x02 0xde 0x3d 0x00 0x62 0x01 0x14 0x00    ..=.b...
    0018   0x7a 0x00 0x00 0x01 0x50 0x02 0x01 0x00    z...P...
##### DEBUG DECIMAL
            110  141  142    6   64  217  155  191
              3    0    0    4  178    1  212   39
              2  222   61    0   98    1   20    0
            122    0    0    1   80    2    1    0
#### RECORD 0 Bolus (2002, 4, 0, 28, 0, 44) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 10.8, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x00 0x6c 0x00                        ..l.
    decimal
              1    0  108    0
    datetime ((2002, 4, 0, 28, 0, 44))
    0000   0x6c 0x00 0x1c 0x00 0xb2                   l....
    body (0)
    YEAR BITS: [1, 0, 1, 1]
#### RECORD 1 Base (2004, 0, 0, 1, 14, 13) head[2], body[0] op[0x40]

    op hex (2)
    0000   0x40 0x57                                  @W
    decimal
             64   87
    datetime ((2004, 0, 0, 1, 14, 13))
    0000   0x0d 0x0e 0x01 0x00 0x14                   .....
    body (0)
    YEAR BITS: [0, 0, 0, 1]
#### RECORD 2 Base (2008, 2, 24, 0, 4, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x14                                  ..
    decimal
              0   20
    datetime ((2008, 2, 24, 0, 4, 0))
    0000   0x00 0x84 0x00 0x98 0x48                   ....H
    body (0)
    HOUR BITS: [1, 0, 0] DAY BITS: [1, 0, 0] YEAR BITS: [0, 1, 0, 0]
#### RECORD 3 Base (2000, 0, 26, 5, 11, 14) head[2], body[0] op[0x57]

    op hex (2)
    0000   0x57 0x0d                                  W.
    decimal
             87   13
    datetime ((2000, 0, 26, 5, 11, 14))
    0000   0x0e 0x0b 0x65 0xda 0xa0                   ..e..
    body (0)
    DAY BITS: [1, 1, 0] YEAR BITS: [1, 0, 1, 0]
#### RECORD 4 Base (2000, 8, 0, 27, 14, 45) head[2], body[0] op[0x76]

    op hex (2)
    0000   0x76 0x57                                  vW
    decimal
            118   87
    datetime ((2000, 8, 0, 27, 14, 45))
    0000   0xad 0x0e 0x7b 0x00 0x80                   ..{..
    body (0)
    YEAR BITS: [1, 0, 0, 0]
#### RECORD 5 Base (2000, 0, 20, 0, 14, 14) head[2], body[0] op[0x40]

    op hex (2)
    0000   0x40 0x00                                  @.
    decimal
             64    0
    datetime ((2000, 0, 20, 0, 14, 14))
    0000   0x0e 0x0e 0x00 0x14 0x00                   .....
    body (0)

#### RECORD 6 MResultTotals 2014-09-14T00:00:00 head[5], body[0] op[0x07]

    op hex (5)
    0000   0x07 0x00 0x00 0x04 0xb2                   .....
    decimal
              7    0    0    4  178
    datetime (2014-09-14T00:00:00)
    0000   0x8d 0x8e                                  ..
    body (0)
    HOUR BITS: [1, 0, 0]
`end logs/ReadHistoryData-page-13.data: 7 records`
