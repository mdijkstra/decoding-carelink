## START logs/ReadHistoryData-page-5.data
#### STOPPING DOUBLE NULLS @ 485, found 1 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0x99 0x4e 0x48 0x1e 0x0e 0x0b 0x65 0xfc    .NH...e.
    0008   0x8c 0x59 0x48 0xbe 0x0e 0x5b 0x00 0x91    .YH..[..
    0010   0x63 0x0b 0x7e 0x0e 0x64 0x90 0x00 0x46    c.~.d..F
    0018   0x0c 0x38 0x00 0x02 0x38 0x00 0x00 0x00    .8..8...
##### DEBUG DECIMAL
            153   78   72   30   14   11  101  252
            140   89   72  190   14   91    0  145
             99   11  126   14  100  144    0   70
             12   56    0    2   56    0    0    0
#### RECORD 0 Ian0B 2014-09-29T14:11:36 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x73 0x00                             .s.
    decimal
             11  115    0
    datetime (2014-09-29T14:11:36)
    0000   0xa4 0x4b 0x4e 0xbd 0x0e                   .KN..
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [1, 0, 1]
#### RECORD 1 CalBGForPH 2014-09-29T14:14:11 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 87}
```
    op hex (2)
    0000   0x0a 0x57                                  .W
    decimal
             10   87
    datetime (2014-09-29T14:14:11)
    0000   0x8b 0x4e 0x2e 0x7d 0x0e                   .N.}.
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 2 Ian3F 2014-09-29T14:14:11 head[2], body[3] op[0x3f]

    op hex (2)
    0000   0x3f 0x0a                                  ?.
    decimal
             63   10
    datetime (2014-09-29T14:14:11)
    0000   0x8b 0x4e 0xee 0x7d 0x0e                   .N.}.
    body (3)
    hex
    0000   0x70 0x41 0x96                             pA.
    decimal
            112   65  150
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 3 Ian0B 2014-09-29T15:15:44 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x65 0xc8                             .e.
    decimal
             11  101  200
    datetime (2014-09-29T15:15:44)
    0000   0xac 0x4f 0x4f 0xbd 0x0e                   .OO..
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [1, 0, 1]
#### RECORD 4 Ian0B 2014-09-29T16:46:26 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x65 0xf4                             .e.
    decimal
             11  101  244
    datetime (2014-09-29T16:46:26)
    0000   0x9a 0x6e 0x50 0xbd 0x0e                   .nP..
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [1, 0, 1]
#### RECORD 5 BolusWizard 2014-09-29T17:12:31 head[2], body[13] op[0x5b]
###### DECODED
```python
{'_byte[5]': 56,
 '_byte[7]': 0,
 'bg': 0,
 'bg_target_high': 0,
 'bg_target_low': 25,
 'bolus_estimate': 0.0,
 'carb_input': 87,
 'carb_ratio': 0,
 'correction_estimate': 0.8,
 'food_estimate': 0.0,
 'sensitivity': 200,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 172}
```
    op hex (2)
    0000   0x5b 0x00                                  [.
    decimal
             91    0
    datetime (2014-09-29T17:12:31)
    0000   0x9f 0x4c 0x11 0x1d 0x0e                   .L...
    body (13)
    hex
    0000   0x57 0x90 0x00 0xc8 0x19 0x38 0x00 0x00    W....8..
    0008   0xac 0x00 0x00 0x00 0x00                   .....
    decimal
             87  144    0  200   25   56    0    0
            172    0    0    0    0
    HOUR BITS: [0, 1, 0]
#### RECORD 6 Base (2000, 4, 8, 8, 11, 28) head[2], body[0] op[0xac]

    op hex (2)
    0000   0xac 0x4e                                  .N
    decimal
            172   78
    datetime ((2000, 4, 8, 8, 11, 28))
    0000   0x5c 0x0b 0x08 0x08 0x90                   \....
    body (0)
    YEAR BITS: [1, 0, 0, 1]
#### RECORD 7 Base (2001, 8, 16, 18, 40, 16) head[2], body[0] op[0x44]

    op hex (2)
    0000   0x44 0x44                                  DD
    decimal
             68   68
    datetime ((2001, 8, 16, 18, 40, 16))
    0000   0x90 0x28 0xb2 0x90 0x01                   .(...
    body (0)
    HOUR BITS: [0, 0, 1] DAY BITS: [1, 0, 0]
#### RECORD 8 Base (2000, 0, 0, 0, 20, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x14                                  ..
    decimal
              0   20
    datetime ((2000, 0, 0, 0, 20, 0))
    0000   0x00 0x14 0x00 0x00 0x00                   .....
    body (0)

#### RECORD 9 Base (2003, 4, 27, 14, 29, 17) head[2], body[0] op[0x9f]

    op hex (2)
    0000   0x9f 0x4c                                  .L
    decimal
            159   76
    datetime ((2003, 4, 27, 14, 29, 17))
    0000   0x51 0x1d 0x0e 0x7b 0x03                   Q..{.
    body (0)
    DAY BITS: [0, 1, 1]
#### RECORD 10 Base (2008, 0, 4, 14, 29, 18) head[2], body[0] op[0x80]

    op hex (2)
    0000   0x80 0x40                                  .@
    decimal
            128   64
    datetime ((2008, 0, 4, 14, 29, 18))
    0000   0x12 0x1d 0x0e 0x24 0x18                   ...$.
    body (0)
    DAY BITS: [0, 0, 1] YEAR BITS: [0, 0, 0, 1]
#### RECORD 11 Base (2002, 5, 15, 8, 29, 37) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x0b                                  ..
    decimal
              0   11
    datetime ((2002, 5, 15, 8, 29, 37))
    0000   0x65 0x5d 0xa8 0x4f 0x52                   e].OR
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 0] YEAR BITS: [0, 1, 0, 1]
#### RECORD 12 Base (2008, 0, 0, 24, 0, 1) head[2], body[0] op[0xbd]

    op hex (2)
    0000   0xbd 0x8e                                  ..
    decimal
            189  142
    datetime ((2008, 0, 0, 24, 0, 1))
    0000   0x01 0x00 0x78 0x00 0x78                   ..x.x
    body (0)
    YEAR BITS: [0, 1, 1, 1]
#### RECORD 13 Base (2013, 2, 18, 17, 5, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x08                                  ..
    decimal
              0    8
    datetime ((2013, 2, 18, 17, 5, 0))
    0000   0x00 0x85 0x51 0x52 0x1d                   ..QR.
    body (0)
    HOUR BITS: [1, 0, 0] DAY BITS: [0, 1, 0] YEAR BITS: [0, 0, 0, 1]
#### RECORD 14 Base (2000, 0, 20, 0, 20, 0) head[2], body[0] op[0x0e]

    op hex (2)
    0000   0x0e 0x01                                  ..
    decimal
             14    1
    datetime ((2000, 0, 20, 0, 20, 0))
    0000   0x00 0x14 0x00 0x14 0x00                   .....
    body (0)

#### RECORD 15 Base (2014, 9, 29, 18, 20, 12) head[2], body[0] op[0x80]

    op hex (2)
    0000   0x80 0x00                                  ..
    decimal
            128    0
    datetime ((2014, 9, 29, 18, 20, 12))
    0000   0x8c 0x54 0x52 0x1d 0x0e                   .TR..
    body (0)
    HOUR BITS: [0, 1, 0]
#### RECORD 16 Ian0B 2014-09-29T18:29:00 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x68 0x00                             .h.
    decimal
             11  104    0
    datetime (2014-09-29T18:29:00)
    0000   0x80 0x5d 0x52 0xbd 0x0e                   .]R..
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [1, 0, 1]
#### RECORD 17 CalBGForPH 2014-09-29T18:29:51 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 450}
```
    op hex (2)
    0000   0x0a 0xc2                                  ..
    decimal
             10  194
    datetime (2014-09-29T18:29:51)
    0000   0xb3 0x5d 0x32 0x7d 0x8e                   .]2}.
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1] YEAR BITS: [1, 0, 0, 0]
#### RECORD 18 Ian3F 2014-09-29T18:29:51 head[2], body[3] op[0x3f]

    op hex (2)
    0000   0x3f 0x38                                  ?8
    decimal
             63   56
    datetime (2014-09-29T18:29:51)
    0000   0xb3 0x5d 0x52 0x7d 0x0e                   .]R}.
    body (3)
    hex
    0000   0x70 0x41 0x96                             pA.
    decimal
            112   65  150
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 19 BolusWizard 2014-09-29T18:31:49 head[2], body[13] op[0x5b]
###### DECODED
```python
{'_byte[5]': 56,
 '_byte[7]': 0,
 'bg': 250,
 'bg_target_high': 0,
 'bg_target_low': 25,
 'bolus_estimate': 14.0,
 'carb_input': 0,
 'carb_ratio': 0,
 'correction_estimate': 0.8,
 'food_estimate': 1.6,
 'sensitivity': 140,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.8,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 0}
```
    op hex (2)
    0000   0x5b 0xfa                                  [.
    decimal
             91  250
    datetime (2014-09-29T18:31:49)
    0000   0xb1 0x5f 0x12 0x1d 0x0e                   ._...
    body (13)
    hex
    0000   0x00 0x90 0x00 0x8c 0x19 0x38 0x10 0x00    .....8..
    0008   0x00 0x08 0x00 0x8c 0x00                   .....
    decimal
              0  144    0  140   25   56   16    0
              0    8    0  140    0
    HOUR BITS: [0, 1, 0]
#### RECORD 20 Base (2000, 4, 13, 24, 17, 28) head[2], body[0] op[0x84]

    op hex (2)
    0000   0x84 0x4e                                  .N
    decimal
            132   78
    datetime ((2000, 4, 13, 24, 17, 28))
    0000   0x5c 0x11 0x58 0x0d 0x80                   \.X..
    body (0)
    YEAR BITS: [1, 0, 0, 0]
#### RECORD 21 LowReservoir (2008, 8, 0, 19, 20, 0) head[2], body[0] op[0x34]
###### DECODED
```python
{'amount': 2.3}
```
    op hex (2)
    0000   0x34 0x17                                  4.
    decimal
             52   23
    datetime ((2008, 8, 0, 19, 20, 0))
    0000   0x80 0x14 0x53 0x80 0x08                   ..S..
    body (0)
    DAY BITS: [1, 0, 0]
#### RECORD 22 Base (2006, 6, 10, 16, 19, 4) head[2], body[0] op[0x57]

    op hex (2)
    0000   0x57 0x90                                  W.
    decimal
             87  144
    datetime ((2006, 6, 10, 16, 19, 4))
    0000   0x44 0x93 0x90 0x0a 0x86                   D....
    body (0)
    HOUR BITS: [1, 0, 0] YEAR BITS: [1, 0, 0, 0]
#### RECORD 23 Base (2000, 1, 31, 14, 61, 50) head[2], body[0] op[0x8f]

    op hex (2)
    0000   0x8f 0x60                                  .`
    decimal
            143   96
    datetime ((2000, 1, 31, 14, 61, 50))
    0000   0x32 0x7d 0x8e 0x3f 0x30                   2}.?0
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 0, 1] YEAR BITS: [0, 0, 1, 1]
#### RECORD 24 Base (2001, 13, 16, 14, 61, 18) head[2], body[0] op[0x8f]

    op hex (2)
    0000   0x8f 0x60                                  .`
    decimal
            143   96
    datetime ((2001, 13, 16, 14, 61, 18))
    0000   0xd2 0x7d 0x0e 0x70 0x41                   .}.pA
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 1, 1] YEAR BITS: [0, 1, 0, 0]
#### RECORD 25 Base (2013, 14, 18, 0, 53, 24) head[2], body[0] op[0x96]

    op hex (2)
    0000   0x96 0x5b                                  .[
    decimal
            150   91
    datetime ((2013, 14, 18, 0, 53, 24))
    0000   0xd8 0xb5 0x60 0x12 0x7d                   ..`.}
    body (0)
    HOUR BITS: [1, 0, 1] YEAR BITS: [0, 1, 1, 1]
#### RECORD 26 Base (2008, 8, 25, 12, 0, 16) head[2], body[0] op[0x0e]

    op hex (2)
    0000   0x0e 0x00                                  ..
    decimal
             14    0
    datetime ((2008, 8, 25, 12, 0, 16))
    0000   0x90 0x00 0x8c 0x19 0x38                   ....8
    body (0)
    YEAR BITS: [0, 0, 1, 1]
#### RECORD 27 Base (2000, 0, 8, 0, 0, 0) head[2], body[0] op[0xdc]

    op hex (2)
    0000   0xdc 0x00                                  ..
    decimal
            220    0
    datetime ((2000, 0, 8, 0, 0, 0))
    0000   0x00 0x00 0x00 0x88 0x00                   .....
    body (0)
    DAY BITS: [1, 0, 0]
#### RECORD 28 Ian54 (2000, 4, 14, 24, 17, 28) head[2], body[57] op[0x54]

    op hex (2)
    0000   0x54 0x4e                                  TN
    decimal
             84   78
    datetime ((2000, 4, 14, 24, 17, 28))
    0000   0x5c 0x11 0x58 0x0e 0x80                   \.X..
    body (57)
    hex
    0000   0x34 0x18 0x80 0x14 0x54 0x80 0x08 0x58    4...T..X
    0008   0x90 0x44 0x94 0x90 0x01 0x00 0x28 0x00    .D....(.
    0010   0x28 0x00 0x88 0x00 0xb5 0x60 0x52 0x7d    (....`R}
    0018   0x0e 0x01 0x00 0x14 0x00 0x14 0x00 0xac    ........
    0020   0x00 0x8f 0x62 0x52 0x1d 0x0e 0x0b 0x65    ..bR...e
    0028   0x86 0xa7 0x6e 0x52 0xbd 0x8e 0x01 0x00    ..nR....
    0030   0x28 0x00 0x28 0x00 0xac 0x00 0x99 0x6f    (.(....o
    0038   0x52                                       R
    decimal
             52   24  128   20   84  128    8   88
            144   68  148  144    1    0   40    0
             40    0  136    0  181   96   82  125
             14    1    0   20    0   20    0  172
              0  143   98   82   29   14   11  101
            134  167  110   82  189  142    1    0
             40    0   40    0  172    0  153  111
             82
    YEAR BITS: [1, 0, 0, 0]
#### RECORD 29 Base (2005, 1, 12, 0, 53, 11) head[2], body[0] op[0x1d]

    op hex (2)
    0000   0x1d 0x0e                                  ..
    decimal
             29   14
    datetime ((2005, 1, 12, 0, 53, 11))
    0000   0x0b 0x75 0x00 0x8c 0x45                   .u..E
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [1, 0, 0] YEAR BITS: [0, 1, 0, 0]
#### RECORD 30 Base (2000, 1, 0, 4, 59, 14) head[2], body[0] op[0x53]

    op hex (2)
    0000   0x53 0xbd                                  S.
    decimal
             83  189
    datetime ((2000, 1, 0, 4, 59, 14))
    0000   0x0e 0x7b 0x04 0x80 0x40                   .{..@
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [1, 0, 0] YEAR BITS: [0, 1, 0, 0]
#### RECORD 31 SelectBasalProfile (2010, 0, 0, 29, 40, 14) head[2], body[0] op[0x14]

    op hex (2)
    0000   0x14 0x1d                                  ..
    decimal
             20   29
    datetime ((2010, 0, 0, 29, 40, 14))
    0000   0x0e 0x28 0x1d 0x00 0x0a                   .(...
    body (0)
    HOUR BITS: [0, 0, 1]
#### RECORD 32 Base (2015, 4, 14, 29, 52, 9) head[2], body[0] op[0x99]

    op hex (2)
    0000   0x99 0xbb                                  ..
    decimal
            153  187
    datetime ((2015, 4, 14, 29, 52, 9))
    0000   0x49 0x34 0x7d 0x0e 0x3f                   I4}.?
    body (0)
    HOUR BITS: [0, 0, 1] YEAR BITS: [0, 0, 1, 1]
#### RECORD 33 Base (2000, 4, 14, 29, 52, 9) head[2], body[0] op[0x13]

    op hex (2)
    0000   0x13 0xbb                                  ..
    decimal
             19  187
    datetime ((2000, 4, 14, 29, 52, 9))
    0000   0x49 0x34 0x7d 0x0e 0x70                   I4}.p
    body (0)
    HOUR BITS: [0, 0, 1] YEAR BITS: [0, 1, 1, 1]
#### RECORD 34 Base (2000, 4, 0, 0, 0, 59) head[2], body[0] op[0x41]

    op hex (2)
    0000   0x41 0x96                                  A.
    decimal
             65  150
    datetime ((2000, 4, 0, 0, 0, 59))
    0000   0x7b 0x00 0x80 0x40 0x00                   {..@.
    body (0)
    DAY BITS: [0, 1, 0]
#### RECORD 35 PumpSuspend (2000, 0, 7, 0, 20, 0) head[2], body[0] op[0x1e]

    op hex (2)
    0000   0x1e 0x0e                                  ..
    decimal
             30   14
    datetime ((2000, 0, 7, 0, 20, 0))
    0000   0x00 0x14 0x00 0x07 0x00                   .....
    body (0)

#### RECORD 36 Base (2000, 14, 0, 14, 29, 42) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x03                                  ..
    decimal
              0    3
    datetime ((2000, 14, 0, 14, 29, 42))
    0000   0xea 0x9d 0x8e 0x00 0x00                   .....
    body (0)
    HOUR BITS: [1, 0, 0]
#### RECORD 37 Base (2010, 10, 16, 6, 14, 29) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x6e                                  .n
    decimal
              0  110
    datetime ((2010, 10, 16, 6, 14, 29))
    0000   0x9d 0x8e 0x06 0x10 0xfa                   .....
    body (0)
    HOUR BITS: [1, 0, 0] YEAR BITS: [1, 1, 1, 1]
#### RECORD 38 Base (2010, 0, 3, 0, 0, 5) head[2], body[0] op[0x57]

    op hex (2)
    0000   0x57 0xc2                                  W.
    decimal
             87  194
    datetime ((2010, 0, 3, 0, 0, 5))
    0000   0x05 0x00 0x00 0x03 0xea                   .....
    body (0)
    YEAR BITS: [1, 1, 1, 0]
#### RECORD 39 Bolus (2000, 0, 26, 0, 53, 24) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 21.0, 'dual_component': '??', 'programmed': 4.7, 'type': '??'}
```
    op hex (4)
    0000   0x01 0xd2 0x2f 0x02                        ../.
    decimal
              1  210   47    2
    datetime ((2000, 0, 26, 0, 53, 24))
    0000   0x18 0x35 0x00 0xba 0x00                   .5...
    body (0)
    HOUR BITS: [0, 0, 1] DAY BITS: [1, 0, 1]
#### RECORD 40 Base (2008, 0, 0, 24, 0, 40) head[2], body[0] op[0x80]

    op hex (2)
    0000   0x80 0x00                                  ..
    decimal
            128    0
    datetime ((2008, 0, 0, 24, 0, 40))
    0000   0x28 0x00 0x78 0x00 0xf8                   (.x..
    body (0)
    YEAR BITS: [1, 1, 1, 1]
#### RECORD 41 Prime (2013, 8, 0, 17, 19, 44) head[5], body[0] op[0x03]
###### DECODED
```python
{'amount': 0.0, 'fixed': 0.1, 'type': 'fixed'}
```
    op hex (5)
    0000   0x03 0x01 0x01 0x06 0x00                   .....
    decimal
              3    1    1    6    0
    datetime ((2013, 8, 0, 17, 19, 44))
    0000   0xac 0x13 0x51 0x00 0x1d                   ..Q..
    body (0)
    YEAR BITS: [0, 0, 0, 1]
#### RECORD 42 Base (2004, 0, 0, 0, 0, 2) head[2], body[0] op[0x39]

    op hex (2)
    0000   0x39 0x00                                  9.
    decimal
             57    0
    datetime ((2004, 0, 0, 0, 0, 2))
    0000   0x02 0x00 0x00 0x00 0x04                   .....
    body (0)

#### RECORD 43 Bolus (2000, 0, 19, 11, 0, 0) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 0.0, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x00 0x00 0x01                        ....
    decimal
              1    0    0    1
    datetime ((2000, 0, 19, 11, 0, 0))
    0000   0x00 0x00 0x0b 0x73 0x00                   ...s.
    body (0)
    DAY BITS: [0, 1, 1]
#### RECORD 44 Base (2006, 6, 11, 14, 62, 0) head[2], body[0] op[0x87]

    op hex (2)
    0000   0x87 0x54                                  .T
    decimal
            135   84
    datetime ((2006, 6, 11, 14, 62, 0))
    0000   0x40 0xbe 0x0e 0x0b 0x66                   @...f
    body (0)
    HOUR BITS: [1, 0, 1] YEAR BITS: [0, 1, 1, 0]
#### RECORD 45 Base (2011, 5, 14, 30, 0, 25) head[2], body[0] op[0x48]

    op hex (2)
    0000   0x48 0x8c                                  H.
    decimal
             72  140
    datetime ((2011, 5, 14, 30, 0, 25))
    0000   0x59 0x40 0xbe 0x0e 0x7b                   Y@..{
    body (0)
    HOUR BITS: [0, 1, 0] YEAR BITS: [0, 1, 1, 1]
#### RECORD 46 Bolus (2000, 0, 27, 16, 14, 30) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 12.8, 'dual_component': '??', 'programmed': 6.4, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x80 0x40 0x08                        ..@.
    decimal
              1  128   64    8
    datetime ((2000, 0, 27, 16, 14, 30))
    0000   0x1e 0x0e 0x10 0x1b 0x00                   .....
    body (0)

#### RECORD 47 Ian0B 2014-09-30T08:10:00 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x68 0x00                             .h.
    decimal
             11  104    0
    datetime (2014-09-30T08:10:00)
    0000   0x80 0x4a 0x48 0xbe 0x0e                   .JH..
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [1, 0, 1]
#### RECORD 48 CalBGForPH 2014-09-30T08:13:59 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 254}
```
    op hex (2)
    0000   0x0a 0xfe                                  ..
    decimal
             10  254
    datetime (2014-09-30T08:13:59)
    0000   0xbb 0x4d 0x28 0x7e 0x0e                   .M(~.
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 49 Ian3F 2014-09-30T08:13:59 head[2], body[3] op[0x3f]

    op hex (2)
    0000   0x3f 0x1f                                  ?.
    decimal
             63   31
    datetime (2014-09-30T08:13:59)
    0000   0xbb 0x4d 0xc8 0x7e 0x0e                   .M.~.
    body (3)
    hex
    0000   0x70 0x41 0x96                             pA.
    decimal
            112   65  150
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 50 BolusWizard 2014-09-30T08:14:25 head[2], body[13] op[0x5b]
###### DECODED
```python
{'_byte[5]': 56,
 '_byte[7]': 0,
 'bg': 141,
 'bg_target_high': 0,
 'bg_target_low': 28,
 'bolus_estimate': 0.0,
 'carb_input': 0,
 'carb_ratio': 0,
 'correction_estimate': 0.8,
 'food_estimate': 8.8,
 'sensitivity': 170,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 0}
```
    op hex (2)
    0000   0x5b 0x8d                                  [.
    decimal
             91  141
    datetime (2014-09-30T08:14:25)
    0000   0x99 0x4e 0x08 0x1e 0x0e                   .N...
    body (13)
    hex
    0000   0x00 0x90 0x00 0xaa 0x1c 0x38 0x58 0x00    .....8X.
    0008   0x00 0x00 0x00 0x00 0x00                   .....
    decimal
              0  144    0  170   28   56   88    0
              0    0    0    0    0
    HOUR BITS: [0, 1, 0]
#### RECORD 51 Base (2008, 0, 0, 24, 0, 1) head[2], body[0] op[0x58]

    op hex (2)
    0000   0x58 0x4e                                  XN
    decimal
             88   78
    datetime ((2008, 0, 0, 24, 0, 1))
    0000   0x01 0x00 0x58 0x00 0x58                   ..X.X
    body (0)
    YEAR BITS: [0, 1, 0, 1]
`end logs/ReadHistoryData-page-5.data: 52 records`
