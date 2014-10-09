## START logs/ReadHistoryData-page-30.data
#### STOPPING DOUBLE NULLS @ 441, found 1 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0xa6 0x19 0x4d 0x0f 0x0e 0x5b 0x00 0x8c    ..M..[..
    0008   0x39 0x0d 0x6f 0x0e 0x5f 0x90 0x00 0x46    9.o._..F
    0010   0x0c 0x38 0x00 0x02 0x1c 0x00 0x00 0x00    .8......
    0018   0x02 0x1c 0x4e 0x5c 0x05 0x70 0x27 0x80    ..N\.p'.
##### DEBUG DECIMAL
            166   25   77   15   14   91    0  140
             57   13  111   14   95  144    0   70
             12   56    0    2   28    0    0    0
              2   28   78   92    5  112   39  128
#### RECORD 0 Base (2014, 8, 14, 15, 1, 9) head[2], body[0] op[0x53]

    op hex (2)
    0000   0x53 0x00                                  S.
    decimal
             83    0
    datetime ((2014, 8, 14, 15, 1, 9))
    0000   0x89 0x01 0x0f 0x0e 0x0e                   .....
    body (0)

#### RECORD 1 Base (2015, 7, 2, 0, 9, 37) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x0b                                  ..
    decimal
              0   11
    datetime ((2015, 7, 2, 0, 9, 37))
    0000   0x65 0xc9 0x80 0x02 0x4f                   e...O
    body (0)
    HOUR BITS: [1, 1, 0] YEAR BITS: [0, 1, 0, 0]
#### RECORD 2 Base (2004, 0, 0, 20, 0, 1) head[2], body[0] op[0xae]

    op hex (2)
    0000   0xae 0x0e                                  ..
    decimal
            174   14
    datetime ((2004, 0, 0, 20, 0, 1))
    0000   0x01 0x00 0x14 0x00 0x14                   .....
    body (0)
    YEAR BITS: [0, 0, 0, 1]
#### RECORD 3 Base (2014, 2, 15, 3, 16, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x08                                  ..
    decimal
              0    8
    datetime ((2014, 2, 15, 3, 16, 0))
    0000   0x00 0x90 0x03 0x4f 0x0e                   ...O.
    body (0)
    HOUR BITS: [1, 0, 0] DAY BITS: [0, 1, 0]
#### RECORD 4 Base (2000, 0, 20, 0, 20, 0) head[2], body[0] op[0x0e]

    op hex (2)
    0000   0x0e 0x01                                  ..
    decimal
             14    1
    datetime ((2000, 0, 20, 0, 20, 0))
    0000   0x00 0x14 0x00 0x14 0x00                   .....
    body (0)

#### RECORD 5 SelectBasalProfile 2014-08-14T15:28:17 head[2], body[0] op[0x14]

    op hex (2)
    0000   0x14 0x00                                  ..
    decimal
             20    0
    datetime (2014-08-14T15:28:17)
    0000   0x91 0x1c 0x4f 0x0e 0x0e                   ..O..
    body (0)

#### RECORD 6 Bolus (2007, 0, 0, 4, 0, 60) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 6.0, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x00 0x3c 0x00                        ..<.
    decimal
              1    0   60    0
    datetime ((2007, 0, 0, 4, 0, 60))
    0000   0x3c 0x00 0x24 0x00 0xb7                   <.$..
    body (0)
    YEAR BITS: [1, 0, 1, 1]
#### RECORD 7 Base (2004, 0, 0, 1, 14, 14) head[2], body[0] op[0x2c]

    op hex (2)
    0000   0x2c 0x4f                                  ,O
    decimal
             44   79
    datetime ((2004, 0, 0, 1, 14, 14))
    0000   0x0e 0x0e 0x01 0x00 0x14                   .....
    body (0)
    YEAR BITS: [0, 0, 0, 1]
