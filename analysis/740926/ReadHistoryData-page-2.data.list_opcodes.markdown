## START logs/ReadHistoryData-page-2.data
#### STOPPING DOUBLE NULLS @ 374, found 2 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0x48 0x4e 0x5c 0x11 0x50 0x9f 0x80 0x6e    HN\.P..n
    0008   0xdb 0x80 0x22 0xe5 0x80 0x14 0x49 0x90    .."...I.
    0010   0x08 0xb7 0x90 0x01 0x00 0x48 0x00 0x48    .....H.H
    0018   0x00 0x00 0x00 0xa4 0x9b 0x57 0x65 0x0e    .....We.
##### DEBUG DECIMAL
             72   78   92   17   80  159  128  110
            219  128   34  229  128   20   73  144
              8  183  144    1    0   72    0   72
              0    0    0  164  155   87  101   14
#### RECORD 0 BasalProfileStart 2014-10-05T08:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x01                                  {.
    decimal
            123    1
    datetime (2014-10-05T08:00:00)
    0000   0x80 0x80 0x08 0x05 0x0e                   .....
    body (3)
    hex
    0000   0x10 0x1b 0x00                             ...
    decimal
             16   27    0
    HOUR BITS: [1, 0, 0]
#### RECORD 1 Ian0B 2014-10-05T09:38:28 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x65 0xf2                             .e.
    decimal
             11  101  242
    datetime (2014-10-05T09:38:28)
    0000   0x9c 0xa6 0x49 0xa5 0x0e                   ..I..
    body (0)
    HOUR BITS: [1, 0, 1] DAY BITS: [1, 0, 1]
#### RECORD 2 Bolus (2002, 0, 0, 0, 0, 20) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 2.0, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x00 0x14 0x00                        ....
    decimal
              1    0   20    0
    datetime ((2002, 0, 0, 0, 0, 20))
    0000   0x14 0x00 0x00 0x00 0xb2                   .....
    body (0)
    YEAR BITS: [1, 0, 1, 1]
#### RECORD 3 Base (2009, 0, 28, 10, 14, 5) head[2], body[0] op[0xb5]

    op hex (2)
    0000   0xb5 0x49                                  .I
    decimal
            181   73
    datetime ((2009, 0, 28, 10, 14, 5))
    0000   0x05 0x0e 0x0a 0xfc 0x89                   .....
    body (0)
    DAY BITS: [1, 1, 1] YEAR BITS: [1, 0, 0, 0]
#### RECORD 4 Base (2009, 4, 31, 31, 14, 37) head[2], body[0] op[0xb5]

    op hex (2)
    0000   0xb5 0x2a                                  .*
    decimal
            181   42
    datetime ((2009, 4, 31, 31, 14, 37))
    0000   0x65 0x0e 0x3f 0x1f 0x89                   e.?..
    body (0)
    YEAR BITS: [1, 0, 0, 0]
#### RECORD 5 Base (2006, 4, 1, 16, 14, 37) head[2], body[0] op[0xb5]

    op hex (2)
    0000   0xb5 0x8a                                  ..
    decimal
            181  138
    datetime ((2006, 4, 1, 16, 14, 37))
    0000   0x65 0x0e 0x70 0x41 0x96                   e.pA.
    body (0)
    DAY BITS: [0, 1, 0] YEAR BITS: [1, 0, 0, 1]
#### RECORD 6 Bolus (2011, 4, 0, 8, 0, 16) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 8.0, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x00 0x50 0x00                        ..P.
    decimal
              1    0   80    0
    datetime ((2011, 4, 0, 8, 0, 16))
    0000   0x50 0x00 0x08 0x00 0xbb                   P....
    body (0)
    YEAR BITS: [1, 0, 1, 1]
#### RECORD 7 Base (2012, 0, 5, 11, 14, 5) head[2], body[0] op[0x85]

    op hex (2)
    0000   0x85 0x4b                                  .K
    decimal
            133   75
    datetime ((2012, 0, 5, 11, 14, 5))
    0000   0x05 0x0e 0x0b 0x65 0xfc                   ...e.
    body (0)
    DAY BITS: [0, 1, 1] YEAR BITS: [1, 1, 1, 1]
