# ia4eng_afmp_jdbs_project
repositorio para el proyecto del curso Inteligencia Artificial para las Ciencias e Ingenierías

## Rúbricas del README

### Integrantes
1. José David Bustamante Sierra, c.c: 1035440377, ingeniería mecánica.

2. Andrea Fernanda Muegues Pedraza, c.c: 1102381554, ingeniería mecánica.

### Fuente de los datos usados
[Forest Cover Type Prediction - Use cartographic variables to classify forest categories](https://www.kaggle.com/competitions/forest-cover-type-prediction/data)

## Obtener datos y hacerlos disponibles
### Elementos necesarios
1. Cuenta en la plataforma [kaggle](https://www.kaggle.com/)
2. Token en formato .json para interactuar con la API de kaggle. [What is Kaggle API Key? How to get my Kaggle Key?](https://forum.jovian.ai/forum/t/what-is-kaggle-api-key-how-to-get-my-kaggle-key/17721)
### Obtención de datos
#### Carga de token kaggle
```
#call API
!pip install kaggle
#upload kaggle token .json
from google.colab import files
files.upload()
```
Se puede subir el token mediante la opción desplegada de subida de archivos
#### Creación de DataFrame para _train_
```
#Make a directory named kaggle and copy the kaggle.json file there.
!mkdir -p ~/.kaggle
!cp kaggle.json ~/.kaggle/
# change the permission of the file
!chmod 600 ~/.kaggle/kaggle.json
#API from forest cover dataset
!kaggle competitions download -c forest-cover-type-prediction
#unzip files
file_name = 'forest-cover-type-prediction.zip' #the file is the dataset exact name
with ZipFile(file_name, 'r') as zip:
  zip.extractall()
  print('Done')
# .zip is now not necessary
!rm *.zip
#create DF from train
df_train = pd.read_csv('train.csv')
df_train.head()
```
