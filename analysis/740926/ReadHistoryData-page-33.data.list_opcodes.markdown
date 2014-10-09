## START logs/ReadHistoryData-page-33.data
#### STOPPING DOUBLE NULLS @ 32, found 1 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0xd8 0x4e 0x5c 0x0b 0x50 0x08 0x80 0x32    .N\.P..2
    0008   0x30 0x80 0xb2 0x3a 0x80 0x0b 0x65 0xd9    0..:..e.
    0010   0x85 0x1b 0x4d 0xa9 0x0e 0x01 0x00 0x88    ..M.....
    0018   0x00 0x88 0x00 0xc4 0x00 0xa1 0x1a 0x4d    .......M
##### DEBUG DECIMAL
            216   78   92   11   80    8  128   50
             48  128  178   58  128   11  101  217
            133   27   77  169   14    1    0  136
              0  136    0  196    0  161   26   77
#### RECORD 0 Bolus (2014, 4, 0, 8, 0, 16) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 8.0, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x00 0x50 0x00                        ..P.
    decimal
              1    0   80    0
    datetime ((2014, 4, 0, 8, 0, 16))
    0000   0x50 0x00 0x88 0x00 0x8e                   P....
    body (0)
    YEAR BITS: [1, 0, 0, 0]
#### RECORD 1 SelectBasalProfile (2001, 0, 0, 27, 14, 9) head[2], body[0] op[0x14]

    op hex (2)
    0000   0x14 0x4d                                  .M
    decimal
             20   77
    datetime ((2001, 0, 0, 27, 14, 9))
    0000   0x09 0x0e 0x5b 0x00 0xa1                   ..[..
    body (0)
    YEAR BITS: [1, 0, 1, 0]
#### RECORD 2 Battery 2000-04-16T06:14:41 head[2], body[0] op[0x1a]

    op hex (2)
    0000   0x1a 0x0d                                  ..
    decimal
             26   13
    datetime (2000-04-16T06:14:41)
    0000   0x69 0x0e 0x26 0x90 0x00                   i.&..
    body (0)
    DAY BITS: [1, 0, 0]
#### RECORD 3 Base (2000, 0, 24, 0, 0, 56) head[2], body[0] op[0x46]

    op hex (2)
    0000   0x46 0x0c                                  F.
    decimal
             70   12
    datetime ((2000, 0, 24, 0, 0, 56))
    0000   0x38 0x00 0x00 0xd8 0x00                   8....
    body (0)
    DAY BITS: [1, 1, 0]
`end logs/ReadHistoryData-page-33.data: 4 records`
