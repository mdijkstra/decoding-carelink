## START logs/ReadHistoryData-page-14.data
#### STOPPING DOUBLE NULLS @ 389, found 1 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0x83 0x63 0x53 0x0c 0x0e 0x0b 0x65 0xef    .cS...e.
    0008   0x96 0x71 0x53 0xac 0x0e 0x7b 0x04 0x80    .qS..{..
    0010   0x40 0x14 0x0c 0x0e 0x28 0x1d 0x00 0x5b    @...(..[
    0018   0x00 0xbb 0x4e 0x14 0x6c 0x0e 0x16 0x90    ..N.l...
##### DEBUG DECIMAL
            131   99   83   12   14   11  101  239
            150  113   83  172   14  123    4  128
             64   20   12   14   40   29    0   91
              0  187   78   20  108   14   22  144
#### RECORD 0 Ian0B 2014-09-11T15:58:36 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x73 0x00                             .s.
    decimal
             11  115    0
    datetime (2014-09-11T15:58:36)
    0000   0xa4 0x7a 0x4f 0xab 0x0e                   .zO..
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [1, 0, 1]
#### RECORD 1 BasalProfileStart 2014-09-11T18:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x03                                  {.
    decimal
            123    3
    datetime (2014-09-11T18:00:00)
    0000   0x80 0x40 0x12 0x0b 0x0e                   .@...
    body (3)
    hex
    0000   0x24 0x18 0x00                             $..
    decimal
             36   24    0
    HOUR BITS: [0, 1, 0]
#### RECORD 2 Ian0B 2014-09-11T19:44:00 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x68 0x00                             .h.
    decimal
             11  104    0
    datetime (2014-09-11T19:44:00)
    0000   0x80 0x6c 0x53 0xab 0x0e                   .lS..
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [1, 0, 1]
#### RECORD 3 BasalProfileStart 2014-09-11T20:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x04                                  {.
    decimal
            123    4
    datetime (2014-09-11T20:00:00)
    0000   0x80 0x40 0x14 0x0b 0x0e                   .@...
    body (3)
    hex
    0000   0x28 0x1d 0x00                             (..
    decimal
             40   29    0
    HOUR BITS: [0, 1, 0]
#### RECORD 4 Ian0B 2014-09-11T20:44:00 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x68 0x00                             .h.
    decimal
             11  104    0
    datetime (2014-09-11T20:44:00)
    0000   0x80 0x6c 0x54 0xab 0x0e                   .lT..
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [1, 0, 1]
#### RECORD 5 CalBGForPH 2014-09-11T20:53:21 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 122}
```
    op hex (2)
    0000   0x0a 0x7a                                  .z
    decimal
             10  122
    datetime (2014-09-11T20:53:21)
    0000   0x95 0x75 0x34 0x6b 0x0e                   .u4k.
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 6 Ian3F 2014-09-11T20:53:21 head[2], body[3] op[0x3f]

    op hex (2)
    0000   0x3f 0x0f                                  ?.
    decimal
             63   15
    datetime (2014-09-11T20:53:21)
    0000   0x95 0x75 0x54 0x6b 0x0e                   .uTk.
    body (3)
    hex
    0000   0x70 0x41 0x96                             pA.
    decimal
            112   65  150
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 7 Bolus 2007-08-03T00:00:32 head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 16.0, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x00 0xa0 0x00                        ....
    decimal
              1    0  160    0
    datetime (2007-08-03T00:00:32)
    0000   0xa0 0x00 0x00 0x03 0x97                   .....
    body (0)
    YEAR BITS: [1, 0, 0, 1]
#### RECORD 8 Base (2000, 0, 0, 1, 14, 11) head[2], body[0] op[0x79]

    op hex (2)
    0000   0x79 0xb4                                  y.
    decimal
            121  180
    datetime ((2000, 0, 0, 1, 14, 11))
    0000   0x0b 0x0e 0x01 0x00 0xa0                   .....
    body (0)
    YEAR BITS: [1, 0, 1, 0]
#### RECORD 9 Base (2006, 0, 11, 0, 0, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0xa0                                  ..
    decimal
              0  160
    datetime ((2006, 0, 11, 0, 0, 0))
    0000   0x00 0x00 0x00 0xab 0x76                   ....v
    body (0)
    DAY BITS: [1, 0, 1] YEAR BITS: [0, 1, 1, 1]
#### RECORD 10 Base (2000, 0, 0, 0, 1, 14) head[2], body[0] op[0x94]

    op hex (2)
    0000   0x94 0x0b                                  ..
    decimal
            148   11
    datetime ((2000, 0, 0, 0, 1, 14))
    0000   0x0e 0x01 0x00 0xa0 0x00                   .....
    body (0)
    DAY BITS: [1, 0, 1]
#### RECORD 11 Base (2005, 8, 24, 21, 0, 12) head[2], body[0] op[0xa0]

    op hex (2)
    0000   0xa0 0x00                                  ..
    decimal
            160    0
    datetime ((2005, 8, 24, 21, 0, 12))
    0000   0x8c 0x00 0x95 0x78 0x55                   ...xU
    body (0)
    DAY BITS: [0, 1, 1] YEAR BITS: [0, 1, 0, 1]
#### RECORD 12 Ian0B (2012, 2, 0, 0, 0, 0) head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x0e 0x7b                             ..{
    decimal
             11   14  123
    datetime ((2012, 2, 0, 0, 0, 0))
    0000   0x00 0x80 0x40 0x00 0x0c                   ..@..
    body (0)
    HOUR BITS: [1, 0, 0]
#### RECORD 13 Base (2000, 0, 0, 7, 0, 20) head[2], body[0] op[0x0e]

    op hex (2)
    0000   0x0e 0x00                                  ..
    decimal
             14    0
    datetime ((2000, 0, 0, 7, 0, 20))
    0000   0x14 0x00 0x07 0x00 0x00                   .....
    body (0)

#### RECORD 14 Base (2000, 10, 0, 0, 14, 11) head[2], body[0] op[0x05]

    op hex (2)
    0000   0x05 0x18                                  ..
    decimal
              5   24
    datetime ((2000, 10, 0, 0, 14, 11))
    0000   0x8b 0x8e 0x00 0x00 0x00                   .....
    body (0)
    HOUR BITS: [1, 0, 0]
#### RECORD 15 Sara6E 2014-09-12T00:00:00 head[1], body[49] op[0x6e]

    op hex (1)
    0000   0x6e                                       n
    decimal
            110
    datetime (2014-09-12T00:00:00)
    0000   0x8b 0x8e                                  ..
    body (49)
    hex
    0000   0x06 0x00 0x77 0x7a 0x9f 0x03 0x00 0x00    ..wz....
    0008   0x05 0x18 0x01 0xd4 0x24 0x03 0x44 0x40    ....$.D@
    0010   0x00 0x46 0x01 0x64 0x00 0x00 0x00 0x00    .F.d....
    0018   0x01 0xe0 0x01 0x00 0x00 0x02 0x00 0x87    ........
    0020   0x00 0x64 0x00 0x0f 0x17 0x00 0x01 0x4d    .d.....M
    0028   0x4d 0x00 0x00 0x01 0x00 0x00 0x00 0x00    M.......
    0030   0x00                                       .
    decimal
              6    0  119  122  159    3    0    0
              5   24    1  212   36    3   68   64
              0   70    1  100    0    0    0    0
              1  224    1    0    0    2    0  135
              0  100    0   15   23    0    1   77
             77    0    0    1    0    0    0    0
              0
    HOUR BITS: [1, 0, 0]
#### RECORD 16 CalBGForPH 2014-09-12T01:06:37 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 152}
```
    op hex (2)
    0000   0x0a 0x98                                  ..
    decimal
             10  152
    datetime (2014-09-12T01:06:37)
    0000   0xa5 0x46 0x21 0x6c 0x0e                   .F!l.
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 17 Ian3F 2014-09-12T01:06:37 head[2], body[3] op[0x3f]

    op hex (2)
    0000   0x3f 0x13                                  ?.
    decimal
             63   19
    datetime (2014-09-12T01:06:37)
    0000   0xa5 0x46 0x01 0x6c 0x0e                   .F.l.
    body (3)
    hex
    0000   0x70 0x41 0x96                             pA.
    decimal
            112   65  150
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 18 Ian0B 2014-09-12T04:13:12 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x73 0x00                             .s.
    decimal
             11  115    0
    datetime (2014-09-12T04:13:12)
    0000   0x8c 0x4d 0x44 0xac 0x0e                   .MD..
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [1, 0, 1]
#### RECORD 19 CalBGForPH 2014-09-12T07:22:03 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 141}
```
    op hex (2)
    0000   0x0a 0x8d                                  ..
    decimal
             10  141
    datetime (2014-09-12T07:22:03)
    0000   0x83 0x56 0x27 0x6c 0x0e                   .V'l.
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 20 Ian3F 2014-09-12T07:22:03 head[2], body[3] op[0x3f]

    op hex (2)
    0000   0x3f 0x11                                  ?.
    decimal
             63   17
    datetime (2014-09-12T07:22:03)
    0000   0x83 0x56 0xa7 0x6c 0x0e                   .V.l.
    body (3)
    hex
    0000   0x70 0x41 0x96                             pA.
    decimal
            112   65  150
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 21 BasalProfileStart 2014-09-12T08:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x01                                  {.
    decimal
            123    1
    datetime (2014-09-12T08:00:00)
    0000   0x80 0x40 0x08 0x0c 0x0e                   .@...
    body (3)
    hex
    0000   0x10 0x1b 0x00                             ...
    decimal
             16   27    0
    HOUR BITS: [0, 1, 0]
#### RECORD 22 BolusWizard 2014-09-12T09:25:12 head[2], body[13] op[0x5b]
###### DECODED
```python
{'_byte[5]': 56,
 '_byte[7]': 0,
 'bg': 0,
 'bg_target_high': 0,
 'bg_target_low': 28,
 'bolus_estimate': 0.0,
 'carb_input': 68,
 'carb_ratio': 0,
 'correction_estimate': 0.8,
 'food_estimate': 0.0,
 'sensitivity': 170,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 160}
```
    op hex (2)
    0000   0x5b 0x00                                  [.
    decimal
             91    0
    datetime (2014-09-12T09:25:12)
    0000   0x8c 0x59 0x09 0x0c 0x0e                   .Y...
    body (13)
    hex
    0000   0x44 0x90 0x00 0xaa 0x1c 0x38 0x00 0x00    D....8..
    0008   0xa0 0x00 0x00 0x00 0x00                   .....
    decimal
             68  144    0  170   28   56    0    0
            160    0    0    0    0
    HOUR BITS: [0, 1, 0]
#### RECORD 23 Base (2009, 4, 25, 20, 0, 27) head[2], body[0] op[0xa0]

    op hex (2)
    0000   0xa0 0x4e                                  .N
    decimal
            160   78
    datetime ((2009, 4, 25, 20, 0, 27))
    0000   0x5b 0x00 0x94 0x59 0x09                   [..Y.
    body (0)
    DAY BITS: [0, 1, 0]
#### RECORD 24 ClearAlarm 2012-06-10T00:16:04 head[2], body[0] op[0x0c]

    op hex (2)
    0000   0x0c 0x0e                                  ..
    decimal
             12   14
    datetime (2012-06-10T00:16:04)
    0000   0x44 0x90 0x00 0xaa 0x1c                   D....
    body (0)
    HOUR BITS: [1, 0, 0] DAY BITS: [1, 0, 1] YEAR BITS: [0, 0, 0, 1]
#### RECORD 25 Base (2000, 2, 0, 0, 32, 0) head[2], body[0] op[0x38]

    op hex (2)
    0000   0x38 0x00                                  8.
    decimal
             56    0
    datetime ((2000, 2, 0, 0, 32, 0))
    0000   0x00 0xa0 0x00 0x00 0x00                   .....
    body (0)
    HOUR BITS: [1, 0, 1]
#### RECORD 26 Base (2000, 4, 8, 0, 1, 14) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0xa0                                  ..
    decimal
              0  160
    datetime ((2000, 4, 8, 0, 1, 14))
    0000   0x4e 0x01 0x00 0xc8 0x00                   N....
    body (0)
    DAY BITS: [1, 1, 0]
#### RECORD 27 Base (2009, 0, 25, 20, 0, 0) head[2], body[0] op[0xc8]

    op hex (2)
    0000   0xc8 0x00                                  ..
    decimal
            200    0
    datetime ((2009, 0, 25, 20, 0, 0))
    0000   0x00 0x00 0x94 0x59 0x49                   ...YI
    body (0)
    DAY BITS: [0, 1, 0] YEAR BITS: [0, 1, 0, 0]
#### RECORD 28 ClearAlarm (2008, 0, 0, 8, 0, 1) head[2], body[0] op[0x0c]

    op hex (2)
    0000   0x0c 0x0e                                  ..
    decimal
             12   14
    datetime ((2008, 0, 0, 8, 0, 1))
    0000   0x01 0x00 0xc8 0x00 0xc8                   .....
    body (0)
    YEAR BITS: [1, 1, 0, 0]
#### RECORD 29 Base (2012, 2, 9, 15, 41, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0xac                                  ..
    decimal
              0  172
    datetime ((2012, 2, 9, 15, 41, 0))
    0000   0x00 0xa9 0x6f 0x49 0x0c                   ..oI.
    body (0)
    HOUR BITS: [1, 0, 1] DAY BITS: [0, 1, 0]
#### RECORD 30 Base (2010, 7, 11, 3, 10, 37) head[2], body[0] op[0x0e]

    op hex (2)
    0000   0x0e 0x0b                                  ..
    decimal
             14   11
    datetime ((2010, 7, 11, 3, 10, 37))
    0000   0x65 0xca 0x83 0x6b 0x4a                   e..kJ
    body (0)
    HOUR BITS: [1, 1, 0] DAY BITS: [0, 1, 1] YEAR BITS: [0, 1, 0, 0]
#### RECORD 31 Base (2004, 0, 0, 4, 0, 1) head[2], body[0] op[0xac]

    op hex (2)
    0000   0xac 0x0e                                  ..
    decimal
            172   14
    datetime ((2004, 0, 0, 4, 0, 1))
    0000   0x01 0x00 0x64 0x00 0x64                   ..d.d
    body (0)
    YEAR BITS: [0, 1, 1, 0]
#### RECORD 32 Base (2012, 2, 10, 11, 24, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x94                                  ..
    decimal
              0  148
    datetime ((2012, 2, 10, 11, 24, 0))
    0000   0x00 0x98 0x6b 0x4a 0x0c                   ..kJ.
    body (0)
    HOUR BITS: [1, 0, 0] DAY BITS: [0, 1, 0]
#### RECORD 33 Base (2012, 2, 12, 0, 0, 2) head[2], body[0] op[0x0e]

    op hex (2)
    0000   0x0e 0x7b                                  .{
    decimal
             14  123
    datetime ((2012, 2, 12, 0, 0, 2))
    0000   0x02 0x80 0x40 0x0c 0x0c                   ..@..
    body (0)
    HOUR BITS: [1, 0, 0]
#### RECORD 34 Base (2000, 0, 3, 27, 0, 6) head[2], body[0] op[0x0e]

    op hex (2)
    0000   0x0e 0x18                                  ..
    decimal
             14   24
    datetime ((2000, 0, 3, 27, 0, 6))
    0000   0x06 0x00 0x7b 0x03 0x80                   ..{..
    body (0)
    YEAR BITS: [1, 0, 0, 0]
#### RECORD 35 Base (2000, 0, 24, 4, 14, 12) head[2], body[0] op[0x40]

    op hex (2)
    0000   0x40 0x12                                  @.
    decimal
             64   18
    datetime ((2000, 0, 24, 4, 14, 12))
    0000   0x0c 0x0e 0x24 0x18 0x00                   ..$..
    body (0)

#### RECORD 36 Ian0B 2014-09-12T19:22:00 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x68 0x00                             .h.
    decimal
             11  104    0
    datetime (2014-09-12T19:22:00)
    0000   0x80 0x56 0x53 0xac 0x0e                   .VS..
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [1, 0, 1]
#### RECORD 37 CalBGForPH 2014-09-12T19:34:35 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 250}
```
    op hex (2)
    0000   0x0a 0xfa                                  ..
    decimal
             10  250
    datetime (2014-09-12T19:34:35)
    0000   0xa3 0x62 0x33 0x6c 0x0e                   .b3l.
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 38 Ian3F 2014-09-12T19:34:35 head[2], body[3] op[0x3f]

    op hex (2)
    0000   0x3f 0x1f                                  ?.
    decimal
             63   31
    datetime (2014-09-12T19:34:35)
    0000   0xa3 0x62 0x53 0x6c 0x0e                   .bSl.
    body (3)
    hex
    0000   0x70 0x41 0x96                             pA.
    decimal
            112   65  150
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 39 BolusWizard 2014-09-12T19:35:03 head[2], body[13] op[0x5b]
###### DECODED
```python
{'_byte[5]': 56,
 '_byte[7]': 0,
 'bg': 139,
 'bg_target_high': 0,
 'bg_target_low': 25,
 'bolus_estimate': 0.0,
 'carb_input': 40,
 'carb_ratio': 0,
 'correction_estimate': 0.8,
 'food_estimate': 9.6,
 'sensitivity': 140,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 112}
```
    op hex (2)
    0000   0x5b 0x8b                                  [.
    decimal
             91  139
    datetime (2014-09-12T19:35:03)
    0000   0x83 0x63 0x13 0x0c 0x0e                   .c...
    body (13)
    hex
    0000   0x28 0x90 0x00 0x8c 0x19 0x38 0x60 0x00    (....8`.
    0008   0x70 0x00 0x00 0x00 0x00                   p....
    decimal
             40  144    0  140   25   56   96    0
            112    0    0    0    0
    HOUR BITS: [0, 1, 1]
#### RECORD 40 Base (2000, 0, 0, 16, 0, 1) head[2], body[0] op[0xd0]

    op hex (2)
    0000   0xd0 0x4e                                  .N
    decimal
            208   78
    datetime ((2000, 0, 0, 16, 0, 1))
    0000   0x01 0x00 0xd0 0x00 0xd0                   .....
    body (0)
    YEAR BITS: [1, 1, 0, 1]
`end logs/ReadHistoryData-page-14.data: 41 records`
