## START logs/ReadHistoryData-page-6.data
#### STOPPING DOUBLE NULLS @ 77, found 0 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0xf8 0x4e 0x5c 0x08 0x64 0x7b 0x80 0x28    .N\.d{.(
    0008   0xc1 0x80 0x01 0x00 0x78 0x00 0x78 0x00    ....x.x.
    0010   0x00 0x00 0x8c 0x69 0x4d 0x7b 0x0e 0x0b    ...iM{..
    0018   0x68 0x00 0xac 0x77 0x4d 0xbb 0x0e 0x0a    h..wM...
##### DEBUG DECIMAL
            248   78   92    8  100  123  128   40
            193  128    1    0  120    0  120    0
              0    0  140  105   77  123   14   11
            104    0  172  119   77  187   14   10
#### RECORD 0 BasalProfileStart 2014-09-27T12:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x02                                  {.
    decimal
            123    2
    datetime (2014-09-27T12:00:00)
    0000   0x80 0x40 0x0c 0x1b 0x0e                   .@...
    body (3)
    hex
    0000   0x18 0x06 0x00                             ...
    decimal
             24    6    0
    HOUR BITS: [0, 1, 0]
#### RECORD 1 CalBGForPH 2014-09-27T13:40:19 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 275}
```
    op hex (2)
    0000   0x0a 0x13                                  ..
    decimal
             10   19
    datetime (2014-09-27T13:40:19)
    0000   0x93 0x68 0x2d 0x7b 0x8e                   .h-{.
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 1, 1] YEAR BITS: [1, 0, 0, 0]
#### RECORD 2 Ian3F 2014-09-27T13:40:19 head[2], body[3] op[0x3f]

    op hex (2)
    0000   0x3f 0x22                                  ?"
    decimal
             63   34
    datetime (2014-09-27T13:40:19)
    0000   0x93 0x68 0x6d 0x7b 0x0e                   .hm{.
    body (3)
    hex
    0000   0x70 0x41 0x96                             pA.
    decimal
            112   65  150
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 3 BolusWizard 2014-09-27T13:41:05 head[2], body[13] op[0x5b]
###### DECODED
```python
{'_byte[5]': 56,
 '_byte[7]': 0,
 'bg': 153,
 'bg_target_high': 0,
 'bg_target_low': 12,
 'bolus_estimate': 0.0,
 'carb_input': 0,
 'carb_ratio': 0,
 'correction_estimate': 0.8,
 'food_estimate': 24.8,
 'sensitivity': 70,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 0}
```
    op hex (2)
    0000   0x5b 0x99                                  [.
    decimal
             91  153
    datetime (2014-09-27T13:41:05)
    0000   0x85 0x69 0x0d 0x7b 0x0e                   .i.{.
    body (13)
    hex
    0000   0x00 0x90 0x00 0x46 0x0c 0x38 0xf8 0x00    ...F.8..
    0008   0x00 0x00 0x00 0x00 0x00                   .....
    decimal
              0  144    0   70   12   56  248    0
              0    0    0    0    0
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 4 Base (2000, 4, 27, 4, 8, 28) head[2], body[0] op[0xf8]

    op hex (2)
    0000   0xf8 0x4e                                  .N
    decimal
            248   78
    datetime ((2000, 4, 27, 4, 8, 28))
    0000   0x5c 0x08 0x64 0x7b 0x80                   \.d{.
    body (0)
    DAY BITS: [0, 1, 1] YEAR BITS: [1, 0, 0, 0]
#### RECORD 5 Base (2009, 9, 12, 25, 27, 0) head[2], body[0] op[0x28]

    op hex (2)
    0000   0x28 0xc1                                  (.
    decimal
             40  193
    datetime ((2009, 9, 12, 25, 27, 0))
    0000   0x80 0x5b 0x99 0x8c 0x69                   .[..i
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [1, 0, 0] YEAR BITS: [0, 1, 1, 0]
#### RECORD 6 Base (2006, 0, 0, 16, 0, 14) head[2], body[0] op[0x0d]

    op hex (2)
    0000   0x0d 0x7b                                  .{
    decimal
             13  123
    datetime ((2006, 0, 0, 16, 0, 14))
    0000   0x0e 0x00 0x90 0x00 0x46                   ....F
    body (0)
    YEAR BITS: [0, 1, 0, 0]
#### RECORD 7 ClearAlarm (2000, 12, 0, 0, 0, 56) head[2], body[0] op[0x0c]

    op hex (2)
    0000   0x0c 0x38                                  .8
    decimal
             12   56
    datetime ((2000, 12, 0, 0, 0, 56))
    0000   0xf8 0x00 0x00 0x00 0x00                   .....
    body (0)

`end logs/ReadHistoryData-page-6.data: 8 records`
