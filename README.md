# backend-nodejs
aprendiendo node

NOVIEMBRE 18/2022

Requisitos:
SO: Linux
Uso de Terminal

Herramientas para el desarrollo:
*Plugin para dar mas características a la terminal
https://starship.rs/

Instalación
1. Fuente: Nerd Font
2.Configuracion de inicio de bash variables de entorno de manera persistente

*

Configurar nano como editor:
git config --global core.editor "nano"

# INTRODUCCION A NODEJS

Entorno de ejecución (runtime) de javascript fuera del navegador.

Características:
Concurrente
Motor V8
Modular
Orientado a Eventos

Sin DOM
Aplicaciones del lado del servidor
Acceso al sistema de archivos (file system)
Versiones
CommonJS

Instalación Nodejs:
https://nodejs.org/es/

Instalar por medio de una libreri: nvm (Node version manager)
para poder utilizar diferentes versiones
https://github.com/nvm-sh/nvm

Instalacion en terminal
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.2/install.sh | bash

Declarando las variables de entorno nevesrias para ejecutar el script (donde guardara las diferentes versiones)
export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm

Comprobar instalacion
nvm --version

Node.js
nvm

MIDDLEWARE

npm multer

EXPRESS
https://expressjs.com

CLEAN ARCHITECTURE
Entidades -> "Models" Recursos/objetos (usuario, orden producto)
Casos de Uso -> "Uses cases" Representa que podemos hacer con esa información (Actualizar, Crear, Eliminar, Autenticación[caso de uso específico]
EndPoints -> "Routes" Rutas de acceso a los recursos
Librerias/Conexiones a BD ->"Lib"(config.js,db.js,encrypt.js,jwt.js)

DICIEMBRE 8/2022
jwt

