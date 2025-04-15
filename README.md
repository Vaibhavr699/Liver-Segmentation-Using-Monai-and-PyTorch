# Liver Segmentation Using MONAI and PyTorch

This project demonstrates **automated liver segmentation** from medical imaging data (CT scans) using **MONAI**, a deep learning framework built on top of PyTorch and specialized for healthcare imaging applications.

## 🧠 Overview

Liver segmentation is a crucial step in medical image analysis and diagnosis. This project uses a UNet-based deep learning model to segment liver regions from CT scans. The model is trained and evaluated using the **Medical Open Network for AI (MONAI)** framework, which simplifies healthcare deep learning workflows.

## 🔧 Tech Stack

- **Python**
- **PyTorch**
- **MONAI**
- **NumPy / Pandas**
- **Matplotlib / Seaborn**
- **Nifti format (.nii) / DICOM**
- **Jupyter Notebooks**

## 📂 Project Structure

## 📈 Results

- **Dice Score**: (Add your result here after training)
- **IoU**: (Add your result here)
- Visualizations of segmentation masks can be found in the `outputs/` folder.

## 🧪 How to Run

🧪 How to Run
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/Vaibhavr699/Liver-Segmentation-Using-Monai-and-PyTorch.git
cd Liver-Segmentation-Using-Monai-and-PyTorch
2. Set Up Environment
Install the required packages using pip:

bash
Copy
Edit
pip install -r requirements.txt
Or manually install the dependencies:

bash
Copy
Edit
pip install monai torch nibabel matplotlib opencv-python pydicom
3. Convert Data (if needed)
Use the dcomtoniftyy.py script to convert DICOM to NIFTI format:

bash
Copy
Edit
python dcomtoniftyy.py
4. Train the Model
bash
Copy
Edit
python train.py
5. Evaluate
Open and run the testing.ipynb notebook for evaluation and result visualization.

📌 TODO
 Add full training logs and metrics

 Improve model performance with data augmentation

 Add support for 3D UNet

 Export model to ONNX or TorchScript

🙌 Acknowledgments
MONAI Framework

Medical imaging datasets used for this project

PyTorch community and documentation

📃 License
This project is licensed under the MIT License – see the LICENSE file for details.

Made with ❤️ by Vaibhavr699