#### RECORD 8 Base (2003, 1, 28, 0, 16, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x14                                  ..
    decimal
              0   20
    datetime ((2003, 1, 28, 0, 16, 0))
    0000   0x00 0x50 0x00 0x9c 0x03                   .P...
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [1, 0, 0]
#### RECORD 9 Ian50 (2000, 0, 20, 0, 1, 14) head[2], body[34] op[0x50]

    op hex (2)
    0000   0x50 0x0e                                  P.
    decimal
             80   14
    datetime ((2000, 0, 20, 0, 1, 14))
    0000   0x0e 0x01 0x00 0x14 0x00                   .....
    body (34)
    hex
    0000   0x14 0x00 0x54 0x00 0xa6 0x0f 0x50 0x0e    ..T...P.
    0008   0x0e 0x0a 0xd9 0x96 0x16 0x30 0x6e 0x0e    .....0n.
    0010   0x3f 0x1b 0x96 0x16 0x30 0x6e 0x0e 0x70    ?...0n.p
    0018   0x41 0x96 0x0b 0x65 0xd4 0x8e 0x1f 0x50    A..e...P
    0020   0xae 0x0e                                  ..
    decimal
             20    0   84    0  166   15   80   14
             14   10  217  150   22   48  110   14
             63   27  150   22   48  110   14  112
             65  150   11  101  212  142   31   80
            174   14

#### RECORD 10 BasalProfileStart 2014-08-14T18:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x03                                  {.
    decimal
            123    3
    datetime (2014-08-14T18:00:00)
    0000   0x80 0x00 0x12 0x0e 0x0e                   .....
    body (3)
    hex
    0000   0x24 0x18 0x00                             $..
    decimal
             36   24    0

#### RECORD 11 Bolus (2006, 8, 0, 0, 0, 32) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 16.0, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x00 0xa0 0x00                        ....
    decimal
              1    0  160    0
    datetime ((2006, 8, 0, 0, 0, 32))
    0000   0xa0 0x00 0x00 0x00 0x96                   .....
    body (0)
    YEAR BITS: [1, 0, 0, 1]
#### RECORD 12 Base (2008, 0, 0, 1, 14, 14) head[2], body[0] op[0x25]

    op hex (2)
    0000   0x25 0x53                                  %S
    decimal
             37   83
    datetime ((2008, 0, 0, 1, 14, 14))
    0000   0x0e 0x0e 0x01 0x00 0x28                   ....(
    body (0)
    YEAR BITS: [0, 0, 1, 0]
#### RECORD 13 Base (2009, 2, 20, 0, 32, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x28                                  .(
    decimal
              0   40
    datetime ((2009, 2, 20, 0, 32, 0))
    0000   0x00 0xa0 0x00 0x94 0x29                   ....)
    body (0)
    HOUR BITS: [1, 0, 1] DAY BITS: [1, 0, 0] YEAR BITS: [0, 0, 1, 0]
