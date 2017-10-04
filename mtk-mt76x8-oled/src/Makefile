#if compile x86 demo on unbuntu 64.
CC:=//Users/mango/openwrt/openwrt-3.10.14/staging_dir/toolchain-mipsel_24kec+dsp_gcc-4.8-linaro_uClibc-0.9.33.2/bin/mipsel-openwrt-linux-gcc
export STAGING_DIR:=/Users/mango/openwrt/openwrt-3.10.14/staging_dir


all: app0
	@echo build complete


clean:
	-rm oled

app0:oled.c
	$(CC) oled.c -o oled -O0 -g3 
