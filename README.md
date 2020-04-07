# EPOS4 Driver

## EtherCAT module CST mapping – Default values for RxPDO

```
1st 0x6040-00 Controlword

2nd 0x6071-00 Target torque

3rd 0x60B2-00 Torque offset

4th 0x6060-00 Modes of operation

5th 0x60FE-01 Digital outputs
```

## EtherCAT module CST mapping – Default values for TxPDO

```
1st 0x6041-00 Statusword

2nd 0x6064-00 Position actual value

3rd 0x606C-00 Velocity actual value

4th 0x6077-00 Torque actual value

5th 0x6061-00 Modes of operation display

6th 0x60FD-00 Digital inputs
```

Author: stefano.dallagasperina@polimi.it

Reference: EPOS4 Firmware Specification CCMC | 2019-11 | rel8758
