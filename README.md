"# MaskDetection" 
## IMPORTANTE

En este proyecto realizamos la detección de tapabocas en video usando el modelo Retinanet, entrenando una red neuronal convolucional ResNet50 preentrenada.


### Pre-requisitos 📋

      _Anaconda
      _Jupyter notebook o google colab
      _Tensorflow 
      _Keras
      _Keras Retinanet https://github.com/DavidReveloLuna/keras-retinanet
      _labelImg (https://github.com/tzutalin/labelImg.git)

### Instalación labelImg (Windows + Anaconda)🔧

      git clone https://github.com/tzutalin/labelImg.git
      cd labelImg
      conda install pyqt=5
      pyrcc5 -o libs/resources.py resources.qrc
      python labelImg.py

### Dataset modificado a partir de:
		https://medium.com/face-mask-detector-using-deep-learning-yolov3/face-mask-detector-using-deep-learning-yolov3-209b57f77e92

### Descripción del directorio

1. ...\MaskDetection\images

      Directorio donde estan las imagenes para el entrenamiento y pruebas

2. ...\MaskDetection\snapshots
      
      En este directorio debe encontrarse el modelo entrenado de extensión .h5

3. ...\MaskDetection

      En este directorio deben encontrarse los archivos .csv que contienen la información del dataset de entrenamiento y pruebas
        annotations.csv
        classes.csv
        annotations_test.csv

4. MaskDetectionColab.txt contiene el codigo para google colab que entrena la red neuronal

5. MaskDetection.ipynb contiene el codigo para jupyter notebook donde probamos la red en imágenes y en video

# **Canal de Youtube**
[Click aquì pare ver mi canal de YOUTUBE](https://www.youtube.com/channel/UCr_dJOULDvSXMHA1PSHy2rg)
