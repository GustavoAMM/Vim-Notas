# Vim - Nvim 

> 
> Sábado 29 de octubre de 2022
> 
> By Gustavo Angel Montoya Martínez
> 

## Instalación 

Link para descargar [VIM](https://www.vim.org/download.php)

Link para descargar [Nvim](https://neovim.io/)

## Salir de vim

Pasos:

- esc [Tecla]
- :q
- enter [Tecla]

Pasos para forzar la salida:

- esc [Tecla]
- :q!
- enter [Tecla]

## Movimiento del cursor

Teclas: 

- h => Moverse a la derecha  
- l => Moverse a la izquierda 
- j => Moverse hacia abajo
- k => Moverse hacia arriba

- w => Moverse al comienzo de la palabra siguiente 
- e => Moverse al final de la palabra siguiente  
- b => Moverse al comienzo de la palabra anterior 

## Insertar 

Tecla:

- i => Insertar texto 
- esc => [Tecla para volver al modo normal]

> Nos coloca el cursor antes del carácter usando **i**

- a => Insertar texto 
- esc => [Tecla para volver al modo normal]

> Nos coloca el cursor depues del carácter usando **a**

- A => Insertar texto
- esc => [Tecla para volver al modo normal]

> Nos coloca el cursor al final del renglon usando **A**
 
## Eliminar

Tecla:

- x => Eliminar un carácter

## Guardar

> Asegurar que estas en el modo normal

Tecla:

- esc => Salir a el modo normal
- :w => Guardar el documento

Ejemplo 2:

- esc => Salir a el modo normal
- :wq => Guardar el documento y salir 

## Eliminar, Undo y Redo

> Asegurar que estamos en el modo normal

Para eliminar las palabras es:

- d - w => (delete word)

Para deshacer cambios: 

- u => (undo)

Para rehacer cambios: 

- ctrl(sostenido) - r => (redo)

Para eliminar toda una linea desde la posición del cursor:

- d + $ -> (normalmente es shift + 4)


## Eliminar lineas y pegarla

- dd - p -> Eliminar linea y pegarla despues del cursor 

- dd - P -> Eliminar linea y pegarl antes del cursor 

## Operador de cambio

- r - new_char => remplazar un carácter 

- c - i - w => cambiar la palabra sin importar la posición del cursor en la palabra 


## Saltar lineas y buscar

- g - g -> Para ir al comienzo del archivo

- G -> Para ir al final del archivo 

- (number) - G -> Para ir a una numero de linea en especifico 

- / - filtro -> Buscar apartir de la posición del cursor - en nvim va a buscar en todo el texto a diferencia de VIM

> n -> Te sigues a la siguiente coincidencia en el resultado de la busqueda 
> N -> Te sigues a la anterior coincidencia en el resultado de la busqueda 



 


