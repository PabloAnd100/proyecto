# ROGII - Wellbore Geology Prediction (Kaggle)

## Integrantes y cuentas de Kaggle
- **Pablo Andres Gonzalez Argüelles** — GitHub: `@PabloAnd100` — Kaggle: `pabloand02`

## Reglas de Kaggle y descarga de datos
Este proyecto respeta las reglas oficiales de la competencia ROGII: Wellbore Geology Prediction. Los archivos de datos no se redistribuyen en este repositorio; para descargarlos localmente mediante la API oficial de Kaggle:

python datos/descargar.py

## Estructura del repositorio
- `datos/descargar.py`: descarga y descomprime los datos de la competencia usando la API de Kaggle.
- `libretas/`: flujo de trabajo del proyecto (`01-exploracion.ipynb`, `02-validacion-y-linea-base.ipynb`, `03-modelos.ipynb`, `04-envio-final.ipynb`).
- `src/`: funciones reutilizables de ingeniería de atributos, validación y modelos.
- `experimentos.csv`: bitácora con un renglón por experimento y su métrica local/pública.
- `leaderboard/`: capturas de pantalla de los envíos y de la tabla de posiciones.

## Citas y referencias externas
- *(Agregar enlaces a libretas públicas, discusiones o artículos consultados y describir qué idea o fragmento se adaptó).*

## Declaración de uso de IA
- **Herramientas utilizadas:** Gemini.
- **En qué partes se usó:** generación de la estructura base del repositorio, configuración de `.gitignore` y plantillas iniciales de documentación/scripts.
- **Validación:** todo el código, los experimentos de modelado y los envíos fueron revisados, ejecutados y validados por el autor.

## Licencia
Este proyecto se distribuye bajo licencia MIT. Consulta el archivo `LICENSE`.
