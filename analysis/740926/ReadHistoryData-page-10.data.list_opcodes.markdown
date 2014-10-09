## START logs/ReadHistoryData-page-10.data
#### STOPPING DOUBLE NULLS @ 541, found 0 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0x06 0x04 0x01 0xd4 0x1e 0x04 0x30 0x46    ......0F
    0008   0x01 0x15 0x02 0xd0 0x00 0x00 0x00 0x00    ........
    0010   0x01 0x60 0x06 0x00 0x00 0x06 0x04 0x94    .`......
    0018   0x15 0x4e 0x01 0x20 0x3b 0x00 0x05 0x00    .N. ;...
##### DEBUG DECIMAL
              6    4    1  212   30    4   48   70
              1   21    2  208    0    0    0    0
              1   96    6    0    0    6    4  148
             21   78    1   32   59    0    5    0
#### RECORD 0 CalBGForPH 2014-09-19T08:12:21 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 96}
```
    op hex (2)
    0000   0x0a 0x60                                  .`
    decimal
             10   96
    datetime (2014-09-19T08:12:21)
    0000   0x95 0x4c 0x28 0x73 0x0e                   .L(s.
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 1 Ian3F 2014-09-19T08:12:21 head[2], body[3] op[0x3f]

    op hex (2)
    0000   0x3f 0x0c                                  ?.
    decimal
             63   12
    datetime (2014-09-19T08:12:21)
    0000   0x95 0x4c 0x08 0x73 0x0e                   .L.s.
    body (3)
    hex
    0000   0x70 0x41 0x96                             pA.
    decimal
            112   65  150
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 2 BolusWizard 2014-09-19T08:32:44 head[2], body[13] op[0x5b]
###### DECODED
```python
{'_byte[5]': 56,
 '_byte[7]': 0,
 'bg': 0,
 'bg_target_high': 0,
 'bg_target_low': 28,
 'bolus_estimate': 0.0,
 'carb_input': 46,
 'carb_ratio': 0,
 'correction_estimate': 0.8,
 'food_estimate': 0.0,
 'sensitivity': 170,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 108}
