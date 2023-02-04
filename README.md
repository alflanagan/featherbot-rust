# Featherbot Rust Project

## Overview

This is a project to drive the featherbot using a rust program. The base chip for the robot is the Expresif ESP32-S2.
See the [Programming Guide](https://docs.espressif.com/projects/esp-idf/en/latest/esp32s2/) for more information.

For all the information you need to set up an environment and compile rust code for the ESP line of chips, check out
the [Rust on ESP Book](https://esp-rs.github.io/book/introduction.html)

The cargo command to generate the initial project was:

```shell
cargo generate --git https://github.com/esp-rs/esp-idf-template --bin cargo 
```
