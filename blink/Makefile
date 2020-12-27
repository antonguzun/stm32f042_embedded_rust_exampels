build:
	cargo build --release \
	&& arm-none-eabi-objcopy -O binary target/thumbv6m-none-eabi/release/blinky-rust blinky-rust.bin

flash:
	cargo flash --chip stm32f042k6 --release
