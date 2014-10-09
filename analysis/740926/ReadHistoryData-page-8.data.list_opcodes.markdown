## START logs/ReadHistoryData-page-8.data
#### STOPPING DOUBLE NULLS @ 163, found 0 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0xbb 0x75 0x54 0x77 0x0e 0x1e 0x01 0x98    .uTw....
    0008   0x42 0x15 0x17 0x0e 0x01 0x00 0x4c 0x00    B.....L.
    0010   0x08 0x00 0xf8 0x00 0x91 0x42 0x55 0x17    .....BU.
    0018   0x0e 0x7b 0x04 0x9d 0x42 0x15 0x17 0x0e    .{..B...
##### DEBUG DECIMAL
            187  117   84  119   14   30    1  152
             66   21   23   14    1    0   76    0
              8    0  248    0  145   66   85   23
             14  123    4  157   66   21   23   14
#### RECORD 0 Ian3F 2014-09-23T07:13:57 head[2], body[3] op[0x3f]

    op hex (2)
    0000   0x3f 0x11                                  ?.
    decimal
             63   17
    datetime (2014-09-23T07:13:57)
    0000   0xb9 0x4d 0x87 0x77 0x0e                   .M.w.
    body (3)
    hex
    0000   0x70 0x41 0x96                             pA.
    decimal
            112   65  150
    HOUR BITS: [0, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 1 BasalProfileStart 2014-09-23T08:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x01                                  {.
    decimal
            123    1
    datetime (2014-09-23T08:00:00)
    0000   0x80 0x40 0x08 0x17 0x0e                   .@...
    body (3)
    hex
    0000   0x10 0x1b 0x00                             ...
    decimal
             16   27    0
    HOUR BITS: [0, 1, 0]
#### RECORD 2 Ian0B 2014-09-23T10:48:13 head[3], body[0] op[0x0b]

    op hex (3)
    0000   0x0b 0x73 0x00                             .s.
    decimal
             11  115    0
    datetime (2014-09-23T10:48:13)
    0000   0x8d 0x70 0x4a 0xb7 0x0e                   .pJ..
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [1, 0, 1]
#### RECORD 3 Bolus (2001, 8, 0, 0, 0, 16) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.1, 'dual_component': '??', 'programmed': 14.4, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x01 0x90 0x01                        ....
    decimal
              1    1  144    1
    datetime ((2001, 8, 0, 0, 0, 16))
    0000   0x90 0x00 0x00 0x00 0x81                   .....
    body (0)
    YEAR BITS: [1, 0, 0, 0]
#### RECORD 4 old6c (2007, 0, 5, 11, 14, 23) head[2], body[38] op[0x6c]

    op hex (2)
    0000   0x6c 0x4b                                  lK
    decimal
            108   75
    datetime ((2007, 0, 5, 11, 14, 23))
    0000   0x17 0x0e 0x0b 0x65 0xc7                   ...e.
    body (38)
    hex
    0000   0x9f 0x79 0x4b 0xb7 0x0e 0x7b 0x02 0x80    .yK..{..
    0008   0x40 0x0c 0x17 0x0e 0x18 0x06 0x00 0x01    @.......
    0010   0x00 0x50 0x00 0x50 0x01 0x74 0x00 0xab    .P.P.t..
    0018   0x7a 0x4b 0x17 0x0e 0x0b 0x73 0x00 0x97    zK...s..
    0020   0x75 0x4e 0xb7 0x0e 0x0a 0x73              uN...s
    decimal
            159  121   75  183   14  123    2  128
             64   12   23   14   24    6    0    1
              0   80    0   80    1  116    0  171
            122   75   23   14   11  115    0  151
            117   78  183   14   10  115
    DAY BITS: [0, 1, 1] YEAR BITS: [1, 1, 0, 0]
#### RECORD 5 Base (2014, 1, 31, 14, 55, 47) head[2], body[0] op[0x9b]

    op hex (2)
    0000   0x9b 0x50                                  .P
    decimal
            155   80
    datetime ((2014, 1, 31, 14, 55, 47))
    0000   0x2f 0x77 0x0e 0x3f 0x0e                   /w.?.
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 0, 1]
#### RECORD 6 Base (2001, 5, 16, 14, 55, 47) head[2], body[0] op[0x9b]

    op hex (2)
    0000   0x9b 0x50                                  .P
    decimal
            155   80
    datetime ((2001, 5, 16, 14, 55, 47))
    0000   0x6f 0x77 0x0e 0x70 0x41                   ow.pA
    body (0)
    HOUR BITS: [0, 1, 1] DAY BITS: [0, 1, 1] YEAR BITS: [0, 1, 0, 0]
#### RECORD 7 Base (2000, 4, 13, 23, 0, 51) head[2], body[0] op[0x96]

    op hex (2)
    0000   0x96 0x0b                                  ..
    decimal
            150   11
    datetime ((2000, 4, 13, 23, 0, 51))
    0000   0x73 0x00 0x97 0x4d 0x50                   s..MP
    body (0)
    DAY BITS: [0, 1, 0] YEAR BITS: [0, 1, 0, 1]
#### RECORD 8 Base (2002, 4, 0, 0, 3, 59) head[2], body[0] op[0xb7]

    op hex (2)
    0000   0xb7 0x0e                                  ..
    decimal
            183   14
    datetime ((2002, 4, 0, 0, 3, 59))
    0000   0x7b 0x03 0x80 0x40 0x12                   {..@.
    body (0)
    DAY BITS: [0, 1, 0] YEAR BITS: [0, 0, 0, 1]
#### RECORD 9 ChangeTime (2003, 0, 11, 0, 24, 36) head[2], body[0] op[0x17]

    op hex (2)
    0000   0x17 0x0e                                  ..
    decimal
             23   14
    datetime ((2003, 0, 11, 0, 24, 36))
    0000   0x24 0x18 0x00 0x0b 0x73                   $...s
    body (0)
    YEAR BITS: [0, 1, 1, 1]
#### RECORD 10 Base (2011, 5, 14, 23, 19, 37) head[2], body[0] op[0x00]

    op hex (2)
    0000   0x00 0x9b                                  ..
    decimal
              0  155
    datetime ((2011, 5, 14, 23, 19, 37))
    0000   0x65 0x53 0xb7 0x0e 0x7b                   eS..{
    body (0)
    HOUR BITS: [0, 1, 0] YEAR BITS: [0, 1, 1, 1]
#### RECORD 11 Base (2008, 4, 14, 23, 20, 0) head[2], body[0] op[0x04]

    op hex (2)
    0000   0x04 0x80                                  ..
    decimal
              4  128
    datetime ((2008, 4, 14, 23, 20, 0))
    0000   0x40 0x14 0x17 0x0e 0x28                   @...(
    body (0)
    YEAR BITS: [0, 0, 1, 0]
#### RECORD 12 Base (2004, 4, 21, 27, 0, 27) head[2], body[0] op[0x1d]

    op hex (2)
    0000   0x1d 0x00                                  ..
    decimal
             29    0
    datetime ((2004, 4, 21, 27, 0, 27))
    0000   0x5b 0x00 0xbb 0x75 0x14                   [..u.
    body (0)
    DAY BITS: [0, 1, 1] YEAR BITS: [0, 0, 0, 1]
#### RECORD 13 Base (2009, 6, 12, 0, 16, 26) head[2], body[0] op[0x77]

    op hex (2)
    0000   0x77 0x0e                                  w.
    decimal
            119   14
    datetime ((2009, 6, 12, 0, 16, 26))
    0000   0x5a 0x90 0x00 0x8c 0x19                   Z....
    body (0)
    HOUR BITS: [1, 0, 0] DAY BITS: [1, 0, 0] YEAR BITS: [0, 0, 0, 1]
#### RECORD 14 Base (2000, 0, 0, 0, 0, 1) head[2], body[0] op[0x38]

    op hex (2)
    0000   0x38 0x00                                  8.
    decimal
             56    0
    datetime ((2000, 0, 0, 0, 0, 1))
    0000   0x01 0x00 0x00 0x00 0x00                   .....
    body (0)

#### RECORD 15 Bolus (2000, 0, 0, 1, 0, 1) head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 7.8, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x00 0x4e 0x01                        ..N.
    decimal
              1    0   78    1
    datetime ((2000, 0, 0, 1, 0, 1))
    0000   0x01 0x00 0x01 0x00 0x00                   .....
    body (0)

`end logs/ReadHistoryData-page-8.data: 16 records`
