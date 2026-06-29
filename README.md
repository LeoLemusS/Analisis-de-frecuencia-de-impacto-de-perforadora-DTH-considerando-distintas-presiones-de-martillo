# Analisis-de-frecuencia-de-impacto-de-perforadora-DTH-considerando-distintas-presiones-de-martillo

## Objetivo General 
Analizar el comportamiento de la frecuencia de impacto en una perforadora DTH bajo diferentes condiciones de presión en el martillo, evaluando, mediante el procesamiento de señales, cómo estas variaciones influyen en el rendimiento del proceso de perforación.

## Sistema de perforación DTH
<img width="400" height="500" alt="dth" src="https://github.com/user-attachments/assets/1dbbf0a1-d55d-4f0b-8df0-24b5d4fe5d4d" /> 
<img width="600" height="500" alt="20250407_160555" src="https://github.com/user-attachments/assets/91b44e9c-8481-4b1b-ab8d-97f993ba0663" />

## Sistema Measurement While Drilling

En los sistemas MWD, se registran diversas variables para obtener datos relevantes sobre las condiciones y características de la masa rocosa que se perfora. La perforadora cuenta con un sensor de desplazamiento encargado de medir la profundidad, mientras que también se registra el voltaje y la corriente del motor de inducción trifásico mediante sondas para calcular el flujo, velocidad y torque. 

<img width="1145" height="517" alt="image" src="https://github.com/user-attachments/assets/4f998f21-9997-4f50-8634-fce05433a182" />

## Modelos de estimación

Para estimar el torque y velocidad, primero se debe estimar los enlaces de flujo, en este caso se utiliza el modelo hibrido. Este modelo se obtiene a partir de la combinación de los flujos de rotor en ejes estacionarios del modelo de voltaje y corriente. 
El método BEMF-MRAS es el más efectivo para estimar la velocidad en motores jaula de ardilla, como los de perforadoras DTH. Utiliza ecuaciones del estator y rotor como modelos de referencia, basándose en la fuerza contraelectromotriz

<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/2d1281f6-43c9-45ab-adc4-73720a99d099" />
<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/a6f31228-b566-4c9e-842b-3bcbccb96e30" />

## Evaluaciones experimentales de perforación
<img width="822" height="444" alt="image" src="https://github.com/user-attachments/assets/d9250279-b0c4-4121-94d6-07463697132b" />

## Variables operacionales
<img width="427" height="345" alt="image" src="https://github.com/user-attachments/assets/047dc0a6-c31e-41ed-a7cf-9386cc45b250" />
<img width="426" height="339" alt="image" src="https://github.com/user-attachments/assets/69e9f40f-381d-4a22-aff2-db5b0f0181a8" />

## STFT de la señal de velocidad
<img width="389" height="350" alt="image" src="https://github.com/user-attachments/assets/8c2ea605-4c20-4728-a623-8ad34de6c6bc" />

## Variación de la frecuencia de impacto en el tiempo
<img width="1848" height="767" alt="image" src="https://github.com/user-attachments/assets/6d1c65e8-ad2c-4c5a-bf2b-73ae69837ecb" />








