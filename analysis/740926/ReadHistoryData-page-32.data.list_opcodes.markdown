## START logs/ReadHistoryData-page-32.data
#### STOPPING DOUBLE NULLS @ 206, found 1 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0xd4 0x4e 0x5c 0x0e 0x3c 0xac 0x80 0x30    .N\.<..0
    0008   0x06 0x90 0x50 0x24 0x90 0x1c 0xce 0x91    ..P$....
    0010   0x01 0x00 0xd4 0x00 0xd4 0x00 0x00 0x00    ........
    0018   0xb9 0x14 0x53 0x0b 0x0e 0x01 0x00 0x28    ..S....(
##### DEBUG DECIMAL
            212   78   92   14   60  172  128   48
              6  144   80   36  144   28  206  145
              1    0  212    0  212    0    0    0
            185   20   83   11   14    1    0   40
#### RECORD 0 BolusWizard 2014-08-11T11:38:49 head[2], body[13] op[0x5b]
###### DECODED
```python
{'_byte[5]': 56,
 '_byte[7]': 1,
 'bg': 0,
 'bg_target_high': 1,
 'bg_target_low': 12,
 'bolus_estimate': 0.0,
 'carb_input': 50,
 'carb_ratio': 0,
 'correction_estimate': 0.9,
 'food_estimate': 0.0,
 'sensitivity': 70,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 28}
```
    op hex (2)
    0000   0x5b 0x00                                  [.
    decimal
             91    0
    datetime (2014-08-11T11:38:49)
    0000   0xb1 0x26 0x0b 0x0b 0x0e                   .&...
    body (13)
    hex
    0000   0x32 0x90 0x00 0x46 0x0c 0x38 0x00 0x01    2..F.8..
    0008   0x1c 0x00 0x00 0x00 0x01                   .....
    decimal
             50  144    0   70   12   56    0    1
             28    0    0    0    1
    HOUR BITS: [0, 0, 1]
#### RECORD 1 Base (2000, 4, 20, 16, 8, 28) head[2], body[0] op[0x1c]

    op hex (2)
    0000   0x1c 0x4e                                  .N
    decimal
             28   78
    datetime ((2000, 4, 20, 16, 8, 28))
    0000   0x5c 0x08 0x50 0x14 0x80                   \.P..
    body (0)
    YEAR BITS: [1, 0, 0, 0]
#### RECORD 2 Base (2001, 8, 28, 1, 1, 0) head[2], body[0] op[0x04]

    op hex (2)
    0000   0x04 0xa0                                  ..
    decimal
              4  160
    datetime ((2001, 8, 28, 1, 1, 0))
    0000   0x80 0x01 0x01 0x1c 0x01                   .....
    body (0)

#### RECORD 3 Base (2011, 4, 6, 17, 0, 12) head[2], body[0] op[0x1c]

    op hex (2)
    0000   0x1c 0x00                                  ..
    decimal
             28    0
    datetime ((2011, 4, 6, 17, 0, 12))
    0000   0x4c 0x00 0xb1 0x26 0x4b                   L..&K
    body (0)
    DAY BITS: [0, 0, 1] YEAR BITS: [0, 1, 0, 0]
#### RECORD 4 Ian0B 2011-02-12T00:00:02 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x0e 0x7b                             ..{
    decimal
             11   14  123
    datetime (2011-02-12T00:00:02)
    0000   0x02 0x80 0x00 0x0c 0x0b                   .....
    body (0)
    HOUR BITS: [1, 0, 0]
#### RECORD 5 Base (2004, 0, 22, 19, 0, 6) head[2], body[0] op[0x0e]

    op hex (2)
    0000   0x0e 0x18                                  ..
    decimal
             14   24
    datetime ((2004, 0, 22, 19, 0, 6))
    0000   0x06 0x00 0x33 0x96 0xa4                   ..3..
    body (0)
    DAY BITS: [1, 0, 0] YEAR BITS: [1, 0, 1, 0]
#### RECORD 6 Base (2004, 0, 22, 8, 14, 11) head[2], body[0] op[0x3a]

    op hex (2)
    0000   0x3a 0x0c                                  :.
    decimal
             58   12
    datetime ((2004, 0, 22, 8, 14, 11))
    0000   0x0b 0x0e 0x08 0x16 0x14                   .....
    body (0)
    YEAR BITS: [0, 0, 0, 1]
#### RECORD 7 Base (2000, 0, 1, 14, 11, 12) head[2], body[0] op[0xa4]

    op hex (2)
    0000   0xa4 0x3a                                  .:
    decimal
            164   58
    datetime ((2000, 0, 1, 14, 11, 12))
    0000   0x0c 0x0b 0x0e 0x01 0x00                   .....
    body (0)

#### RECORD 8 Ian50 (2011, 4, 0, 0, 0, 16) head[2], body[34] op[0x50]

    op hex (2)
    0000   0x50 0x00                                  P.
    decimal
             80    0
    datetime ((2011, 4, 0, 0, 0, 16))
    0000   0x50 0x00 0x00 0x00 0x9b                   P....
    body (34)
    hex
    0000   0x22 0x4e 0x0b 0x0e 0x5b 0x00 0x93 0x25    "N..[..%
    0008   0x0e 0x0b 0x0e 0x4b 0x90 0x00 0xc8 0x0c    ...K....
    0010   0x38 0x00 0x00 0x94 0x00 0x00 0x00 0x00    8.......
    0018   0x94 0x4e 0x5c 0x0e 0x50 0x09 0x80 0x1c    .N\.P...
    0020   0xb3 0x81                                  ..
    decimal
             34   78   11   14   91    0  147   37
             14   11   14   75  144    0  200   12
             56    0    0  148    0    0    0    0
            148   78   92   14   80    9  128   28
            179  129
    YEAR BITS: [1, 0, 0, 1]
#### RECORD 9 Ian50 2011-08-16T19:04:00 head[2], body[34] op[0x50]

    op hex (2)
    0000   0x50 0xc7                                  P.
    decimal
             80  199
    datetime (2011-08-16T19:04:00)
    0000   0x80 0x04 0x53 0x90 0x5b                   ..S.[
    body (34)
    hex
    0000   0x00 0xbb 0x00 0x0f 0x6b 0x0e 0x19 0x90    ....k...
    0008   0x00 0xc8 0x19 0x38 0x00 0x00 0x30 0x00    ...8..0.
    0010   0x00 0x00 0x00 0x30 0x4e 0x5c 0x0e 0x50    ...0N\.P
    0018   0x20 0x80 0x1c 0xca 0x81 0x50 0xde 0x80     ....P..
    0020   0x04 0x6a                                  .j
    decimal
              0  187    0   15  107   14   25  144
              0  200   25   56    0    0   48    0
              0    0    0   48   78   92   14   80
             32  128   28  202  129   80  222  128
              4  106
    DAY BITS: [1, 0, 0] YEAR BITS: [0, 1, 0, 1]
#### RECORD 10 Base (2000, 0, 16, 0, 48, 0) head[2], body[0] op[0x90]

    op hex (2)
    0000   0x90 0x01                                  ..
    decimal
            144    1
    datetime ((2000, 0, 16, 0, 48, 0))
    0000   0x00 0x30 0x00 0x30 0x00                   .0.0.
    body (0)
    HOUR BITS: [0, 0, 1] DAY BITS: [0, 0, 1]
#### RECORD 11 Base (2014, 8, 11, 15, 0, 59) head[2], body[0] op[0x40]

    op hex (2)
    0000   0x40 0x00                                  @.
    decimal
             64    0
    datetime ((2014, 8, 11, 15, 0, 59))
    0000   0xbb 0x00 0x4f 0x6b 0x0e                   ..Ok.
    body (0)
    DAY BITS: [0, 1, 1]
#### RECORD 12 Ian0B 2014-08-11T16:30:55 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x65 0xc9                             .e.
    decimal
             11  101  201
    datetime (2014-08-11T16:30:55)
    0000   0xb7 0x1e 0x50 0xab 0x0e                   ..P..
    body (0)
    DAY BITS: [1, 0, 1]
#### RECORD 13 Bolus (2005, 0, 0, 8, 0, 60) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 6.0, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x00 0x3c 0x00                        ..<.
    decimal
              1    0   60    0
    datetime ((2005, 0, 0, 8, 0, 60))
    0000   0x3c 0x00 0x08 0x00 0x95                   <....
    body (0)
    YEAR BITS: [1, 0, 0, 1]
#### RECORD 14 PumpResume (2009, 0, 0, 27, 14, 11) head[2], body[0] op[0x1f]

    op hex (2)
    0000   0x1f 0x50                                  .P
    decimal
             31   80
    datetime ((2009, 0, 0, 27, 14, 11))
    0000   0x0b 0x0e 0x5b 0x00 0xb9                   ..[..
    body (0)
    YEAR BITS: [1, 0, 1, 1]
#### RECORD 15 SelectBasalProfile (2000, 0, 16, 11, 14, 11) head[2], body[0] op[0x14]

    op hex (2)
    0000   0x14 0x13                                  ..
    decimal
             20   19
    datetime ((2000, 0, 16, 11, 14, 11))
    0000   0x0b 0x0e 0x4b 0x90 0x00                   ..K..
    body (0)
    DAY BITS: [1, 0, 0]
#### RECORD 16 Base (2000, 0, 20, 0, 0, 56) head[2], body[0] op[0x8c]

    op hex (2)
    0000   0x8c 0x19                                  ..
    decimal
            140   25
    datetime ((2000, 0, 20, 0, 0, 56))
    0000   0x38 0x00 0x00 0xd4 0x00                   8....
    body (0)
    DAY BITS: [1, 1, 0]
`end logs/ReadHistoryData-page-32.data: 17 records`
