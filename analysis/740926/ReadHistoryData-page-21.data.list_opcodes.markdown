## START logs/ReadHistoryData-page-21.data
#### STOPPING DOUBLE NULLS @ 29, found 1 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0xb9 0x27 0x4b 0x7d 0x0e 0x7b 0x02 0x80    .'K}.{..
    0008   0x00 0x0c 0x1d 0x0e 0x18 0x06 0x00 0x0b    ........
    0010   0x65 0xc7 0xae 0x15 0x4c 0xbd 0x0e 0x1e    e...L...
    0018   0x01 0x87 0x16 0x0c 0x1d 0x0e 0x01 0x00    ........
##### DEBUG DECIMAL
            185   39   75  125   14  123    2  128
              0   12   29   14   24    6    0   11
            101  199  174   21   76  189   14   30
              1  135   22   12   29   14    1    0
#### RECORD 0 BolusWizard 2014-08-29T11:39:57 head[2], body[13] op[0x5b]
###### DECODED
```python
{'_byte[5]': 56,
 '_byte[7]': 1,
 'bg': 0,
 'bg_target_high': 1,
 'bg_target_low': 12,
 'bolus_estimate': 0.0,
 'carb_input': 83,
 'carb_ratio': 0,
 'correction_estimate': 0.9,
 'food_estimate': 0.0,
 'sensitivity': 70,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 216}
```
    op hex (2)
    0000   0x5b 0x00                                  [.
    decimal
             91    0
    datetime (2014-08-29T11:39:57)
    0000   0xb9 0x27 0x0b 0x7d 0x0e                   .'.}.
    body (13)
    hex
    0000   0x53 0x90 0x00 0x46 0x0c 0x38 0x00 0x01    S..F.8..
    0008   0xd8 0x00 0x00 0x00 0x01                   .....
    decimal
             83  144    0   70   12   56    0    1
            216    0    0    0    1
    HOUR BITS: [0, 0, 1] DAY BITS: [0, 1, 1]
#### RECORD 1 Base (2000, 0, 1, 16, 1, 1) head[2], body[0] op[0xd8]

    op hex (2)
    0000   0xd8 0x4e                                  .N
    decimal
            216   78
    datetime ((2000, 0, 1, 16, 1, 1))
    0000   0x01 0x01 0x90 0x01 0x90                   .....
    body (0)
    YEAR BITS: [1, 0, 0, 1]
`end logs/ReadHistoryData-page-21.data: 2 records`
