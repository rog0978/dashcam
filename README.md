# Dashcam Tools

This is a fork of the **[original Tesla Dashcam repo →]([https://rog0978.github.io/dashcam/index.html](https://github.com/teslamotors/dashcam))**. The updates are:

1. Added a nice visual overlay from the SEI metadata
2. Added an export function to download the overlaid clip after processing

## Dashcam SEI Explorer (Easiest)

**[Use the online SEI Explorer →](https://rog0978.github.io/dashcam/index.html)**

Just drag and drop your MP4 file to view the clip and assocaited SEI metadata. Works entirely in your browser - your files never leave your computer.

## Troubleshooting

Not all Tesla-generated dashcam clips contain SEI data. Only clips recorded on Tesla firmware 2025.44.25 or later and HW3 or above contain SEI data. If car is parked, SEI data may not be present.

If no SEI metadata is found, ensure your dashcam footage meets these requirements.
