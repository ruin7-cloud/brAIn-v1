# brAIn-v1

https://ruin7-cloud.github.io/brAIn-v1/

**brAIn-v1** is a web-based demo project that classifies brain MRI images using a Teachable Machine model.

---

## Disclaimer

- This project **currently works only with brain MRI images**.
- It is **under development** and **cannot be used for medical diagnosis**.
- The predictions are **for demonstration purposes only**.

---

## How to Use

1. Click **Choose Image**.
2. Upload a brain MRI image in any standard image format (JPEG, PNG, etc.).
3. The model will predict the class and show probability bars for each relevant class.
4. Images that are **not brain MRI images** will trigger a warning message.

---

## Project Structure

brAIn-v1/
│
├── index.html       # Main web interface
├── model/           # Teachable Machine model files
│   ├── model.json
│   └── metadata.json
└── README.md


## Technologies Used

-TensorFlow.js
-Teachable Machine

## Updates

Project Update Notes: 08/31/2025
The brAIn project has received a major update that significantly improves its interface and capabilities. The key new features in this release are:
-New UI/UX Design: The project's interface has been completely revamped with a more modern and user-friendly design.
-Multiple File and Camera Support: Multiple MR images can now be loaded simultaneously, or instant scans can be performed using the device camera.
-Advanced Reporting System: Analysis results can now be downloaded as a professional PDF report containing watermarks, QR codes, and methodology explanations.
-Overall Confidence Score: An “Overall Confidence Score” has been added to the results screen, indicating how confident the model is in its predictions.
-Multi-Language Support: The interface offers Turkish and English language support, with English as the default language. Users can switch between languages instantly.
-Project Information Screen: The “About” button added to the top right provides information about the project's purpose, the technologies used, and the developer.
