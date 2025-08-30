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

## Future Improvements

-Support for DICOM MRI images.
-Improved accuracy with larger datasets.
-Better UI/UX enhancements.

