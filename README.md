# Pokémon data capstone
Repositorio inicial para una exploración reproducible de datos públicos de Pokémon.
## Pregunta del proyecto
¿Cómo cambia la distribución de tipos de Pokémon entre generaciones en la Pokédex pública, y qué tipos aparecen con mayor frecuencia?
## Audiencia
Estudiantes y lectores que quieran entender, con un análisis descriptivo sencillo, cómo se organiza la información de la Pokédex.
## Fuente de datos
Usaremos registros públicos de la Pokédex disponibles en [PokéAPI](https://pokeapi.co/), una API mantenida por la comunidad. Documentaremos la fecha de consulta, los campos utilizados, la licencia y las transformaciones antes de guardar datos. No usaremos datos privados ni telemetría de jugadores de Pokémon GO.
## Resultado esperado
Un notebook reproducible con tablas y gráficas descriptivas por generación y tipo, más un breve reporte que explique los hallazgos y sus límites.
## Limitación actual
Los registros de la Pokédex describen especies y tipos; no miden apariciones, capturas, popularidad ni comportamiento de jugadores dentro de Pokémon GO. Por eso, el análisis no permitirá sacar conclusiones sobre uso del juego. Las formas regionales y cambios entre versiones también pueden afectar los conteos.
## Cómo empezar
Se requiere Python 3.12 o posterior. Desde la carpeta raíz del repositorio, crea un entorno e instala las dependencias:
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
python src/hello_ds.py
```
El notebook de análisis se agregará en `notebooks/` cuando se defina el primer corte de datos.
## Estructura
```text
.github/workflows/  Validaciones automáticas
assignments/        Evidencias y entregas del proyecto
data/raw/           Datos originales, sin modificar
data/processed/     Datos derivados y documentados
notebooks/          Análisis exploratorio reproducible
reports/            Hallazgos y visualizaciones
src/                Código Python reutilizable
```
No subas contraseñas, tokens, datos personales ni archivos de datos con licencias incompatibles.
