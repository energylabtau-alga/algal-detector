[README.md](https://github.com/user-attachments/files/33628820/README.md)
# algal-detector
Offline cell review and measurement for microscope images.
# Algal Detector

Algal Detector is an offline Windows application for reviewing and measuring algae and cyanobacteria in microscope images.

## Download

Published downloads are available under [Releases](https://github.com/energylabtau-alga/algal-detector/releases). Download `Algal-Detector-Windows-Setup.exe` to install the application, or `Algal-Detector-Windows-Portable.zip` to use the portable version. Extract the complete portable ZIP before running it. Windows 64-bit; no separate Python installation is required.

The release includes `Algal-Detector-User-Guide.pdf`, `READ-ME-FIRST.txt`, and `SHA256SUMS.txt`.

## What it does

- Suggests candidate cell outlines and reads clear scale-bar labels locally.
- Provides manual outline editing, smoothing, and touching-cell separation.
- Uses accepted cells and rejected objects to guide subsequent searches in the same image.
- Saves editable projects and exports accepted measurements, annotated images, and cell crops.

No account, analysis server, or internet connection is required. Images and measurements are processed locally. This is an assisted measurement tool: automatic detections and scale suggestions require visual checking. General biological detection accuracy has not been established, and species identification is not provided.

## Version 1.5.1

The release passed 95 automated software tests and separate packaged startup, calibration, detection, project, export, and installer-extraction checks. These checks do not establish biological accuracy across all images.

The Windows build is not digitally signed; Windows may show an unknown-publisher warning. Bundled dependency notices are in `THIRD_PARTY_NOTICES.txt` inside the installed application.
