# Guia de Trabajo: Laboratorio 01 - Fundamentos de Git

Documentacion completa sobre la instalacion, configuracion global y primeros pasos en el control de versiones con Git.

## Descripcion del Proyecto

Este documento sirve como guia paso a paso para configurar el entorno local de desarrollo y vincular la identidad del estudiante con repositorios de GitHub.

### Prerrequisitos de Software

Antes de comenzar la configuracion, asegurate de contar con:
- Sistema operativo Windows 11.
- Terminal PowerShell o Git Bash.
- Cuenta registrada en la plataforma de GitHub.

## Pasos de Instalacion y Uso

1. Descargar e instalar la version mas reciente de Git para Windows.
2. Abrir la terminal de comandos y validar la instalacion correcta.
3. Definir las credenciales globales de usuario con tu nombre y correo.

### Flujo de preparacion inicial

- Verificar la instalacion con `git --version`
- Configurar el nombre de usuario global
- Registrar el correo electronico de GitHub

## Estado del Proyecto

- [x] Instalacion del cliente Git en la computadora
- [x] Configuracion de credenciales globales
- [ ] Creacion de llaves SSH para conexion segura

## Archivos y Comandos Principales

| Archivo / Comando | Tipo | Descripcion |
| --- | --- | --- |
| `git config` | Comando | Establece valores de configuracion global |
| `git init` | Comando | Inicializa un repositorio vacio local |
| `.gitignore` | Archivo | Lista de archivos ignorados por Git |

## Ejemplo de Codigo

Para establecer tu nombre y correo electronico global en Git, ejecuta las siguientes lineas en tu terminal:

```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tu-correo@tecsup.edu.pe"
git config --global --list