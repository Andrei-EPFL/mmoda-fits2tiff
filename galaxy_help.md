---
description: Tool to convert FITS files to TIFF
long_description: Tool to convert FITS files to TIFF
additional_files:
---


This tool converts images stored in FITS files to TIFF format. If the FITS file contains multiple HDUs, the desired HDU index can be specified. The image data itself is not altered during the conversion.

In addition to the TIFF file, the tool also outputs a JSON file containing the metadata from the header of the selected FITS HDU.