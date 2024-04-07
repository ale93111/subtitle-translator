## Real-Time Translation and Text Recognition with Python

This Python script demonstrates real-time translation of text captured from the screen using OCR (Optical Character Recognition) and DeepL API. The translated text is displayed on a Pygame window.

![alt tag](https://github.com/ale93111/subtitle-translator/blob/main/asset/example.gif)


### Features:

- Utilizes the EasyOCR library for text recognition from images.
- Implements DeepL API for language translation.
- Uses Pygame for creating a simple display window.
- Captures a portion of the screen using MSS (Python Screen Capture).
- Continuously updates the translated text in real-time.

### Prerequisites:

- Python 3.x
- `numpy`, `matplotlib`, `PIL`, `pygame`, `easyocr`, `mss`, and `deepl-python` libraries. Install them using `pip install`.

### Usage:

1. Clone the repository or download the script file.
2. Install the required Python packages mentioned in `requirements.txt`.
3. Replace `auth_key` variable with your DeepL API authentication key.
4. Run the script. It will open a Pygame window displaying the translated text.

### How it Works:

1. The script captures a specified portion of the screen using MSS.
2. It recognizes text from the captured image using EasyOCR.
3. The recognized Dutch text is translated into English using DeepL API.
4. The translated text is displayed on a Pygame window.
5. The process repeats continuously, updating the translated text in real-time.

### Notes:

- Ensure that the screen capture bounding box is adjusted according to your screen resolution and the area of interest.
- DeepL API requires an authentication key which can be obtained by signing up on the DeepL website.

### License:

This project is licensed under the [MIT License](LICENSE).

