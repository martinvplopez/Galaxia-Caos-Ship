# Galaxia-Caos-Ship
## Realizado por Martín van Puffelen López
### Práctica 4 CIU: *Modelo cámara*
___

#### Introducción
##### Simulación de una galaxia incoherente, casi inhabitable, donde el Sol (Cream) es el satélite más pequeño y la Luna (Planetoon), el planeta más grande.
##### Integración de objetos 3D (PShape) que sufren transfrormaciones (rotación, traslación, escalado) para producir una animación, en este caso, con una opción de entrar en una nave dirigida por el usuario que se desplazará por el sistema.

#### Instrucciones
##### Ejecutar programa y apreciar animación donde existen satélites y planetas que orbitan y rotan. En vista general será posible modificar el modo de visibilidad: ver sólo planetas, sólo satélites o todos los cuerpos (por defecto).
##### Entrar en modo "nave" *[ESPACIO]* para navegar y apreciar otras perspectivas del entorno.

![GIF Principal](https://github.com/martinvplopez/Galaxia-Caos-Ship/blob/main/images/presentationGIF.gif)

#### Detalles implementación
#### Más allá de las herramientas de visibilidad de la práctica anterior (ver sólo satélites o planetas) se ha incluido una nave como cámara libre dirigida por el usuario.
- ##### **Información**: *Botones Mostrar/Ocultar*, dispone de un buen tamaño, al clicar cambia su estado y a su vez el texto de los cuerpos celestes visibles cambia para aportar un feedback e información extra al usuario. El resto de información serán de tipo texto que se ha intentado añadir de la forma más simple y minimalista.
- ##### **Color**: Blanco para resaltar de la mejor forma posible.
- ##### **Texturas**: Se han seleccionado texturas de elementos naturales y primitivos, por ejemplo, arena, agua o roca, para resaltar la idea de sistema hostil y no habitado.
- ##### **Controles**: *ESPACIO* para activar/desactivar modo nave, y, en el modo nave, las teclas [*W*],[*A*],[*S*],[*D*], [*ARROW-UP*] Y [*ARROW-DOWN*] para el movimiento de la posición de la misma: avanzar, izquierda, retroceder, derecha, subir, bajar. Se han elegido estos controles porque son muy intuitivos. [*R*], tecla de reseteo de la nave, control al usuario y tolerancia a errores.

#### Posibles modificaciones
##### El poder seleccionar un sólo objeto y ver sus características ( oxígeno, Co2, etcétera).
##### Ver la nave desde la vista general.

#### Referencias
- [Documentación asignatura](https://github.com/otsedom/otsedom.github.io/blob/main/CIU/P4/README.md)
- [Imágenes de Google](https://www.google.com/imghp?hl=EN)
- [Documentación Processing](https://processing.org/reference)
