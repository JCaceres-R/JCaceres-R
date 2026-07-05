<div align="center">

# ¡Hola! Soy Johan Sebastián Cáceres Rodríguez 👋

### Ingeniero Electrónico | Data & AI Engineering | Industrial IoT

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/johan-sebastian-caceres-rodriguez-5b19a135b)
[![GitHub](https://img.shields.io/badge/GitHub-JCaceres--R-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JCaceres-R)
[![Email](https://img.shields.io/badge/Gmail-scaceresr70%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:scaceresr70@gmail.com)

</div>
---

##  Sobre mí

Me muevo con comodidad entre el mundo del **hardware/control** (PID, protocolos industriales, sistemas embebidos) y el del **software/datos** (Machine Learning, arquitecturas RAG, análisis predictivo). Formación complementaria en Data Science (Alura One) y Asistencia Administrativa (SENA).

-  Actualmente construyendo un **agente RAG multi-herramienta** para automatización industrial.
-  Profundizando en **redes ART (Adaptive Resonance Theory)** y detección de anomalías con autoencoders.
-  Interesado en la intersección entre **IoT industrial, Smart Grids y sistemas de IA aplicada**.
-  Fun fact: además del código, sueldo cables — he armado circuitos de adquisición de señales biomédicas (ECG, EMG, EEG) y controlado motores/servos desde una Raspberry Pi Pico 2W.

---

## 🛠️ Stack técnico

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![MicroPython](https://img.shields.io/badge/MicroPython-2B2728?style=flat-square&logo=micropython&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![OCI](https://img.shields.io/badge/Oracle_Cloud-F80000?style=flat-square&logo=oracle&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![GNS3](https://img.shields.io/badge/GNS3-2D2D2D?style=flat-square&logo=gns3&logoColor=white)

</div>

| Área | Herramientas y temas |
|---|---|
| **IA / Machine Learning** | Scikit-learn, Keras, 1D-CNN, MLP, SOM, Bayesian classifiers, QDA/LDA, SMOTE, PCA/t-SNE |
| **Agentic AI / RAG** | LangGraph, FAISS/ChromaDB, Groq API, arquitecturas multi-tool, routing determinístico vs. semántico |
| **Redes y Telecomunicaciones** | TCP/IP (Reno, Cubic, BBR), IPv6, DHCP, 5G NR, OFDM, MIMO, Okumura-Hata, GNS3, Wireshark |
| **Embebidos / IoT** | Raspberry Pi Pico 2W (MicroPython), PWM, servos, motores DC, protocolos industriales |
| **Cloud & Infra** | OCI (Oracle Cloud Infrastructure), pipelines de documentación técnica multi-formato |
| **Documentación técnica** | LaTeX (Overleaf), Markdown, HTML, CSV para bases de conocimiento y agentes RAG |

---

##  Proyectos destacados

### 🏭 [Industrial RAG Router](https://github.com/JCaceres-R/industrial-rag-router)
Agente multi-herramienta construido con **LangGraph** que enruta consultas entre recuperación semántica (RAG sobre manuales técnicos, ej. control PID) y análisis numérico determinístico sobre datos tabulares (Pandas). Pensado para entornos de automatización industrial, con despliegue en **OCI Ampere A1** y frontend en Streamlit.
> El proyecto insignia de mi trabajo en Auvix: conecta directamente la ingeniería de contenido técnico con la infraestructura de un agente de IA en producción.

### ⚙️ [Paderborn Bearing Fault Diagnosis](https://github.com/JCaceres-R/paderborn-bearing-fault-diagnosis)
Pipeline end-to-end para diagnóstico de fallas en rodamientos sobre el dataset de Paderborn: extracción de features, **Self-Organizing Maps (SOM)** y deep learning, validado con **Leave-One-Bearing-Out (LOBO)** para garantizar generalización real entre rodamientos y evitar fugas de información entre condiciones de operación.

### 📈 [TelecomX Churn Prediction](https://github.com/JCaceres-R/telecomx-churn-prediction)
Modelo predictivo de cancelación de clientes (churn): comparación entre Regresión Logística y Random Forest, con selección justificada por negocio del modelo con mejor **Recall (78.8%)** sobre la clase de interés, priorizando minimizar falsos negativos.

### 📊 [TelecomX Churn Analysis](https://github.com/JCaceres-R/telecomx-churn-analysis)
EDA completo previo al modelo de churn: ETL sobre JSON anidado, identificación de los factores de mayor riesgo (contrato mes-a-mes, pago por Electronic Check) que sustentan las decisiones de modelado posteriores.

### 🛒 [Alura Store Data Analysis](https://github.com/JCaceres-R/alura-store-data-analysis)
Análisis comparativo de desempeño entre 4 tiendas (ingresos, concentración de ventas, satisfacción de clientes, costos logísticos) con recomendación de negocio sustentada en datos.

### 🖥️ [SPARCV8 over 4](https://github.com/JCaceres-R/SPARCV8over4_U)
Implementación y análisis de la arquitectura **SPARCv8** sobre un diseño de hardware personalizado, en el marco de Arquitectura de Computadores.

---

## 📚 Otros trabajos relevantes

- **Sistema embebido web-controlado** (Raspberry Pi Pico 2W, MicroPython): control de servo SG90, motor DC (L293D) y salida PWM independiente.
- **Detección de anomalías en tráfico de red** con autoencoders sobre el dataset CICIDS2017 (propuesta de tesis).
- **Redes ART (Adaptive Resonance Theory)**: arquitectura, parámetro de vigilancia y comparación frente a CNNs en aprendizaje continuo.
- **Mantenimiento predictivo** con el dataset AI4I 2020 — trabajo colaborativo con estado del arte y metodología.
- **Laboratorios de telemática**: control de congestión TCP (Cubic/Reno/BBR) y simulación de cobertura 5G NR (HTZ Communications, XIRIO Online).

---

## 📫 Contacto

<div align="center">

Siempre abierto a conversar sobre **IA aplicada a industria, IoT, Smart Grids** o proyectos de datos.

</div>
