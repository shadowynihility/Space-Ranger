# Space Ranger I Radio Link Budget Analysis

**Date:** 20260604

---

## VHF 1.2 kbps BPSK Uplink

- **Maximum slant range** (1719.54 km @ 5°) path loss: **-140.43 dB**
- **Minimum slant range** (510 km @ 90°) path loss: **-130.0 dB**
- **Satellite receiver sensitivity:** **-118 dBm @ 10⁻⁵ BER**
- **Polarization:** -0.5 dB
- **Ionosphere:** -3.5 dB
- **Other loss:** -0.5 dB
- **Satellite antenna gain:** 0 dBi

### Typical Earth Station

- **Antenna:** 15 dBi circular polarization Yagi antenna
- **Cable loss:** -3 dB
- **Transmitting power:** 47 dBm

**Result:** Signal level at receiver input port is **-113.07 dBm** at maximum slant range. It is much higher than the satellite receiver sensitivity.

---

## UHF 4.096 kbps BPSK Telemetry Downlink

- **Maximum slant range** (1860.74 km @ 5°) path loss: **-152.6 dB**
- **Minimum slant range** (510 km @ 90°) path loss: **-139.2 dB**
- **Satellite RF output:** 27 dBm
- **Ionosphere:** -3.5 dB
- **Other loss:** -0.5 dB
- **Satellite antenna gain:** -8.0 dBi

### Typical Earth Station

- **Antenna:** 22 dBi circular polarization Yagi antenna
- **Polarization:** -3 dB
- **Cable loss:** -0.5 dB (with LNA)
- **Receiver sensitivity:** **-117 dBm @ 10⁻³ BER**

**Result:** Signal at receiver input port is **-137.12 dBm** at maximum slant range. It is higher than the receiver sensitivity.
