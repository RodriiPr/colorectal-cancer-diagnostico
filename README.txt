# Deep Learning para la detección de cáncer colorrectal y análisis de imágenes histopatológicas

![Banner de Cáncer Colorrectal](https://via.placeholder.com/1200x400/2D3748/FFFFFF?text=Deep+Learning+para+detección+de+cáncer+colorrectal)

Proyecto de investigación que implementa modelos de Deep Learning para el análisis automatizado de imágenes histopatológicas de cáncer colorrectal, permitiendo la clasificación precisa de tejidos cancerosos mediante redes neuronales convolucionales.

## Tabla de Contenidos
- [Autores](#autores)
- [Características Técnicas](#características-técnicas)
- [Requisitos](#requisitos)
- [Instalación](#instalación)
- [Uso](#uso)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Dataset](#dataset)
- [Resultados](#resultados)
- [Referencias](#referencias)
- [Licencia](#licencia)

## Autores
- **Albarrán Jara Carlos Fernando** - Investigador Principal
- **Montenegro Baca Zee Ricardo** - Especialista en Modelos DL
- **Rodriguez Preciado André Jhonel** - Ingeniero de Datos

**Director**: Dr. Juan Pedro Santos Fernández  
**Departamento**: Ingeniería de Sistemas  
**Universidad**: Universidad Nacional de Trujillo (UNT)  
**Convocatoria**: Julio 2025

## Características Técnicas
### Hardware
- **GPU**: Nvidia GeForce RTX 2060 6GB GDDR6
- **CPU**: Intel Core i7-9750H (12MB Cache, up to 4.5GHz)
- **RAM**: 16GB DDR4 2666MHz
- **Almacenamiento**: SSD NVMe 1TB

### Software
- **Sistema Operativo**: Windows 10 Pro 64-bit (Build 19045)
- **Python**: 3.8.10
- **Entorno**: Docker 24.0.5
- **CUDA**: 11.7
- **cuDNN**: 8.5.0

## Requisitos
Principales dependencias:
```bash
torch==2.0.1
torchvision==0.15.2
opencv-python==4.7.0.72
numpy==1.24.3
matplotlib==3.7.1
scikit-learn==1.2.2
pandas==2.0.2


Dataset
Nombre: NCT-CRC-HE-100K

Origen: National Center for Tumor Diseases (NCT), Alemania

Características:

100,000 imágenes de tejido colorrectal

Resolución: 224×224 píxeles (0.5 µm/px)

9 clases histológicas:

Tumor (TUM)

Estroma (STR)

Tejido linfático (LYM)

Tejido sano (NORM)

Músculo (MUS)

Tejido adiposo (ADIP)

Tejido necrótico (NEC)

Debris (DEB)

Mucosa (MUC)

Resultados
Métrica	Valor (%)
Accuracy	98.7
Precision	97.2
Recall	96.8
F1-Score	97.0
AUC-ROC	99.1


MIT License © 2025 - Albarrán Jara, Montenegro Baca, Rodriguez Preciado
