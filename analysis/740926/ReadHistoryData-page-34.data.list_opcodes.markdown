## START logs/ReadHistoryData-page-34.data
#### STOPPING DOUBLE NULLS @ 142, found 1 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0xbc 0x4e 0x5c 0x0e 0x3c 0x51 0x80 0x44    .N\.<Q.D
    0008   0x6f 0x80 0xb4 0x79 0x80 0x0c 0xab 0x80    o..y....
    0010   0x01 0x00 0x8c 0x00 0x8c 0x00 0x20 0x00    ...... .
    0018   0x8f 0x3b 0x4d 0x08 0x0e 0x5b 0x00 0x9c    .;M..[..
##### DEBUG DECIMAL
            188   78   92   14   60   81  128   68
            111  128  180  121  128   12  171  128
              1    0  140    0  140    0   32    0
            143   59   77    8   14   91    0  156
#### RECORD 0 BasalProfileStart 2014-08-08T12:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x02                                  {.
    decimal
            123    2
    datetime (2014-08-08T12:00:00)
    0000   0x80 0x00 0x0c 0x08 0x0e                   .....
    body (3)
    hex
    0000   0x18 0x06 0x00                             ...
    decimal
             24    6    0

#### RECORD 1 BolusWizard 2014-08-08T12:02:09 head[2], body[13] op[0x5b]
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
    datetime (2014-08-08T12:02:09)
    0000   0x89 0x02 0x0c 0x08 0x0e                   .....
    body (13)
    hex
    0000   0x32 0x90 0x00 0x46 0x0c 0x38 0x00 0x01    2..F.8..
    0008   0x1c 0x00 0x00 0x00 0x01                   .....
    decimal
             50  144    0   70   12   56    0    1
             28    0    0    0    1

#### RECORD 2 Base (2000, 4, 22, 12, 5, 28) head[2], body[0] op[0x1c]

    op hex (2)
    0000   0x1c 0x4e                                  .N
    decimal
             28   78
    datetime ((2000, 4, 22, 12, 5, 28))
    0000   0x5c 0x05 0x0c 0x36 0x80                   \..6.
    body (0)
    DAY BITS: [0, 0, 1] YEAR BITS: [1, 0, 0, 0]
#### RECORD 3 CalBGForPH 2014-08-08T12:02:56 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 145}
```
    op hex (2)
    0000   0x0a 0x91                                  ..
    decimal
             10  145
    datetime (2014-08-08T12:02:56)
    0000   0xb8 0x02 0x2c 0x68 0x0e                   ..,h.
    body (0)
    DAY BITS: [0, 1, 1]
#### RECORD 4 Ian3F 2014-08-08T12:02:56 head[2], body[3] op[0x3f]

    op hex (2)
    0000   0x3f 0x12                                  ?.
    decimal
             63   18
    datetime (2014-08-08T12:02:56)
    0000   0xb8 0x02 0x2c 0x68 0x0e                   ..,h.
    body (3)
    hex
    0000   0x70 0x41 0x96                             pA.
    decimal
            112   65  150
    DAY BITS: [0, 1, 1]
#### RECORD 5 Bolus (2009, 8, 0, 8, 0, 52) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 18.0, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x00 0xb4 0x00                        ....
    decimal
              1    0  180    0
    datetime ((2009, 8, 0, 8, 0, 52))
    0000   0xb4 0x00 0x08 0x00 0x89                   .....
    body (0)
    YEAR BITS: [1, 0, 0, 0]
#### RECORD 6 Base (2008, 0, 16, 27, 14, 8) head[2], body[0] op[0x02]

    op hex (2)
    0000   0x02 0x4c                                  .L
    decimal
              2   76
    datetime ((2008, 0, 16, 27, 14, 8))
    0000   0x08 0x0e 0x5b 0x50 0x88                   ..[P.
    body (0)
    DAY BITS: [0, 1, 0] YEAR BITS: [1, 0, 0, 0]
#### RECORD 7 ClearAlarm 2000-04-16T12:14:40 head[2], body[0] op[0x0c]

    op hex (2)
    0000   0x0c 0x0c                                  ..
    decimal
             12   12
    datetime (2000-04-16T12:14:40)
    0000   0x68 0x0e 0x0c 0x90 0x00                   h....
    body (0)
    DAY BITS: [1, 0, 0]
#### RECORD 8 Base (2000, 0, 4, 0, 4, 56) head[2], body[0] op[0x46]

    op hex (2)
    0000   0x46 0x0c                                  F.
    decimal
             70   12
    datetime ((2000, 0, 4, 0, 4, 56))
    0000   0x38 0x04 0x00 0x44 0x00                   8..D.
    body (0)
    DAY BITS: [0, 1, 0]
#### RECORD 9 Base (2008, 1, 28, 14, 4, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0xb4                                  ..
    decimal
              0  180
    datetime ((2008, 1, 28, 14, 4, 0))
    0000   0x00 0x44 0x4e 0x5c 0x08                   .DN\.
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 0]
#### RECORD 10 Base (2001, 8, 0, 0, 12, 0) head[2], body[0] op[0xb4]

    op hex (2)
    0000   0xb4 0x0e                                  ..
    decimal
            180   14
    datetime ((2001, 8, 0, 0, 12, 0))
    0000   0x80 0x0c 0x40 0x80 0x01                   ..@..
    body (0)
    DAY BITS: [1, 0, 0]
#### RECORD 11 Base (2000, 1, 20, 0, 4, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x44                                  .D
    decimal
              0   68
    datetime ((2000, 1, 20, 0, 4, 0))
    0000   0x00 0x44 0x00 0xb4 0x00                   .D...
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [1, 0, 1]
#### RECORD 12 Base (2000, 5, 1, 14, 40, 12) head[2], body[0] op[0x88]

    op hex (2)
    0000   0x88 0x0c                                  ..
    decimal
            136   12
    datetime ((2000, 5, 1, 14, 40, 12))
    0000   0x4c 0x68 0x0e 0x01 0x00                   Lh...
    body (0)
    HOUR BITS: [0, 1, 1]
#### RECORD 13 Base (2011, 0, 0, 24, 0, 60) head[2], body[0] op[0x3c]

    op hex (2)
    0000   0x3c 0x00                                  <.
    decimal
             60    0
    datetime ((2011, 0, 0, 24, 0, 60))
    0000   0x3c 0x00 0xb8 0x00 0xbb                   <....
    body (0)
    YEAR BITS: [1, 0, 1, 1]
#### RECORD 14 ChangeRemoteID (2015, 0, 0, 27, 14, 8) head[2], body[0] op[0x27]

    op hex (2)
    0000   0x27 0x4c                                  'L
    decimal
             39   76
    datetime ((2015, 0, 0, 27, 14, 8))
    0000   0x08 0x0e 0x5b 0x00 0x8f                   ..[..
    body (0)
    YEAR BITS: [1, 0, 0, 0]
#### RECORD 15 Base (2000, 0, 16, 1, 14, 8) head[2], body[0] op[0x3b]

    op hex (2)
    0000   0x3b 0x0d                                  ;.
    decimal
             59   13
    datetime ((2000, 0, 16, 1, 14, 8))
    0000   0x08 0x0e 0x21 0x90 0x00                   ..!..
    body (0)
    DAY BITS: [1, 0, 0]
#### RECORD 16 Base (2000, 0, 28, 0, 0, 56) head[2], body[0] op[0x46]

    op hex (2)
    0000   0x46 0x0c                                  F.
    decimal
             70   12
    datetime ((2000, 0, 28, 0, 0, 56))
    0000   0x38 0x00 0x00 0xbc 0x00                   8....
    body (0)
    DAY BITS: [1, 0, 1]
`end logs/ReadHistoryData-page-34.data: 17 records`
