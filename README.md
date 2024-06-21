# Descripción del proyecto

Los clientes de Beta Bank se están yendo, cada mes, poco a poco. Los banqueros descubrieron que es más barato salvar a los clientes existentes que atraer nuevos.

Necesitamos predecir si un cliente dejará el banco pronto. Tú tienes los datos sobre el comportamiento pasado de los clientes y la terminación de contratos con el banco.

Crea un modelo con el máximo valor F1 posible. Para aprobar la revisión, necesitas un valor F1 de al menos 0.59. Verifica F1 para el conjunto de prueba.

Además, debes medir la métrica AUC-ROC y compararla con el valor F1.

## Instrucciones del proyecto

1. **Descarga y prepara los datos.** Explica el procedimiento.
2. **Examina el equilibrio de clases.** Entrena el modelo sin tener en cuenta el desequilibrio. Describe brevemente tus hallazgos.
3. **Mejora la calidad del modelo.** Asegúrate de utilizar al menos dos enfoques para corregir el desequilibrio de clases. Utiliza conjuntos de entrenamiento y validación para encontrar el mejor modelo y el mejor conjunto de parámetros. Entrena diferentes modelos en los conjuntos de entrenamiento y validación. Encuentra el mejor. Describe brevemente tus hallazgos.
4. **Realiza la prueba final.**

## Descripción de los datos

Puedes encontrar los datos en el archivo `/datasets/Churn.csv`. Descarga el conjunto de datos.

### Características

- **RowNumber:** índice de cadena de datos
- **CustomerId:** identificador de cliente único
- **Surname:** apellido
- **CreditScore:** valor de crédito
- **Geography:** país de residencia
- **Gender:** sexo
- **Age:** edad
- **Tenure:** período durante el cual ha madurado el depósito a plazo fijo de un cliente (años)
- **Balance:** saldo de la cuenta
- **NumOfProducts:** número de productos bancarios utilizados por el cliente
- **HasCrCard:** el cliente tiene una tarjeta de crédito (1 - sí; 0 - no)
- **IsActiveMember:** actividad del cliente (1 - sí; 0 - no)
- **EstimatedSalary:** salario estimado

### Objetivo

- **Exited:** El cliente se ha ido (1 - sí; 0 - no)

## Evaluación del proyecto

Hemos definido los criterios de evaluación para el proyecto. Lee esto con atención antes de pasar al ejercicio.

Esto es lo que los revisores buscarán cuando evalúen tu proyecto:

1. ¿Cómo preparaste los datos para el entrenamiento? ¿Procesaste todos los tipos de características?
2. ¿Explicaste los pasos de preprocesamiento lo suficientemente bien?
3. ¿Cómo investigaste el equilibrio de clases?
4. ¿Estudiaste el modelo sin tener en cuenta el desequilibrio de clases?
5. ¿Qué descubriste sobre la investigación del ejercicio?
6. ¿Dividiste correctamente los datos en conjuntos?
7. ¿Cómo trabajaste con el desequilibrio de clases?
8. ¿Utilizaste al menos dos técnicas para corregir el desequilibrio?
9. ¿Realizaste correctamente el entrenamiento, la validación y las pruebas finales del modelo?
10. ¿Qué tan alto es tu valor F1?
11. ¿Examinaste los valores AUC-ROC?
12. ¿Mantuviste la estructura del proyecto y el código limpio?

Ya tienes las hojas informativas y los resúmenes de capítulos, tienes todo para continuar con el proyecto.

¡Buena suerte!
