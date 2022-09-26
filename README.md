# LazaGRUB

Una GRUB hecha en [reFind](https://sourceforge.net/projects/refind/) basada en Lazaro©™



## Instalacion

#### Instalar reFind BootManager

```http
sudo apt-add-repository ppa:rodsmith/refind
sudo apt-get update
sudo apt-get install refind
```
#### Instalar Tema

Tema modificado de [refind-Minimal-Black](https://github.com/andersfischernielsen/rEFInd-minimal-black)

- Encontrar la carpeta EFI, suele estar en ```/boot```, abrir la carpeta con permisos de administrador
- Mover la carpeta  ```rEFInd-minimal-black``` a la ubicacion de la carpeta ```refind/themes``` dentro de la carpeta efihttps://github.com/andersfischernielsen/rEFInd-minimal-black
- Si la carpeta themes no esta , crea una 
- Añadir al final del archivo ```refind.conf```, la siguiente linea : ```include themes/rEFInd-minimal-black/theme.conf```
- Guarda el archivo y el tema estara instalado





