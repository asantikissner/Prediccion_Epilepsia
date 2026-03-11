# Prediccion_Epilepsia

El presente trabajo corresponde al examen final de la materia Procesamiento de Señales e Imágenes Biomédicas. Se expone un algoritmo basado en el artículo científico A Patient-Specific Approach for Short-Term Epileptic Seizures Prediction Through the Analysis of EEG Synchronization.

A lo largo del informe se desarrollan funciones para el preprocesamiento de señales de EEG provenientes de la base de datos Siena Scalp Database. El objetivo final es, a partir de índices de sincronización de fase entre canales y de características estadísticas de las señales, predecir correctamente el período de 300 segundos previo a las distintas crisis epilépticas de 5 pacientes. La predicción se realiza aplicando algoritmos de aprendizaje supervisado, en particular, clasificadores Random Forest y Support Vector Machine entrenados con un subconjunto de datos de cada paciente y testeados con los datos restantes.
