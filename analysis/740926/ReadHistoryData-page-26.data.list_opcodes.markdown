## START logs/ReadHistoryData-page-26.data
#### STOPPING DOUBLE NULLS @ 74, found 1 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0x91 0x30 0x4c 0x75 0x0e 0x01 0x00 0xa8    .0Lu....
    0008   0x00 0xa8 0x00 0xe0 0x00 0xaf 0x16 0x4d    .......M
    0010   0x15 0x0e 0x01 0x00 0xb4 0x00 0xb4 0x01    ........
    0018   0x68 0x00 0xa3 0x1e 0x4d 0x15 0x0e 0x0b    h...M...
##### DEBUG DECIMAL
            145   48   76  117   14    1    0  168
              0  168    0  224    0  175   22   77
             21   14    1    0  180    0  180    1
            104    0  163   30   77   21   14   11
#### RECORD 0 BasalProfileStart 2014-08-21T08:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x01                                  {.
    decimal
            123    1
    datetime (2014-08-21T08:00:00)
    0000   0x80 0x00 0x08 0x15 0x0e                   .....
    body (3)
    hex
    0000   0x10 0x1b 0x00                             ...
    decimal
             16   27    0

#### RECORD 1 CalBGForPH 2014-08-21T08:56:01 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 110}
```
    op hex (2)
    0000   0x0a 0x6e                                  .n
    decimal
             10  110
    datetime (2014-08-21T08:56:01)
    0000   0x81 0x38 0x28 0x75 0x0e                   .8(u.
    body (0)
    HOUR BITS: [0, 0, 1] DAY BITS: [0, 1, 1]
#### RECORD 2 Ian3F 2014-08-21T08:56:01 head[2], body[3] op[0x3f]

    op hex (2)
    0000   0x3f 0x0d                                  ?.
    decimal
             63   13
    datetime (2014-08-21T08:56:01)
    0000   0x81 0x38 0xc8 0x75 0x0e                   .8.u.
    body (3)
    hex
    0000   0x70 0x41 0x96                             pA.
    decimal
            112   65  150
    HOUR BITS: [0, 0, 1] DAY BITS: [0, 1, 1]
#### RECORD 3 Ian0B 2014-08-21T09:41:57 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x73 0x00                             .s.
    decimal
             11  115    0
    datetime (2014-08-21T09:41:57)
    0000   0xb9 0x29 0x49 0xb5 0x0e                   .)I..
    body (0)
    HOUR BITS: [0, 0, 1] DAY BITS: [1, 0, 1]
#### RECORD 4 BasalProfileStart 2014-08-21T12:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x02                                  {.
    decimal
            123    2
    datetime (2014-08-21T12:00:00)
    0000   0x80 0x00 0x0c 0x15 0x0e                   .....
    body (3)
    hex
    0000   0x18 0x06 0x00                             ...
    decimal
             24    6    0

#### RECORD 5 BolusWizard 2014-08-21T12:48:17 head[2], body[13] op[0x5b]
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
    datetime (2014-08-21T12:48:17)
    0000   0x91 0x30 0x0c 0x75 0x0e                   .0.u.
    body (13)
    hex
    0000   0x32 0x90 0x00 0x46 0x0c 0x38 0x00 0x01    2..F.8..
    0008   0x1c 0x00 0x00 0x00 0x01                   .....
    decimal
             50  144    0   70   12   56    0    1
             28    0    0    0    1
    HOUR BITS: [0, 0, 1] DAY BITS: [0, 1, 1]
#### RECORD 6 Base (2012, 0, 1, 28, 1, 1) head[2], body[0] op[0x1c]

    op hex (2)
    0000   0x1c 0x4e                                  .N
    decimal
             28   78
    datetime ((2012, 0, 1, 28, 1, 1))
    0000   0x01 0x01 0x1c 0x01 0x1c                   .....
    body (0)
    YEAR BITS: [0, 0, 0, 1]
`end logs/ReadHistoryData-page-26.data: 7 records`
