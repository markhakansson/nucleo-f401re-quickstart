# Nucleo-F401RE Quickstart
This is the [Cortex-M Quickstart](https://github.com/rust-embedded/cortex-m-quickstart)
with some changes to make it work with Nucleo-F401RE dev board. 

## Instructions to flash

1. Connect to the dev board:
```
openocd
```
This will automatically use the settings in openocd.cfg

2. Build and flash the program 
```
cargo run
```
