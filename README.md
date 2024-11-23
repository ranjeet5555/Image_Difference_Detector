 # 🖼️ Spot the Difference: Image Comparison Tool

This project compares two images using Python. It identifies and highlights differences between the images using the **Structural Similarity Index (SSIM)**. 
Results include marked differences, masks, and similarity scores.

---

## 📚 Table of Contents  

- ✨ **[Features](#-features)**  
- 🛠️ **[Installation and Setup](#-installation-and-setup)**  
- 🚀 **[How to Run the Notebook](#-how-to-run-the-notebook)**  
- 📂 **[File Structure](#-file-structure)**  
- 💡 **[Key Functions Explained](#-key-functions-explained)**  
- 🖼️ **[Screenshots](#-screenshots-example-output)**  
- 🌟 **[Dependencies](#-dependencies)**  
- 📋 **[How to Use](#-how-to-use)**  
- 📧 **[Contact](#-contact)**  

---

## ✨ Features

- **Compare Images**: Detects and marks differences between two images.
- **Visual Highlights**: Produces visualizations such as:
  - Side-by-side image comparison.
  - Masked differences.
  - Highlighted regions.
- **Similarity Scoring**: Calculates a similarity percentage for the two images.

---

## 🛠️ Installation and Setup

### 1. Clone the Repository
```bash
git clone https://github.com/ranjeet5555/spot-the-difference.git
cd spot-the-difference
```

### 2. Install Python
Ensure Python (version 3.8 or higher) is installed. Download it from [python.org](https://www.python.org/).

### 3. Install Required Libraries
```bash
pip install numpy opencv-python matplotlib scikit-image
```

---

## 🚀 How to Run the Notebook

1. Open the notebook in Jupyter or any compatible IDE:
   ```bash
   jupyter notebook Diffrence_Btw_2_Images.ipynb
   ```
2. Follow the instructions in the notebook to load your images and view results.

---

## 📂 File Structure
```
spot-the-difference/
│
├── Diffrence_Btw_2_Images.ipynb  # Main Jupyter Notebook
├── images/                       # Directory for sample images (create manually)
└── README.md                     # Documentation
```

---

## 💡 Key Functions Explained

### `check_image(Input_image1, Input_image2)`
- Verifies the existence of both images.
- Ensures images have the same dimensions before comparison.

### `spot_the_difference(Input_image1, Input_image2, Minvalue)`
- Identifies differences between two images using SSIM.
- Generates highlighted regions and masked images.

### `viewing_images(w, h)`
- Displays the results, including:
  - Initial images.
  - Highlighted differences.
  - Masks.

---

## 🖼️ Screenshots (Example Output)

1. **Side-by-side Images**
  ![side_by_side_view](https://github.com/user-attachments/assets/bfe98c27-6c69-464e-b322-346069f1f77a)

2. **Differences Highlighted**
   - Highlights regions of difference in red.
    ![image_difference](https://github.com/user-attachments/assets/73b5427c-af99-4a02-88e4-48f307b45950)

3. **Filled_mask**
  ![Mask_filled](https://github.com/user-attachments/assets/d04cde9c-0e74-4ad6-afcb-39e9b7974c00)
---

## 🌟 Dependencies

- **NumPy**: For numerical operations.
- **OpenCV**: For image processing.
- **Matplotlib**: For visualization.
- **scikit-image**: For calculating SSIM.

---

## 📋 How to Use

1. **Input Images**: Place two images you want to compare in the `images/` directory.
2. **Run Functions**: Follow the notebook instructions to run the `check_image()` and `spot_the_difference()` functions.
3. **View Results**: Output includes similarity scores and highlighted differences.

---

## 📧 Contact

- Email: ranjeetkumar4261770@gmail.com
- GitHub: [ranjeet5555](https://github.com/ranjeet5555)
