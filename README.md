# Clothing Detection Project

This project is a web-based application designed to detect and classify clothing items in uploaded images. The application leverages TensorFlow.js and the MobileNet model to provide accurate and efficient clothing classification directly in the browser.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [How It Works](#how-it-works)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Image Upload**: Users can upload images through a simple and intuitive web interface.
- **Real-time Preview**: Uploaded images are displayed immediately for preview.
- **Clothing Classification**: Utilizes the MobileNet model to classify clothing items in the image and displays predictions with associated probabilities.
- **Responsive Design**: The interface is designed to be responsive and user-friendly across various devices.

## Technologies Used

- **HTML & CSS**: For the structure and styling of the web interface.
- **JavaScript**: For handling user interactions and integrating the TensorFlow.js model.
- **TensorFlow.js**: A powerful library for machine learning in JavaScript, used to load and run the MobileNet model for image classification.

## How It Works

1. **Model Loading**: The MobileNet model is loaded asynchronously when the application starts.
2. **Image Upload**: Users can select an image file from their device. The selected image is read and displayed in the preview section.
3. **Image Classification**: The uploaded image is processed by the MobileNet model, which returns predictions of the clothing items present in the image along with their probabilities.
4. **Display Results**: The classification results are displayed below the image preview, showing each detected item and its associated probability.

## Future Enhancements

- **Expand Classification Categories**: Integrate a more specialized model for clothing detection to classify a wider range of clothing items.
- **Improve UI/UX**: Enhance the user interface for a more intuitive and seamless experience.
- **Batch Processing**: Allow users to upload and classify multiple images at once.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
<br>
<br>
<h1>Sample Images</h1>
<img width="1440" alt="Screenshot 2024-08-04 at 12 18 45 AM" src="https://github.com/user-attachments/assets/0e909712-e40c-4870-bd47-ed59b2178822">
<br>
<img width="1440" alt="Screenshot 2024-08-04 at 12 18 35 AM" src="https://github.com/user-attachments/assets/a6a28d35-3312-475c-be71-b3f334e464eb">
<br>
<img width="1440" alt="Screenshot 2024-08-04 at 12 18 26 AM" src="https://github.com/user-attachments/assets/28322be7-be2c-4162-87bb-246623326e8e">
<br>
<img width="1440" alt="Screenshot 2024-08-04 at 12 18 07 AM" src="https://github.com/user-attachments/assets/1a4bb990-e953-4158-b2d5-8b25e2ac1136">
<br>

