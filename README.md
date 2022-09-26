# LazaGRUB

Una GRUB hecha en [rEFInd](https://sourceforge.net/projects/refind/) basada en Lazaro©™

![background](https://user-images.githubusercontent.com/114153352/192299904-d6031f94-f3f4-4c8f-9da9-60c7ad63ad89.png)

## Que es esto

GNU GRUB es un cargador de arranque múltiple, desarrollado por el proyecto GNU que nos permite elegir qué Sistema Operativo arrancar de los instalados,
rEFInd es asi tambien un gestor de arranque basado en GRUB pero con una interfaz grafica mucho mas customizable.

En resumen esto es un gestor de arranque grafico con una tema modificado con Lazaro©™, no se que mas quieres.

## Instalacion

#### Instalar rEFInd BootManager

```
sudo apt-add-repository ppa:rodsmith/refind
sudo apt-get update
sudo apt-get install refind
```
#### Instalar Tema

Tema modificado de [refind-Minimal-Black](https://github.com/andersfischernielsen/rEFInd-minimal-black)

- Encontrar la carpeta EFI, suele estar en ```/boot```, abrir la carpeta con permisos de administrador
- Mover la carpeta  ```rEFInd-minimal-black``` a la ubicacion de la carpeta ```refind/themes``` dentro de la carpeta EFI
- Si la carpeta themes no esta , crea una 
- Añadir al final del archivo ```refind.conf``` de la carpeta refind, la siguiente linea : ```include themes/rEFInd-minimal-black/theme.conf```
- Guarda el archivo y el tema estara instalado





## Eliminar Boots Inecesarios

Para eliminar boots que no queremos, simplemente elimina la linea de ```include themes/rEFInd-minimal-black/theme.conf```
en ```renfind.conf```y reinicia el PC, cuando salga el menu principal de reFind podras eliminar los que quieras seleccionando boots
y presionando Suprimir, hecho eso puedes volver a dejar el archivo de```refind.conf``` como estaba.
