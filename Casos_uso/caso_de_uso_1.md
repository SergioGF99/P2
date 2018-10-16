## Mostar animal
**ID**: 001

**Breve descripción:** El sistema permite añadir a un alumno


**Actores principales:** Profesores

**Actores secundarios:** Alumnos

**Precondiciones:**
1. Si el DNI o el correo del nuevo alumnno introducido coinciden con uno ya existente, el sistema indicará un error.

**Flujo principal:**
1. El caso de uso empieza cuando el usuario quiere introducir un nuevo alumno.
2. El sistema guarda los datos del nuevo alumno.

**Postcondiciones:**
* El sistema mostrará un mensaje de éxito si todo ha ido correctamente.

**Flujos alternativos:**  

  2.a. Si los datos que se desean guardar coindicen con los de otro alumno, el sistema impedirá que se guarden esos datos y pedirá unos nuevos.


