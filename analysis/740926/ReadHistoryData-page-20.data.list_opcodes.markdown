## START logs/ReadHistoryData-page-20.data
#### STOPPING DOUBLE NULLS @ 175, found 0 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0x06 0x33 0x01 0xd3 0x1d 0x04 0x60 0x47    .3....`G
    0008   0x00 0x6a 0x00 0xf0 0x00 0x00 0x00 0x00    .j......
    0010   0x03 0x70 0x02 0x00 0x00 0x0c 0x00 0x9d    .p......
    0018   0x1f 0x40 0x05 0x20 0x40 0x00 0x09 0x41    .@. @..A
##### DEBUG DECIMAL
              6   51    1  211   29    4   96   71
              0  106    0  240    0    0    0    0
              3  112    2    0    0   12    0  157
             31   64    5   32   64    0    9   65
#### RECORD 0 PumpResume 2014-08-30T18:18:46 head[2], body[0] op[0x1f]

    op hex (2)
    0000   0x1f 0x20                                  . 
    decimal
             31   32
    datetime (2014-08-30T18:18:46)
    0000   0xae 0x12 0x12 0x1e 0x0e                   .....
    body (0)

#### RECORD 1 Bolus (2003, 0, 0, 8, 0, 12) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 1.2, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x00 0x0c 0x00                        ....
    decimal
              1    0   12    0
    datetime ((2003, 0, 0, 8, 0, 12))
    0000   0x0c 0x00 0x08 0x00 0xb3                   .....
    body (0)
    YEAR BITS: [1, 0, 1, 1]
#### RECORD 2 Base (2010, 0, 5, 11, 14, 30) head[2], body[0] op[0x12]

    op hex (2)
    0000   0x12 0x52                                  .R
    decimal
             18   82
    datetime ((2010, 0, 5, 11, 14, 30))
    0000   0x1e 0x0e 0x0b 0x65 0xca                   ...e.
    body (0)
    DAY BITS: [0, 1, 1] YEAR BITS: [1, 1, 0, 0]
#### RECORD 3 Base (2000, 6, 1, 14, 62, 18) head[2], body[0] op[0xae]

    op hex (2)
    0000   0xae 0x15                                  ..
    decimal
            174   21
    datetime ((2000, 6, 1, 14, 62, 18))
    0000   0x52 0xbe 0x0e 0x01 0x00                   R....
    body (0)
    HOUR BITS: [1, 0, 1]
#### RECORD 4 Base (2011, 4, 0, 4, 0, 48) head[2], body[0] op[0x70]

    op hex (2)
    0000   0x70 0x00                                  p.
    decimal
            112    0
    datetime ((2011, 4, 0, 4, 0, 48))
    0000   0x70 0x00 0x04 0x00 0xab                   p....
    body (0)
    YEAR BITS: [1, 0, 1, 0]
