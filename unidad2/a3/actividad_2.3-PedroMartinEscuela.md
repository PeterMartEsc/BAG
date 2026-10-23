# Actividad 2.3 - Políticas de contraseñas GNU/Linux

__Autor:__ Pedro Martín Escuela
__Asignatura:__ Bastionado de Redes y Sistemas

## Introducción:

A continuación se muestran las principales características que deben de formar parte de una política de contraseñas y en qué ficheros o módulos se configuran.

- Período mínimo y máximo de validez de la contraseña
- Complejidad y tamaño de la contraseña
- Algoritmo Hash utilizado para guardar las contraseñas
- Número de intentos erróneos permitidos y tiempo de bloqueo de usuario
- Historial de contraseñas recordadas que no se pueden repetir
- Evitar la posibilidad de acceso de usuarios sin contraseña

Para gestionar estas políticas podemos utilizar software como __Pam_Pwquality__.

### 1. Instala __Pwquality__ en tu sistema __Linux__.



### 2. Busca cuál es su fichero principal de __configuración__.


__Busca información sobre los diferentes parámetros de configuración:__

- minlen
- minclass
- difok
- maxrepeat
- maxclassrepeat
- dictpath
- badwords

### 3. Cambia las políticas de contraseña de tu sistema para que se ajusten a lo siguiente:

- Tamaño mínimo de la contraseña: 14

- La contraseña debe de contener mayúsculas, minúsculas, dígitos y caracteres especiales.

- Número máximo de contraseñas recordadas que no se pueden repetir será de 5

- Cambiar la contraseña cada 90 días como máximo y 1 día como mínimo. Se avisará de la caducidad con 7 días de antelación.

- La cuenta se bloqueará durante 15 min después de 5 intentos fallidos.

- Evitar la posibilidad de acceso de usuarios sin contraseña.

