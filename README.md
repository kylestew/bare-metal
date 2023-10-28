# STM32 Bare Metal

> Featuring the BluePill

## Install command line tools

    $ brew install gcc-arm-embedded stlink


## LibOpenCM3

clone as submodule

https://libopencm3.org/docs/latest/stm32f1/html/modules.html


## Wiring guide (and flashing demo)

https://www.youtube.com/watch?v=YEGKD6JQJyM

## Connecting to ST-Link

    $ st-info --probe


## Flashing

    $ st-flash --reset write blink.bin 0x8000000


### Other Resources

https://github.com/potatopplking/STM32F0_baremetal

https://github.com/libopencm3/libopencm3-examples/tree/master/examples/stm32/f0/stm32f0-discovery/miniblink

https://www.youtube.com/watch?v=06ICtJjPKlA&list=PLP29wDx6QmW7HaCrRydOnxcy8QmW0SNdQ&index=2