FROM ubuntu:16.04
RUN apt-get update
RUN apt-get install -y --no-install-recommends \
    gcc-arm-linux-gnueabi libc6-dev-armel-cross qemu-user-static
ENV PATH=$PATH:/rust/bin \
    CARGO_TARGET_ARM_UNKNOWN_LINUX_GNUEABI_LINKER=arm-linux-gnueabi-gcc \
    QEMU_LD_PREFIX=/usr/arm-linux-gnueabi
