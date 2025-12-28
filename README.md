# Build a Fake Phone, Find Real Bugs: Qualcomm GPU Emulation and Fuzzing with LibAFL QEMU

This is the hub repository for the talk presented during 39C3.
I'll upload here the slides and the various links to the related projects.

## Links to projects evoqued during the talk

- [Qualcomm GPU patches for QEMU](https://github.com/quic/qemu/tree/rmalmain/qcom_canoe_graphics): QEMU patches to get Qualcomm GPU support
- [LibAFL QEMU](https://github.com/AFLplusplus/LibAFL/tree/main/crates/libafl_qemu): LibAFL QEMU main crate
- [qemu-libafl-bridge](https://github.com/AFLplusplus/qemu-libafl-bridge): The official QEMU fork of LibAFL
- [`fdtviz`](https://github.com/rmalmain/fdtviz): Create graphviz visualizations from a DTB blob
- [`libvharness`](https://github.com/rmalmain/libvharness): Build your own harnesses for embedded and kernel fuzzing. Cross-architecture support
- [`linux-qemu-image-builder`](https://github.com/AFLplusplus/linux-qemu-image-builder): Automatic building of fully-featured and minimal Linux images for fuzzing
