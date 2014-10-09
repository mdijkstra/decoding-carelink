## START logs/ReadHistoryData-page-23.data
#### STOPPING DOUBLE NULLS @ 29, found 1 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0x83 0x22 0x4b 0x7a 0x0e 0x0a 0xf2 0xa7    ."Kz....
    0008   0x27 0x2b 0x7a 0x0e 0x3f 0x1e 0xa7 0x27    '+z.?..'
    0010   0x4b 0x7a 0x0e 0x70 0x41 0x96 0x5b 0x86    Kz.pA.[.
    0018   0xb9 0x27 0x0b 0x7a 0x0e 0x00 0x90 0x00    .'.z....
##### DEBUG DECIMAL
            131   34   75  122   14   10  242  167
             39   43  122   14   63   30  167   39
             75  122   14  112   65  150   91  134
            185   39   11  122   14    0  144    0
#### RECORD 0 BolusWizard 2014-08-26T11:34:03 head[2], body[13] op[0x5b]
###### DECODED
```python
{'_byte[5]': 56,
 '_byte[7]': 2,
 'bg': 0,
 'bg_target_high': 2,
 'bg_target_low': 12,
 'bolus_estimate': 0.0,
 'carb_input': 99,
 'carb_ratio': 0,
 'correction_estimate': 1.0,
 'food_estimate': 0.0,
 'sensitivity': 70,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 52}
```
    op hex (2)
    0000   0x5b 0x00                                  [.
    decimal
             91    0
    datetime (2014-08-26T11:34:03)
    0000   0x83 0x22 0x0b 0x7a 0x0e                   .".z.
    body (13)
    hex
    0000   0x63 0x90 0x00 0x46 0x0c 0x38 0x00 0x02    c..F.8..
    0008   0x34 0x00 0x00 0x00 0x02                   4....
    decimal
             99  144    0   70   12   56    0    2
             52    0    0    0    2
    HOUR BITS: [0, 0, 1] DAY BITS: [0, 1, 1]
#### RECORD 1 LowReservoir (2008, 0, 1, 24, 1, 1) head[2], body[0] op[0x34]
###### DECODED
```python
{'amount': 7.8}
```
    op hex (2)
    0000   0x34 0x4e                                  4N
    decimal
             52   78
    datetime ((2008, 0, 1, 24, 1, 1))
    0000   0x01 0x01 0xb8 0x01 0xb8                   .....
    body (0)
    YEAR BITS: [1, 0, 1, 1]
`end logs/ReadHistoryData-page-23.data: 2 records`
