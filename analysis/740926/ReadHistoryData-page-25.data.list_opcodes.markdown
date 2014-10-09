## START logs/ReadHistoryData-page-25.data
#### STOPPING DOUBLE NULLS @ 259, found 0 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0x18 0x0e 0x00 0x14 0x00 0x07 0x00 0x00    ........
    0008   0x03 0xab 0x97 0x0e 0x00 0x00 0x00 0x6e    .......n
    0010   0x97 0x0e 0x06 0x10 0xcc 0x8d 0x25 0x03    ......%.
    0018   0x00 0x00 0x03 0xab 0x01 0xb7 0x2f 0x01    ....../.
##### DEBUG DECIMAL
             24   14    0   20    0    7    0    0
              3  171  151   14    0    0    0  110
            151   14    6   16  204  141   37    3
              0    0    3  171    1  183   47    1
#### RECORD 0 BolusWizard 2014-08-23T17:57:48 head[2], body[13] op[0x5b]
###### DECODED
```python
{'_byte[5]': 56,
 '_byte[7]': 0,
 'bg': 0,
 'bg_target_high': 0,
 'bg_target_low': 25,
 'bolus_estimate': 0.0,
 'carb_input': 120,
 'carb_ratio': 0,
 'correction_estimate': 0.8,
 'food_estimate': 0.0,
 'sensitivity': 200,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 240}
```
    op hex (2)
    0000   0x5b 0x00                                  [.
    decimal
             91    0
    datetime (2014-08-23T17:57:48)
    0000   0xb0 0x39 0x11 0x77 0x0e                   .9.w.
    body (13)
    hex
    0000   0x78 0x90 0x00 0xc8 0x19 0x38 0x00 0x00    x....8..
    0008   0xf0 0x00 0x00 0x00 0x00                   .....
    decimal
            120  144    0  200   25   56    0    0
            240    0    0    0    0
    HOUR BITS: [0, 0, 1] DAY BITS: [0, 1, 1]
#### RECORD 1 Base (2000, 4, 17, 8, 8, 28) head[2], body[0] op[0xf0]

    op hex (2)
    0000   0xf0 0x4e                                  .N
    decimal
            240   78
    datetime ((2000, 4, 17, 8, 8, 28))
    0000   0x5c 0x08 0x28 0xd1 0x80                   \.(..
    body (0)
    DAY BITS: [1, 1, 0] YEAR BITS: [1, 0, 0, 0]
#### RECORD 2 Base (2000, 9, 0, 3, 59, 16) head[2], body[0] op[0xa0]

    op hex (2)
    0000   0xa0 0x3f                                  .?
    decimal
            160   63
    datetime ((2000, 9, 0, 3, 59, 16))
    0000   0x90 0x7b 0x03 0x80 0x00                   .{...
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [1, 0, 0]
#### RECORD 3 Base (2001, 0, 0, 24, 36, 14) head[2], body[0] op[0x12]

    op hex (2)
    0000   0x12 0x17                                  ..
    decimal
             18   23
    datetime ((2001, 0, 0, 24, 36, 14))
    0000   0x0e 0x24 0x18 0x00 0x01                   .$...
    body (0)
    HOUR BITS: [0, 0, 1]
#### RECORD 4 Base (2000, 3, 0, 0, 8, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0xc8                                  ..
    decimal
              0  200
    datetime ((2000, 3, 0, 0, 8, 0))
    0000   0x00 0xc8 0x00 0x00 0x00                   .....
    body (0)
    HOUR BITS: [1, 1, 0]
#### RECORD 5 Base (2000, 5, 1, 14, 55, 17) head[2], body[0] op[0xb0]

    op hex (2)
    0000   0xb0 0x39                                  .9
    decimal
            176   57
    datetime ((2000, 5, 1, 14, 55, 17))
    0000   0x51 0x77 0x0e 0x01 0x00                   Qw...
    body (0)
    HOUR BITS: [0, 1, 1]
#### RECORD 6 Base (2007, 0, 0, 20, 0, 40) head[2], body[0] op[0x28]

    op hex (2)
    0000   0x28 0x00                                  (.
    decimal
             40    0
    datetime ((2007, 0, 0, 20, 0, 40))
    0000   0x28 0x00 0xb4 0x00 0x87                   (....
    body (0)
    YEAR BITS: [1, 0, 0, 0]
#### RECORD 7 Base (2004, 0, 0, 1, 14, 23) head[2], body[0] op[0x15]

    op hex (2)
    0000   0x15 0x52                                  .R
    decimal
             21   82
    datetime ((2004, 0, 0, 1, 14, 23))
    0000   0x17 0x0e 0x01 0x00 0x14                   .....
    body (0)
    YEAR BITS: [0, 0, 0, 1]
#### RECORD 8 Base (2000, 3, 12, 0, 4, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x14                                  ..
    decimal
              0   20
    datetime ((2000, 3, 12, 0, 4, 0))
    0000   0x00 0xc4 0x00 0xac 0x20                   .... 
    body (0)
    HOUR BITS: [1, 1, 0] DAY BITS: [1, 0, 1] YEAR BITS: [0, 0, 1, 0]
#### RECORD 9 Base (2000, 0, 20, 0, 1, 14) head[2], body[0] op[0x52]

    op hex (2)
    0000   0x52 0x17                                  R.
    decimal
             82   23
    datetime ((2000, 0, 20, 0, 1, 14))
    0000   0x0e 0x01 0x00 0x14 0x00                   .....
    body (0)

#### RECORD 10 SelectBasalProfile 2002-08-23T14:00:20 head[2], body[0] op[0x14]

    op hex (2)
    0000   0x14 0x00                                  ..
    decimal
             20    0
    datetime (2002-08-23T14:00:20)
    0000   0x94 0x00 0xae 0x37 0x52                   ...7R
    body (0)
    DAY BITS: [0, 0, 1] YEAR BITS: [0, 1, 0, 1]
#### RECORD 11 ChangeTime 2001-01-24T06:37:11 head[2], body[0] op[0x17]

    op hex (2)
    0000   0x17 0x0e                                  ..
    decimal
             23   14
    datetime (2001-01-24T06:37:11)
    0000   0x0b 0x65 0xc6 0xb8 0x01                   .e...
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [1, 0, 1]
#### RECORD 12 Base (2000, 1, 0, 4, 59, 14) head[2], body[0] op[0x53]

    op hex (2)
    0000   0x53 0xb7                                  S.
    decimal
             83  183
    datetime ((2000, 1, 0, 4, 59, 14))
    0000   0x0e 0x7b 0x04 0x80 0x00                   .{...
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [1, 0, 0]
#### RECORD 13 SelectBasalProfile (2010, 0, 0, 29, 40, 14) head[2], body[0] op[0x14]

    op hex (2)
    0000   0x14 0x17                                  ..
    decimal
             20   23
    datetime ((2010, 0, 0, 29, 40, 14))
    0000   0x0e 0x28 0x1d 0x00 0x0a                   .(...
    body (0)
    HOUR BITS: [0, 0, 1]
#### RECORD 14 Base (2015, 0, 14, 23, 52, 10) head[2], body[0] op[0x25]

    op hex (2)
    0000   0x25 0x85                                  %.
    decimal
             37  133
    datetime ((2015, 0, 14, 23, 52, 10))
    0000   0x0a 0x34 0x77 0x8e 0x3f                   .4w.?
    body (0)
    HOUR BITS: [0, 0, 1] DAY BITS: [1, 0, 0] YEAR BITS: [0, 0, 1, 1]
#### RECORD 15 Base (2000, 2, 14, 23, 52, 10) head[2], body[0] op[0x24]

    op hex (2)
    0000   0x24 0x85                                  $.
    decimal
             36  133
    datetime ((2000, 2, 14, 23, 52, 10))
    0000   0x0a 0xb4 0x77 0x0e 0x70                   ..w.p
    body (0)
    HOUR BITS: [1, 0, 1] YEAR BITS: [0, 1, 1, 1]
#### RECORD 16 Base (2004, 0, 11, 12, 50, 51) head[2], body[0] op[0x41]

    op hex (2)
    0000   0x41 0x96                                  A.
    decimal
             65  150
    datetime ((2004, 0, 11, 12, 50, 51))
    0000   0x33 0x32 0x8c 0x0b 0x14                   32...
    body (0)
    HOUR BITS: [0, 0, 1] YEAR BITS: [0, 0, 0, 1]
#### RECORD 17 ChangeTime (2011, 0, 12, 2, 22, 8) head[2], body[0] op[0x17]

    op hex (2)
    0000   0x17 0x0e                                  ..
    decimal
             23   14
    datetime ((2011, 0, 12, 2, 22, 8))
    0000   0x08 0x16 0x02 0x8c 0x0b                   .....
    body (0)
    DAY BITS: [1, 0, 0]
#### RECORD 18 SelectBasalProfile (2000, 0, 26, 0, 51, 14) head[2], body[0] op[0x14]

    op hex (2)
    0000   0x14 0x17                                  ..
    decimal
             20   23
    datetime ((2000, 0, 26, 0, 51, 14))
    0000   0x0e 0x33 0x00 0xba 0x10                   .3...
    body (0)
    HOUR BITS: [0, 0, 1] DAY BITS: [1, 0, 1] YEAR BITS: [0, 0, 0, 1]
#### RECORD 19 SelectBasalProfile (2010, 0, 0, 22, 8, 14) head[2], body[0] op[0x14]

    op hex (2)
    0000   0x14 0x17                                  ..
    decimal
             20   23
    datetime ((2010, 0, 0, 22, 8, 14))
    0000   0x0e 0x08 0x16 0x00 0xba                   .....
    body (0)
    YEAR BITS: [1, 0, 1, 1]
#### RECORD 20 Base (2010, 0, 4, 27, 14, 23) head[2], body[0] op[0x10]

    op hex (2)
    0000   0x10 0x14                                  ..
    decimal
             16   20
    datetime ((2010, 0, 4, 27, 14, 23))
    0000   0x17 0x0e 0x7b 0x04 0xba                   ..{..
    body (0)
    YEAR BITS: [1, 0, 1, 1]
#### RECORD 21 Base (2000, 0, 29, 8, 14, 23) head[2], body[0] op[0x10]

    op hex (2)
    0000   0x10 0x14                                  ..
    decimal
             16   20
    datetime ((2000, 0, 29, 8, 14, 23))
    0000   0x17 0x0e 0x28 0x1d 0x00                   ..(..
    body (0)

#### RECORD 22 Ian0B 2014-08-23T20:31:10 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x65 0x13                             .e.
    decimal
             11  101   19
    datetime (2014-08-23T20:31:10)
    0000   0x8a 0x1f 0x54 0xb7 0x8e                   ..T..
    body (0)
    DAY BITS: [1, 0, 1] YEAR BITS: [1, 0, 0, 0]
#### RECORD 23 Ian0B 2014-08-23T21:01:56 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x75 0x00                             .u.
    decimal
             11  117    0
    datetime (2014-08-23T21:01:56)
    0000   0xb8 0x01 0x55 0xb7 0x0e                   ..U..
    body (0)
    DAY BITS: [1, 0, 1]
#### RECORD 24 TempBasal 2014-08-23T21:02:34 head[2], body[1] op[0x33]
###### DECODED
```python
{'rate': 1.25}
```
    op hex (2)
    0000   0x33 0x32                                  32
    decimal
             51   50
    datetime (2014-08-23T21:02:34)
    0000   0xa2 0x02 0x15 0x17 0x0e                   .....
    body (1)
    hex
    0000   0x08                                       .
    decimal
              8

#### RECORD 25 TempBasalDuration 2014-08-23T21:02:34 head[2], body[0] op[0x16]
###### DECODED
```python
{'duration (min)': 30}
```
    op hex (2)
    0000   0x16 0x01                                  ..
    decimal
             22    1
    datetime (2014-08-23T21:02:34)
    0000   0xa2 0x02 0x15 0x17 0x0e                   .....
    body (0)

#### RECORD 26 CalBGForPH 2014-08-23T21:22:01 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 141}
```
    op hex (2)
    0000   0x0a 0x8d                                  ..
    decimal
             10  141
    datetime (2014-08-23T21:22:01)
    0000   0x81 0x16 0x35 0x77 0x0e                   ..5w.
    body (0)
    DAY BITS: [0, 1, 1]
#### RECORD 27 Ian3F 2014-08-23T21:22:01 head[2], body[3] op[0x3f]

    op hex (2)
    0000   0x3f 0x11                                  ?.
    decimal
             63   17
    datetime (2014-08-23T21:22:01)
    0000   0x81 0x16 0xb5 0x77 0x0e                   ...w.
    body (3)
    hex
    0000   0x70 0x41 0x96                             pA.
    decimal
            112   65  150
    DAY BITS: [0, 1, 1]
#### RECORD 28 BasalProfileStart 2014-08-23T21:32:34 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x04                                  {.
    decimal
            123    4
    datetime (2014-08-23T21:32:34)
    0000   0xa2 0x20 0x15 0x17 0x0e                   . ...
    body (3)
    hex
    0000   0x28 0x1d 0x00                             (..
    decimal
             40   29    0
    HOUR BITS: [0, 0, 1]
#### RECORD 29 Ian0B 2014-08-23T22:05:46 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x73 0x00                             .s.
    decimal
             11  115    0
    datetime (2014-08-23T22:05:46)
    0000   0xae 0x05 0x56 0xb7 0x0e                   ..V..
    body (0)
    DAY BITS: [1, 0, 1]
#### RECORD 30 Ian0B 2014-08-23T22:27:06 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x73 0x00                             .s.
    decimal
             11  115    0
    datetime (2014-08-23T22:27:06)
    0000   0x86 0x1b 0x56 0xb7 0x0e                   ..V..
    body (0)
    DAY BITS: [1, 0, 1]
#### RECORD 31 Bolus (2015, 0, 0, 0, 0, 20) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 2.0, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x00 0x14 0x00                        ....
    decimal
              1    0   20    0
    datetime ((2015, 0, 0, 0, 0, 20))
    0000   0x14 0x00 0x00 0x00 0x8f                   .....
    body (0)
    YEAR BITS: [1, 0, 0, 0]
#### RECORD 32 Base (2000, 0, 0, 27, 14, 23) head[2], body[0] op[0x0f]

    op hex (2)
    0000   0x0f 0x57                                  .W
    decimal
             15   87
    datetime ((2000, 0, 0, 27, 14, 23))
    0000   0x17 0x0e 0x7b 0x00 0x80                   ..{..
    body (0)
    YEAR BITS: [1, 0, 0, 0]
`end logs/ReadHistoryData-page-25.data: 33 records`
