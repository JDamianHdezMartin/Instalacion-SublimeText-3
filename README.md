# Instalacion-SublimeText-3
Guía y tutorial para la instalación de SublimeText 3
Por Jesús Damián Hernández Martín

1. [Introducción](#P1)
2. [¿Qués es SublimeText 3](#P2)
3. [Pasos a seguir](#P3)

<div id='P1' />

# Introducción 

Esta pequeña guía nos indica cómo instalar Sublime Text Linux Ubuntu y también cómo usar Sublime Text.

<div id='P2' />

# ¿Qué es SublimeText 3?

Sublime Text es un potente editor de texto construido a partir de componentes personalizados, que proporciona una capacidad de respuesta inigualable. Desde un potente kit de herramientas de interfaz de usuario multiplataforma personalizado hasta un motor de resaltado de sintaxis sin igual, Sublime Text establece el estándar de rendimiento

<div id='P3' />

# Pasos a seguir

Seguir estos pasos uno a uno

## Paso nº1
Utilizamos el comando a continuación para actualizar el instalador de paquetes

```bash
sudo apt-get upgrade
```

![Captura de pantalla de 2021-09-25 14-41-18](https://user-images.githubusercontent.com/91153503/134773918-cb002860-e651-49fd-accd-d83454c73512.png)


## Paso nº2
Introduciendo el comando siguiente obtenemos la clave de instalación

```bash
wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
```

![Captura de pantalla de 2021-09-25 14-44-02](https://user-images.githubusercontent.com/91153503/134773939-1a905817-1b45-487e-ab5b-f67af393bf2f.png)


## Paso nº3
Usamos el comando siguiente

```bash
sudo apt-get install apt-transport-https
```

![Captura de pantalla de 2021-09-25 14-44-30](https://user-images.githubusercontent.com/91153503/134773946-e6c7a493-13b2-4d08-b589-3fc567aa81c9.png)


## Paso nº4
Continuamos con el comando a siguiente

```bash
echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
```

![Captura de pantalla de 2021-09-25 14-44-55](https://user-images.githubusercontent.com/91153503/134773957-8e707ca4-40ac-43e2-aae1-d26d946ed9b8.png)


## Paso nº5
Continuamos con

```bash
sudo apt update
```

![Captura de pantalla de 2021-09-25 14-45-33](https://user-images.githubusercontent.com/91153503/134773969-2fd8674e-7eeb-4404-a493-eb8fa97c1766.png)


## Paso nº6:
Instalamos SublimeText 3

```bash
sudo apt install sublime-text
```

![Captura de pantalla de 2021-09-25 14-45-55](https://user-images.githubusercontent.com/91153503/134773981-91d118dd-0b78-4399-93f0-497c6b5be8a3.png)


## Paso 7:
SublimeText ya estaría instalado

![Captura de pantalla de 2021-09-25 14-49-20](https://user-images.githubusercontent.com/91153503/134773989-d2c57bc6-ed12-45af-8870-9bbf1ee8c642.png)

