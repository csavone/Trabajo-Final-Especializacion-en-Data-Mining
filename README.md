# Trabajo-Final-Especialización-Data-Mining UBA
Predicción de formación de hidratos en pozos de petróleo

Este es el trabajo final integrador aprobado para la Especialización en Exploración de Datos y Descubrimiento del Conocimiento de la Universidad de Buenos Aires.

El objetivo de este trabajo es predecir en tiempo real la formación de hidratos en las líneas de producción de pozos de petróleo, a partir de mediciones de presión y temperatura, mediante la aplicación de algoritmos de aprendizaje supervisado. La formación de hidratos es un evento no deseado en las operaciones de producción de hidrocarburo por sus consecuencias sobre las instalaciones, personas y medio ambiente.
Con datos reales de pozos offshore, la aplicación de técnicas de tratamiento de datos, ingeniería de atributos y utilizando K-Nearest Neighbors, Random Forest, y redes neuronales como algoritmos clasificadores, se diseñaron diferentes modelos predictivos multiclase para identificar la etapa previa, transitoria y estacionaria de formación de hidratos. 
El ajuste de los modelos se realizó priorizando la detección temprana del evento asociado a la etapa transitoria y penalizando las falsas alarmas. Bajo esta premisa la red neuronal combinada con la técnica de undersampling fue el modelo con mejor rendimiento, pudiendo distinguir con alto desempeño la etapa normal de la etapa transitoria del evento. Ninguno de los modelos logró predecir correctamente la etapa estacionaria de formación de hidratos. 
