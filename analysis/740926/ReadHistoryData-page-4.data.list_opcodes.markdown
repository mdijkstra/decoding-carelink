## START logs/ReadHistoryData-page-4.data
#### STOPPING DOUBLE NULLS @ 174, found 1 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0xa0 0x02 0x00 0x00 0x04 0x00 0x9d 0x0c    ........
    0008   0x58 0x00 0x20 0x22 0x00 0x00 0x00 0x00    X. "....
    0010   0x00 0x02 0x01 0x00 0x00 0x00 0x00 0x00    ........
    0018   0x5b 0x00 0x8d 0x8b 0x01 0x02 0x0e 0x14    [.......
##### DEBUG DECIMAL
            160    2    0    0    4    0  157   12
             88    0   32   34    0    0    0    0
              0    2    1    0    0    0    0    0
             91    0  141  139    1    2   14   20
#### RECORD 0 BasalProfileStart 2014-10-01T18:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x03                                  {.
    decimal
            123    3
    datetime (2014-10-01T18:00:00)
    0000   0x80 0x80 0x12 0x01 0x0e                   .....
    body (3)
    hex
    0000   0x24 0x18 0x00                             $..
    decimal
             36   24    0
    HOUR BITS: [1, 0, 0]
#### RECORD 1 CalBGForPH 2014-10-01T19:10:09 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 121}
```
    op hex (2)
    0000   0x0a 0x79                                  .y
    decimal
             10  121
    datetime (2014-10-01T19:10:09)
    0000   0x89 0x8a 0x33 0x61 0x0e                   ..3a.
    body (0)
    HOUR BITS: [1, 0, 0] DAY BITS: [0, 1, 1]
#### RECORD 2 Ian3F 2014-10-01T19:10:09 head[2], body[3] op[0x3f]

    op hex (2)
    0000   0x3f 0x0f                                  ?.
    decimal
             63   15
    datetime (2014-10-01T19:10:09)
    0000   0x89 0x8a 0x33 0x61 0x0e                   ..3a.
    body (3)
    hex
    0000   0x70 0x41 0x96                             pA.
    decimal
            112   65  150
    HOUR BITS: [1, 0, 0] DAY BITS: [0, 1, 1]
#### RECORD 3 BolusWizard 2014-10-01T19:33:47 head[2], body[13] op[0x5b]
###### DECODED
```python
{'_byte[5]': 56,
 '_byte[7]': 1,
 'bg': 0,
 'bg_target_high': 1,
 'bg_target_low': 25,
 'bolus_estimate': 0.0,
 'carb_input': 160,
 'carb_ratio': 0,
 'correction_estimate': 0.9,
 'food_estimate': 0.0,
 'sensitivity': 140,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 200}
```
    op hex (2)
    0000   0x5b 0x00                                  [.
    decimal
             91    0
    datetime (2014-10-01T19:33:47)
    0000   0xaf 0xa1 0x13 0x01 0x0e                   .....
    body (13)
    hex
    0000   0xa0 0x90 0x00 0x8c 0x19 0x38 0x00 0x01    .....8..
    0008   0xc8 0x00 0x00 0x00 0x01                   .....
    decimal
            160  144    0  140   25   56    0    1
            200    0    0    0    1
    HOUR BITS: [1, 0, 1]
#### RECORD 4 Base (2000, 4, 31, 4, 8, 28) head[2], body[0] op[0xc8]

    op hex (2)
    0000   0xc8 0x4e                                  .N
    decimal
            200   78
    datetime ((2000, 4, 31, 4, 8, 28))
    0000   0x5c 0x08 0x24 0x9f 0x90                   \.$..
    body (0)
    DAY BITS: [1, 0, 0] YEAR BITS: [1, 0, 0, 1]
#### RECORD 5 Ian54 2000-08-16T00:01:16 head[2], body[57] op[0x54]

    op hex (2)
    0000   0x54 0xa9                                  T.
    decimal
             84  169
    datetime (2000-08-16T00:01:16)
    0000   0x90 0x01 0x00 0x10 0x00                   .....
    body (57)
    hex
    0000   0x10 0x00 0x00 0x00 0xaf 0xa1 0x53 0x01    ......S.
    0008   0x0e 0x7b 0x04 0x80 0x80 0x14 0x01 0x0e    .{......
    0010   0x28 0x1d 0x00 0x0b 0x65 0xce 0x86 0x94    (...e...
    0018   0x54 0xa1 0x0e 0x01 0x00 0x28 0x00 0x28    T....(.(
    0020   0x00 0x0c 0x00 0x80 0x95 0x54 0x01 0x0e    .....T..
    0028   0x01 0x00 0x50 0x00 0x50 0x00 0x10 0x00    ..P.P...
    0030   0xb5 0x9d 0x55 0x01 0x0e 0x01 0x00 0x14    ..U.....
    0038   0x00                                       .
    decimal
             16    0    0    0  175  161   83    1
             14  123    4  128  128   20    1   14
             40   29    0   11  101  206  134  148
             84  161   14    1    0   40    0   40
              0   12    0  128  149   84    1   14
              1    0   80    0   80    0   16    0
            181  157   85    1   14    1    0   20
              0

#### RECORD 6 SelectBasalProfile 2005-04-21T10:00:12 head[2], body[0] op[0x14]

    op hex (2)
    0000   0x14 0x00                                  ..
    decimal
             20    0
    datetime (2005-04-21T10:00:12)
    0000   0x4c 0x00 0xaa 0xb5 0x55                   L...U
    body (0)
    DAY BITS: [1, 0, 1] YEAR BITS: [0, 1, 0, 1]
#### RECORD 7 Bolus 2014-10-02T00:00:00 head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 1.4, 'dual_component': '??', 'programmed': 12.3, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x0e 0x7b 0x00                        ..{.
    decimal
              1   14  123    0
    datetime (2014-10-02T00:00:00)
    0000   0x80 0x80 0x00 0x02 0x0e                   .....
    body (0)
    HOUR BITS: [1, 0, 0]
#### RECORD 8 Base (2002, 0, 0, 0, 7, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x14                                  ..
    decimal
              0   20
    datetime ((2002, 0, 0, 0, 7, 0))
    0000   0x00 0x07 0x00 0x00 0x02                   .....
    body (0)

#### RECORD 9 Base (2014, 0, 0, 0, 0, 14) head[2], body[0] op[0xe8]

    op hex (2)
    0000   0xe8 0xa1                                  ..
    decimal
            232  161
    datetime ((2014, 0, 0, 0, 0, 14))
    0000   0x0e 0x00 0x00 0x00 0x6e                   ....n
    body (0)
    YEAR BITS: [0, 1, 1, 0]
#### RECORD 10 Base (2003, 0, 12, 11, 0, 6) head[2], body[0] op[0xa1]

    op hex (2)
    0000   0xa1 0x0e                                  ..
    decimal
            161   14
    datetime ((2003, 0, 12, 11, 0, 6))
    0000   0x06 0x00 0x8b 0x6c 0xc3                   ...l.
    body (0)
    DAY BITS: [0, 1, 1] YEAR BITS: [1, 1, 0, 0]
#### RECORD 11 Base (2004, 0, 1, 8, 2, 0) head[2], body[0] op[0x04]

    op hex (2)
    0000   0x04 0x00                                  ..
    decimal
              4    0
    datetime ((2004, 0, 1, 8, 2, 0))
    0000   0x00 0x02 0xe8 0x01 0xd4                   .....
    body (0)
    YEAR BITS: [1, 1, 0, 1]
#### RECORD 12 Ian3F (2000, 0, 22, 0, 37, 20) head[2], body[3] op[0x3f]

    op hex (2)
    0000   0x3f 0x01                                  ?.
    decimal
             63    1
    datetime ((2000, 0, 22, 0, 37, 20))
    0000   0x14 0x25 0x00 0xd6 0x00                   .%...
    body (3)
    hex
    0000   0x74 0x00 0x00                             t..
    decimal
            116    0    0
    HOUR BITS: [0, 0, 1] DAY BITS: [1, 1, 0]
`end logs/ReadHistoryData-page-4.data: 13 records`
