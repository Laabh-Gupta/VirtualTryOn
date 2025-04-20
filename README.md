# Virtual Try-On

This project implements a Virtual Try-On system using Deep Learning techniques, specifically Generative Adversarial Networks (GANs). It enables users to visualize how a particular piece of clothing would look on a given person without physically trying it on.

## 📆 Project Status
The project is currently in development. Several GAN-based models and classification networks are being tested for optimal results.

---

## 🚀 Features
- Image classification to identify and separate person and cloth images
- Generative models (GANs) for virtual try-on synthesis
- Modular Jupyter Notebooks and Python scripts for various stages of the pipeline
- Custom preprocessing and dataset management

---

## 📁 Project Structure
```
VirtualTryOn/
│
├── classify.ipynb            # Classification notebook for separating cloth and person images
├── GAN.ipynb                 # GAN-based image synthesis
├── gan.py                    # GAN implementation in script form
├── model.ipynb               # Model architecture and experiments
├── model.py                  # Main model logic
├── new_model.ipynb           # Updated or experimental model work
└── test/                     # Test data folder
    └── image/                # Mixed person and cloth images
```

---

## 🚧 Requirements
- Python 3.8+
- TensorFlow or PyTorch (based on implementation)
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook

Install dependencies:
```bash
pip install -r requirements.txt
```
(Note: You may need to create a `requirements.txt` based on your environment.)

---

## 📅 How to Use
1. Place mixed images in the `test/image/` directory.
2. Run `classify.ipynb` to segregate person and cloth images.
3. Run the appropriate GAN notebook or script to perform virtual try-on.
4. View the generated results and compare different model outputs.

---

## 🌐 Dataset
You can use the [DeepFashion Dataset](http://mmlab.ie.cuhk.edu.hk/projects/DeepFashion.html) or your custom dataset.
Ensure you have one-to-one correspondence between person and clothing images.

---

## ✍️ Author
- [Laabh Gupta](https://github.com/Laabh-Gupta)

---

## 📊 Future Work
- Improve synthesis quality using more advanced GANs (e.g., CycleGAN, VITON)
- Integrate GUI for user-friendly interaction
- Add real-time image try-on capability
- Improve dataset annotation pipeline

---

## ✨ Acknowledgements
- DeepFashion Dataset creators
- PyTorch and TensorFlow communities
- Open-source contributors in virtual try-on and GAN research

---

## ✅ License
This project is open-source under the MIT License.

