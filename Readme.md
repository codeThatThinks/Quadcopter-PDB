# Quadcopter PDB

A custom power distribution board for by quadcopter frame. It is rated for 120 amps, or 30 amps per ESC. There is a MOSFET controlled high side switch which allows power to be turned off without having to disconnect the battery connector. The current sensor is essential an integrated version of [this AttoPilot current sensor](https://www.sparkfun.com/products/10644). There is also an onboard 5V switching regulator that provides filtered VTX power.


## Specs

* Rated Current: 120 A
* Max ESC: 30 A
* Max Battery: 6S
* VTX Current: 3 A
* Current Sensor Output: 18.30 mV/Amp


## License

The MIT License (MIT)

Copyright (c) 2017 Ian Glen

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
