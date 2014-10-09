## START logs/ReadHistoryData-page-16.data
#### STOPPING DOUBLE NULLS @ 408, found 0 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0xae 0x55 0x40 0x68 0x0e 0x01 0x00 0x3c    .U@h...<
    0008   0x00 0x3c 0x00 0x28 0x00 0x9f 0x55 0x41    .<.(..UA
    0010   0x08 0x0e 0x7b 0x01 0x80 0x40 0x08 0x08    ..{..@..
    0018   0x0e 0x10 0x1b 0x00 0x0a 0x89 0x87 0x49    .......I
##### DEBUG DECIMAL
            174   85   64  104   14    1    0   60
              0   60    0   40    0  159   85   65
              8   14  123    1  128   64    8    8
             14   16   27    0   10  137  135   73
#### RECORD 0 Ian3F 2014-09-07T11:53:57 head[2], body[3] op[0x3f]

    op hex (2)
    0000   0x3f 0x0b                                  ?.
    decimal
             63   11
    datetime (2014-09-07T11:53:57)
    0000   0xb9 0x75 0xab 0x67 0x0e                   .u.g.
    body (3)
    hex
    0000   0x70 0x41 0x96                             pA.
    decimal
            112   65  150
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 1 BasalProfileStart 2014-09-07T12:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x02                                  {.
    decimal
            123    2
    datetime (2014-09-07T12:00:00)
    0000   0x80 0x40 0x0c 0x07 0x0e                   .@...
    body (3)
    hex
    0000   0x18 0x06 0x00                             ...
    decimal
             24    6    0
    HOUR BITS: [0, 1, 0]
#### RECORD 2 Ian0B 2014-09-07T12:15:12 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x73 0x00                             .s.
    decimal
             11  115    0
    datetime (2014-09-07T12:15:12)
    0000   0x8c 0x4f 0x4c 0xa7 0x0e                   .OL..
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [1, 0, 1]
#### RECORD 3 Ian0B 2014-09-07T12:20:22 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x66 0x4f                             .fO
    decimal
             11  102   79
    datetime (2014-09-07T12:20:22)
    0000   0x96 0x54 0x4c 0xa7 0x0e                   .TL..
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [1, 0, 1]
#### RECORD 4 Bolus (2005, 0, 0, 0, 0, 28) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 2.8, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x00 0x1c 0x00                        ....
    decimal
              1    0   28    0
    datetime ((2005, 0, 0, 0, 0, 28))
    0000   0x1c 0x00 0x00 0x00 0xa5                   .....
    body (0)
    YEAR BITS: [1, 0, 1, 0]
#### RECORD 5 Base (2000, 0, 5, 11, 14, 7) head[2], body[0] op[0x68]

    op hex (2)
    0000   0x68 0x4d                                  hM
    decimal
            104   77
    datetime ((2000, 0, 5, 11, 14, 7))
    0000   0x07 0x0e 0x0b 0x65 0xd0                   ...e.
    body (0)
    DAY BITS: [0, 1, 1] YEAR BITS: [1, 1, 0, 1]
#### RECORD 6 Base (2000, 6, 1, 14, 39, 14) head[2], body[0] op[0x8c]

    op hex (2)
    0000   0x8c 0x4a                                  .J
    decimal
            140   74
    datetime ((2000, 6, 1, 14, 39, 14))
    0000   0x4e 0xa7 0x0e 0x01 0x00                   N....
    body (0)
    HOUR BITS: [1, 0, 1]
#### RECORD 7 Base (2004, 0, 0, 4, 0, 40) head[2], body[0] op[0x28]

    op hex (2)
    0000   0x28 0x00                                  (.
    decimal
             40    0
    datetime ((2004, 0, 0, 4, 0, 40))
    0000   0x28 0x00 0x04 0x00 0x94                   (....
    body (0)
    YEAR BITS: [1, 0, 0, 1]
#### RECORD 8 Base (2012, 0, 0, 1, 14, 7) head[2], body[0] op[0x4b]

    op hex (2)
    0000   0x4b 0x4f                                  KO
    decimal
             75   79
    datetime ((2012, 0, 0, 1, 14, 7))
    0000   0x07 0x0e 0x01 0x00 0x1c                   .....
    body (0)
    YEAR BITS: [0, 0, 0, 1]
#### RECORD 9 Base (2006, 0, 15, 0, 44, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x1c                                  ..
    decimal
              0   28
    datetime ((2006, 0, 15, 0, 44, 0))
    0000   0x00 0x2c 0x00 0xaf 0x56                   .,..V
    body (0)
    HOUR BITS: [0, 0, 1] DAY BITS: [1, 0, 1] YEAR BITS: [0, 1, 0, 1]
#### RECORD 10 Base (2006, 0, 20, 5, 11, 14) head[2], body[0] op[0x4f]

    op hex (2)
    0000   0x4f 0x07                                  O.
    decimal
             79    7
    datetime ((2006, 0, 20, 5, 11, 14))
    0000   0x0e 0x0b 0x65 0xf4 0x96                   ..e..
    body (0)
    DAY BITS: [1, 1, 1] YEAR BITS: [1, 0, 0, 1]
#### RECORD 11 Base (2015, 8, 5, 11, 14, 39) head[2], body[0] op[0x68]

    op hex (2)
    0000   0x68 0x4f                                  hO
    decimal
            104   79
    datetime ((2015, 8, 5, 11, 14, 39))
    0000   0xa7 0x0e 0x0b 0x65 0xcf                   ...e.
    body (0)
    DAY BITS: [0, 1, 1] YEAR BITS: [1, 1, 0, 0]
#### RECORD 12 Base (2000, 6, 1, 14, 39, 17) head[2], body[0] op[0x96]

    op hex (2)
    0000   0x96 0x68                                  .h
    decimal
            150  104
    datetime ((2000, 6, 1, 14, 39, 17))
    0000   0x51 0xa7 0x0e 0x01 0x00                   Q....
    body (0)
    HOUR BITS: [1, 0, 1]
#### RECORD 13 Ian50 (2009, 4, 0, 0, 0, 16) head[2], body[34] op[0x50]

    op hex (2)
    0000   0x50 0x00                                  P.
    decimal
             80    0
    datetime ((2009, 4, 0, 0, 0, 16))
    0000   0x50 0x00 0x00 0x00 0xb9                   P....
    body (34)
    hex
    0000   0x6a 0x51 0x07 0x0e 0x5b 0x00 0xa4 0x77    jQ..[..w
    0008   0x11 0x67 0x0e 0x78 0x90 0x00 0xc8 0x19    .g.x....
    0010   0x38 0x00 0x00 0xf0 0x00 0x00 0x00 0x00    8.......
    0018   0xf0 0x4e 0x5c 0x0e 0x50 0x11 0x80 0x1c    .N\.P...
    0020   0x9d 0x80                                  ..
    decimal
            106   81    7   14   91    0  164  119
             17  103   14  120  144    0  200   25
             56    0    0  240    0    0    0    0
            240   78   92   14   80   17  128   28
            157  128
    YEAR BITS: [1, 0, 1, 1]
#### RECORD 14 Base (2011, 8, 16, 1, 28, 0) head[2], body[0] op[0x28]

    op hex (2)
    0000   0x28 0xa7                                  (.
    decimal
             40  167
    datetime ((2011, 8, 16, 1, 28, 0))
    0000   0x80 0x1c 0x01 0x90 0x7b                   ....{
    body (0)
    DAY BITS: [1, 0, 0] YEAR BITS: [0, 1, 1, 1]
#### RECORD 15 Prime (2001, 0, 0, 24, 36, 14) head[5], body[0] op[0x03]
###### DECODED
```python
{'amount': 0.7, 'fixed': 6.4, 'type': 'fixed'}
```
    op hex (5)
    0000   0x03 0x80 0x40 0x12 0x07                   ..@..
    decimal
              3  128   64   18    7
    datetime ((2001, 0, 0, 24, 36, 14))
    0000   0x0e 0x24 0x18 0x00 0x01                   .$...
    body (0)
    HOUR BITS: [0, 0, 1]
#### RECORD 16 Bolus 2007-01-04T00:12:00 head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 2.4, 'dual_component': '??', 'programmed': 0.1, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x18 0x01 0x18                        ....
    decimal
              1   24    1   24
    datetime (2007-01-04T00:12:00)
    0000   0x00 0x4c 0x00 0xa4 0x77                   .L..w
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [1, 0, 1] YEAR BITS: [0, 1, 1, 1]
#### RECORD 17 Base (2000, 0, 0, 0, 1, 14) head[2], body[0] op[0x51]

    op hex (2)
    0000   0x51 0x67                                  Qg
    decimal
             81  103
    datetime ((2000, 0, 0, 0, 1, 14))
    0000   0x0e 0x01 0x00 0xa0 0x00                   .....
    body (0)
    DAY BITS: [1, 0, 1]
#### RECORD 18 Base (2002, 0, 18, 6, 0, 48) head[2], body[0] op[0xa0]

    op hex (2)
    0000   0xa0 0x01                                  ..
    decimal
            160    1
    datetime ((2002, 0, 18, 6, 0, 48))
    0000   0x30 0x00 0x86 0x52 0x52                   0..RR
    body (0)
    DAY BITS: [0, 1, 0] YEAR BITS: [0, 1, 0, 1]
#### RECORD 19 MResultTotals 2002-08-13T00:00:00 head[5], body[0] op[0x07]

    op hex (5)
    0000   0x07 0x0e 0x0b 0x75 0x00                   ...u.
    decimal
              7   14   11  117    0
    datetime (2002-08-13T00:00:00)
    0000   0x8c 0x72                                  .r
    body (0)
    HOUR BITS: [0, 1, 1]
#### RECORD 20 Base (2006, 0, 0, 19, 11, 14) head[2], body[0] op[0x52]

    op hex (2)
    0000   0x52 0xa7                                  R.
    decimal
             82  167
    datetime ((2006, 0, 0, 19, 11, 14))
    0000   0x0e 0x0b 0x73 0x00 0x96                   ..s..
    body (0)
    YEAR BITS: [1, 0, 0, 1]
#### RECORD 21 Base (2008, 8, 0, 1, 14, 39) head[2], body[0] op[0x40]

    op hex (2)
    0000   0x40 0x53                                  @S
    decimal
             64   83
    datetime ((2008, 8, 0, 1, 14, 39))
    0000   0xa7 0x0e 0x01 0x00 0x28                   ....(
    body (0)
    YEAR BITS: [0, 0, 1, 0]
#### RECORD 22 Base (2011, 1, 7, 0, 44, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x28                                  .(
    decimal
              0   40
    datetime ((2011, 1, 7, 0, 44, 0))
    0000   0x00 0x6c 0x00 0xa7 0x5b                   .l..[
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [1, 0, 1] YEAR BITS: [0, 1, 0, 1]
#### RECORD 23 Base (2000, 1, 0, 4, 59, 14) head[2], body[0] op[0x53]

    op hex (2)
    0000   0x53 0x07                                  S.
    decimal
             83    7
    datetime ((2000, 1, 0, 4, 59, 14))
    0000   0x0e 0x7b 0x04 0x80 0x40                   .{..@
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [1, 0, 0] YEAR BITS: [0, 1, 0, 0]
#### RECORD 24 SelectBasalProfile (2010, 0, 0, 29, 40, 14) head[2], body[0] op[0x14]

    op hex (2)
    0000   0x14 0x07                                  ..
    decimal
             20    7
    datetime ((2010, 0, 0, 29, 40, 14))
    0000   0x0e 0x28 0x1d 0x00 0x0a                   .(...
    body (0)
    HOUR BITS: [0, 0, 1]
#### RECORD 25 Base (2015, 4, 14, 7, 53, 26) head[2], body[0] op[0x5f]

    op hex (2)
    0000   0x5f 0x93                                  _.
    decimal
             95  147
    datetime ((2015, 4, 14, 7, 53, 26))
    0000   0x5a 0x35 0x67 0x0e 0x3f                   Z5g.?
    body (0)
    HOUR BITS: [0, 0, 1] YEAR BITS: [0, 0, 1, 1]
#### RECORD 26 Ian0B (2001, 13, 16, 14, 39, 53) head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x93 0x5a                             ..Z
    decimal
             11  147   90
    datetime ((2001, 13, 16, 14, 39, 53))
    0000   0xf5 0x67 0x0e 0x70 0x41                   .g.pA
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 1, 1] YEAR BITS: [0, 1, 0, 0]
#### RECORD 27 Base (2005, 4, 27, 2, 0, 51) head[2], body[0] op[0x96]

    op hex (2)
    0000   0x96 0x0b                                  ..
    decimal
            150   11
    datetime ((2005, 4, 27, 2, 0, 51))
    0000   0x73 0x00 0x82 0x7b 0x55                   s..{U
    body (0)
    DAY BITS: [0, 1, 1] YEAR BITS: [0, 1, 0, 1]
#### RECORD 28 Base (2008, 1, 22, 0, 51, 11) head[2], body[0] op[0xa7]

    op hex (2)
    0000   0xa7 0x0e                                  ..
    decimal
            167   14
    datetime ((2008, 1, 22, 0, 51, 11))
    0000   0x0b 0x73 0x00 0x96 0x68                   .s..h
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [1, 0, 0] YEAR BITS: [0, 1, 1, 0]
#### RECORD 29 Base (2002, 0, 14, 6, 11, 14) head[2], body[0] op[0x57]

    op hex (2)
    0000   0x57 0xa7                                  W.
    decimal
             87  167
    datetime ((2002, 0, 14, 6, 11, 14))
    0000   0x0e 0x0b 0x66 0x4e 0x82                   ..fN.
    body (0)
    DAY BITS: [0, 1, 0] YEAR BITS: [1, 0, 0, 0]
#### RECORD 30 BasalProfileStart (2000, 8, 0, 27, 14, 39) head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x57                                  {W
    decimal
            123   87
    datetime ((2000, 8, 0, 27, 14, 39))
    0000   0xa7 0x0e 0x7b 0x00 0x80                   ..{..
    body (3)
    hex
    0000   0x40 0x00 0x08                             @..
    decimal
             64    0    8
    YEAR BITS: [1, 0, 0, 0]
#### RECORD 31 Base (2000, 0, 0, 7, 0, 20) head[2], body[0] op[0x0e]

    op hex (2)
    0000   0x0e 0x00                                  ..
    decimal
             14    0
    datetime ((2000, 0, 0, 7, 0, 20))
    0000   0x14 0x00 0x07 0x00 0x00                   .....
    body (0)

#### RECORD 32 Base (2000, 10, 0, 0, 14, 7) head[2], body[0] op[0x04]

    op hex (2)
    0000   0x04 0x6c                                  .l
    decimal
              4  108
    datetime ((2000, 10, 0, 0, 14, 7))
    0000   0x87 0x8e 0x00 0x00 0x00                   .....
    body (0)
    HOUR BITS: [1, 0, 0]
#### RECORD 33 Sara6E 2014-09-08T00:00:00 head[1], body[49] op[0x6e]

    op hex (1)
    0000   0x6e                                       n
    decimal
            110
    datetime (2014-09-08T00:00:00)
    0000   0x87 0x8e                                  ..
    body (49)
    hex
    0000   0x06 0x00 0x5e 0x5d 0x5f 0x02 0x00 0x00    ..^]_...
    0008   0x04 0x6c 0x01 0xd4 0x29 0x02 0x98 0x3b    .l..)..;
    0010   0x00 0x78 0x00 0x00 0x00 0x00 0x01 0x18    .x......
    0018   0x01 0x80 0x00 0x00 0x01 0x07 0x00 0x99    ........
    0020   0x10 0x53 0x01 0x08 0x31 0x00 0x06 0x00    .S..1...
    0028   0x00 0x03 0x03 0x01 0x00 0x00 0x01 0x00    ........
    0030   0x00                                       .
    decimal
              6    0   94   93   95    2    0    0
              4  108    1  212   41    2  152   59
              0  120    0    0    0    0    1   24
              1  128    0    0    1    7    0  153
             16   83    1    8   49    0    6    0
              0    3    3    1    0    0    1    0
              0
    HOUR BITS: [1, 0, 0]
#### RECORD 34 Ian0B 2014-09-08T00:04:30 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x73 0x00                             .s.
    decimal
             11  115    0
    datetime (2014-09-08T00:04:30)
    0000   0x9e 0x44 0x40 0xa8 0x0e                   .D@..
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [1, 0, 1]
#### RECORD 35 CalBGForPH 2014-09-08T00:21:25 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 40}
```
    op hex (2)
    0000   0x0a 0x28                                  .(
    decimal
             10   40
    datetime (2014-09-08T00:21:25)
    0000   0x99 0x55 0x40 0x08 0x0e                   .U@..
    body (0)
    HOUR BITS: [0, 1, 0]
#### RECORD 36 CalBGForPH 2014-09-08T00:21:31 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 42}
```
    op hex (2)
    0000   0x0a 0x2a                                  .*
    decimal
             10   42
    datetime (2014-09-08T00:21:31)
    0000   0x9f 0x55 0x40 0x08 0x0e                   .U@..
    body (0)
    HOUR BITS: [0, 1, 0]
#### RECORD 37 BolusWizard 2014-09-08T00:21:46 head[2], body[13] op[0x5b]
###### DECODED
```python
{'_byte[5]': 56,
 '_byte[7]': 0,
 'bg': 42,
 'bg_target_high': 0,
 'bg_target_low': 28,
 'bolus_estimate': 0.0,
 'carb_input': 46,
 'carb_ratio': 0,
 'correction_estimate': 0.8,
 'food_estimate': 23.6,
 'sensitivity': 170,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 24.8,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 108}
```
    op hex (2)
    0000   0x5b 0x2a                                  [*
    decimal
             91   42
    datetime (2014-09-08T00:21:46)
    0000   0xae 0x55 0x00 0x68 0x0e                   .U.h.
    body (13)
    hex
    0000   0x2e 0x90 0x00 0xaa 0x1c 0x38 0xec 0x00    .....8..
    0008   0x6c 0xf8 0x00 0x00 0x00                   l....
    decimal
             46  144    0  170   28   56  236    0
            108  248    0    0    0
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 38 Base (2000, 4, 5, 20, 20, 28) head[2], body[0] op[0x58]

    op hex (2)
    0000   0x58 0x4e                                  XN
    decimal
             88   78
    datetime ((2000, 4, 5, 20, 20, 28))
    0000   0x5c 0x14 0x14 0x25 0x90                   \..%.
    body (0)
    DAY BITS: [0, 0, 1] YEAR BITS: [1, 0, 0, 1]
#### RECORD 39 SelectBasalProfile 2008-10-16T11:32:16 head[2], body[0] op[0x14]

    op hex (2)
    0000   0x14 0x2f                                  ./
    decimal
             20   47
    datetime (2008-10-16T11:32:16)
    0000   0x90 0xa0 0x6b 0x90 0x88                   ..k..
    body (0)
    HOUR BITS: [1, 0, 1] DAY BITS: [1, 0, 0] YEAR BITS: [1, 0, 0, 0]
#### RECORD 40 Base (2003, 10, 16, 16, 9, 16) head[2], body[0] op[0x7f]

    op hex (2)
    0000   0x7f 0x90                                  ..
    decimal
            127  144
    datetime ((2003, 10, 16, 16, 9, 16))
    0000   0x90 0x89 0x90 0x50 0x93                   ...P.
    body (0)
    HOUR BITS: [1, 0, 0] DAY BITS: [0, 1, 0] YEAR BITS: [1, 0, 0, 1]
#### RECORD 41 Base (2000, 1, 24, 0, 24, 0) head[2], body[0] op[0x90]

    op hex (2)
    0000   0x90 0x01                                  ..
    decimal
            144    1
    datetime ((2000, 1, 24, 0, 24, 0))
    0000   0x00 0x58 0x00 0x58 0x00                   .X.X.
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 0]
`end logs/ReadHistoryData-page-16.data: 42 records`
