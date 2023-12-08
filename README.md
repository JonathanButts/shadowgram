# Shadowgrams

## Overview
**Shadowgrams** is an innovative project that leverages freely available software to create standardized and repeatable shadowgrams. This method utilizes advanced illuminant and camera simulations within the app to provide plastic surgeons with a reliable tool for preoperative planning and postoperative evaluation.

SHadowgrams are a way of visualizing topographic projection intuitively that allows for repeatable evaluation.

## Features
- **Standardized Shadowgrams**: Consistent and repeatable shadowgrams for accurate assessments.
- **3D Facial Scans**: High-resolution scans to capture detailed facial features.
- **Blender Integration**: Utilizes Blender for simulations and protocol automation.
- **Manual and Automated Protocols**: Guides for manual performance and an automated solution for efficiency.
- **Preoperative and Postoperative Evaluation**: Ideal for assessing changes and planning surgeries.

## Requirements
- **3D scanner**: A clinical 3D scanner may be used for this protocol
- **iPhone X or later with FaceID**
- **ScandyPro App**: Recommended for obtaining high-quality facial scans.
- **Blender**
    - Minimum Recommended Requirements:
      - 64-bit dual core 2Ghz CPU with SSE2 support
      - 4 GB RAM
      - 1280×768 display
      - Mouse, trackpad or pen+tablet
      - Graphics card with 1 GB RAM, OpenGL 3.3
- **Fiji**: Or other photo editor capable of measuring image ROI

## Links
- [Scandy](https://www.scandy.co/apps/scandy-pro)
- [Blender](https://www.blender.org/download/)

## Saving Scans
- **File Format**: Save the facial scans as `.ply` files to retain vertex and color information when uploading to Blender[^5^][7].

## Getting a Scan
1. Ensure you have a compatible iPhone model with the ScandyPro app installed.
2. Follow the protocol to capture a facial scan: start with the scanner centered on the nose. Then, slowly expand the scan in a circular manner, trying to stay within a 20 degree arc from midline.
3. Save the scan as a `.ply` file with measurement set to mm.
4. Import the `.ply` file into Blender for simulation and analysis.

## Creating the Shadowgram
1. Import
2. 

## Usage
Shadowgrams can be used to quickly assess facial asymmetries, such as nasal asymmetry, offering a superior alternative to anthropometrics and photogrammetry. The detailed process and best practices are outlined in the included documentation.

## Contributing
Interested in contributing to the Shadowgrams project? Please read our contributing guidelines to get started on helping us improve and expand this tool.

## License
Shadowgrams is released under the MIT License. See the `LICENSE` file for more details.

## Contact
For any inquiries or to report issues, please open an issue on the GitHub repository or contact the project maintainers directly.

## Acknowledgments
A special thanks to all the contributors and plastic surgeons who have provided valuable feedback and insights to make Shadowgrams a robust tool for the medical community.
