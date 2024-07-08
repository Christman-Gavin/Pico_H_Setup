# Pico-H setup

&nbsp; This repo provides all you need to start a basic Raspberry Pi Pico program

&nbsp; Included is the following crates:

- cortex-m = "0.7.7"
- cortex-m-rt = "0.7.3"
- embedded-hal = "1.0.0"
- panic-halt = "0.2.0"
- rp2040-boot2 = "0.3.0"
- rp2040-hal = { version = "0.10.2", features = ["rt", "critical-section-impl"] }
- rtt-target = "0.5.0"

### memory.x

&nbsp; Complete configuration with memory lined out and enables a second stage bootloader

### config.toml

&nbsp; Configurations to assist in flashing the program to the Pico. Uses the elf2uf2-rs to allow automatic flashing to thumbv6m-none-eabi target.

### settings.json

&nbsp; Rust analyzer settings so it checks the code against the thumbv6m-none-eabi target
