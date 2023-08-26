
# Ozempic DICOM Viewer

This is a web-based DICOM (Digital Imaging and Communications in Medicine) viewer that allows users to upload a ZIP file containing DICOM images, and then interactively view and adjust them.

### How to Use

1. **Load ZIP File:** The ZIP file must contain each series in a separate folder, with the DICOM images inside (the slices) ordered by their filename. Highly nested folders supported 😉

2. **Scroll Through Slices:** Use the mouse wheel to navigate through the slices.

3. **Drag to adjust Window-center and Window-width:** Hold down the left mouse button and drag horizontally to adjust the window width and vertically to adjust the window center.

4. **Resize:** Drag the bottom-right corner of each series container to resize it.

### Requirements

- Modern web browser with JavaScript enabled

- ZIP file containing DICOM series, with each series organized into separate folders and the filenames ordered by slice number.

### Dependencies

- [cornerstonejs](https://github.com/cornerstonejs):
  - [cornerstone](https://github.com/cornerstonejs/cornerstone): A library for displaying interactive medical images.
  - [dicomParser](https://github.com/cornerstonejs/dicomParser): A lightweight library to parse DICOM P10 byte streams.
  - [cornerstoneWADOImageLoader](https://github.com/cornerstonejs/cornerstoneWADOImageLoader): DICOM WADO Image Loader for the cornerstone library.


- [JSZip](https://github.com/Stuk/jszip): A library to read, create, and manipulate ZIP files.
