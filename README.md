# Identifying Recyclable Materials Using Machine Learning

## Project Overview

Identifying Recyclable Materials Using Machine Learning is a web-based application that automatically classifies recyclable waste materials from images using Machine Learning. The system helps improve waste segregation by identifying different recyclable materials and supporting efficient recycling practices. The application provides a simple interface for uploading images, predicting material categories, and managing recycling-related information.

---

## Features

- Machine Learning-based recyclable material classification
- Image upload and prediction
- User-friendly web interface
- Admin login and user management
- Waste management analytics dashboard
- Easy to extend with additional recyclable material categories

---

## Technologies Used

- Python
- Flask
- TensorFlow / Keras
- OpenCV
- NumPy
- Pandas
- HTML
- CSS
- JavaScript
- Bootstrap

---

## Project Structure

```
Identifying_Recyclable_materials_using_ml/
│
├── Material Detection/
├── Models/
├── dataset/ (Not Included)
├── static/
├── templates/
├── app.py
├── requirements.txt
└── README.md
```

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Vandana312004/Identifying_Recyclable_materials_using_ml.git
```

### 2. Navigate to the Project Folder

```bash
cd Identifying_Recyclable_materials_using_ml
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

If the requirements file is unavailable, install the libraries manually:

```bash
pip install flask tensorflow keras opencv-python numpy pandas pillow scikit-learn mysql-connector-python
```

---

## Dataset

The dataset is **not included** in this repository because it exceeds GitHub's maximum file size limit.

Download or prepare a recyclable materials dataset and place it in the following directory:

```
dataset/
├── train/
├── test/
└── validation/
```

---

## Model Generation

The trained Machine Learning model files (`.h5`) are also **not included** because GitHub does not allow files larger than **100 MB**.

If the model files are missing, train the model using your dataset:

```bash
python train.py
```

or run the training notebook/script included in the project.

After training, the generated model files should be placed inside the **Models** folder.

---

## Running the Project

Navigate to the project directory and start the Flask application:

```bash
python app.py
```

If your main application file has a different name, run that file instead.

After the application starts, open your browser and visit:

```
http://127.0.0.1:5000
```

---

## Admin Login

Use the following administrator credentials:

**Email**

```
admin@mail.com
```

**Password**

```
admin123
```

---

## User Registration

New users can register through the application.

Example:

```
Username : Prajwal93
Email    : praj@gmail.com
Password : Praju123
```

---

## Project Workflow

1. Launch the Flask application.
2. Log in using the administrator account or register as a new user.
3. Upload an image of a recyclable material.
4. The Machine Learning model processes the image.
5. The system predicts the recyclable material category.
6. View the prediction results and waste management analytics.

---

## Important Notes

- The **dataset** is not uploaded because it exceeds GitHub's storage limit.
- The trained **`.h5` model files** are also excluded because GitHub does not allow files larger than **100 MB**.
- Before running the application, ensure that:
  - The dataset is available in the `dataset/` folder.
  - The trained model files are generated or copied into the `Models/` directory.
- If model files are missing, train the model before running the application.

---

## Future Enhancements

- Improve model accuracy with larger datasets.
- Support additional recyclable material categories.
- Real-time webcam-based material detection.
- Mobile application integration.
- Cloud deployment.
- IoT-enabled smart waste segregation.

---

## Author

**Vandana H C**

BCA Final Year Project

GitHub: https://github.com/Vandana312004
