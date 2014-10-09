## START logs/ReadHistoryData-page-7.data
#### STOPPING DOUBLE NULLS @ 206, found 1 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0x6e 0x99 0x8e 0x06 0x00 0x70 0x45 0xae    n....pE.
    0008   0x03 0x00 0x00 0x04 0x90 0x01 0xd4 0x28    .......(
    0010   0x02 0xbc 0x3c 0x00 0x98 0x02 0x38 0x00    ..<...8.
    0018   0x00 0x00 0x00 0x00 0x84 0x03 0x00 0x00    ........
##### DEBUG DECIMAL
            110  153  142    6    0  112   69  174
              3    0    0    4  144    1  212   40
              2  188   60    0  152    2   56    0
              0    0    0    0  132    3    0    0
#### RECORD 0 Ian0B 2014-09-25T17:12:03 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x65 0xca                             .e.
    decimal
             11  101  202
    datetime (2014-09-25T17:12:03)
    0000   0x83 0x4c 0x51 0xb9 0x0e                   .LQ..
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [1, 0, 1]
#### RECORD 1 Bolus (2014, 0, 0, 0, 0, 40) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 4.0, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x00 0x28 0x00                        ..(.
    decimal
              1    0   40    0
    datetime ((2014, 0, 0, 0, 0, 40))
    0000   0x28 0x00 0x00 0x00 0x8e                   (....
    body (0)
    YEAR BITS: [1, 0, 0, 0]
#### RECORD 2 Base (2000, 0, 3, 27, 14, 25) head[2], body[0] op[0x4c]

    op hex (2)
    0000   0x4c 0x51                                  LQ
    decimal
             76   81
    datetime ((2000, 0, 3, 27, 14, 25))
    0000   0x19 0x0e 0x7b 0x03 0x80                   ..{..
    body (0)
    YEAR BITS: [1, 0, 0, 0]
#### RECORD 3 Base (2000, 0, 24, 4, 14, 25) head[2], body[0] op[0x40]

    op hex (2)
    0000   0x40 0x12                                  @.
    decimal
             64   18
    datetime ((2000, 0, 24, 4, 14, 25))
    0000   0x19 0x0e 0x24 0x18 0x00                   ..$..
    body (0)

#### RECORD 4 BasalProfileStart 2014-09-25T20:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x04                                  {.
    decimal
            123    4
    datetime (2014-09-25T20:00:00)
    0000   0x80 0x40 0x14 0x19 0x0e                   .@...
    body (3)
    hex
    0000   0x28 0x1d 0x00                             (..
    decimal
             40   29    0
    HOUR BITS: [0, 1, 0]
#### RECORD 5 Ian0B 2014-09-25T20:17:27 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x73 0x00                             .s.
    decimal
             11  115    0
    datetime (2014-09-25T20:17:27)
    0000   0x9b 0x51 0x54 0xb9 0x0e                   .QT..
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [1, 0, 1]
#### RECORD 6 BolusWizard 2014-09-25T20:19:24 head[2], body[13] op[0x5b]
###### DECODED
```python
{'_byte[5]': 56,
 '_byte[7]': 0,
 'bg': 0,
 'bg_target_high': 0,
 'bg_target_low': 25,
 'bolus_estimate': 0.0,
 'carb_input': 42,
 'carb_ratio': 0,
 'correction_estimate': 0.8,
 'food_estimate': 0.0,
 'sensitivity': 140,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 120}
```
    op hex (2)
    0000   0x5b 0x00                                  [.
    decimal
             91    0
    datetime (2014-09-25T20:19:24)
    0000   0x98 0x53 0x14 0x79 0x0e                   .S.y.
    body (13)
    hex
    0000   0x2a 0x90 0x00 0x8c 0x19 0x38 0x00 0x00    *....8..
    0008   0x78 0x00 0x00 0x00 0x00                   x....
    decimal
             42  144    0  140   25   56    0    0
            120    0    0    0    0
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 7 Base (2000, 4, 31, 8, 8, 28) head[2], body[0] op[0x78]

    op hex (2)
    0000   0x78 0x4e                                  xN
    decimal
            120   78
    datetime ((2000, 4, 31, 8, 8, 28))
    0000   0x5c 0x08 0x28 0xbf 0x80                   \.(..
    body (0)
    DAY BITS: [1, 0, 1] YEAR BITS: [1, 0, 0, 0]
#### RECORD 8 SelectBasalProfile 2000-08-28T00:01:16 head[2], body[0] op[0x14]

    op hex (2)
    0000   0x14 0x55                                  .U
    decimal
             20   85
    datetime (2000-08-28T00:01:16)
    0000   0x90 0x01 0x00 0x3c 0x00                   ...<.
    body (0)
    DAY BITS: [0, 0, 1]
#### RECORD 9 Base (2004, 0, 19, 24, 0, 0) head[2], body[0] op[0x3c]

    op hex (2)
    0000   0x3c 0x00                                  <.
    decimal
             60    0
    datetime ((2004, 0, 19, 24, 0, 0))
    0000   0x00 0x00 0x98 0x53 0x54                   ...ST
    body (0)
    DAY BITS: [0, 1, 0] YEAR BITS: [0, 1, 0, 1]
#### RECORD 10 Base (2004, 1, 1, 1, 29, 10) head[2], body[0] op[0x79]

    op hex (2)
    0000   0x79 0x0e                                  y.
    decimal
            121   14
    datetime ((2004, 1, 1, 1, 29, 10))
    0000   0x0a 0x5d 0xa1 0x61 0x34                   .].a4
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1] YEAR BITS: [0, 0, 1, 1]
#### RECORD 11 Base (2004, 0, 1, 1, 11, 63) head[2], body[0] op[0x79]

    op hex (2)
    0000   0x79 0x0e                                  y.
    decimal
            121   14
    datetime ((2004, 0, 1, 1, 11, 63))
    0000   0x3f 0x0b 0xa1 0x61 0xb4                   ?..a.
    body (0)
    DAY BITS: [0, 1, 1] YEAR BITS: [1, 0, 1, 1]
#### RECORD 12 Base (2000, 5, 1, 22, 1, 48) head[2], body[0] op[0x79]

    op hex (2)
    0000   0x79 0x0e                                  y.
    decimal
            121   14
    datetime ((2000, 5, 1, 22, 1, 48))
    0000   0x70 0x41 0x96 0x01 0x00                   pA...
    body (0)
    HOUR BITS: [0, 1, 0]
#### RECORD 13 ClearAlarm (2011, 0, 0, 8, 0, 12) head[2], body[0] op[0x0c]

    op hex (2)
    0000   0x0c 0x00                                  ..
    decimal
             12    0
    datetime ((2011, 0, 0, 8, 0, 12))
    0000   0x0c 0x00 0x28 0x00 0x9b                   ..(..
    body (0)
    YEAR BITS: [1, 0, 0, 1]
#### RECORD 14 Base (2000, 0, 19, 11, 14, 25) head[2], body[0] op[0x44]

    op hex (2)
    0000   0x44 0x55                                  DU
    decimal
             68   85
    datetime ((2000, 0, 19, 11, 14, 25))
    0000   0x19 0x0e 0x0b 0x73 0x00                   ...s.
    body (0)
    DAY BITS: [0, 1, 1]
#### RECORD 15 Base (2006, 6, 11, 14, 57, 22) head[2], body[0] op[0xb6]

    op hex (2)
    0000   0xb6 0x55                                  .U
    decimal
            182   85
    datetime ((2006, 6, 11, 14, 57, 22))
    0000   0x56 0xb9 0x0e 0x0b 0x66                   V...f
    body (0)
    HOUR BITS: [1, 0, 1] YEAR BITS: [0, 1, 1, 0]
#### RECORD 16 Base (2010, 5, 14, 25, 22, 32) head[2], body[0] op[0x4e]

    op hex (2)
    0000   0x4e 0x83                                  N.
    decimal
             78  131
    datetime ((2010, 5, 14, 25, 22, 32))
    0000   0x60 0x56 0xb9 0x0e 0x0a                   `V...
    body (0)
    HOUR BITS: [0, 1, 0]
#### RECORD 17 Base (2015, 4, 14, 25, 54, 33) head[2], body[0] op[0x45]

    op hex (2)
    0000   0x45 0xb9                                  E.
    decimal
             69  185
    datetime ((2015, 4, 14, 25, 54, 33))
    0000   0x61 0x36 0x79 0x0e 0x3f                   a6y.?
    body (0)
    HOUR BITS: [0, 0, 1] YEAR BITS: [0, 0, 1, 1]
#### RECORD 18 ChangeBasalProfile (2000, 6, 14, 25, 54, 33) head[2], body[44] op[0x08]

    op hex (2)
    0000   0x08 0xb9                                  ..
    decimal
              8  185
    datetime ((2000, 6, 14, 25, 54, 33))
    0000   0x61 0xb6 0x79 0x0e 0x70                   a.y.p
    body (44)
    hex
    0000   0x41 0x96 0x0b 0x66 0x4e 0x97 0x75 0x56    A..fN.uV
    0008   0xb9 0x0e 0x0b 0x73 0x00 0x9f 0x51 0x57    ...s..QW
    0010   0xb9 0x0e 0x0b 0x66 0x50 0x9b 0x65 0x57    ...fP.eW
    0018   0xb9 0x0e 0x0b 0x66 0x50 0x9f 0x79 0x57    ...fP.yW
    0020   0xb9 0x0e 0x7b 0x00 0x80 0x40 0x00 0x1a    ..{..@..
    0028   0x0e 0x00 0x14 0x00                        ....
    decimal
             65  150   11  102   78  151  117   86
            185   14   11  115    0  159   81   87
            185   14   11  102   80  155  101   87
            185   14   11  102   80  159  121   87
            185   14  123    0  128   64    0   26
             14    0   20    0
    HOUR BITS: [1, 0, 1] YEAR BITS: [0, 1, 1, 1]
#### RECORD 19 MResultTotals 2014-09-26T00:00:00 head[5], body[0] op[0x07]

    op hex (5)
    0000   0x07 0x00 0x00 0x04 0x90                   .....
    decimal
              7    0    0    4  144
    datetime (2014-09-26T00:00:00)
    0000   0x99 0x8e                                  ..
    body (0)
    HOUR BITS: [1, 0, 0]
`end logs/ReadHistoryData-page-7.data: 20 records`
