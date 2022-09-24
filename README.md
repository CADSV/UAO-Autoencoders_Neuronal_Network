# UAO-Autoencoders_Neuronal_Network
Conjunto de Redes neuronales basadas en una arquitectura Variational Autoencoders (VAE), entrenadas con métodos no supervisados. 

****

## Descripción de un Autoencoder
Las redes VAE se subdividen en dos sub redes, una que comprime la información y las características de unas imágenes recibidas (encoder), que luego sirven de parámetros de entrada en una red subsiguiente generativa o decodificadora (decoder), que a partir de la data comprimida por el encoder, será capaz de construir la imagen igual al estado inicial antes de ser ingresada en la primera red, o con las modificaciones que deseemos. Adicionalmente, entre estas dos redes se encuentra otra arquitectura conocida como espacio latente, el cual representa el espacio mínimo de representación de la información en todo el autoencoder.

## ¿Qué contiene este repositorio?
Este repositorio contiene 3 archivos que son:

1. **Clasificacion_Autoencoders_MNIST_Carlos_Doffiny_SV.ipynb** el cual es el código hecho en Colab que contiene todo lo relacionado con una red de autoencoders apilados para la clasificación de imágenes del dataset MNIST. 
2. **Clasificacion_Autoencoders_Fashion_MNIST_Carlos_Doffiny_SV.ipynb** el cual es el código hecho en Colab que contiene todo lo relacionado con una red de autoencoders apilados para la clasificación de imágenes del dataset Fashion MNIST. 
3. **Variational_autoencoder_Fashion_MNIST_Carlos_Doffiny_SV.ipynb** el cual es el código hecho en Colab que contiene todo lo relacionado con una red de autoencoder para visualizar en dos dimensiones el comportamiento del dataset Fashion MNIST, y verificando la capacidad de generar nuevas imágenes con el autoencoder entrenado.
4. **Trabajando con Autoencoders - Carlos Doffiny S-V.pdf** el cual es el reporte que contiene la explicación detallada de cada uno de las redes neuronales que aquí se encuentran.

## ¿Qué problema resuelve esta red neuronal?
Esta red neuronal fue hecha como actividad para el curso de Redes Neuronales y Deep Learning en la Universidad Autónoma de Occidente, de Cali, Colombia. Y es capaz de resolver los diferentes problemas explicados en el punto anterior, con el uso de arquitecturas VAE.


## ¿Cómo ejecutar la red neuronal?
Para ejecutar cualquiera de las redes neuronales, se deben seguir los siguientes pasos:
1. Clonar el presente repositorio para poder descargar los archivos.
2. Ingresar al sitio web de [Google Colab](https://colab.research.google.com/).
3. En él aparecerá la siguiente ventana, y nos iremos a la última opción denominada **Subir**, en donde seleccionaremos el archivo que queramos. <p align="center"><img src="https://i.imgur.com/LJ5tLin.png"/></p> 
4. Una vez que se haya cargado el código, deberemos hacer click arriba a la derecha en donde dice **Conectar**, para que así poder utilizar los recursos gratuitos en la nube que ofrece Google Colab. <p align="center"><img src="https://i.imgur.com/zOuZjuf.png"/></p>
5. Para ejecutar la red, es obligatorio el uso de una GPU, y Google Colab nos ofrece una en `Entorno de Ejecución > Cambiar tipo de entorno de ejecución`, en donde se abrirá una ventanita emergente denominada Configuración del cuaderno, y en la primera opción de `Acelerado por hardware` vamos a seleccionar el GPU.<p align="center"><img src="https://i.imgur.com/BhGsSgC.png"/></p> 
6. Por último, solo quedaría ejecutar el código, presionando las teclas `Ctrl + F9` o en el menú superior seleccionar la opción de `Entorno de Ejecución > Ejecutar todas`

## Consideraciones especiales

1. Si quieren cambiar, modificar o agregar cualquier parámetro o función nueva a la red, pueden hacerlo sin problemas, pero para ejecutar los cambios deberán seleccionar en el menú superior la opcion de `Entorno de Ejecución > Reiniciar y Ejecutar todo`
2. Antes de ejecutar la primera vez el código, ya estarán precargados los resultados de la última ejecución realizada antes de subir el código a este repo.


## Contribuciones
Formar una comunidad activa en donde todos podamos aprender y crecer juntos en nuestras jornadas de programación es muy gratificante, por lo cual cualquier contribución es muy apreciada. 
Si tienes alguna sugerencia para mejorar esto, por favor bifurca este repositorio y crea un pull request, o crea un issue con el tag `enhacement`

## Problemas y ayudas
En caso de presentar algún tipo de problema con el código, el data set o necesitar alguna ayuda para resolver una duda, por favor revisen los issues para ver si alguien anteriormente tuvo la misma duda, y sino, pueden crear uno nuevo sin problema.

## Licencia
Este proyecto utiliza una licencia del MI, cuyos detalles puedes encontrar en el archivo `LICENSE.md`. Siéntete libre de usar este proyecto como base para tus próximos proyectos.

## Links de interés
A continuación anexo algunos links de interés que me sirvieron de gran ayuda durante la elaboración del proyecto:
* [Introducción a los codificadores automáticos](https://www.tensorflow.org/tutorials/generative/autoencoder)


****
Programemos para hacer del mundo un mejor lugar :)



