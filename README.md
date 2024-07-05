# OCR Project

This project implements Optical Character Recognition (OCR) using Python, OpenCV, pytesseract, spellchecker, and Levenshtein distance. It preprocesses images, detects characters with bounding boxes, overlays recognized characters, corrects text using spellchecking, and measures accuracy against ground truth.

## Features

- **Image Preprocessing**: Uses OpenCV for adaptive thresholding and denoising.
- **Character Detection**: Utilizes pytesseract for recognizing characters and generating bounding boxes.
- **Text Correction**: Implements spell-checking and text cleaning using the `spellchecker` library.
- **Accuracy Evaluation**: Calculates Levenshtein distance for evaluating OCR accuracy.

## Use of OCR

### Libraries Used

- **OpenCV**: Provides image preprocessing capabilities such as adaptive thresholding and denoising.
- **pytesseract**: Integrates Tesseract OCR engine to detect text and generate bounding boxes.
- **spellchecker**: Implements spell-checking functionality to improve the accuracy of recognized text.
- **Levenshtein**: Calculates the Levenshtein distance to measure the accuracy of OCR results against ground truth.

### Accuracy Measure

- **Levenshtein Distance**: Measures the minimum number of single-character edits required to transform the predicted OCR output into the ground truth text. It quantifies the accuracy of the OCR process by accounting for minor variations like spelling errors or formatting differences.

## Requirements

- Python 3.x
- OpenCV
- pytesseract
- spellchecker
- Levenshtein
- matplotlib (for visualization, optional)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/aishwaryabit1603/Ocr_Project.git
   cd Ocr_Project
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
## Usage
- **Preprocess Images**: Implement preprocessing using OpenCV to prepare images for OCR.
- **Detect Characters**: Utilize pytesseract to detect characters and generate bounding boxes.
- **Overlay Recognized Text**: Draw bounding boxes around detected characters and overlay recognized text.
- **Correct Text**: Implement spell-checking to correct recognized text for improved accuracy.
- **Evaluate Accuracy**: Calculate Levenshtein distance to measure accuracy against ground truth text.

## Contributing
Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

MIT
