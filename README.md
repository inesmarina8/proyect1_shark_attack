# SHARK ATTACK (PANDAS PROJECT IRONHACK 10/2024)

_This project has the objective to deep clean a DataFrame with the peciluarity of being very messed up one._

_Through this notebook it would be possible to see different methods of cleaning a DataFrame and also different visualizations that show the conclusions achieved after clearing the information obtained from the imported DataSet._

_It is only possible to interpret  this DataSet in so many ways as it has been cleared out._

## To begin 🚀

_This project will show a process to clean and develop different hypotheses from a big Data Set with many unknow values._




Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas._

### Pre-requirements 📋

_What we have installed to work with this Data Set_

```
Pandas
Numpy
Seaborn
Matplotlib.pyplot
chardet (optional as I had to in ordert to import the CSV, there are also other was to read the CSV withtout chardet)
```

### Installation 🔧

_Steps followed for the installation of the libraries_

_How I read the CSV with Chardet_

_As always, it is important to understand what is wanted to be done with the imported information.In this specific case, it was asked to make a few hypotheses based on the information got from the CSV. This is why we imported PANDAS and NUMPY._

```
Da un ejemplo
```

_As long as we have a Data Frame we can only analyze as deep as we can print the DF. In this case our DF is so exhaustive that we could not visualize table content. This is the reason to import Seaborn and Matplotlib.pyplot._

_To import the CSV after a few errors the following code was used after chardet library was improted:_
```
with open('attacks.csv', 'rb') as f:
    result = chardet.detect(f.read())
df = pd.read_csv('attacks.csv', encoding=result['encoding'])
print(df.head())
```
## Ejecutando las pruebas ⚙️

_Explica como ejecutar las pruebas automatizadas para este sistema_

### Analice las pruebas end-to-end 🔩

_Explica que verifican estas pruebas y por qué_

```
Da un ejemplo
```

### Y las pruebas de estilo de codificación ⌨️

_Explica que verifican estas pruebas y por qué_

```
Da un ejemplo
```

## Despliegue 📦

_Agrega notas adicionales sobre como hacer deploy_

## Autores ✒️

_Menciona a todos aquellos que ayudaron a levantar el proyecto desde sus inicios_
