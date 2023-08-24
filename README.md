
# Ozempic DICOM Viewer

This is a web-based DICOM (Digital Imaging and Communications in Medicine) viewer that allows users to upload a ZIP file containing DICOM images, and then interactively view and adjust the images.

### How to Use

1. **Load ZIP File:** The ZIP file must contain each series in a separate folder, with the DICOM files inside (the slices) ordered by their filename. Highly nested folders supported 😉

2. **Scroll Through Slices:** Use the mouse wheel to navigate through the slices of each series.

3. **Drag to adjust Window-center and Window-width:** Hold down the left mouse button and drag horizontally to adjust the window width and vertically to adjust the window center.

4. **Resize each series:** Drag the bottom-right corner of each series container to resize it.

### Requirements

- Modern web browser with JavaScript enabled

- ZIP file containing DICOM series, with each series organized into separate folders and the filenames ordered by slice number.

### Dependencies

- <a href="https://github.com/cornerstonejs/cornerstone" target="_new">Cornerstone</a>: A library for displaying interactive medical images.

- <a href="https://github.com/cornerstonejs/dicomParser" target="_new">dicomParser</a>: A lightweight library to parse DICOM P10 byte streams.

- <a href="https://github.com/cornerstonejs/cornerstoneWADOImageLoader" target="_new">cornerstoneWADOImageLoader</a>: A library to load DICOM P10 instances over HTTP.

- <a href="https://github.com/Stuk/jszip" target="_new">JSZip</a>: A library to read, create, and manipulate ZIP files.
