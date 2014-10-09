## START logs/ReadHistoryData-page-3.data
#### STOPPING DOUBLE NULLS @ 39, found 1 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0x83 0xba 0x4b 0x63 0x0e 0x0b 0x6b 0x00    ..Kc..k.
    0008   0x99 0x81 0x4e 0xa3 0x0e 0x0a 0xa3 0xb9    ..N.....
    0010   0x83 0x30 0x63 0x0e 0x3f 0x14 0xb9 0x83    .0c.?...
    0018   0x70 0x63 0x0e 0x70 0x41 0x96 0x5b 0x5a    pc.pA.[Z
##### DEBUG DECIMAL
            131  186   75   99   14   11  107    0
            153  129   78  163   14   10  163  185
            131   48   99   14   63   20  185  131
            112   99   14  112   65  150   91   90
#### RECORD 0 BolusWizard 2014-10-03T11:58:03 head[2], body[13] op[0x5b]
###### DECODED
```python
{'_byte[5]': 56,
 '_byte[7]': 1,
 'bg': 0,
 'bg_target_high': 1,
 'bg_target_low': 12,
 'bolus_estimate': 0.0,
 'carb_input': 55,
 'carb_ratio': 0,
 'correction_estimate': 0.9,
 'food_estimate': 0.0,
 'sensitivity': 70,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 56}
```
    op hex (2)
    0000   0x5b 0x00                                  [.
    decimal
             91    0
    datetime (2014-10-03T11:58:03)
    0000   0x83 0xba 0x0b 0x63 0x0e                   ...c.
    body (13)
    hex
    0000   0x37 0x90 0x00 0x46 0x0c 0x38 0x00 0x01    7..F.8..
    0008   0x38 0x00 0x00 0x00 0x01                   8....
    decimal
             55  144    0   70   12   56    0    1
             56    0    0    0    1
    HOUR BITS: [1, 0, 1] DAY BITS: [0, 1, 1]
#### RECORD 1 Base (2012, 4, 0, 0, 2, 59) head[2], body[0] op[0x38]

    op hex (2)
    0000   0x38 0x4e                                  8N
    decimal
             56   78
    datetime ((2012, 4, 0, 0, 2, 59))
    0000   0x7b 0x02 0x80 0x80 0x0c                   {....
    body (0)
    DAY BITS: [1, 0, 0]
#### RECORD 2 Prime (2004, 0, 1, 4, 1, 1) head[5], body[0] op[0x03]
###### DECODED
```python
{'amount': 0.0, 'fixed': 2.4, 'type': 'fixed'}
```
    op hex (5)
    0000   0x03 0x0e 0x18 0x06 0x00                   .....
    decimal
              3   14   24    6    0
    datetime ((2004, 0, 1, 4, 1, 1))
    0000   0x01 0x01 0x04 0x01 0x04                   .....
    body (0)

`end logs/ReadHistoryData-page-3.data: 3 records`
