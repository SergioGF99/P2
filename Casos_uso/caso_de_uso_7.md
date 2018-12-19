### Guardar 

**ID:** 007

**Breve descripción:** El sistema guardará datos.

**Actores principales:** Usuario/Profesor.

**Actores secundarios:** Alumnos.

**Precondiciones:**

1. El sistema debe tener datos que guardar.


**Flujo principal:**
1. El caso de uso empieza cuando el usuario vaya a guardar datos.

**Postcondiciones:**
* El sistema almacena los datos guardados en un fichero binario.

**Flujos alternativos:**

1.a. Si no hay datos que guardar en el sistema, el mismo creará un fichero vacio con el nombre que indique el usuario.
1.b. Si el nombre que se ha introducido para el fichero coincide con uno ya existente, se sobrescribirán los datos.

