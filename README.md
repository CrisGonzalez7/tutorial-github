# Tutorial de GitHub

Este es un tutorial para personas que están recién iniciándose en GitHub. Este tutorial es para ti si:
- Nunca has usado Git
- No tienes cuenta de GitHub
- Estás recién iniciando en GitHub
- Quieres sacarle el mayor provecho a GitHub

## Índice

- [Instalar Git](#instalar-git)
  - [Linux - Ubuntu](#linux-ubuntu)
- [Iniciando en GitHub](#iniciando-en-github)


## Instalar Git

### Linux - Ubuntu

Si utilizas una distribución de Linux basada en Ubuntu sigue los siguientes pasos:

- Abre una terminal con `Ctrl` + `Alt` + `T`
- Para saber si tienes instalado Git ejecuta: 

```bash
git --version
```

Si te sale un mensaje que dice `Command 'git' not found` significa que no tienes instalado Git en tu computador. 

Si al contrario, te dice `git version [VERSION]`, significa que ya tienes instalado Git y debes saltar al paso [Iniciando en GitHub](#iniciando-en-github)

- Para instalar Git en tu PC ejecuta: 

```bash
sudo apt install git
```
- Ingresa tu contraseña, y cuanddo te pregunte `¿Desea continuar?` ingresa `S` y presiona `Enter`

Una vez terminada la instalación debes configurar Git. Lo primero es crear un nombre de usuario (puede ser tu nombre y apellido)

```bash
git config --global user.name "[NOMBRE]"
```

Luego debes introducir tu correo: 

```bash
git config --global user.email [CORREO]
```

## Iniciando en GitHub

