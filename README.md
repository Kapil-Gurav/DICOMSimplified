![header](https://capsule-render.vercel.app/api?type=venom&height=300&color=gradient&text=DICOMS%20Simplified&textBg=false&reversal=false&animation=twinkling)

# DICOM Simplified

DICOM Simplified is a Python-based application for viewing and processing DICOM (Digital Imaging and Communications in Medicine) files. It provides a user-friendly interface for medical professionals and researchers to interact with medical imaging data.

## Features

- DICOM file reading and visualization
- Multi-slice navigation for 3D datasets
- Real-time contrast adjustment
- Detailed metadata viewer
- DICOM to PNG conversion
- Video creation from DICOM series
- DICOM file anonymization

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/dicom-simplified.git
   cd dicom-simplified
   ```

2. Install the required dependencies:
   ```bash
   pip install ttkbootstrap pillow numpy pydicom opencv-python
   ```

## Usage

Run the application by executing:

```bash
python app.py
```

1. Click "Open" to select a directory containing DICOM files.
2. Use the slider to navigate through slices.
3. Adjust contrast using the "Max" and "Min" sliders.
4. Click "Show info" to view DICOM metadata.
5. Use "Anonymize", "Save PNG", or "MP4" buttons for additional processing.

## Project Structure

- `app.py`: Main application file
- `app_functions.py`: Helper functions for DICOM processing
- `utils/`: Directory containing default images

## Requirements

- Python 3.7+
- ttkbootstrap
- Pillow
- NumPy
- pydicom
- OpenCV

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.



