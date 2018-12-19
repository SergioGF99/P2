### Login 

**ID:** 008

**Breve descripción:** El sistema permite o no la entrada al mismo.

**Actores principales:** Profesor.

**Precondiciones:**

1. El sistema debe tener los datos del profesor que quiere acceder al sistema guardados en un fichero binario.


**Flujo principal:**
1. El caso de uso empieza cuando el profesor quiera acceder al sistema.

**Postcondiciones:**
* El sistema permite el acceso en caso de que el usuario y contraseña introducido coincidan con los que estan en el fichero binario, o en caso de no coincidir el usuario, contraseña o ambos, no accede al sistema.

**Flujos alternativos:**

1.a. Si los datos no coinciden con los que hay en el fichero binario, el sistema pide nuevamente que se introduzca el usuario y contraseña.
