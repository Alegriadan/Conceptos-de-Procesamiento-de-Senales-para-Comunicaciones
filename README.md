# Conceptos de Procesamiento de Señales para Comunicaciones
# Descripción
Práctica de laboratorio enfocada en el análisis y procesamiento de señales periódicas aplicadas a sistemas de comunicaciones, utilizando Series de Fourier, FFT y MATLAB para comparar resultados teóricos y experimentales.
# Objetivos
* Analizar señales periódicas en los dominios del tiempo y la frecuencia.
* Caracterizar señales senoidales, cuadradas, triangulares y trenes de pulsos.
* Calcular los armónicos mediante Series de Fourier.
* Reconstruir señales mediante síntesis armónica en MATLAB.
* Obtener y analizar espectros mediante FFT.
* Comparar resultados teóricos y experimentales.
* Identificar fuentes de discrepancia en las mediciones.
# Desarrollo
Durante la práctica se adquirieron señales con un osciloscopio digital y se analizaron sus características temporales y espectrales. Los datos experimentales fueron exportados y procesados mediante MATLAB para obtener los armónicos, reconstruir las señales y calcular sus espectros.
Las señales estudiadas fueron:
* Señal senoidal
* Señal cuadrada
* Señal triangular
* Pulso con ciclo útil del 50 %
* Pulso con ciclo útil del 20 %
* Pulso con ciclo útil del 30 %
* Pulso con ciclo útil del 80 %
La frecuencia fundamental utilizada fue de **4 kHz**, con una amplitud de **2 V** para el Grupo 8.
# Conceptos estudiados
* Dominio del tiempo
* Dominio de la frecuencia
* Series de Fourier
* Armónicos
* Síntesis y reconstrucción de señales
* Transformada Rápida de Fourier (FFT)
* Fenómeno de Gibbs
* Espectro de frecuencia
* Ciclo útil
# Herramientas utilizadas
* **MATLAB** — Procesamiento, reconstrucción y análisis de señales.
* **Osciloscopio Tektronix TDS2012B** — Adquisición y análisis experimental.
* **OpenChoice Desktop** — Exportación de datos del osciloscopio.

##  Resultados

Los resultados experimentales presentaron una buena correspondencia con los modelos teóricos obtenidos mediante Series de Fourier. En la mayoría de las señales analizadas, las diferencias entre los armónicos teóricos y experimentales fueron inferiores a **0.5 dB**.

También se observaron efectos propios de la adquisición y procesamiento, como el ruido del instrumento, la resolución de la FFT, el leakage espectral y diferencias en la referencia de amplitud.

## 📁 Estructura del repositorio

```text
.
├── README.md
├── MATLAB/
│   ├── lectura_datos.m
│   ├── series_fourier.m
│   └── FFT.m
├── Datos/
│   └── *.csv
├── Resultados/
│   └── graficas/
├── Informe/
│   └── Informe_2_comunicaciones_digitales.pdf
└── Anexos/
```

> La estructura anterior puede modificarse de acuerdo con la organización final de los archivos del repositorio.

## Autores

**Daniel Mateo Alegría Bernate**
**Miguel Ángel Plazas Llanes**

Programa de Ingeniería de Telecomunicaciones
Universidad Militar Nueva Granada

## Referencias

* Proakis, J. G. & Manolakis, D. *Digital Signal Processing: Principles, Algorithms, and Applications*, 5th ed.
* Orfanidis, S. J. *Introduction to Signal Processing*, 2nd ed.
* Lyons, R. G. *Understanding Digital Signal Processing*, 4th ed.
* MathWorks — MATLAB & Simulink Documentation.
* Tektronix — Application Notes sobre análisis FFT y dominio de la frecuencia.
