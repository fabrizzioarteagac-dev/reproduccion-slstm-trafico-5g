# Reproducción SLSTM - Predicción de tráfico 5G

Trabajo del Laboratorio de Paper Individual (curso de Telecomunicaciones e IA, UNI-FIEE).

Reproduzco el modelo SLSTM del paper "5G Traffic Prediction Based on Deep Learning" 
(Gao, 2022), comparándolo contra LSTM, GRU y CNN. Como el dataset original del paper 
es privado, uso el SDN Traffic Engineering Dataset (Kaggle, CC BY 4.0), agregando 
los flujos individuales en una serie de tiempo de tráfico total en bits.

## Contenido
- `Reproduccion_SLSTM_5G_SDN_dataset.ipynb`: notebook completo con carga de datos, 
preprocesamiento (agregación temporal + diferenciación + normalización), 
entrenamiento de los 4 modelos y evaluación comparativa.

## Referencia
Gao, Z. (2022). 5G Traffic Prediction Based on Deep Learning. 
Computational Intelligence and Neuroscience, 2022, Art. 3174530.
