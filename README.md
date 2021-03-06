
# ezcolor
A simple python lib for set text attribute to output, like foreground, background color, bold and underline
## Installation
```
git clone https://github.com/0x0ptim0us/ezcolor.git
cd ezcolor
python setup.py install
```
OR:
```
pip3 install ezcolor
```
## Usage
```python
from ezcolor import cprint
cp = cprint()
cp('Hello World!', foreground='blue', background='yellow', underline=True, bold=True)
```
Screenshot: 
![alt text](https://github.com/0x0ptim0us/images/raw/master/image1.png "ezcolor 1")

## Supported colors
| Foreground and Background| 
| ------------- |
|black| 
|red| 
|green|
|yellow|
|blue|
|magenta|
|cyan|
|light_gray|
|dark_gray|
|light_red|
|light_green|
|light_yellow|
|light_blue|
|light_magenta|
|light_cyan|
|white|


## Credits
Author : Fardin Allahverdinazhand
## License
Copyright 2017 EZCOLOR

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

