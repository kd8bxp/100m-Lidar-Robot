# September 2, 2024 - Archiving code

Robot has been taken apart, this ended up being only part sucessful, but mosted ended up failing  

# 100m LiDar Robot

The goal of this project was to replace a ultrasonic with a electric tape measurement module. The module used can be found here:  
https://www.aliexpress.com/item/100M-Laser-ranging-module-digital-sensors-Distance-Measuring-serial-port-USB-to-RS232-TTL-signal/32702749857.html?spm=a2g0s.9042311.0.0.687e4c4dJz3BNN  
This was suppose to be 100m unit, but under my test, 10m is about the best I was able to get.  
I used a 4 wheel robot chassis, a L298N board, and a Arduino Nano, and many 3D printed parts.  
Version 1, used 2 Arduino Nanos - but that was more than was need. This was a proof of concept version.  
Version 2 moved the laser/lidar sensor to the top platform, removed one of the Nanos, added neopixels to display a range. (The neopixel changed the timings a bit, but it still works.)  
A more complete instructable is in the works.  

## Installation

## Libraries

Uses Adafruit Neopixel (version 1.3.5), and SoftwareSerial libraries (unknown version).  
Because the Arduino IDE has been getting pretty bad handling libraries, I've included the libraries used in the src directory of the sketch. These libraries may have been slightly modified to work from the sketch directory, and do not include the examples.  

## Things To Do

## Usage

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## Support Me

If you find this or any of my projects useful or enjoyable please support me.  
Anything I do get goes to buy more parts and make more/better projects.  
https://www.patreon.com/kd8bxp  
https://ko-fi.com/lfmiller  
https://www.paypal.me/KD8BXP  

## Other Projects

https://www.youtube.com/channel/UCP6Vh4hfyJF288MTaRAF36w  
https://kd8bxp.blogspot.com/  

## Credits

Copyright (c) 2018/2019 LeRoy Miller

## License

This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses>