#### RECORD 8 Base (2000, 6, 1, 14, 37, 11) head[2], body[0] op[0xb7]

    op hex (2)
    0000   0xb7 0x87                                  ..
    decimal
            183  135
    datetime ((2000, 6, 1, 14, 37, 11))
    0000   0x4b 0xa5 0x0e 0x01 0x00                   K....
    body (0)
    HOUR BITS: [1, 0, 1]
#### RECORD 9 ChangeBasalProfile (2012, 0, 0, 16, 0, 8) head[2], body[44] op[0x08]

    op hex (2)
    0000   0x08 0x00                                  ..
    decimal
              8    0
    datetime ((2012, 0, 0, 16, 0, 8))
    0000   0x08 0x00 0x50 0x00 0x8c                   ..P..
    body (44)
    hex
    0000   0x8f 0x4b 0x05 0x0e 0x7b 0x02 0x80 0x80    .K..{...
    0008   0x0c 0x05 0x0e 0x18 0x06 0x00 0x01 0x00    ........
    0010   0x08 0x00 0x08 0x00 0x1c 0x00 0x85 0x90    ........
    0018   0x4c 0x05 0x0e 0x0b 0x65 0xf7 0x8e 0xa5    L...e...
    0020   0x4c 0xa5 0x0e 0x7b 0x02 0xac 0x8a 0x0d    L..{....
    0028   0x05 0x0e 0x18 0x06                        ....
    decimal
            143   75    5   14  123    2  128  128
             12    5   14   24    6    0    1    0
              8    0    8    0   28    0  133  144
             76    5   14   11  101  247  142  165
             76  165   14  123    2  172  138   13
              5   14   24    6
    YEAR BITS: [1, 0, 0, 0]
#### RECORD 10 Base (2010, 0, 5, 0, 5, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x03                                  ..
    decimal
              0    3
    datetime ((2010, 0, 5, 0, 5, 0))
    0000   0x00 0x05 0x00 0x05 0x9a                   .....
    body (0)
    YEAR BITS: [1, 0, 0, 1]
#### RECORD 11 Base (2015, 0, 5, 11, 14, 5) head[2], body[0] op[0x8a]

    op hex (2)
    0000   0x8a 0x0d                                  ..
    decimal
            138   13
    datetime ((2015, 0, 5, 11, 14, 5))
    0000   0x05 0x0e 0x0b 0x65 0xcf                   ...e.
    body (0)
    DAY BITS: [0, 1, 1] YEAR BITS: [1, 1, 0, 0]
#### RECORD 12 Base (2005, 6, 11, 14, 37, 14) head[2], body[0] op[0xae]

    op hex (2)
    0000   0xae 0x87                                  ..
    decimal
            174  135
    datetime ((2005, 6, 11, 14, 37, 14))
    0000   0x4e 0xa5 0x0e 0x0b 0x65                   N...e
    body (0)
    HOUR BITS: [1, 0, 1] YEAR BITS: [0, 1, 1, 0]
#### RECORD 13 Base (2001, 9, 14, 5, 15, 38) head[2], body[0] op[0xe0]

    op hex (2)
    0000   0xe0 0x9c                                  ..
    decimal
            224  156
    datetime ((2001, 9, 14, 5, 15, 38))
    0000   0xa6 0x4f 0xa5 0x0e 0x01                   .O...
    body (0)
    HOUR BITS: [0, 1, 0]
#### RECORD 14 Base (2000, 0, 0, 0, 8, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x08                                  ..
    decimal
              0    8
    datetime ((2000, 0, 0, 0, 8, 0))
    0000   0x00 0x08 0x00 0x00 0x00                   .....
    body (0)

#### RECORD 15 Base (2005, 4, 11, 14, 5, 16) head[2], body[0] op[0x8a]

    op hex (2)
    0000   0x8a 0x8d                                  ..
    decimal
            138  141
    datetime ((2005, 4, 11, 14, 5, 16))
    0000   0x50 0x05 0x0e 0x0b 0x65                   P...e
    body (0)
    YEAR BITS: [0, 1, 1, 0]
#### RECORD 16 Base (2011, 9, 14, 5, 17, 7) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0xaa                                  ..
    decimal
              0  170
    datetime ((2011, 9, 14, 5, 17, 7))
    0000   0x87 0x51 0xa5 0x8e 0x7b                   .Q..{
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [1, 0, 0] YEAR BITS: [0, 1, 1, 1]
#### RECORD 17 Prime (2001, 0, 0, 24, 36, 14) head[5], body[0] op[0x03]
###### DECODED
```python
{'amount': 0.5, 'fixed': 12.8, 'type': 'fixed'}
```
    op hex (5)
    0000   0x03 0x80 0x80 0x12 0x05                   .....
    decimal
              3  128  128   18    5
    datetime ((2001, 0, 0, 24, 36, 14))
    0000   0x0e 0x24 0x18 0x00 0x01                   .$...
    body (0)
    HOUR BITS: [0, 0, 1]
#### RECORD 18 Base (2000, 0, 4, 0, 20, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x14                                  ..
    decimal
              0   20
    datetime ((2000, 0, 4, 0, 20, 0))
    0000   0x00 0x14 0x00 0x04 0x00                   .....
    body (0)

#### RECORD 19 Base (2000, 4, 1, 14, 5, 17) head[2], body[0] op[0xa9]

    op hex (2)
    0000   0xa9 0xbb                                  ..
    decimal
            169  187
    datetime ((2000, 4, 1, 14, 5, 17))
    0000   0x51 0x05 0x0e 0x01 0x00                   Q....
    body (0)

#### RECORD 20 Base (2008, 4, 0, 4, 0, 48) head[2], body[0] op[0x70]

    op hex (2)
    0000   0x70 0x00                                  p.
    decimal
            112    0
    datetime ((2008, 4, 0, 4, 0, 48))
    0000   0x70 0x00 0x04 0x00 0x98                   p....
    body (0)
    YEAR BITS: [1, 0, 0, 1]
#### RECORD 21 Base (2004, 0, 0, 1, 14, 5) head[2], body[0] op[0xaf]

    op hex (2)
    0000   0xaf 0x53                                  .S
    decimal
            175   83
    datetime ((2004, 0, 0, 1, 14, 5))
    0000   0x05 0x0e 0x01 0x00 0x14                   .....
    body (0)
    YEAR BITS: [0, 0, 0, 1]
#### RECORD 22 Base (2001, 1, 13, 0, 52, 0) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x14                                  ..
    decimal
              0   20
    datetime ((2001, 1, 13, 0, 52, 0))
    0000   0x00 0x74 0x00 0xad 0xb1                   .t...
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [1, 0, 1] YEAR BITS: [1, 0, 1, 1]
#### RECORD 23 Base (2005, 1, 23, 0, 27, 14) head[2], body[0] op[0x53]

    op hex (2)
    0000   0x53 0x05                                  S.
    decimal
             83    5
    datetime ((2005, 1, 23, 0, 27, 14))
    0000   0x0e 0x5b 0x00 0xb7 0xb5                   .[...
    body (0)
    HOUR BITS: [0, 1, 0] DAY BITS: [1, 0, 1] YEAR BITS: [1, 0, 1, 1]
#### RECORD 24 Base (2012, 1, 0, 16, 56, 14) head[2], body[0] op[0x13]

    op hex (2)
    0000   0x13 0x65                                  .e
    decimal
             19  101
    datetime ((2012, 1, 0, 16, 56, 14))
    0000   0x0e 0x78 0x90 0x00 0x8c                   .x...
    body (0)
    HOUR BITS: [0, 1, 1] YEAR BITS: [1, 0, 0, 0]
#### RECORD 25 LowBattery (2000, 0, 0, 20, 1, 0) head[2], body[0] op[0x19]

    op hex (2)
    0000   0x19 0x38                                  .8
    decimal
             25   56
    datetime ((2000, 0, 0, 20, 1, 0))
    0000   0x00 0x01 0x54 0x00 0x00                   ..T..
    body (0)

#### RECORD 26 Base (2002, 5, 17, 28, 14, 20) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x01                                  ..
    decimal
              0    1
    datetime ((2002, 5, 17, 28, 14, 20))
    0000   0x54 0x4e 0x5c 0x11 0x62                   TN\.b
    body (0)
    HOUR BITS: [0, 1, 0] YEAR BITS: [0, 1, 1, 0]
#### RECORD 27 Base (2003, 0, 20, 0, 15, 34) head[2], body[0] op[0x05]

    op hex (2)
    0000   0x05 0x80                                  ..
    decimal
              5  128
    datetime ((2003, 0, 20, 0, 15, 34))
    0000   0x22 0x0f 0x80 0x14 0x73                   "...s
    body (0)
    YEAR BITS: [0, 1, 1, 1]
#### RECORD 28 Base (2000, 14, 17, 8, 0, 33) head[2], body[0] op[0x80]

    op hex (2)
    0000   0x80 0x08                                  ..
    decimal
            128    8
    datetime ((2000, 14, 17, 8, 0, 33))
    0000   0xe1 0x80 0x08 0xd1 0x90                   .....
    body (0)
    HOUR BITS: [1, 0, 0] DAY BITS: [1, 1, 0] YEAR BITS: [1, 0, 0, 1]
#### RECORD 29 Bolus (2007, 0, 0, 4, 0, 12) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 1.2, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x00 0x0c 0x00                        ....
    decimal
              1    0   12    0
    datetime ((2007, 0, 0, 4, 0, 12))
    0000   0x0c 0x00 0x84 0x00 0xb7                   .....
    body (0)
    YEAR BITS: [1, 0, 1, 1]
#### RECORD 30 Base (2000, 4, 4, 27, 14, 37) head[2], body[0] op[0xb5]

    op hex (2)
    0000   0xb5 0x53                                  .S
    decimal
            181   83
    datetime ((2000, 4, 4, 27, 14, 37))
    0000   0x65 0x0e 0x7b 0x04 0x80                   e.{..
    body (0)
    YEAR BITS: [1, 0, 0, 0]
#### RECORD 31 Base (2000, 0, 29, 8, 14, 5) head[2], body[0] op[0x80]

    op hex (2)
    0000   0x80 0x14                                  ..
    decimal
            128   20
    datetime ((2000, 0, 29, 8, 14, 5))
    0000   0x05 0x0e 0x28 0x1d 0x00                   ..(..
    body (0)

#### RECORD 32 PumpSuspend 2014-10-05T20:52:05 head[2], body[0] op[0x1e]

    op hex (2)
    0000   0x1e 0x01                                  ..
    decimal
             30    1
    datetime (2014-10-05T20:52:05)
    0000   0x85 0xb4 0x14 0x05 0x0e                   .....
    body (0)
    HOUR BITS: [1, 0, 1]
#### RECORD 33 Bolus (2010, 0, 0, 28, 0, 8) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 10.0, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x00 0x64 0x00                        ..d.
    decimal
              1    0  100    0
    datetime ((2010, 0, 0, 28, 0, 8))
    0000   0x08 0x00 0x3c 0x00 0xba                   ..<..
    body (0)
    YEAR BITS: [1, 0, 1, 1]
#### RECORD 34 Base (2009, 0, 4, 27, 14, 5) head[2], body[0] op[0xb3]

    op hex (2)
    0000   0xb3 0x54                                  .T
    decimal
            179   84
    datetime ((2009, 0, 4, 27, 14, 5))
    0000   0x05 0x0e 0x7b 0x04 0x89                   ..{..
    body (0)
    YEAR BITS: [1, 0, 0, 0]
#### RECORD 35 Base (2000, 0, 29, 8, 14, 5) head[2], body[0] op[0xb4]

    op hex (2)
    0000   0xb4 0x14                                  ..
    decimal
            180   20
    datetime ((2000, 0, 29, 8, 14, 5))
    0000   0x05 0x0e 0x28 0x1d 0x00                   ..(..
    body (0)

#### RECORD 36 PumpResume 2014-10-05T20:52:09 head[2], body[0] op[0x1f]

    op hex (2)
    0000   0x1f 0x20                                  . 
    decimal
             31   32
    datetime (2014-10-05T20:52:09)
    0000   0x89 0xb4 0x14 0x05 0x0e                   .....
    body (0)
    HOUR BITS: [1, 0, 1]
#### RECORD 37 CalBGForPH 2014-10-05T20:53:01 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 203}
```
    op hex (2)
    0000   0x0a 0xcb                                  ..
    decimal
             10  203
    datetime (2014-10-05T20:53:01)
    0000   0x81 0xb5 0x34 0x65 0x0e                   ..4e.
    body (0)
    HOUR BITS: [1, 0, 1] DAY BITS: [0, 1, 1]
#### RECORD 38 Ian3F 2014-10-05T20:53:01 head[2], body[3] op[0x3f]

    op hex (2)
    0000   0x3f 0x19                                  ?.
    decimal
             63   25
    datetime (2014-10-05T20:53:01)
    0000   0x81 0xb5 0x74 0x65 0x0e                   ..te.
    body (3)
    hex
    0000   0x70 0x41 0x96                             pA.
    decimal
            112   65  150
    HOUR BITS: [1, 0, 1] DAY BITS: [0, 1, 1]
#### RECORD 39 Bolus (2013, 4, 0, 0, 0, 8) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 7.2, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x00 0x48 0x00                        ..H.
    decimal
              1    0   72    0
    datetime ((2013, 4, 0, 0, 0, 8))
    0000   0x48 0x00 0x40 0x00 0xad                   H.@..
    body (0)
    YEAR BITS: [1, 0, 1, 0]
#### RECORD 40 Base (2008, 0, 5, 11, 14, 5) head[2], body[0] op[0xb5]

    op hex (2)
    0000   0xb5 0x54                                  .T
    decimal
            181   84
    datetime ((2008, 0, 5, 11, 14, 5))
    0000   0x05 0x0e 0x0b 0x65 0xc8                   ...e.
    body (0)
    DAY BITS: [0, 1, 1] YEAR BITS: [1, 1, 0, 0]
#### RECORD 41 Base (2000, 6, 27, 14, 37, 21) head[2], body[0] op[0xaa]

    op hex (2)
    0000   0xaa 0x87                                  ..
    decimal
            170  135
    datetime ((2000, 6, 27, 14, 37, 21))
    0000   0x55 0xa5 0x0e 0x5b 0x00                   U..[.
    body (0)
    HOUR BITS: [1, 0, 1] DAY BITS: [0, 1, 0]
#### RECORD 42 Base (2000, 1, 26, 14, 37, 23) head[2], body[0] op[0xa3]

    op hex (2)
    0000   0xa3 0x9b                                  ..
    decimal
            163  155
    datetime ((2000, 1, 26, 14, 37, 23))
    0000   0x17 0x65 0x0e 0x1a 0x90                   .e...
    body (0)
    HOUR BITS: [0, 1, 1] YEAR BITS: [1, 0, 0, 1]
#### RECORD 43 Base (2008, 0, 0, 0, 56, 25) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x8c                                  ..
    decimal
              0  140
    datetime ((2008, 0, 0, 0, 56, 25))
    0000   0x19 0x38 0x00 0x00 0x48                   .8..H
    body (0)
    HOUR BITS: [0, 0, 1] YEAR BITS: [0, 1, 0, 0]
`end logs/ReadHistoryData-page-2.data: 44 records`
