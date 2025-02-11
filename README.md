# Trabajo Final - Curso de MLOps | UNI

Este repositorio contiene el trabajo final del curso de MLOps en la Universidad Nacional de Ingeniería (UNI). Se incluyen las soluciones de los laboratorios realizados en clase, así como el desarrollo de un modelo propio implementado en diferentes etapas.

---

## Estructura del repositorio

```bash
UNI-MLOPS
 images                     # Evidencias de los laboratorios y trabajo final
 lab_01 - lab_04            # Directorios con los notebooks de cada laboratorio
 trabajo_final_modelo       # Desarrollo del modelo propio
 trabajo_final_tercer_estadio # Implementaci�n final del modelo
 lab_04_solucion.ipynb         # Soluci�n del laboratorio 4 realizado en clase
 trabajo_final_modelo.ipynb    # Desarrollo del modelo propio
 trabajo_final_tercer_estadio.ipynb  # Modelo final con la estructura level_0.ipynb
 .gitignore
 README.md
```

---

## Contenido

### Laboratorios (lab_01 - lab_04)

Incluyen los ejercicios prácticos realizados durante el curso, con soluciones implementadas en los notebooks.

### Trabajo Final

El trabajo final se centra en la construcción y despliegue de un modelo de machine learning aplicando prácticas de MLOps. Se divide en:

- `trabajo_final_modelo.ipynb`: Desarrollo del modelo propio a partir de los laboratorios.
- `trabajo_final_tercer_estadio.ipynb`: Implementación final con la estructura basada en `level_0.ipynb`.
- `images/`: Capturas de pantalla con las evidencias del proceso.

---

## Requisitos y configuración

Para ejecutar los notebooks, es necesario contar con las siguientes dependencias:

- Python 3.8+
- Jupyter Notebook
- TensorFlow / PyTorch (según el modelo utilizado)
- Pandas, NumPy, Scikit-Learn
- MLflow (para tracking)
- Docker (para despliegue)
- Google Cloud SDK / AWS CLI (si se usa cloud)

Puedes instalar las dependencias con:

```bash
pip install -r requirements.txt
```

---

## Ejecución

1. Clona el repositorio:

   ```bash
   git clone https://github.com/NahumFGz/UNI-MLOPS.git
   cd UNI-MLOPS
   ```

2. Activa un entorno virtual y ejecuta los notebooks:

   ```bash
   python -m venv venv
   source venv/bin/activate  # En Mac/Linux
   venv\Scripts\activate  # En Windows
   jupyter notebook
   ```

3. Abre y ejecuta los notebooks según el orden recomendado.

---

## Herramientas utilizadas

- Jupyter Notebook Desarrollo y pruebas del modelo
- MLflow Tracking de experimentos
- Docker Contenedorización del modelo
- Google Cloud Almacenamiento y despliegue

---

## Contacto

Si tienes preguntas o sugerencias, puedes escribirme a:  
ngutierrez2507@gmail.com

También puedes visitar mi perfil en GitHub:  
[NahumFGz](https://github.com/NahumFGz)
