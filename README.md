# proyecto_ajedrez
Proyecto para crear una página que de ajedrez.

Base de datos mongodb + Mongoose:

- Ya que una partida requiere dos ID_usuario, se divide en ID_negras, ID_blancas como FK al mismo ID_usuario, sería una relacion N:M cosa que
  MongoDB permite como dos 1:N en un mismo documento. Podemos diferenciar el ID del usuario según la autenticación JWT a traves de Node.js.
  Numero de jugadas se puede referenciar por ID de el usuario correspondiente y contando con el mismo backend por hacer.
