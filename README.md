# IEEEOJCOMS2025
We propose a lightweight cipher to secure MAVLink communications in UAVs, addressing its lack of built-in encryption. Tested alongside AES-CTR, ChaCha20, Speck-CTR, and Rabbit on a real drone, it shows strong security (via NIST/Diehard tests) and superior efficiency in memory, CPU, and power usage.

## Drone Components

This repository includes hardware components integrated into a custom UAV platform assembled and tested in the lab.

## References

1. [Cube Orange+ Flight Controller](https://ardupilot.org/copter/docs/common-thecubeorange-overview.html)
2. [Ublox Here3+ GNSS](https://docs.cubepilot.org/user-guides/here-3/here-3-manual)
3. [Radiomaster boxer radio controller](https://cdn.shopify.com/s/files/1/0609/8324/7079/files/BOXER_1.pdf?v=1736839329)
4. [Holybro Sik 433MHz telemetry module](https://ardupilot.org/copter/docs/common-sik-telemetry-radio.html)
5. [Antigravity motor 4006](https://uav-en.tmotor.com/2018/Antigravity_0402/24.html)
6. [Electronic speed controller](https://uav-en.tmotor.com/2018/air_0410/70.html)

## Statistical Test Suites

1. [NIST Test Suite](https://csrc.nist.gov/projects/random-bit-generation/documentation-and-software)
2. [Diehard Test Suite](https://rurban.github.io/dieharder/manual/dieharder.pdf)


