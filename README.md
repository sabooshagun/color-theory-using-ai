### README

# Face Color Analysis and Lipstick Suggestion using OpenAI API

This project aims to analyze facial color regions and provide a color theory analysis using the OpenAI API. Based on the extracted RGB values from the forehead, nose, cheeks, and lips, the script determines the skin type (autumn, spring, winter, or summer) and suggests suitable lipstick shades.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Files](#files)
- [Example](#example)
- [Contributing](#contributing)
- [License](#license)

## Features
- Extracts average colors from specific facial regions (forehead, nose, cheeks, and lips) using OpenCV and dlib.
- Uses the OpenAI API to analyze the skin tone and provide color theory analysis.
- Suggests suitable lipstick shades based on the skin type.

## Installation
### Prerequisites
- Python 3.6 or higher
- OpenCV
- dlib
- numpy
- openai

### Install required packages
You can install the required packages using pip:
```sh
pip install opencv-python dlib numpy openai
```

### Download dlib model
Ensure you have the `shape_predictor_68_face_landmarks.dat` file in your working directory. If not, you can download it from [dlib's model zoo](http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2) and extract it.

## Usage
### Setup OpenAI API Key
Set up your OpenAI API key by replacing `"YOUR_OPENAI_API_KEY"` with your actual API key in the script.

### Run the Script
1. Save your target image in the working directory or specify the correct path to the image.
2. Run the script:


### Example
1. Place your target image in the working directory or specify the correct path.
2. Run the script to get the analysis and lipstick suggestions.

## Files
- `script.py`: Main script to run the face color analysis and OpenAI API call.
- `shape_predictor_68_face_landmarks.dat`: Dlib model file for facial landmark detection (needs to be downloaded).

## Contributing
1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

## License
Distributed under the MIT License. See `LICENSE` for more information.

---

Feel free to reach out for any issues or contributions. Happy coding!
