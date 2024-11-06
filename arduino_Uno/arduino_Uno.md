# Lcnc



**Test_arduino_Uno**

```
halrun -I -f ptest.hal
```



Library list

https://github.com/PaulStoffregen/Encoder



sub module


git submodule add https://github.com/PaulStoffregen/Encoder LinuxCNC_Encoder
git submodule add https://github.com/adafruit/Adafruit_NeoPixel.git LinuxCNC_Adafruit_NeoPixel





insatll arduino_Uno CLI

https://github.com/Tpj-root/Arduino_CLI

# add the line in .bashrc
alias ard='/home/cnc/Desktop/soft/bin/arduino-cli'
alias arduino-cli='ard'



arduino-cli core install arduino:avr 







connect encoder

net xjog axis.x.jog-counts   arduinocounter.0

set value   axis.x.jog-scale 0.1

