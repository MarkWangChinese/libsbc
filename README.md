# Low Complexity Subband Codec (SBC)
This is from Android bluetooth SBC https://cs.android.com/android/platform/superproject/main/+/main:packages/modules/Bluetooth/system/embdrv/sbc/

## Overview
In order to support A2DP in Zephyr, we need to have the SBC encoder and decoder because it is mandatory for A2DP.
Android bluetooth maintain it, so Zephyr can take advantage of it. It's license is Apache2.0
