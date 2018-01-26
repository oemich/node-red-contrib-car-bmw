[![npm version](https://badge.fury.io/js/node-red-contrib-car-bmw.svg)](https://badge.fury.io/js/node-red-contrib-car-bmw)
[![Build Status](https://travis-ci.org/krauskopf/node-red-contrib-car-bmw.svg?branch=master)](https://travis-ci.org/krauskopf/node-red-contrib-car-bmw)

[![NPM](https://nodei.co/npm/node-red-contrib-car-bmw.png?compact=true)](https://nodei.co/npm/node-red-contrib-car-bmw/)

# Node-RED nodes for BMW ConnectedDrive
This package contains nodes to easily connect to BMW ConnectedDrive and read out informations about your vehicles.

NOTE: These nodes are unofficial and do NOT COME from BMW AG. Be careful when using these.

Be careful not to send your login and password to anyone other than BMW or you are giving away the authentication details required to control your car.

Also ensure that you don't overwhelm the BMW servers with requests. Calling REST APIs at very high frequency can put substantial load on the servers and might get your IP blocked by BMW.

## Disclaimer
Use these nodes at your own risk. The authors do not guaranteed the proper functioning of these nodes.
This code attempts to use the same interfaces used by the official BMW ConnectedDrive web portal.
However, it is possible that use of this code may cause unexpected damage for which nobody but you are responsible.
Use of these functions can change the settings on your car and may have negative consequences such as (but not limited to)
reducing the available charge in the battery.

## Installation
Install using the managed palette from inside Node-RED.

## Usage
There are 2 new nodes which appear in the category 'BMW' in your Node-Red palette.

![nodes.png](./doc/nodes.png)

#### BMW List
Reads the list of cars, that are assigned to a BMW ConnectedDrive account.

#### BMW Get
Read different informations about your car.

### Additional Information
For these nodes to work you need a car with BMW ConnectedDrive support and remote services.

## History
- 2017-Dez-01: 0.1.0 - First prototype.
- 2018-Jan-26: 0.1.1 - Remove verbose logging of token code.

## Credits
- Sebastian Krauskopf (mail@sebakrau.de)

This project is heavily influenced by the work of:
- Nils Schneider (https://github.com/Lyve1981/BMW-ConnectedDrive-JSON-Wrapper)
- Sergej Müller (https://github.com/sergejmueller/battery.ebiene.de)
- Terence Eden (https://github.com/edent/BMW-i-Remote)

## Trademarks
- "BMW ConnectedDrive" is a registered trademark of BMW AG.

## Licenses
The MIT License (MIT)

Copyright (c) 2017 sebakrau (mail@sebakrau.de)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

BSD 2-Clause License

Copyright (c) 2017, Nils Schneider
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this
  list of conditions and the following disclaimer.

* Redistributions in binary form must reproduce the above copyright notice,
  this list of conditions and the following disclaimer in the documentation
  and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
