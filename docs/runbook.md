# Runbook inicial

## Preparación local

Con Anaconda:

~~~bash
conda env create -f environment.yml
conda activate pokemon-capstone
jupyter lab
~~~

Con Python 3.12 y pip:

~~~bash
python -m pip install -r requirements.txt
python src/hello_ds.py
~~~

## Actualización de datos

Antes de descargar el corte de PokéAPI, registra endpoints, fecha de consulta, licencia y campos en data/README.md. Guarda la respuesta original en data/raw/ y conserva las transformaciones en código.

## Límites conocidos

La Pokédex no representa apariciones, capturas ni telemetría de jugadores de Pokémon GO. No uses sus conteos como métricas de uso del juego.
