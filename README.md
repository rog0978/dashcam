# Dashcam Tools

This repo contains tools for extracting metadata data from supported Tesla Dashcam videos. This includes information such as vehicle speed, steering wheel angle, and self-driving state.

This information also appears in the Dashcam Viewer during playback on supported vehicle displays and the Tesla App.

## Web Extractor (Easiest)

**[Use the online SEI Extractor →](https://teslamotors.github.io/dashcam/sei_extractor.html)**

Just drag and drop your MP4 files to extract SEI metadata to CSV. Works entirely in your browser - your files never leave your computer.

## Files

* [`sei_extractor.py`](sei_extractor.py)
    * Python-based metadata extractor. Command-line tool for extracting SEI data from MP4 files.
* [`sei_extractor.html`](sei_extractor.html)
    * Web-based metadata extractor. Generates a CSV of the metadata from an MP4.
* [`dashcam.proto`](dashcam.proto)
    * The protobuf spec that is used to decode SEI data in the MP4 file(s).

## Troubleshooting

Not all Tesla-generated dashcam clips contain SEI data. Only clips recorded on Tesla firmware 2025.44.25 or later and HW3 or above contain SEI data. If car is parked, SEI data may not be present.

If no SEI metadata is found, ensure your dashcam footage meets these requirements.
