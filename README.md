# Low Complexity Subband Codec (SBC)
This is from Android bluedroid SBC https://android.googlesource.com/platform/external/bluetooth/bluedroid/+/refs/heads/main/embdrv/sbc

## Overview
In order to support A2DP in Zephyr, we need to have the SBC encoder and decoder because it is mandatory for A2DP.
Android bluedroid maintain it, so Zephyr can take advantage of it. It's license is Apache2.0
