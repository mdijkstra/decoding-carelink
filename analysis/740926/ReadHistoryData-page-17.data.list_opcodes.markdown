## START logs/ReadHistoryData-page-17.data
#### STOPPING DOUBLE NULLS @ 125, found 1 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0x90 0x6d 0x4b 0x65 0x0e 0x7b 0x02 0x80    .mKe.{..
    0008   0x40 0x0c 0x05 0x0e 0x18 0x06 0x00 0x0b    @.......
    0010   0x73 0x00 0x8c 0x72 0x4c 0xa5 0x0e 0x0b    s..rL...
    0018   0x73 0x00 0x8c 0x63 0x4d 0xa5 0x0e 0x0a    s..cM...
##### DEBUG DECIMAL
            144  109   75  101   14  123    2  128
             64   12    5   14   24    6    0   11
            115    0  140  114   76  165   14   11
            115    0  140   99   77  165   14   10
#### RECORD 0 Sara6E 2014-09-05T00:00:00 head[1], body[49] op[0x6e]

    op hex (1)
    0000   0x6e                                       n
    decimal
            110
    datetime (2014-09-05T00:00:00)
    0000   0x84 0x8e                                  ..
    body (49)
    hex
    0000   0x06 0x40 0x96 0x50 0x8b 0x04 0x00 0x00    .@.P....
    0008   0x04 0xf0 0x01 0xd4 0x25 0x03 0x1c 0x3f    ....%..?
    0010   0x00 0x8d 0x01 0xe0 0x00 0x3c 0x00 0x00    .....<..
    0018   0x01 0x00 0x01 0x01 0x00 0x07 0x04 0xa7    ........
    0020   0x13 0x51 0x00 0x20 0x3f 0x00 0x02 0x19    .Q. ?...
    0028   0x19 0x00 0x04 0x01 0x00 0x00 0x00 0x00    ........
    0030   0x00                                       .
    decimal
              6   64  150   80  139    4    0    0
              4  240    1  212   37    3   28   63
              0  141    1  224    0   60    0    0
              1    0    1    1    0    7    4  167
             19   81    0   32   63    0    2   25
             25    0    4    1    0    0    0    0
              0
    HOUR BITS: [1, 0, 0]
#### RECORD 1 CalBGForPH 2014-09-05T01:15:01 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 88}
```
    op hex (2)
    0000   0x0a 0x58                                  .X
    decimal
             10   88
    datetime (2014-09-05T01:15:01)
    0000   0x81 0x4f 0x21 0x65 0x0e                   .O!e.
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 2 Ian3F 2014-09-05T01:15:01 head[2], body[3] op[0x3f]

    op hex (2)
    0000   0x3f 0x0b                                  ?.
    decimal
             63   11
    datetime (2014-09-05T01:15:01)
    0000   0x81 0x4f 0x01 0x65 0x0e                   .O.e.
    body (3)
    hex
    0000   0x70 0x41 0x96                             pA.
    decimal
            112   65  150
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 3 BasalProfileStart 2014-09-05T08:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x01                                  {.
    decimal
            123    1
    datetime (2014-09-05T08:00:00)
    0000   0x80 0x40 0x08 0x05 0x0e                   .@...
    body (3)
    hex
    0000   0x10 0x1b 0x00                             ...
    decimal
             16   27    0
    HOUR BITS: [0, 1, 0]
#### RECORD 4 CalBGForPH 2014-09-05T08:51:07 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 141}
```
    op hex (2)
    0000   0x0a 0x8d                                  ..
    decimal
             10  141
    datetime (2014-09-05T08:51:07)
    0000   0x87 0x73 0x28 0x65 0x0e                   .s(e.
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 5 Ian3F 2014-09-05T08:51:07 head[2], body[3] op[0x3f]

    op hex (2)
    0000   0x3f 0x11                                  ?.
    decimal
             63   17
    datetime (2014-09-05T08:51:07)
    0000   0x87 0x73 0xa8 0x65 0x0e                   .s.e.
    body (3)
    hex
    0000   0x70 0x41 0x96                             pA.
    decimal
            112   65  150
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 6 BolusWizard 2014-09-05T11:45:16 head[2], body[13] op[0x5b]
###### DECODED
```python
{'_byte[5]': 56,
 '_byte[7]': 1,
 'bg': 0,
 'bg_target_high': 1,
 'bg_target_low': 12,
 'bolus_estimate': 0.0,
 'carb_input': 65,
 'carb_ratio': 0,
 'correction_estimate': 0.9,
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
    datetime (2014-09-05T11:45:16)
    0000   0x90 0x6d 0x0b 0x65 0x0e                   .m.e.
    body (13)
    hex
    0000   0x41 0x90 0x00 0x46 0x0c 0x38 0x00 0x01    A..F.8..
    0008   0x70 0x00 0x00 0x00 0x01                   p....
    decimal
             65  144    0   70   12   56    0    1
            112    0    0    0    1
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 7 Base (2000, 0, 1, 16, 1, 1) head[2], body[0] op[0x70]

    op hex (2)
    0000   0x70 0x4e                                  pN
    decimal
            112   78
    datetime ((2000, 0, 1, 16, 1, 1))
    0000   0x01 0x01 0x70 0x01 0x70                   ..p.p
    body (0)
    YEAR BITS: [0, 1, 1, 1]
`end logs/ReadHistoryData-page-17.data: 8 records`
