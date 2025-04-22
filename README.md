# Proyek Klasifikasi Gambar

## Deskripsi
Dataset Kaggle: https://www.kaggle.com/datasets/puneet6060/intel-image-classification

Intel Image Classification

Proyek ini mengimplementasikan model Convolutional Neural Network (CNN) menggunakan TensorFlow dan Keras untuk klasifikasi gambar. Model dilatih untuk mengenali dan mengklasifikasikan gambar ke dalam beberapa kategori. Notebook (`Proyek_Klasifikasi_Gambar.ipynb`) berisi kode lengkap untuk membangun, melatih, mengevaluasi, dan mengonversi model.

## Model Konversi
- tfjs_model
- model.tflite
- saved_model

## Dependensi

Proyek ini membutuhkan library Python berikut:
- keras==3.8.0
- matplotlib==3.10.1
- numpy==2.2.5
- opencv_contrib_python==4.11.0.86
- opencv_python==4.11.0.86
- opencv_python_headless==4.11.0.86
- pandas==2.2.3
- Pillow==11.2.1
- protobuf==6.30.2
- scikit_learn==1.6.1
- seaborn==0.13.2
- skimage==0.0
- tensorflow==2.18.0
- tqdm==4.67.1

Semua dependensi dapat diinstal menggunakan file `requirements.txt`:

```bash
!pip install pipreqs

!pipreqs --scan-notebooks '/content/drive/MyDrive/Colab Notebooks/Proyek Akhir Klasifikasi Gambar'
