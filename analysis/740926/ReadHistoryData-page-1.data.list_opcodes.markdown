## START logs/ReadHistoryData-page-1.data
#### STOPPING DOUBLE NULLS @ 223, found 2 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0x54 0x4e 0x5c 0x08 0x08 0x9b 0x90 0x50    TN\....P
    0008   0xc3 0x90 0x01 0x00 0x28 0x00 0x28 0x00    ....(.(.
    0010   0x00 0x00 0x98 0x9d 0x49 0x07 0x0e 0x19    ....I...
    0018   0x00 0x80 0x81 0x0a 0x07 0x0e 0x01 0x00    ........
##### DEBUG DECIMAL
             84   78   92    8    8  155  144   80
            195  144    1    0   40    0   40    0
              0    0  152  157   73    7   14   25
              0  128  129   10    7   14    1    0
#### RECORD 0 Sara6E 2014-10-07T00:00:00 head[1], body[49] op[0x6e]

    op hex (1)
    0000   0x6e                                       n
    decimal
            110
    datetime (2014-10-07T00:00:00)
    0000   0xa6 0x0e                                  ..
    body (49)
    hex
    0000   0x06 0x00 0x83 0x5f 0xcb 0x03 0x00 0x00    ..._....
    0008   0x05 0x40 0x01 0xd4 0x23 0x03 0x6c 0x41    .@..#.lA
    0010   0x00 0x81 0x01 0x3c 0x00 0x00 0x00 0xe0    ...<....
    0018   0x01 0x50 0x02 0x00 0x01 0x0b 0x00 0x98    .P......
    0020   0x17 0x4c 0x00 0x20 0x3a 0x00 0x04 0x00    .L. :...
    0028   0x00 0x01 0x05 0x01 0x00 0x00 0x00 0x00    ........
    0030   0x00                                       .
    decimal
              6    0  131   95  203    3    0    0
              5   64    1  212   35    3  108   65
              0  129    1   60    0    0    0  224
              1   80    2    0    1   11    0  152
             23   76    0   32   58    0    4    0
              0    1    5    1    0    0    0    0
              0

#### RECORD 1 CalBGForPH 2014-10-07T00:26:55 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 178}
```
    op hex (2)
    0000   0x0a 0xb2                                  ..
    decimal
             10  178
    datetime (2014-10-07T00:26:55)
    0000   0xb7 0x9a 0x20 0x67 0x0e                   .. g.
    body (0)
    HOUR BITS: [1, 0, 0] DAY BITS: [0, 1, 1]
#### RECORD 2 Ian3F 2014-10-07T00:26:55 head[2], body[3] op[0x3f]

    op hex (2)
    0000   0x3f 0x16                                  ?.
    decimal
             63   22
    datetime (2014-10-07T00:26:55)
    0000   0xb7 0x9a 0x40 0x67 0x0e                   ..@g.
    body (3)
    hex
    0000   0x70 0x41 0x96                             pA.
    decimal
            112   65  150
    HOUR BITS: [1, 0, 0] DAY BITS: [0, 1, 1]
#### RECORD 3 BolusWizard 2014-10-07T01:59:49 head[2], body[13] op[0x5b]
###### DECODED
```python
{'_byte[5]': 56,
 '_byte[7]': 0,
 'bg': 0,
 'bg_target_high': 0,
 'bg_target_low': 28,
 'bolus_estimate': 0.0,
 'carb_input': 52,
 'carb_ratio': 0,
 'correction_estimate': 0.8,
 'food_estimate': 0.0,
 'sensitivity': 170,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 120}
```
    op hex (2)
    0000   0x5b 0x00                                  [.
    decimal
             91    0
    datetime (2014-10-07T01:59:49)
    0000   0xb1 0xbb 0x01 0x07 0x0e                   .....
    body (13)
    hex
    0000   0x34 0x90 0x00 0xaa 0x1c 0x38 0x00 0x00    4....8..
    0008   0x78 0x00 0x00 0x00 0x00                   x....
    decimal
             52  144    0  170   28   56    0    0
            120    0    0    0    0
    HOUR BITS: [1, 0, 1]
#### RECORD 4 Base (2000, 4, 17, 20, 29, 28) head[2], body[0] op[0x78]

    op hex (2)
    0000   0x78 0x4e                                  xN
    decimal
            120   78
    datetime ((2000, 4, 17, 20, 29, 28))
    0000   0x5c 0x1d 0x14 0xf1 0x80                   \....
    body (0)
    DAY BITS: [1, 1, 1] YEAR BITS: [1, 0, 0, 0]
#### RECORD 5 NewTimeSet 2010-08-16T03:22:00 head[2], body[0] op[0x18]

    op hex (2)
    0000   0x18 0xfb                                  ..
    decimal
             24  251
    datetime (2010-08-16T03:22:00)
    0000   0x80 0x16 0x23 0x90 0x1a                   ..#..
    body (0)
    DAY BITS: [1, 0, 0] YEAR BITS: [0, 0, 0, 1]
#### RECORD 6 Base (2005, 4, 8, 16, 55, 36) head[2], body[0] op[0x2d]

    op hex (2)
    0000   0x2d 0x90                                  -.
    decimal
             45  144
    datetime ((2005, 4, 8, 16, 55, 36))
    0000   0x64 0x37 0x90 0x08 0x55                   d7..U
    body (0)
    HOUR BITS: [0, 0, 1] YEAR BITS: [0, 1, 0, 1]
#### RECORD 7 Base (2000, 6, 5, 24, 16, 51) head[2], body[0] op[0x90]

    op hex (2)
    0000   0x90 0x50                                  .P
    decimal
            144   80
    datetime ((2000, 6, 5, 24, 16, 51))
    0000   0x73 0x90 0x38 0xa5 0x90                   s.8..
    body (0)
    HOUR BITS: [1, 0, 0] DAY BITS: [1, 0, 1] YEAR BITS: [1, 0, 0, 1]
#### RECORD 8 Base (2000, 8, 16, 0, 1, 16) head[2], body[0] op[0xe0]

    op hex (2)
    0000   0xe0 0xb9                                  ..
    decimal
            224  185
    datetime ((2000, 8, 16, 0, 1, 16))
    0000   0x90 0x01 0x00 0x50 0x00                   ...P.
    body (0)
    DAY BITS: [0, 1, 0]
#### RECORD 9 Ian50 (2001, 0, 27, 17, 0, 0) head[2], body[34] op[0x50]

    op hex (2)
    0000   0x50 0x00                                  P.
    decimal
             80    0
    datetime ((2001, 0, 27, 17, 0, 0))
    0000   0x00 0x00 0xb1 0xbb 0x41                   ....A
    body (34)
    hex
    0000   0x07 0x0e 0x0b 0x65 0xf3 0x8e 0xa5 0x42    ...e...B
    0008   0xa7 0x0e 0x01 0x00 0x08 0x00 0x08 0x00    ........
    0010   0x34 0x00 0x9c 0xad 0x42 0x07 0x0e 0x0b    4...B...
    0018   0x65 0xf0 0x9c 0x92 0x46 0xa7 0x0e 0x0b    e...F...
    0020   0x65 0x10                                  e.
    decimal
              7   14   11  101  243  142  165   66
            167   14    1    0    8    0    8    0
             52    0  156  173   66    7   14   11
            101  240  156  146   70  167   14   11
            101   16
    DAY BITS: [1, 0, 1] YEAR BITS: [0, 1, 0, 0]
#### RECORD 10 Base (2001, 6, 27, 14, 39, 7) head[2], body[0] op[0xaa]

    op hex (2)
    0000   0xaa 0xaf                                  ..
    decimal
            170  175
    datetime ((2001, 6, 27, 14, 39, 7))
    0000   0x47 0xa7 0x8e 0x7b 0x01                   G..{.
    body (0)
    HOUR BITS: [1, 0, 1] DAY BITS: [0, 1, 1]
#### RECORD 11 Base (2011, 0, 16, 14, 7, 8) head[2], body[0] op[0x80]

    op hex (2)
    0000   0x80 0x80                                  ..
    decimal
            128  128
    datetime ((2011, 0, 16, 14, 7, 8))
    0000   0x08 0x07 0x0e 0x10 0x1b                   .....
    body (0)
    YEAR BITS: [0, 0, 0, 1]
#### RECORD 12 Base (2009, 4, 17, 14, 3, 37) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x0b                                  ..
    decimal
              0   11
    datetime ((2009, 4, 17, 14, 3, 37))
    0000   0x65 0x03 0x8e 0x91 0x49                   e...I
    body (0)
    DAY BITS: [1, 0, 0] YEAR BITS: [0, 1, 0, 0]
#### RECORD 13 Base (2009, 3, 29, 9, 54, 10) head[2], body[0] op[0xa7]

    op hex (2)
    0000   0xa7 0x8e                                  ..
    decimal
            167  142
    datetime ((2009, 3, 29, 9, 54, 10))
    0000   0x0a 0xf6 0x89 0x9d 0x29                   ....)
    body (0)
    HOUR BITS: [1, 1, 1] DAY BITS: [1, 0, 0] YEAR BITS: [0, 0, 1, 0]
#### RECORD 14 Base (2009, 0, 29, 9, 30, 63) head[2], body[0] op[0x67]

    op hex (2)
    0000   0x67 0x0e                                  g.
    decimal
            103   14
    datetime ((2009, 0, 29, 9, 30, 63))
    0000   0x3f 0x1e 0x89 0x9d 0xc9                   ?....
    body (0)
    DAY BITS: [1, 0, 0] YEAR BITS: [1, 1, 0, 0]
#### RECORD 15 Base (2009, 5, 27, 22, 1, 48) head[2], body[0] op[0x67]

    op hex (2)
    0000   0x67 0x0e                                  g.
    decimal
            103   14
    datetime ((2009, 5, 27, 22, 1, 48))
    0000   0x70 0x41 0x96 0x5b 0x89                   pA.[.
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 0] YEAR BITS: [1, 0, 0, 0]
#### RECORD 16 Base (2000, 0, 0, 14, 7, 9) head[2], body[0] op[0x98]

    op hex (2)
    0000   0x98 0x9d                                  ..
    decimal
            152  157
    datetime ((2000, 0, 0, 14, 7, 9))
    0000   0x09 0x07 0x0e 0x00 0x90                   .....
    body (0)
    YEAR BITS: [1, 0, 0, 1]
#### RECORD 17 Base (2000, 0, 0, 20, 56, 28) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0xaa                                  ..
    decimal
              0  170
    datetime ((2000, 0, 0, 20, 56, 28))
    0000   0x1c 0x38 0x54 0x00 0x00                   .8T..
    body (0)
    HOUR BITS: [0, 0, 1]
`end logs/ReadHistoryData-page-1.data: 18 records`
