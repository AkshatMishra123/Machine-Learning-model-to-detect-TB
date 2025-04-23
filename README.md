# 🦠 TB-XNet: Machine Learning Model to Detect Tuberculosis

This project is a deep learning-based approach to detect Tuberculosis (TB) from chest X-ray images. It uses convolutional neural networks (CNNs) to classify images as TB-positive or TB-negative, offering a potential assistive tool for early diagnosis.

---

<img src="TuberCulosis.jpg" width="400"/>


## 📁 Project Structure


---

## 🚀 Features

- ✅ CNN-based architecture
- 🧪 Binary classification: TB-positive vs TB-negative
- 📊 Evaluation metrics: Accuracy, Precision, Recall, AUC
- 📁 Modular and well-structured code

---

## 📦 Requirements

Install required dependencies:

```bash
pip install -r requirements.txt


Or manually install major ones:

pip install torch torchvision matplotlib opencv-python scikit-learn

🏃‍♂️ How to Run
python train_tb_xnet.py


Dataset Recreation
To recreate the dataset that we used for our experiments, follow these steps:

Download the original dataset here.
Extract the files.
Run the create_dataset.py script, making sure to point the 'datapath' argument at the root directory containing the extracted files. This script will perform pre-processing on all the images, converting them into the format we used.
Wait for the processing to complete.
Results
These are the final results for TB-Net on the test dataset. The test dataset contains 348 normal samples and 345 tuberculosis samples.

TB-Net Details
Accuracy	Sensitivity	Specificity	# Params (M)	MACs (G)
92.54	98.0	96.51	7.36	0.65


🙋‍♂️ Author
Akshat Mishra



---

Let me know:
- Do you want to add a dataset source link or description?
- Want me to include image results or model architecture summary?
- Planning to deploy it? I can help with a web interface too.

Let’s make this repo top-notch 💻✨
