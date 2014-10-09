## START logs/ReadHistoryData-page-18.data
#### STOPPING DOUBLE NULLS @ 214, found 1 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0x88 0x57 0x4e 0x63 0x0e 0x01 0x00 0x14    .WNc....
    0008   0x00 0x14 0x00 0x30 0x00 0x95 0x64 0x4f    ...0..dO
    0010   0x03 0x0e 0x0b 0x73 0x00 0x82 0x7b 0x4f    ...s..{O
    0018   0xa3 0x0e 0x0a 0x49 0x8d 0x48 0x30 0x63    ...I.H0c
##### DEBUG DECIMAL
            136   87   78   99   14    1    0   20
              0   20    0   48    0  149  100   79
              3   14   11  115    0  130  123   79
            163   14   10   73  141   72   48   99
#### RECORD 0 UnabsorbedInsulinBolus unknown head[8], body[0] op[0x5c]
###### DECODED
```python
[{'age': 106, 'amount': 3.0, 'curve': 144},
 {'age': 116, 'amount': 5.3, 'curve': 144}]
```
    op hex (8)
    0000   0x5c 0x08 0x78 0x6a 0x90 0xd4 0x74 0x90    \.xj..t.
    decimal
             92    8  120  106  144  212  116  144
    datetime (unknown)

    body (0)

#### RECORD 1 Bolus (2004, 4, 0, 0, 0, 44) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 10.8, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x00 0x6c 0x00                        ..l.
    decimal
              1    0  108    0
    datetime ((2004, 4, 0, 0, 0, 44))
    0000   0x6c 0x00 0x00 0x00 0x84                   l....
    body (0)
    YEAR BITS: [1, 0, 0, 0]
#### RECORD 2 Ian54 (2000, 4, 1, 27, 14, 35) head[2], body[57] op[0x54]

    op hex (2)
    0000   0x54 0x40                                  T@
    decimal
             84   64
    datetime ((2000, 4, 1, 27, 14, 35))
    0000   0x63 0x0e 0x7b 0x01 0x80                   c.{..
    body (57)
    hex
    0000   0x40 0x08 0x03 0x0e 0x10 0x1b 0x00 0x0b    @.......
    0008   0x68 0x00 0x80 0x75 0x49 0xa3 0x0e 0x0a    h..uI...
    0010   0x9d 0xbb 0x41 0x2a 0x63 0x0e 0x3f 0x13    ..A*c.?.
    0018   0xbb 0x41 0xaa 0x63 0x0e 0x70 0x41 0x96    .A.c.pA.
    0020   0x5b 0x57 0x9b 0x42 0x0a 0x63 0x0e 0x00    [W.B.c..
    0028   0x90 0x00 0xaa 0x1c 0x38 0x0c 0x00 0x00    ....8...
    0030   0x00 0x00 0x00 0x00 0x0c 0x4e 0x01 0x00    .....N..
    0038   0x0c                                       .
    decimal
             64    8    3   14   16   27    0   11
            104    0  128  117   73  163   14   10
            157  187   65   42   99   14   63   19
            187   65  170   99   14  112   65  150
             91   87  155   66   10   99   14    0
            144    0  170   28   56   12    0    0
              0    0    0    0   12   78    1    0
             12
    YEAR BITS: [1, 0, 0, 0]
#### RECORD 3 Base (2002, 0, 27, 0, 0, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x0c                                  ..
    decimal
              0   12
    datetime ((2002, 0, 27, 0, 0, 0))
    0000   0x00 0x00 0x00 0x9b 0x42                   ....B
    body (0)
    DAY BITS: [1, 0, 0] YEAR BITS: [0, 1, 0, 0]
#### RECORD 4 Base (2009, 1, 31, 0, 27, 14) head[2], body[0] op[0x4a]

    op hex (2)
    0000   0x4a 0x63                                  Jc
    decimal
             74   99
    datetime ((2009, 1, 31, 0, 27, 14))
    0000   0x0e 0x5b 0x00 0x9f 0x79                   .[..y
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [1, 0, 0] YEAR BITS: [0, 1, 1, 1]
#### RECORD 5 CalBGForPH (2006, 0, 0, 16, 47, 14) head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 99}
```
    op hex (2)
    0000   0x0a 0x63                                  .c
    decimal
             10   99
    datetime ((2006, 0, 0, 16, 47, 14))
    0000   0x0e 0x2f 0x90 0x00 0x46                   ./..F
    body (0)
    HOUR BITS: [0, 0, 1] YEAR BITS: [0, 1, 0, 0]
#### RECORD 6 ClearAlarm (2000, 0, 0, 12, 1, 0) head[2], body[0] op[0x0c]

    op hex (2)
    0000   0x0c 0x38                                  .8
    decimal
             12   56
    datetime ((2000, 0, 0, 12, 1, 0))
    0000   0x00 0x01 0x0c 0x00 0x00                   .....
    body (0)

#### RECORD 7 Base (2012, 1, 5, 28, 14, 12) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x01                                  ..
    decimal
              0    1
    datetime ((2012, 1, 5, 28, 14, 12))
    0000   0x0c 0x4e 0x5c 0x05 0x0c                   .N\..
    body (0)
    HOUR BITS: [0, 1, 0]
#### RECORD 8 Base (2000, 0, 0, 0, 0, 1) head[2], body[0] op[0x3b]

    op hex (2)
    0000   0x3b 0x80                                  ;.
    decimal
             59  128
    datetime ((2000, 0, 0, 0, 0, 1))
    0000   0x01 0x00 0xa0 0x00 0xa0                   .....
    body (0)
    YEAR BITS: [1, 0, 1, 0]
#### RECORD 9 Base (2003, 2, 10, 25, 31, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x08                                  ..
    decimal
              0    8
    datetime ((2003, 2, 10, 25, 31, 0))
    0000   0x00 0x9f 0x79 0x4a 0x63                   ..yJc
    body (0)
    HOUR BITS: [1, 0, 0] DAY BITS: [0, 1, 0] YEAR BITS: [0, 1, 1, 0]
#### RECORD 10 Base (2000, 0, 0, 0, 32, 0) head[2], body[0] op[0x0e]

    op hex (2)
    0000   0x0e 0x01                                  ..
    decimal
             14    1
    datetime ((2000, 0, 0, 0, 32, 0))
    0000   0x00 0x20 0x00 0x20 0x00                   . . .
    body (0)
    HOUR BITS: [0, 0, 1] DAY BITS: [0, 0, 1]
#### RECORD 11 Base (2014, 9, 3, 11, 34, 31) head[2], body[0] op[0x78]

    op hex (2)
    0000   0x78 0x00                                  x.
    decimal
            120    0
    datetime ((2014, 9, 3, 11, 34, 31))
    0000   0x9f 0x62 0x4b 0x03 0x0e                   .bK..
    body (0)
    HOUR BITS: [0, 1, 1]
#### RECORD 12 BasalProfileStart 2014-09-03T12:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x02                                  {.
    decimal
            123    2
    datetime (2014-09-03T12:00:00)
    0000   0x80 0x40 0x0c 0x03 0x0e                   .@...
    body (3)
    hex
    0000   0x18 0x06 0x00                             ...
    decimal
             24    6    0
    HOUR BITS: [0, 1, 0]
#### RECORD 13 CalBGForPH 2014-09-03T14:03:05 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 113}
```
    op hex (2)
    0000   0x0a 0x71                                  .q
    decimal
             10  113
    datetime (2014-09-03T14:03:05)
    0000   0x85 0x43 0x2e 0x63 0x0e                   .C.c.
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 14 Ian3F 2014-09-03T14:03:05 head[2], body[3] op[0x3f]

    op hex (2)
    0000   0x3f 0x0e                                  ?.
    decimal
             63   14
    datetime (2014-09-03T14:03:05)
    0000   0x85 0x43 0x2e 0x63 0x0e                   .C.c.
    body (3)
    hex
    0000   0x70 0x41 0x96                             pA.
    decimal
            112   65  150
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 15 BolusWizard 2014-09-03T14:23:08 head[2], body[13] op[0x5b]
###### DECODED
```python
{'_byte[5]': 56,
 '_byte[7]': 1,
 'bg': 0,
 'bg_target_high': 1,
 'bg_target_low': 12,
 'bolus_estimate': 0.0,
 'carb_input': 67,
 'carb_ratio': 0,
 'correction_estimate': 0.9,
 'food_estimate': 0.0,
 'sensitivity': 70,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 124}
```
    op hex (2)
    0000   0x5b 0x00                                  [.
    decimal
             91    0
    datetime (2014-09-03T14:23:08)
    0000   0x88 0x57 0x0e 0x63 0x0e                   .W.c.
    body (13)
    hex
    0000   0x43 0x90 0x00 0x46 0x0c 0x38 0x00 0x01    C..F.8..
    0008   0x7c 0x00 0x00 0x00 0x01                   |....
    decimal
             67  144    0   70   12   56    0    1
            124    0    0    0    1
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 16 Base (2000, 4, 15, 0, 14, 28) head[2], body[0] op[0x7c]

    op hex (2)
    0000   0x7c 0x4e                                  |N
    decimal
            124   78
    datetime ((2000, 4, 15, 0, 14, 28))
    0000   0x5c 0x0e 0x20 0xaf 0x80                   \. ..
    body (0)
    DAY BITS: [1, 0, 1] YEAR BITS: [1, 0, 0, 0]
#### RECORD 17 Base (2012, 8, 0, 23, 26, 0) head[2], body[0] op[0x86]

    op hex (2)
    0000   0x86 0xcd                                  ..
    decimal
            134  205
    datetime ((2012, 8, 0, 23, 26, 0))
    0000   0x80 0x1a 0xd7 0x80 0x0c                   .....
    body (0)
    DAY BITS: [1, 0, 0]
#### RECORD 18 Base (2000, 0, 0, 16, 0, 1) head[2], body[0] op[0x09]

    op hex (2)
    0000   0x09 0x90                                  ..
    decimal
              9  144
    datetime ((2000, 0, 0, 16, 0, 1))
    0000   0x01 0x00 0xb0 0x00 0xb0                   .....
    body (0)
    YEAR BITS: [1, 0, 1, 1]
`end logs/ReadHistoryData-page-18.data: 19 records`
