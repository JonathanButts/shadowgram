# Shadowgrams

## Overview
**Shadowgrams** is an innovative project that leverages freely available software to create standardized and repeatable shadowgrams. This method utilizes advanced illuminant and camera simulations within the app to provide plastic surgeons with a reliable tool for preoperative planning and postoperative evaluation.

Shadowgrams are a way of visualizing topographic projection intuitively that allows for repeatable evaluation.

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

## How to Make a Shadowgram from a PLY File
1. Open Blender and import the PLY file that you want to use. The template is available to download above.
2. Use the bisect tool to cut off any unnecessary parts of the mesh and make it easier to work with.
3. Use the transform panel in the sidebar to rotate and position the mesh as you like.
4. Make sure that the pronasale (the tip of the nose) is at the origin of the coordinate system.
5. Switch to edit mode, select the pogonion vertex (the most forward point of the chin), press shift-s and choose snap cursor to selected, switch back to object mode, go to the options menu in the top right corner, change the origin option to cursor, right-click and select set origin to cursor, and rotate the mesh so that the nasion (the bridge of the nose) is pointing upwards.
6. Position the camera and light sources as needed for your use. Defaults are point source, 1m above origin, at 5,000W.
7. Render the image (F12) and save as PNG 16b in B&W.

[Youtube link for educational video.](https://youtu.be/yPQkbHup7DQ)

## Quantification
1. Open the image into ImageJ
2. Shadow facets can be manually outlined with the freehand selection tool
3. Calibrate the image based on a fixed measurement such as alar width

## Shadow Facets
Shadow Surface faces
# Paired:
1. Maxillofrontale – S: nasion I: endocanthion line, L: Medial upper lid highlight, M: dorsal aesthetic line
2. Upper Lateral – Sup: endocanthion line, Med: Dorsal aesthetic line, Lat: nasomalar fold or extent of shadow, Inf: rhinion
3. Lower Lateral – Sup: Rhinion, Med: Dorsal aesthetic line, Lat: lateral extent of shadow, Inf: tip
4. Soft triangle
5. Alar margin
6. Subalare – alar groove from tip to sill
7. Sill
8. Lateral philtrum – Philtral column down to crista philitri and laterally over lateral lip element
   
# Unpaired:
1. Radix – Glabellar line to border of nasion highlight, DAL’s
2. Supratip
3. Subnasale
4. Medial philtrum

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