#### RECORD 14 Base (2000, 1, 0, 4, 59, 14) head[2], body[0] op[0x53]

    op hex (2)
    0000   0x53 0x0e                                  S.
    decimal
             83   14
    datetime ((2000, 1, 0, 4, 59, 14))
    0000   0x0e 0x7b 0x04 0x80 0x00                   .{...
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [1, 0, 0]
#### RECORD 15 SelectBasalProfile (2001, 0, 0, 29, 40, 14) head[2], body[0] op[0x14]

    op hex (2)
    0000   0x14 0x0e                                  ..
    decimal
             20   14
    datetime ((2001, 0, 0, 29, 40, 14))
    0000   0x0e 0x28 0x1d 0x00 0x01                   .(...
    body (0)
    HOUR BITS: [0, 0, 1]
#### RECORD 16 Base (2000, 1, 20, 0, 56, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x78                                  .x
    decimal
              0  120
    datetime ((2000, 1, 20, 0, 56, 0))
    0000   0x00 0x78 0x00 0xb4 0x00                   .x...
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [1, 0, 1]
#### RECORD 17 Base (2000, 4, 1, 14, 14, 19) head[2], body[0] op[0x99]

    op hex (2)
    0000   0x99 0x3b                                  .;
    decimal
            153   59
    datetime ((2000, 4, 1, 14, 14, 19))
    0000   0x53 0x0e 0x0e 0x01 0x00                   S....
    body (0)

#### RECORD 18 Ian50 (2012, 4, 0, 8, 1, 16) head[2], body[34] op[0x50]

    op hex (2)
    0000   0x50 0x00                                  P.
    decimal
             80    0
    datetime ((2012, 4, 0, 8, 1, 16))
    0000   0x50 0x01 0x08 0x00 0xac                   P....
    body (34)
    hex
    0000   0x0d 0x54 0x0e 0x0e 0x1e 0x01 0xb1 0x23    .T.....#
    0008   0x15 0x0e 0x0e 0x01 0x00 0x50 0x00 0x14    .....P..
    0010   0x00 0x2c 0x00 0x9e 0x23 0x55 0x0e 0x0e    .,..#U..
    0018   0x7b 0x04 0xb5 0x23 0x15 0x0e 0x0e 0x28    {..#...(
    0020   0x1d 0x00                                  ..
    decimal
             13   84   14   14   30    1  177   35
             21   14   14    1    0   80    0   20
              0   44    0  158   35   85   14   14
            123    4  181   35   21   14   14   40
             29    0
    YEAR BITS: [1, 0, 1, 0]
#### RECORD 19 PumpResume 2014-08-14T21:35:53 head[2], body[0] op[0x1f]

    op hex (2)
    0000   0x1f 0x20                                  . 
    decimal
             31   32
    datetime (2014-08-14T21:35:53)
    0000   0xb5 0x23 0x15 0x0e 0x0e                   .#...
    body (0)
    HOUR BITS: [0, 0, 1]
#### RECORD 20 Bolus (2010, 0, 0, 0, 0, 40) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 4.0, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x00 0x28 0x00                        ..(.
    decimal
              1    0   40    0
    datetime ((2010, 0, 0, 0, 0, 40))
    0000   0x28 0x00 0x40 0x00 0xba                   (.@..
    body (0)
    YEAR BITS: [1, 0, 1, 1]
#### RECORD 21 Base (2000, 0, 0, 1, 14, 14) head[2], body[0] op[0x23]

    op hex (2)
    0000   0x23 0x55                                  #U
    decimal
             35   85
    datetime ((2000, 0, 0, 1, 14, 14))
    0000   0x0e 0x0e 0x01 0x00 0x10                   .....
    body (0)
    YEAR BITS: [0, 0, 0, 1]
#### RECORD 22 Base (2011, 0, 16, 0, 56, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x10                                  ..
    decimal
              0   16
    datetime ((2011, 0, 16, 0, 56, 0))
    0000   0x00 0x38 0x00 0x90 0x3b                   .8..;
    body (0)
    HOUR BITS: [0, 0, 1] DAY BITS: [1, 0, 0] YEAR BITS: [0, 0, 1, 1]
#### RECORD 23 Base (2000, 0, 12, 0, 1, 14) head[2], body[0] op[0x55]

    op hex (2)
    0000   0x55 0x0e                                  U.
    decimal
             85   14
    datetime ((2000, 0, 12, 0, 1, 14))
    0000   0x0e 0x01 0x00 0x2c 0x00                   ...,.
    body (0)
    DAY BITS: [0, 0, 1]
#### RECORD 24 Base (2006, 4, 6, 26, 0, 0) head[2], body[0] op[0x2c]

    op hex (2)
    0000   0x2c 0x00                                  ,.
    decimal
             44    0
    datetime ((2006, 4, 6, 26, 0, 0))
    0000   0x40 0x00 0x9a 0x06 0x56                   @...V
    body (0)
    YEAR BITS: [0, 1, 0, 1]
#### RECORD 25 Base (2000, 4, 0, 0, 0, 59) head[2], body[0] op[0x0e]

    op hex (2)
    0000   0x0e 0x0e                                  ..
    decimal
             14   14
    datetime ((2000, 4, 0, 0, 0, 59))
    0000   0x7b 0x00 0x80 0x00 0x00                   {....
    body (0)

#### RECORD 26 Base (2000, 0, 7, 0, 20, 0) head[2], body[0] op[0x0f]

    op hex (2)
    0000   0x0f 0x0e                                  ..
    decimal
             15   14
    datetime ((2000, 0, 7, 0, 20, 0))
    0000   0x00 0x14 0x00 0x07 0x00                   .....
    body (0)

#### RECORD 27 Base (2000, 6, 0, 14, 14, 60) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x04                                  ..
    decimal
              0    4
    datetime ((2000, 6, 0, 14, 14, 60))
    0000   0x7c 0x8e 0x0e 0x00 0x00                   |....
    body (0)
    HOUR BITS: [1, 0, 0]
#### RECORD 28 Base (2000, 8, 0, 6, 14, 14) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x6e                                  .n
    decimal
              0  110
    datetime ((2000, 8, 0, 6, 14, 14))
    0000   0x8e 0x0e 0x06 0x00 0xd0                   .....
    body (0)
    YEAR BITS: [1, 1, 0, 1]
#### RECORD 29 Base (2012, 0, 4, 0, 0, 2) head[2], body[0] op[0xc7]

    op hex (2)
    0000   0xc7 0xd9                                  ..
    decimal
            199  217
    datetime ((2012, 0, 4, 0, 0, 2))
    0000   0x02 0x00 0x00 0x04 0x7c                   ....|
    body (0)
    YEAR BITS: [0, 1, 1, 1]
#### RECORD 30 Bolus 2000-08-23T00:59:40 head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 21.2, 'dual_component': '??', 'programmed': 4.1, 'type': '??'}
```
    op hex (4)
    0000   0x01 0xd4 0x29 0x02                        ..).
    decimal
              1  212   41    2
    datetime (2000-08-23T00:59:40)
    0000   0xa8 0x3b 0x00 0x17 0x00                   .;...
    body (0)
    HOUR BITS: [0, 0, 1]
#### RECORD 31 ChangeBasalProfile (2000, 0, 2, 0, 0, 0) head[2], body[44] op[0x08]

    op hex (2)
    0000   0x08 0x00                                  ..
    decimal
              8    0
    datetime ((2000, 0, 2, 0, 0, 0))
    0000   0x00 0x00 0x00 0x02 0xa0                   .....
    body (44)
    hex
    0000   0x01 0x00 0x00 0x0f 0x00 0xaf 0x10 0x54    .......T
    0008   0x00 0x20 0x22 0x00 0x00 0x00 0x00 0x00    . ".....
    0010   0x04 0x01 0x00 0x00 0x00 0x00 0x00 0x0b    ........
    0018   0x73 0x00 0x92 0x0b 0x40 0xaf 0x0e 0x0b    s...@...
    0020   0x73 0x00 0x8e 0x1f 0x40 0xaf 0x0e 0x0b    s...@...
    0028   0x66 0x48 0x8a 0x07                        fH..
    decimal
              1    0    0   15    0  175   16   84
              0   32   34    0    0    0    0    0
              4    1    0    0    0    0    0   11
            115    0  146   11   64  175   14   11
            115    0  142   31   64  175   14   11
            102   72  138    7
    YEAR BITS: [1, 0, 1, 0]
#### RECORD 32 Base (2014, 0, 0, 19, 11, 14) head[2], body[0] op[0x41]

    op hex (2)
    0000   0x41 0xaf                                  A.
    decimal
             65  175
    datetime ((2014, 0, 0, 19, 11, 14))
    0000   0x0e 0x0b 0x73 0x00 0x8e                   ..s..
    body (0)
    YEAR BITS: [1, 0, 0, 0]
#### RECORD 33 Ian0B (2002, 0, 6, 26, 10, 14) head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x41 0xaf                             .A.
    decimal
             11   65  175
    datetime ((2002, 0, 6, 26, 10, 14))
    0000   0x0e 0x0a 0x7a 0xa6 0x12                   ..z..
    body (0)
    DAY BITS: [1, 0, 1] YEAR BITS: [0, 0, 0, 1]
#### RECORD 34 Base (2002, 0, 6, 15, 63, 14) head[2], body[0] op[0x22]

    op hex (2)
    0000   0x22 0x6f                                  "o
    decimal
             34  111
    datetime ((2002, 0, 6, 15, 63, 14))
    0000   0x0e 0x3f 0x0f 0xa6 0x12                   .?...
    body (0)
    HOUR BITS: [0, 0, 1] DAY BITS: [1, 0, 1] YEAR BITS: [0, 0, 0, 1]
#### RECORD 35 Base (2011, 1, 22, 1, 48, 14) head[2], body[0] op[0x42]

    op hex (2)
    0000   0x42 0x6f                                  Bo
    decimal
             66  111
    datetime ((2011, 1, 22, 1, 48, 14))
    0000   0x0e 0x70 0x41 0x96 0x7b                   .pA.{
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [1, 0, 0] YEAR BITS: [0, 1, 1, 1]
#### RECORD 36 Bolus (2000, 0, 27, 16, 14, 15) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 12.8, 'dual_component': '??', 'programmed': 0.0, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x80 0x00 0x08                        ....
    decimal
              1  128    0    8
    datetime ((2000, 0, 27, 16, 14, 15))
    0000   0x0f 0x0e 0x10 0x1b 0x00                   .....
    body (0)

#### RECORD 37 CalBGForPH 2014-08-15T10:48:12 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 119}
```
    op hex (2)
    0000   0x0a 0x77                                  .w
    decimal
             10  119
    datetime (2014-08-15T10:48:12)
    0000   0x8c 0x30 0x2a 0x6f 0x0e                   .0*o.
    body (0)
    HOUR BITS: [0, 0, 1] DAY BITS: [0, 1, 1]
#### RECORD 38 Ian3F 2014-08-15T10:48:12 head[2], body[3] op[0x3f]

    op hex (2)
    0000   0x3f 0x0e                                  ?.
    decimal
             63   14
    datetime (2014-08-15T10:48:12)
    0000   0x8c 0x30 0xea 0x6f 0x0e                   .0.o.
    body (3)
    hex
    0000   0x70 0x41 0x96                             pA.
    decimal
            112   65  150
    HOUR BITS: [0, 0, 1] DAY BITS: [0, 1, 1]
#### RECORD 39 BasalProfileStart 2014-08-15T12:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x02                                  {.
    decimal
            123    2
    datetime (2014-08-15T12:00:00)
    0000   0x80 0x00 0x0c 0x0f 0x0e                   .....
    body (3)
    hex
    0000   0x18 0x06 0x00                             ...
    decimal
             24    6    0

#### RECORD 40 BolusWizard 2014-08-15T13:25:38 head[2], body[13] op[0x5b]
###### DECODED
```python
{'_byte[5]': 56,
 '_byte[7]': 0,
 'bg': 0,
 'bg_target_high': 0,
 'bg_target_low': 12,
 'bolus_estimate': 0.0,
 'carb_input': 20,
 'carb_ratio': 0,
 'correction_estimate': 0.8,
 'food_estimate': 0.0,
 'sensitivity': 70,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 112}
```
    op hex (2)
    0000   0x5b 0x00                                  [.
    decimal
             91    0
    datetime (2014-08-15T13:25:38)
    0000   0xa6 0x19 0x0d 0x0f 0x0e                   .....
    body (13)
    hex
    0000   0x14 0x90 0x00 0x46 0x0c 0x38 0x00 0x00    ...F.8..
    0008   0x70 0x00 0x00 0x00 0x00                   p....
    decimal
             20  144    0   70   12   56    0    0
            112    0    0    0    0

#### RECORD 41 Base (2000, 0, 0, 16, 0, 1) head[2], body[0] op[0x70]

    op hex (2)
    0000   0x70 0x4e                                  pN
    decimal
            112   78
    datetime ((2000, 0, 0, 16, 0, 1))
    0000   0x01 0x00 0x70 0x00 0x70                   ..p.p
    body (0)
    YEAR BITS: [0, 1, 1, 1]
`end logs/ReadHistoryData-page-30.data: 42 records`
