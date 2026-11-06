# Inventario y diccionario de datos

La fuente propuesta es PokéAPI (https://pokeapi.co/). No se ha descargado un corte de datos en esta etapa.

| Campo | Definición | Tipo | Fuente | Nota |
| --- | --- | --- | --- | --- |
| pokemon_name | Nombre canónico de la especie en la fuente | texto | PokéAPI | Mantener el identificador de la fuente para trazabilidad |
| pokemon_type | Tipo asociado a la especie | texto | PokéAPI | Una especie puede tener más de un tipo |
| generation | Generación asociada a la especie | texto/identificador | PokéAPI | Confirmar reglas de asignación al preparar el corte |

Al incorporar datos, añadir la fecha de consulta, endpoint, licencia, reglas para formas regionales, tratamiento de duplicados y pruebas de calidad de los campos.
