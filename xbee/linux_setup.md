## Setup:  
XCTU
- Parent Node: xbee D3D5
  - Child Node: xbee D3B1

## Miscellaneous
$ minicom /dev/ttyUSB0 -b 9600
    >  +++
    <  OK
    >  AT
    <  OK
    >  ATBD 3
    <  OK
    >  ATWR
    <  OK
    >  ATID
    <  3332
    >  ATSL
    <  40C2D3D5
    >  ATSH
    <  13A200

... give up, install XCTU v. 6.3.0, Linux x64
