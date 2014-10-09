## START logs/ReadHistoryData-page-28.data
#### STOPPING DOUBLE NULLS @ 122, found 1 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0x95 0x1c 0x48 0x72 0x0e 0x0b 0x73 0x00    ..Hr..s.
    0008   0x91 0x0b 0x4a 0xb2 0x0e 0x0b 0x66 0x51    ..J...fQ
    0010   0x89 0x1b 0x4a 0xb2 0x0e 0x0a 0x72 0x8c    ..J...r.
    0018   0x23 0x2a 0x72 0x0e 0x3f 0x0e 0x8c 0x23    #*r.?..#
##### DEBUG DECIMAL
            149   28   72  114   14   11  115    0
            145   11   74  178   14   11  102   81
            137   27   74  178   14   10  114  140
             35   42  114   14   63   14  140   35
#### RECORD 0 Sara6E 2014-08-18T00:00:00 head[1], body[49] op[0x6e]

    op hex (1)
    0000   0x6e                                       n
    decimal
            110
    datetime (2014-08-18T00:00:00)
    0000   0x91 0x0e                                  ..
    body (49)
    hex
    0000   0x06 0x00 0x99 0x5f 0xc8 0x06 0x00 0x00    ..._....
    0008   0x04 0x81 0x01 0xcd 0x28 0x02 0xb4 0x3c    ....(..<
    0010   0x00 0xe1 0x01 0xf4 0x00 0x58 0x00 0x00    .....X..
    0018   0x00 0x68 0x02 0x02 0x00 0x03 0x00 0x91    .h......
    0020   0x03 0x5d 0x04 0x11 0x25 0x00 0x04 0x00    .]..%...
    0028   0x00 0x03 0x02 0x01 0x00 0x00 0x00 0x00    ........
    0030   0x00                                       .
    decimal
              6    0  153   95  200    6    0    0
              4  129    1  205   40    2  180   60
              0  225    1  244    0   88    0    0
              0  104    2    2    0    3    0  145
              3   93    4   17   37    0    4    0
              0    3    2    1    0    0    0    0
              0

#### RECORD 1 BasalProfileStart 2014-08-18T08:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x01                                  {.
    decimal
            123    1
    datetime (2014-08-18T08:00:00)
    0000   0x80 0x00 0x08 0x12 0x0e                   .....
    body (3)
    hex
    0000   0x10 0x1b 0x00                             ...
    decimal
             16   27    0

#### RECORD 2 CalBGForPH 2014-08-18T08:14:00 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 97}
```
    op hex (2)
    0000   0x0a 0x61                                  .a
    decimal
             10   97
    datetime (2014-08-18T08:14:00)
    0000   0x80 0x0e 0x28 0x72 0x0e                   ..(r.
    body (0)
    DAY BITS: [0, 1, 1]
#### RECORD 3 Ian3F 2014-08-18T08:14:00 head[2], body[3] op[0x3f]

    op hex (2)
    0000   0x3f 0x0c                                  ?.
    decimal
             63   12
    datetime (2014-08-18T08:14:00)
    0000   0x80 0x0e 0x28 0x72 0x0e                   ..(r.
    body (3)
    hex
    0000   0x70 0x41 0x96                             pA.
    decimal
            112   65  150
    DAY BITS: [0, 1, 1]
#### RECORD 4 CalBGForPH 2014-08-18T08:27:57 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 45}
```
    op hex (2)
    0000   0x0a 0x2d                                  .-
    decimal
             10   45
    datetime (2014-08-18T08:27:57)
    0000   0xb9 0x1b 0x48 0x12 0x0e                   ..H..
    body (0)

#### RECORD 5 CalBGForPH 2014-08-18T08:28:04 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 54}
```
    op hex (2)
    0000   0x0a 0x36                                  .6
    decimal
             10   54
    datetime (2014-08-18T08:28:04)
    0000   0x84 0x1c 0x48 0x12 0x0e                   ..H..
    body (0)

#### RECORD 6 BolusWizard 2014-08-18T08:28:21 head[2], body[13] op[0x5b]
###### DECODED
```python
{'_byte[5]': 56,
 '_byte[7]': 0,
 'bg': 54,
 'bg_target_high': 0,
 'bg_target_low': 28,
 'bolus_estimate': 0.0,
 'carb_input': 52,
 'carb_ratio': 0,
 'correction_estimate': 0.8,
 'food_estimate': 25.2,
 'sensitivity': 170,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 24.8,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 120}
```
    op hex (2)
    0000   0x5b 0x36                                  [6
    decimal
             91   54
    datetime (2014-08-18T08:28:21)
    0000   0x95 0x1c 0x08 0x72 0x0e                   ...r.
    body (13)
    hex
    0000   0x34 0x90 0x00 0xaa 0x1c 0x38 0xfc 0x00    4....8..
    0008   0x78 0xf8 0x00 0x00 0x00                   x....
    decimal
             52  144    0  170   28   56  252    0
            120  248    0    0    0
    DAY BITS: [0, 1, 1]
#### RECORD 7 Base (2004, 0, 0, 20, 0, 1) head[2], body[0] op[0x74]

    op hex (2)
    0000   0x74 0x4e                                  tN
    decimal
            116   78
    datetime ((2004, 0, 0, 20, 0, 1))
    0000   0x01 0x00 0x74 0x00 0x74                   ..t.t
    body (0)
    YEAR BITS: [0, 1, 1, 1]
`end logs/ReadHistoryData-page-28.data: 8 records`
