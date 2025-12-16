# Dashcam Overlay Creator

![Screenshot of Dashcam SEI Explorer with g force](https://github.com/rog0978/dashcam/blob/master/screenshot.png)

This is a fork of the **[original Tesla Dashcam repo](https://github.com/teslamotors/dashcam)**. 

The updates are:

1. Added a nice visual overlay from the SEI metadata
2. Added an export function to download the overlaid clip after processing
3. Added multi-file processing (sequence based on timestamps in filenames from the USB dashcam files)

## Usage

**[Use the online SEI Creator →](https://rog0978.github.io/dashcam/add_SEI_Overlay.html)**

Just drag and drop your MP4 file from the Dashcam USB stick to view the clip with the associated telemetry SEI metadata and export a videoclip with the embedded visualization. Works entirely in your browser - your files never leave your computer!

## Troubleshooting

Not all Tesla-generated dashcam clips contain SEI data. Only clips recorded on Tesla firmware 2025.44.25 or later and HW3 or above contain SEI data. If car is parked, SEI data may not be present.

If no SEI metadata is found, ensure your dashcam footage meets these requirements.
