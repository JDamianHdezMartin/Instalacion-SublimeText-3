# Instalacion-SublimeText-3
Guía y tutorial para la instalación de SublimeText 3
Por Jesús Damián Hernández Martín

1. [Introducción](#P1)
2. [¿Qués es SublimeText 3](#P2)
3. [Pasos a seguir](#P3)

<div id='P1' />

# Introducción 

Esta peqqueña guía nos indica cómo instalar Sublime Text Linux Ubuntu y también cómo usar Sublime Text.

<div id='P2' />

# ¿Qués es SublimeText 3?

Sublime Text es un potente editor de texto construido a partir de componentes personalizados, que proporciona una capacidad de respuesta inigualable. Desde un potente kit de herramientas de interfaz de usuario multiplataforma personalizado hasta un motor de resaltado de sintaxis sin igual, Sublime Text establece el estándar de rendimiento

<div id='P3' />

# Pasos a seguir

Seguir estos pasos uno a uno

## Paso nº1
Utilizamos el comando a continuación para actualizar el instalador de paquetes

```bash
sudo apt-get upgrade
```

## Paso nº2
Introduciendo el comando siguiente obtenemos la clave de instalación

```bash
wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
```

## Paso nº3
Usamos el comando siguiente

```bash
sudo apt-get install apt-transport-https
```

## Paso nº4
Continuamos con el comando a siguiente

```bash
echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
```

## Paso nº5
COntinuamos con

```bash
sudo apt update
```


## Paso nº6:
Instalamos sublime text

```bash
sudo apt install sublime-text
```

## Paso 7:
Pulsa el símbolo de ubuntu en la esquina superior izquierda en azul y busca _sublime_.
