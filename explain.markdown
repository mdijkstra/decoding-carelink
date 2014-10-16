# ./status-quo.sh /dev/ttyUSB0 740926
## cat ./status-quo.sh
```bash
```
## cat logs/explain.log
OUT
## Observations
di okt 14 15:54:27 CEST 2014

## stick

* stick runs appear to be ok

## pump


## downloaded: 15

```
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][0]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][10]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][11]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][12]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][12]:data[832]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][13]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][14]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][1]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][2]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][3]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][4]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][5]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][6]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][7]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][8]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][9]:data[1024]:
```


## commands session:finished: 28

```
INFO:session:finished executing:ReadBasalTemp:size[64]:data:{'duration': 0, 'rate': 0.2}
INFO:session:finished executing:ReadBatteryStatus:size[64]:data:{'status': 'normal', 'voltage': 1.31}
INFO:session:finished executing:ReadContrast:size[64]:data:bytearray(b'\x02\x07\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00')
INFO:session:finished executing:ReadCurPageNumber:pages:36
INFO:session:finished executing:ReadFirmwareVersion:size[64]:data:'VER 2.8A1.1'
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][0]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][10]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][11]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][12]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][12]:data[832]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][13]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][14]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][1]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][2]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][3]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][4]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][5]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][6]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][7]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][8]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][9]:data[1024]:
INFO:session:finished executing:ReadPumpID:size[64]:data:'740926'
INFO:session:finished executing:ReadPumpModel:size[64]:data:'754'
INFO:session:finished executing:ReadRadioCtrlACL:size[64]:data:['------', '------', '------']
INFO:session:finished executing:ReadRemainingInsulin:size[64]:data:0.0
INFO:session:finished executing:ReadRTC:size[64]:data:'2014-10-14T15:52:1'
INFO:session:finished executing:ReadSettings:size[64]:data:{'low_reservoir_warn_point': 40, 'keypad_lock_status': 0, 'maxBasal': 1408, 'temp_basal': {'percent': 100, 'type': 'Percent'}, 'paradigm_enabled': 1, 'insulinConcentration': 50, 'audio_bolus_enable': False, 'variable_bolus_enable': True, 'alarm': {'volume': -1, 'mode': 1}, 'rf_enable': False, 'block_enable': False, 'timeformat': 80, 'auto_off_duration_hrs': 14, 'audio_bolus_size': 0, 'selected_pattern': 0, 'patterns_enabled': False, 'insulin_action_type': 2, 'maxBolus': 0.0, 'low_reservoir_warn_type': 1}
INFO:session:finished executing:ReadTotalsToday:size[64]:data:{'yesterday': 86.8, 'today': 0.0}
```

## howdy! pump runs appear to be OK


## CRC errors found, caught, recovered: 1

```
28909:INFO:stick:XXX:IGNORE:BadCRC:returning empty message, sleep .100, avoid errors.
```

* no nak found
* SUCCESS, GOOD CLEAN RUN
