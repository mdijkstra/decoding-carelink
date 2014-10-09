## START logs/ReadHistoryData-page-9.data
#### STOPPING DOUBLE NULLS @ 78, found 1 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0xab 0x72 0x4b 0x75 0x0e 0x7b 0x02 0x80    .rKu.{..
    0008   0x40 0x0c 0x15 0x0e 0x18 0x06 0x00 0x5b    @......[
    0010   0x00 0xa9 0x4a 0x0c 0x75 0x0e 0x0a 0x90    ..J.u...
    0018   0x00 0x46 0x0c 0x38 0x00 0x00 0x38 0x00    .F.8..8.
##### DEBUG DECIMAL
            171  114   75  117   14  123    2  128
             64   12   21   14   24    6    0   91
              0  169   74   12  117   14   10  144
              0   70   12   56    0    0   56    0
#### RECORD 0 Ian0B 2014-09-21T10:08:13 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x73 0x00                             .s.
    decimal
             11  115    0
    datetime (2014-09-21T10:08:13)
    0000   0x8d 0x48 0x4a 0xb5 0x0e                   .HJ..
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [1, 0, 1]
#### RECORD 1 Ian0B 2014-09-21T10:21:54 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x66 0x51                             .fQ
    decimal
             11  102   81
    datetime (2014-09-21T10:21:54)
    0000   0xb6 0x55 0x4a 0xb5 0x0e                   .UJ..
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [1, 0, 1]
#### RECORD 2 Ian0B 2014-09-21T10:43:13 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x66 0x50                             .fP
    decimal
             11  102   80
    datetime (2014-09-21T10:43:13)
    0000   0x8d 0x6b 0x4a 0xb5 0x0e                   .kJ..
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [1, 0, 1]
#### RECORD 3 Ian0B 2014-09-21T11:01:54 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x66 0x51                             .fQ
    decimal
             11  102   81
    datetime (2014-09-21T11:01:54)
    0000   0xb6 0x41 0x4b 0xb5 0x0e                   .AK..
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [1, 0, 1]
#### RECORD 4 CalBGForPH 2014-09-21T11:15:07 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 95}
```
    op hex (2)
    0000   0x0a 0x5f                                  ._
    decimal
             10   95
    datetime (2014-09-21T11:15:07)
    0000   0x87 0x4f 0x2b 0x75 0x0e                   .O+u.
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 5 Ian3F 2014-09-21T11:15:07 head[2], body[3] op[0x3f]

    op hex (2)
    0000   0x3f 0x0b                                  ?.
    decimal
             63   11
    datetime (2014-09-21T11:15:07)
    0000   0x87 0x4f 0xeb 0x75 0x0e                   .O.u.
    body (3)
    hex
    0000   0x70 0x41 0x96                             pA.
    decimal
            112   65  150
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 6 BolusWizard 2014-09-21T11:50:43 head[2], body[13] op[0x5b]
###### DECODED
```python
{'_byte[5]': 56,
 '_byte[7]': 2,
 'bg': 0,
 'bg_target_high': 2,
 'bg_target_low': 12,
 'bolus_estimate': 0.0,
 'carb_input': 90,
 'carb_ratio': 0,
 'correction_estimate': 1.0,
 'food_estimate': 0.0,
 'sensitivity': 70,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 0}
```
    op hex (2)
    0000   0x5b 0x00                                  [.
    decimal
             91    0
    datetime (2014-09-21T11:50:43)
    0000   0xab 0x72 0x0b 0x75 0x0e                   .r.u.
    body (13)
    hex
    0000   0x5a 0x90 0x00 0x46 0x0c 0x38 0x00 0x02    Z..F.8..
    0008   0x00 0x00 0x00 0x00 0x02                   .....
    decimal
             90  144    0   70   12   56    0    2
              0    0    0    0    2
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 7 Base (2000, 0, 1, 16, 1, 1) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x4e                                  .N
    decimal
              0   78
    datetime ((2000, 0, 1, 16, 1, 1))
    0000   0x01 0x01 0x90 0x01 0x90                   .....
    body (0)
    YEAR BITS: [1, 0, 0, 1]
`end logs/ReadHistoryData-page-9.data: 8 records`
