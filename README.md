## Descripción

El importador JavaScript está diseñado para importar cualquier fichero ASCII que haya sido creado con las siguientes características:

- La primera fila debe contener los identificadores de los campos destino separados por el separador elegido como separador de campos (por ejemplo: tabulador, coma, slash, etc.)
- Los campos tipo fecha deben ser exportados al fichero en formato AAAA/MM/DD.

El fichero importAscii.js debe ser instalado en el directorio de scripts del proyecto donde queramos ejecutar las importaciones o en algunos de los proyectos que estén heredados por dicho proyecto.

### Otras consideraciones

- El nombre del fichero ASCII así como su extensión pueden ser los que desee el programador, la función JavaScript recibirá como uno de sus parámetros la senda completa del fichero a importar.
- Este proceso puede ejecutarse tanto en primer como en segundo plano, teniendo en cuenta que la senda del fichero debe estar accesible por el cliente o servidor en función del plano de ejecución.
- Otro de los parámetros a pasar a la función es el carácter de separación de campos.
- El nombre de la tabla a importar será otro de los parámetros a pasar a la función y debe incluir el formato completo idRef (alias/id_tabla).

