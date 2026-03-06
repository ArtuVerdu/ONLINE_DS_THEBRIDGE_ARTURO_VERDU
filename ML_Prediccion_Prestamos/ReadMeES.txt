Descripcion del problema:

Nuestro cliente es un banco que quiere hacer un modelo de IA para predecir si el perfil de un cliente es apto para un prestamo, basandose en su situacion social, familiar, financiera y la ubicacion del hogar donde quiere comprar.

Dataset utilizado:

Dataset de origen publico, Licensia CC0 (Dominio publico), sin derechos de autor de ningun tipo.

Home Loan Approval - Rushikesh Konapure
https://www.kaggle.com/datasets/rishikeshkonapure/home-loan-approval/data

Solucion adoptada:

Se usaron modelos de Regresion Logistica, KNN, SVM y Random Forest, pero se presentaron mejores resultados de los modelos de SVM y Regresion Logistica.

Estructura del repositorio:

Tecnologicas utilizadas:

Blibliotecas utilizadas:
Pandas
Matplotlib
Seaborn
NumPy
SKLearn (preprocessing, model_selection, linear_model, neighbors, metrics, svm, ensemble)

Instrucciones de reproduccion:

El codigo es ejecutable en el orden en el que esta presente, es recomendado usar "Ejecutar todas las celdas" al verlo.

Principales resultados:

Se ha conseguido un modelo con 85% de accuracy y un F1-Score de 89% para el recall.

Se ha buscado la mayor precision possible para el recall para que el cliente (el banco) pueda evitar la mayor cantidad de Falsos Negativos o Malos Perfiles que son aprobados al costo de Falsos Positivos o Buenos Perfiles que son rechazados.

Autores:

Arturo Verdu
- GitHub: https://github.com/ArtuVerdu

