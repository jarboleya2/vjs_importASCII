El importador JavaScript está diseñado para importar cualquier fichero ASCII que haya sido creado con las siguientes características:

- La primera fila debe contener los identificadores de los campos destino separados por el separador elegido como separador de campos (por ejemplo: tabulador, coma, slash, etc.)
- Los campos tipo fecha deben ser exportados al fichero en formato AAAA/MM/DD.

El fichero importAscii.js debe ser instalado en el directorio de scripts del proyecto donde queramos ejecutar las importaciones o en algunos de los proyectos que estén heredados por dicho proyecto.

...