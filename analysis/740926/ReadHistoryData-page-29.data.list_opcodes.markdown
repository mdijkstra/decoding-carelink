## START logs/ReadHistoryData-page-29.data
#### STOPPING DOUBLE NULLS @ 54, found 1 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0xb5 0x06 0x50 0x10 0x0e 0x0a 0xa1 0xaf    ..P.....
    0008   0x18 0x50 0x10 0x0e 0x5b 0xa1 0xb3 0x18    .P..[...
    0010   0x10 0x10 0x0e 0x00 0x90 0x00 0xc8 0x19    ........
    0018   0x38 0x84 0x00 0x00 0x00 0x00 0x24 0x00    8.....$.
##### DEBUG DECIMAL
            181    6   80   16   14   10  161  175
             24   80   16   14   91  161  179   24
             16   16   14    0  144    0  200   25
             56  132    0    0    0    0   36    0
#### RECORD 0 Bolus (2006, 12, 0, 0, 0, 8) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 20.0, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x00 0xc8 0x00                        ....
    decimal
              1    0  200    0
    datetime ((2006, 12, 0, 0, 0, 8))
    0000   0xc8 0x00 0x00 0x00 0xb6                   .....
    body (0)
    YEAR BITS: [1, 0, 1, 1]
#### RECORD 1 TempBasal (2008, 4, 0, 1, 14, 48) head[2], body[1] op[0x33]
###### DECODED
```python
{'rate': 1.9}
```
    op hex (2)
    0000   0x33 0x4c                                  3L
    decimal
             51   76
    datetime ((2008, 4, 0, 1, 14, 48))
    0000   0x70 0x0e 0x01 0x00 0xc8                   p....
    body (1)
    hex
    0000   0x00                                       .
    decimal
              0
    YEAR BITS: [1, 1, 0, 0]
#### RECORD 2 Base (2013, 4, 9, 21, 0, 48) head[2], body[0] op[0xc8]

    op hex (2)
    0000   0xc8 0x00                                  ..
    decimal
            200    0
    datetime ((2013, 4, 9, 21, 0, 48))
    0000   0x70 0x00 0x95 0x29 0x4d                   p..)M
    body (0)
    DAY BITS: [0, 0, 1] YEAR BITS: [0, 1, 0, 0]
#### RECORD 3 Base (2000, 0, 0, 16, 0, 1) head[2], body[0] op[0x10]

    op hex (2)
    0000   0x10 0x0e                                  ..
    decimal
             16   14
    datetime ((2000, 0, 0, 16, 0, 1))
    0000   0x01 0x00 0x50 0x00 0x50                   ..P.P
    body (0)
    YEAR BITS: [0, 1, 0, 1]
#### RECORD 4 Base (2000, 2, 14, 6, 45, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0xe0                                  ..
    decimal
              0  224
    datetime ((2000, 2, 14, 6, 45, 0))
    0000   0x00 0xad 0x06 0x4e 0x10                   ...N.
    body (0)
    HOUR BITS: [1, 0, 1] DAY BITS: [0, 1, 0] YEAR BITS: [0, 0, 0, 1]
#### RECORD 5 Base (2015, 7, 11, 13, 14, 37) head[2], body[0] op[0x0e]

    op hex (2)
    0000   0x0e 0x0b                                  ..
    decimal
             14   11
    datetime ((2015, 7, 11, 13, 14, 37))
    0000   0x65 0xce 0x8d 0x0b 0x4f                   e...O
    body (0)
    HOUR BITS: [1, 1, 0] YEAR BITS: [0, 1, 0, 0]
#### RECORD 6 Base (2008, 0, 0, 8, 0, 1) head[2], body[0] op[0xb0]

    op hex (2)
    0000   0xb0 0x0e                                  ..
    decimal
            176   14
    datetime ((2008, 0, 0, 8, 0, 1))
    0000   0x01 0x00 0x28 0x00 0x28                   ..(.(
    body (0)
    YEAR BITS: [0, 0, 1, 0]
`end logs/ReadHistoryData-page-29.data: 7 records`