#### RECORD 5 TempBasal (2000, 0, 4, 27, 14, 30) head[2], body[1] op[0x33]
###### DECODED
```python
{'rate': 2.075}
```
    op hex (2)
    0000   0x33 0x53                                  3S
    decimal
             51   83
    datetime ((2000, 0, 4, 27, 14, 30))
    0000   0x1e 0x0e 0x7b 0x04 0x80                   ..{..
    body (1)
    hex
    0000   0x00                                       .
    decimal
              0
    YEAR BITS: [1, 0, 0, 0]
#### RECORD 6 SelectBasalProfile (2011, 0, 0, 29, 40, 14) head[2], body[0] op[0x14]

    op hex (2)
    0000   0x14 0x1e                                  ..
    decimal
             20   30
    datetime ((2011, 0, 0, 29, 40, 14))
    0000   0x0e 0x28 0x1d 0x00 0x0b                   .(...
    body (0)
    HOUR BITS: [0, 0, 1]
#### RECORD 7 Base (2014, 8, 30, 20, 13, 15) head[2], body[0] op[0x65]

    op hex (2)
    0000   0x65 0xc6                                  e.
    decimal
            101  198
    datetime ((2014, 8, 30, 20, 13, 15))
    0000   0x8f 0x0d 0x54 0xbe 0x0e                   ..T..
    body (0)
    DAY BITS: [1, 0, 1]
#### RECORD 8 Bolus 2003-08-04T04:00:52 head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 18.0, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x00 0xb4 0x00                        ....
    decimal
              1    0  180    0
    datetime (2003-08-04T04:00:52)
    0000   0xb4 0x00 0x44 0x04 0xa3                   ..D..
    body (0)
    YEAR BITS: [1, 0, 1, 0]
#### RECORD 9 Base (2000, 0, 0, 1, 14, 30) head[2], body[0] op[0x2a]

    op hex (2)
    0000   0x2a 0xb4                                  *.
    decimal
             42  180
    datetime ((2000, 0, 0, 1, 14, 30))
    0000   0x1e 0x0e 0x01 0x00 0xa0                   .....
    body (0)
    YEAR BITS: [1, 0, 1, 0]
#### RECORD 10 Base (2007, 1, 23, 0, 4, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0xa0                                  ..
    decimal
              0  160
    datetime ((2007, 1, 23, 0, 4, 0))
    0000   0x00 0x44 0x00 0xb7 0x27                   .D..'
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [1, 0, 1] YEAR BITS: [0, 0, 1, 0]
#### RECORD 11 Base (2000, 0, 28, 0, 1, 14) head[2], body[0] op[0x94]

    op hex (2)
    0000   0x94 0x1e                                  ..
    decimal
            148   30
    datetime ((2000, 0, 28, 0, 1, 14))
    0000   0x0e 0x01 0x00 0x3c 0x00                   ...<.
    body (0)
    DAY BITS: [0, 0, 1]
#### RECORD 12 Base (2004, 12, 24, 1, 0, 20) head[2], body[0] op[0x3c]

    op hex (2)
    0000   0x3c 0x00                                  <.
    decimal
             60    0
    datetime ((2004, 12, 24, 1, 0, 20))
    0000   0xd4 0x00 0x81 0x38 0x54                   ...8T
    body (0)
    DAY BITS: [0, 0, 1] YEAR BITS: [0, 1, 0, 1]
#### RECORD 13 PumpSuspend 2009-01-14T05:37:11 head[2], body[0] op[0x1e]

    op hex (2)
    0000   0x1e 0x0e                                  ..
    decimal
             30   14
    datetime (2009-01-14T05:37:11)
    0000   0x0b 0x65 0x05 0xae 0x29                   .e..)
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [1, 0, 1] YEAR BITS: [0, 0, 1, 0]
#### RECORD 14 Base (2000, 8, 8, 0, 1, 14) head[2], body[0] op[0x55]

    op hex (2)
    0000   0x55 0xbe                                  U.
    decimal
             85  190
    datetime ((2000, 8, 8, 0, 1, 14))
    0000   0x8e 0x01 0x00 0x28 0x00                   ...(.
    body (0)
    DAY BITS: [0, 0, 1]
#### RECORD 15 Base (2005, 8, 10, 14, 0, 44) head[2], body[0] op[0x28]

    op hex (2)
    0000   0x28 0x00                                  (.
    decimal
             40    0
    datetime ((2005, 8, 10, 14, 0, 44))
    0000   0xac 0x00 0x8e 0x2a 0x55                   ...*U
    body (0)
    DAY BITS: [0, 0, 1] YEAR BITS: [0, 1, 0, 1]
#### RECORD 16 PumpSuspend 2007-01-26T13:41:10 head[2], body[0] op[0x1e]

    op hex (2)
    0000   0x1e 0x0e                                  ..
    decimal
             30   14
    datetime (2007-01-26T13:41:10)
    0000   0x0a 0x69 0xad 0x1a 0x37                   .i..7
    body (0)
    HOUR BITS: [0, 1, 1] YEAR BITS: [0, 0, 1, 1]
#### RECORD 17 Base (2007, 0, 26, 13, 13, 63) head[2], body[0] op[0x7e]

    op hex (2)
    0000   0x7e 0x0e                                  ~.
    decimal
            126   14
    datetime ((2007, 0, 26, 13, 13, 63))
    0000   0x3f 0x0d 0xad 0x1a 0x37                   ?...7
    body (0)
    YEAR BITS: [0, 0, 1, 1]
#### RECORD 18 Base (2003, 5, 11, 22, 1, 48) head[2], body[0] op[0x7e]

    op hex (2)
    0000   0x7e 0x0e                                  ~.
    decimal
            126   14
    datetime ((2003, 5, 11, 22, 1, 48))
    0000   0x70 0x41 0x96 0x0b 0x73                   pA..s
    body (0)
    HOUR BITS: [0, 1, 0] YEAR BITS: [0, 1, 1, 1]
#### RECORD 19 Base (2011, 1, 14, 30, 23, 33) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x8f                                  ..
    decimal
              0  143
    datetime ((2011, 1, 14, 30, 23, 33))
    0000   0x21 0x57 0xbe 0x0e 0x7b                   !W..{
    body (0)
    HOUR BITS: [0, 1, 0] YEAR BITS: [0, 1, 1, 1]
#### RECORD 20 Base (2000, 0, 14, 31, 0, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x80                                  ..
    decimal
              0  128
    datetime ((2000, 0, 14, 31, 0, 0))
    0000   0x00 0x00 0x1f 0x0e 0x00                   .....
    body (0)

#### RECORD 21 SelectBasalProfile (2003, 0, 6, 0, 0, 7) head[2], body[0] op[0x14]

    op hex (2)
    0000   0x14 0x00                                  ..
    decimal
             20    0
    datetime ((2003, 0, 6, 0, 0, 7))
    0000   0x07 0x00 0x00 0x06 0x33                   ....3
    body (0)
    YEAR BITS: [0, 0, 1, 1]
#### RECORD 22 Base (2014, 0, 14, 0, 0, 0) head[2], body[0] op[0x9e]

    op hex (2)
    0000   0x9e 0x0e                                  ..
    decimal
            158   14
    datetime ((2014, 0, 14, 0, 0, 0))
    0000   0x00 0x00 0x00 0x6e 0x9e                   ...n.
    body (0)
    DAY BITS: [0, 1, 1] YEAR BITS: [1, 0, 0, 1]
#### RECORD 23 Base (2004, 1, 4, 23, 41, 0) head[2], body[0] op[0x0e]

    op hex (2)
    0000   0x0e 0x06                                  ..
    decimal
             14    6
    datetime ((2004, 1, 4, 23, 41, 0))
    0000   0x00 0x69 0x57 0xa4 0x04                   .iW..
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [1, 0, 1]
`end logs/ReadHistoryData-page-20.data: 24 records`