```
    op hex (2)
    0000   0x5b 0x00                                  [.
    decimal
             91    0
    datetime (2014-09-19T08:32:44)
    0000   0xac 0x60 0x08 0x73 0x0e                   .`.s.
    body (13)
    hex
    0000   0x2e 0x90 0x00 0xaa 0x1c 0x38 0x00 0x00    .....8..
    0008   0x6c 0x00 0x00 0x00 0x00                   l....
    decimal
             46  144    0  170   28   56    0    0
            108    0    0    0    0
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 3 old6c (2000, 4, 6, 28, 5, 28) head[2], body[38] op[0x6c]

    op hex (2)
    0000   0x6c 0x4e                                  lN
    decimal
            108   78
    datetime ((2000, 4, 6, 28, 5, 28))
    0000   0x5c 0x05 0x3c 0xc6 0x90                   \.<..
    body (38)
    hex
    0000   0x01 0x00 0x6c 0x00 0x6c 0x00 0x00 0x00    ..l.l...
    0008   0xac 0x60 0x48 0x73 0x0e 0x5b 0x00 0xac    .`Hs.[..
    0010   0x68 0x08 0x73 0x0e 0x07 0x90 0x00 0xaa    h.s.....
    0018   0x1c 0x38 0x00 0x00 0x10 0x00 0x00 0x00    .8......
    0020   0x00 0x10 0x4e 0x5c 0x08 0x6c              ..N\.l
    decimal
              1    0  108    0  108    0    0    0
            172   96   72  115   14   91    0  172
            104    8  115   14    7  144    0  170
             28   56    0    0   16    0    0    0
              0   16   78   92    8  108
    DAY BITS: [1, 1, 0] YEAR BITS: [1, 0, 0, 1]
#### RECORD 4 ClearAlarm (2000, 3, 1, 16, 14, 60) head[2], body[0] op[0x0c]

    op hex (2)
    0000   0x0c 0x80                                  ..
    decimal
             12  128
    datetime ((2000, 3, 1, 16, 14, 60))
    0000   0x3c 0xce 0x90 0x01 0x00                   <....
    body (0)
    HOUR BITS: [1, 1, 0]
#### RECORD 5 Base (2012, 0, 0, 12, 0, 16) head[2], body[0] op[0x10]

    op hex (2)
    0000   0x10 0x00                                  ..
    decimal
             16    0
    datetime ((2012, 0, 0, 12, 0, 16))
    0000   0x10 0x00 0x6c 0x00 0xac                   ..l..
    body (0)
    YEAR BITS: [1, 0, 1, 0]
#### RECORD 6 Base (2008, 4, 0, 1, 14, 51) head[2], body[0] op[0x68]

    op hex (2)
    0000   0x68 0x48                                  hH
    decimal
            104   72
    datetime ((2008, 4, 0, 1, 14, 51))
    0000   0x73 0x0e 0x01 0x00 0x28                   s...(
    body (0)
    YEAR BITS: [0, 0, 1, 0]
#### RECORD 7 Base (2003, 1, 18, 0, 12, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x28                                  .(
    decimal
              0   40
    datetime ((2003, 1, 18, 0, 12, 0))
    0000   0x00 0x4c 0x00 0x92 0x53                   .L..S
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [1, 0, 0] YEAR BITS: [0, 1, 0, 1]
#### RECORD 8 Base (2000, 0, 28, 0, 1, 14) head[2], body[0] op[0x49]

    op hex (2)
    0000   0x49 0x13                                  I.
    decimal
             73   19
    datetime ((2000, 0, 28, 0, 1, 14))
    0000   0x0e 0x01 0x00 0x3c 0x00                   ...<.
    body (0)
    DAY BITS: [0, 0, 1]
#### RECORD 9 Base (2009, 4, 12, 7, 0, 8) head[2], body[0] op[0x3c]

    op hex (2)
    0000   0x3c 0x00                                  <.
    decimal
             60    0
    datetime ((2009, 4, 12, 7, 0, 8))
    0000   0x48 0x00 0xa7 0x6c 0x49                   H..lI
    body (0)
    DAY BITS: [0, 1, 1] YEAR BITS: [0, 1, 0, 0]
#### RECORD 10 Base (2003, 1, 12, 24, 37, 11) head[2], body[0] op[0x13]

    op hex (2)
    0000   0x13 0x0e                                  ..
    decimal
             19   14
    datetime ((2003, 1, 12, 24, 37, 11))
    0000   0x0b 0x65 0xd8 0xac 0x43                   .e..C
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [1, 0, 1] YEAR BITS: [0, 1, 0, 0]
#### RECORD 11 Base (2000, 0, 16, 0, 1, 14) head[2], body[0] op[0x4a]

    op hex (2)
    0000   0x4a 0xb3                                  J.
    decimal
             74  179
    datetime ((2000, 0, 16, 0, 1, 14))
    0000   0x0e 0x01 0x00 0x50 0x00                   ...P.
    body (0)
    DAY BITS: [0, 1, 0]
#### RECORD 12 Ian50 2010-04-04T00:00:36 head[2], body[34] op[0x50]

    op hex (2)
    0000   0x50 0x00                                  P.
    decimal
             80    0
    datetime (2010-04-04T00:00:36)
    0000   0x64 0x00 0x80 0x44 0x4a                   d..DJ
    body (34)
    hex
    0000   0x13 0x0e 0x0b 0x65 0xd7 0xba 0x60 0x4b    ...e..`K
    0008   0xb3 0x0e 0x5b 0x00 0xb0 0x67 0x0b 0x13    ..[..g..
    0010   0x0e 0x2e 0x90 0x00 0x46 0x0c 0x38 0x00    ....F.8.
    0018   0x01 0x04 0x00 0x00 0x00 0x01 0x04 0x4e    .......N
    0020   0x5c 0x11                                  \.
    decimal
             19   14   11  101  215  186   96   75
            179   14   91    0  176  103   11   19
             14   46  144    0   70   12   56    0
              1    4    0    0    0    1    4   78
             92   17
    DAY BITS: [0, 1, 0] YEAR BITS: [0, 1, 0, 0]
#### RECORD 13 Ian50 (2008, 8, 0, 25, 60, 0) head[2], body[34] op[0x50]

    op hex (2)
    0000   0x50 0x65                                  Pe
    decimal
             80  101
    datetime ((2008, 8, 0, 25, 60, 0))
    0000   0x80 0x3c 0x79 0x80 0x28                   .<y.(
    body (34)
    hex
    0000   0x8d 0x80 0x10 0xb5 0x80 0x6c 0xbf 0x80    .....l..
    0008   0x01 0x00 0xa0 0x00 0xa0 0x00 0x0c 0x00    ........
    0010   0xb0 0x67 0x4b 0x13 0x0e 0x7b 0x02 0x80    .gK..{..
    0018   0x40 0x0c 0x13 0x0e 0x18 0x06 0x00 0x0a    @.......
    0020   0x98 0x83                                  ..
    decimal
            141  128   16  181  128  108  191  128
              1    0  160    0  160    0   12    0
            176  103   75   19   14  123    2  128
             64   12   19   14   24    6    0   10
            152  131
    HOUR BITS: [0, 0, 1] DAY BITS: [1, 0, 0] YEAR BITS: [0, 0, 1, 0]
#### RECORD 14 ChangeTimeDisplay (2003, 4, 19, 31, 14, 51) head[2], body[0] op[0x64]

    op hex (2)
    0000   0x64 0x2e                                  d.
    decimal
            100   46
    datetime ((2003, 4, 19, 31, 14, 51))
    0000   0x73 0x0e 0x3f 0x13 0x83                   s.?..
    body (0)
    YEAR BITS: [1, 0, 0, 0]
#### RECORD 15 ChangeTimeDisplay 2006-04-01T16:14:51 head[2], body[0] op[0x64]

    op hex (2)
    0000   0x64 0x0e                                  d.
    decimal
            100   14
    datetime (2006-04-01T16:14:51)
    0000   0x73 0x0e 0x70 0x41 0x96                   s.pA.
    body (0)
    DAY BITS: [0, 1, 0] YEAR BITS: [1, 0, 0, 1]
#### RECORD 16 BolusWizard 2014-09-19T15:44:14 head[2], body[13] op[0x5b]
###### DECODED
```python
{'_byte[5]': 56,
 '_byte[7]': 0,
 'bg': 0,
 'bg_target_high': 0,
 'bg_target_low': 25,
 'bolus_estimate': 0.0,
 'carb_input': 48,
 'carb_ratio': 0,
 'correction_estimate': 0.8,
 'food_estimate': 0.0,
 'sensitivity': 200,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 96}
```
    op hex (2)
    0000   0x5b 0x00                                  [.
    decimal
             91    0
    datetime (2014-09-19T15:44:14)
    0000   0x8e 0x6c 0x0f 0x73 0x0e                   .l.s.
    body (13)
    hex
    0000   0x30 0x90 0x00 0xc8 0x19 0x38 0x00 0x00    0....8..
    0008   0x60 0x00 0x00 0x00 0x00                   `....
    decimal
             48  144    0  200   25   56    0    0
             96    0    0    0    0
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 17 Base (2000, 4, 22, 0, 20, 28) head[2], body[0] op[0x60]

    op hex (2)
    0000   0x60 0x4e                                  `N
    decimal
             96   78
    datetime ((2000, 4, 22, 0, 20, 28))
    0000   0x5c 0x14 0xa0 0xf6 0x80                   \....
    body (0)
    DAY BITS: [1, 1, 1] YEAR BITS: [1, 0, 0, 0]
#### RECORD 18 Ian50 (2008, 8, 16, 14, 60, 16) head[2], body[34] op[0x50]

    op hex (2)
    0000   0x50 0x5a                                  PZ
    decimal
             80   90
    datetime ((2008, 8, 16, 14, 60, 16))
    0000   0x90 0x3c 0x6e 0x90 0x28                   .<n.(
    body (34)
    hex
    0000   0x82 0x90 0x10 0xaa 0x90 0x6c 0xb4 0x90    .....l..
    0008   0x01 0x00 0x60 0x00 0x60 0x00 0x00 0x00    ..`.`...
    0010   0x8e 0x6c 0x4f 0x73 0x0e 0x0b 0x65 0xc7    .lOs..e.
    0018   0xa2 0x5b 0x50 0xb3 0x0e 0x01 0x00 0x50    .[P....P
    0020   0x00 0x50                                  .P
    decimal
            130  144   16  170  144  108  180  144
              1    0   96    0   96    0    0    0
            142  108   79  115   14   11  101  199
            162   91   80  179   14    1    0   80
              0   80
    HOUR BITS: [0, 0, 1] DAY BITS: [1, 0, 0] YEAR BITS: [0, 0, 1, 0]
#### RECORD 19 Base (2003, 2, 17, 29, 14, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x08                                  ..
    decimal
              0    8
    datetime ((2003, 2, 17, 29, 14, 0))
    0000   0x00 0x8e 0x5d 0x51 0x13                   ..]Q.
    body (0)
    HOUR BITS: [1, 0, 0] DAY BITS: [0, 1, 0] YEAR BITS: [0, 0, 0, 1]
#### RECORD 20 Base (2001, 4, 26, 12, 15, 37) head[2], body[0] op[0x0e]

    op hex (2)
    0000   0x0e 0x0b                                  ..
    decimal
             14   11
    datetime ((2001, 4, 26, 12, 15, 37))
    0000   0x65 0x0f 0xac 0x7a 0x51                   e..zQ
    body (0)
    DAY BITS: [0, 1, 1] YEAR BITS: [0, 1, 0, 1]
#### RECORD 21 Base (2012, 0, 0, 12, 0, 1) head[2], body[0] op[0xb3]

    op hex (2)
    0000   0xb3 0x8e                                  ..
    decimal
            179  142
    datetime ((2012, 0, 0, 12, 0, 1))
    0000   0x01 0x00 0x0c 0x00 0x0c                   .....
    body (0)

#### RECORD 22 Base (2003, 2, 17, 27, 10, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x44                                  .D
    decimal
              0   68
    datetime ((2003, 2, 17, 27, 10, 0))
    0000   0x00 0x8a 0x7b 0x51 0x13                   ..{Q.
    body (0)
    HOUR BITS: [1, 0, 0] DAY BITS: [0, 1, 0] YEAR BITS: [0, 0, 0, 1]
#### RECORD 23 Base (2003, 2, 18, 0, 0, 3) head[2], body[0] op[0x0e]

    op hex (2)
    0000   0x0e 0x7b                                  .{
    decimal
             14  123
    datetime ((2003, 2, 18, 0, 0, 3))
    0000   0x03 0x80 0x40 0x12 0x13                   ..@..
    body (0)
    HOUR BITS: [1, 0, 0] YEAR BITS: [0, 0, 0, 1]
#### RECORD 24 Base (2001, 0, 14, 10, 0, 24) head[2], body[0] op[0x0e]

    op hex (2)
    0000   0x0e 0x24                                  .$
    decimal
             14   36
    datetime ((2001, 0, 14, 10, 0, 24))
    0000   0x18 0x00 0x0a 0x8e 0x91                   .....
    body (0)
    DAY BITS: [1, 0, 0] YEAR BITS: [1, 0, 0, 1]
#### RECORD 25 Base (2008, 0, 14, 27, 14, 19) head[2], body[0] op[0x4e]

    op hex (2)
    0000   0x4e 0x52                                  NR
    decimal
             78   82
    datetime ((2008, 0, 14, 27, 14, 19))
    0000   0x13 0x0e 0x5b 0x8e 0xa8                   ..[..
    body (0)
    DAY BITS: [1, 0, 0] YEAR BITS: [1, 0, 1, 0]
#### RECORD 26 Base (2000, 4, 16, 4, 14, 51) head[2], body[0] op[0x4e]

    op hex (2)
    0000   0x4e 0x12                                  N.
    decimal
             78   18
    datetime ((2000, 4, 16, 4, 14, 51))
    0000   0x73 0x0e 0x64 0x90 0x00                   s.d..
    body (0)
    DAY BITS: [1, 0, 0]
#### RECORD 27 Base (2000, 1, 28, 1, 36, 56) head[2], body[0] op[0x8c]

    op hex (2)
    0000   0x8c 0x19                                  ..
    decimal
            140   25
    datetime ((2000, 1, 28, 1, 36, 56))
    0000   0x38 0x64 0x01 0x1c 0x00                   8d...
    body (0)
    HOUR BITS: [0, 1, 1]
#### RECORD 28 Base (2014, 1, 28, 14, 0, 1) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x40                                  .@
    decimal
              0   64
    datetime ((2014, 1, 28, 14, 0, 1))
    0000   0x01 0x40 0x4e 0x5c 0x0e                   .@N\.
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 0]
#### RECORD 29 ClearAlarm (2000, 9, 0, 14, 16, 0) head[2], body[0] op[0x0c]

    op hex (2)
    0000   0x0c 0x10                                  ..
    decimal
             12   16
    datetime ((2000, 9, 0, 14, 16, 0))
    0000   0x80 0x50 0x2e 0x80 0x60                   .P..`
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [1, 0, 0] YEAR BITS: [0, 1, 1, 0]
#### RECORD 30 Base (2001, 10, 1, 16, 12, 32) head[2], body[0] op[0x9c]

    op hex (2)
    0000   0x9c 0x80                                  ..
    decimal
            156  128
    datetime ((2001, 10, 1, 16, 12, 32))
    0000   0xa0 0x8c 0x90 0x01 0x01                   .....
    body (0)
    HOUR BITS: [1, 0, 0]
#### RECORD 31 NewTimeSet (2008, 0, 0, 0, 0, 24) head[2], body[0] op[0x18]

    op hex (2)
    0000   0x18 0x01                                  ..
    decimal
             24    1
    datetime ((2008, 0, 0, 0, 0, 24))
    0000   0x18 0x00 0x40 0x00 0xa8                   ..@..
    body (0)
    YEAR BITS: [1, 0, 1, 0]
#### RECORD 32 Base (2000, 4, 0, 1, 14, 51) head[2], body[0] op[0x4e]

    op hex (2)
    0000   0x4e 0x52                                  NR
    decimal
             78   82
    datetime ((2000, 4, 0, 1, 14, 51))
    0000   0x73 0x0e 0x01 0x00 0x50                   s...P
    body (0)
    YEAR BITS: [0, 1, 0, 1]
#### RECORD 33 Base (2012, 3, 7, 0, 60, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x50                                  .P
    decimal
              0   80
    datetime ((2012, 3, 7, 0, 60, 0))
    0000   0x00 0xfc 0x00 0xa7 0x6c                   ....l
    body (0)
    HOUR BITS: [1, 1, 1] DAY BITS: [1, 0, 1] YEAR BITS: [0, 1, 1, 0]
#### RECORD 34 Base (2006, 0, 3, 5, 11, 14) head[2], body[0] op[0x52]

    op hex (2)
    0000   0x52 0x13                                  R.
    decimal
             82   19
    datetime ((2006, 0, 3, 5, 11, 14))
    0000   0x0e 0x0b 0x65 0xe3 0xb6                   ..e..
    body (0)
    DAY BITS: [1, 1, 1] YEAR BITS: [1, 0, 1, 1]
#### RECORD 35 UnabsorbedInsulinBolus unknown head[83], body[0] op[0x5c]
###### DECODED
```python
[{'age': 14, 'amount': 4.475, 'curve': 10},
 {'age': 131, 'amount': 3.175, 'curve': 120},
 {'age': 115, 'amount': 1.275, 'curve': 14},
 {'age': 15, 'amount': 1.575, 'curve': 131},
 {'age': 243, 'amount': 3.0, 'curve': 115},
 {'age': 112, 'amount': 0.35, 'curve': 65},
 {'age': 123, 'amount': 3.75, 'curve': 4},
 {'age': 64, 'amount': 3.2, 'curve': 20},
 {'age': 14, 'amount': 0.475, 'curve': 40},
 {'age': 0, 'amount': 0.725, 'curve': 11},
 {'age': 0, 'amount': 2.875, 'curve': 172},
 {'age': 84, 'amount': 1.675, 'curve': 179},
 {'age': 11, 'amount': 0.35, 'curve': 115},
 {'age': 130, 'amount': 0.0, 'curve': 97},
 {'age': 179, 'amount': 2.1, 'curve': 14},
 {'age': 115, 'amount': 0.275, 'curve': 0},
 {'age': 116, 'amount': 4.65, 'curve': 84},
 {'age': 14, 'amount': 4.475, 'curve': 11},
 {'age': 81, 'amount': 2.55, 'curve': 153},
 {'age': 84, 'amount': 3.025, 'curve': 179},
 {'age': 10, 'amount': 0.35, 'curve': 119},
 {'age': 104, 'amount': 4.475, 'curve': 53},
 {'age': 14, 'amount': 2.875, 'curve': 63},
 {'age': 179, 'amount': 0.35, 'curve': 104},
 {'age': 115, 'amount': 6.125, 'curve': 14},
 {'age': 65, 'amount': 2.8, 'curve': 150},
 {'age': 115, 'amount': 0.275, 'curve': 0}]
```
    op hex (83)
    0000   0x5c 0x53 0xb3 0x0e 0x0a 0x7f 0x83 0x78    \S.....x
    0008   0x33 0x73 0x0e 0x3f 0x0f 0x83 0x78 0xf3    3s.?..x.
    0010   0x73 0x0e 0x70 0x41 0x96 0x7b 0x04 0x80    s.pA.{..
    0018   0x40 0x14 0x13 0x0e 0x28 0x1d 0x00 0x0b    @...(...
    0020   0x73 0x00 0xac 0x43 0x54 0xb3 0x0e 0x0b    s..CT...
    0028   0x73 0x00 0x82 0x61 0x54 0xb3 0x0e 0x0b    s..aT...
    0030   0x73 0x00 0xba 0x74 0x54 0xb3 0x0e 0x0b    s..tT...
    0038   0x66 0x51 0x99 0x79 0x54 0xb3 0x0e 0x0a    fQ.yT...
    0040   0x77 0xb3 0x68 0x35 0x73 0x0e 0x3f 0x0e    w.h5s.?.
    0048   0xb3 0x68 0xf5 0x73 0x0e 0x70 0x41 0x96    .h.s.pA.
    0050   0x0b 0x73 0x00                             .s.
    decimal
             92   83  179   14   10  127  131  120
             51  115   14   63   15  131  120  243
            115   14  112   65  150  123    4  128
             64   20   19   14   40   29    0   11
            115    0  172   67   84  179   14   11
            115    0  130   97   84  179   14   11
            115    0  186  116   84  179   14   11
            102   81  153  121   84  179   14   10
            119  179  104   53  115   14   63   14
            179  104  245  115   14  112   65  150
             11  115    0
    datetime (unknown)

    body (0)

#### RECORD 36 Base (2003, 6, 11, 14, 51, 22) head[2], body[0] op[0x9e]

    op hex (2)
    0000   0x9e 0x56                                  .V
    decimal
            158   86
    datetime ((2003, 6, 11, 14, 51, 22))
    0000   0x56 0xb3 0x0e 0x0b 0x73                   V...s
    body (0)
    HOUR BITS: [1, 0, 1] YEAR BITS: [0, 1, 1, 1]
#### RECORD 37 Base (2011, 5, 14, 19, 22, 43) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0xac                                  ..
    decimal
              0  172
    datetime ((2011, 5, 14, 19, 22, 43))
    0000   0x6b 0x56 0xb3 0x0e 0x7b                   kV..{
    body (0)
    HOUR BITS: [0, 1, 0] YEAR BITS: [0, 1, 1, 1]
#### RECORD 38 Base (2000, 4, 14, 20, 0, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x80                                  ..
    decimal
              0  128
    datetime ((2000, 4, 14, 20, 0, 0))
    0000   0x40 0x00 0x14 0x0e 0x00                   @....
    body (0)

#### RECORD 39 SelectBasalProfile (2004, 0, 6, 0, 0, 7) head[2], body[0] op[0x14]

    op hex (2)
    0000   0x14 0x00                                  ..
    decimal
             20    0
    datetime ((2004, 0, 6, 0, 0, 7))
    0000   0x07 0x00 0x00 0x06 0x04                   .....
    body (0)

#### RECORD 40 Base (2003, 0, 14, 0, 0, 0) head[2], body[0] op[0x93]

    op hex (2)
    0000   0x93 0x8e                                  ..
    decimal
            147  142
    datetime ((2003, 0, 14, 0, 0, 0))
    0000   0x00 0x00 0x00 0x6e 0x93                   ...n.
    body (0)
    DAY BITS: [0, 1, 1] YEAR BITS: [1, 0, 0, 1]
#### RECORD 41 Base (2005, 6, 24, 0, 22, 0) head[2], body[0] op[0x8e]

    op hex (2)
    0000   0x8e 0x06                                  ..
    decimal
            142    6
    datetime ((2005, 6, 24, 0, 22, 0))
    0000   0x40 0x96 0x60 0x98 0x05                   @.`..
    body (0)
    HOUR BITS: [1, 0, 0] DAY BITS: [1, 0, 0]
`end logs/ReadHistoryData-page-10.data: 42 records`
