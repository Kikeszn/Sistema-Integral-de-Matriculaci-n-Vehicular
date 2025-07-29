# Sistema-Integral-de-Matriculaci-n-Vehicular
# Sistema Integral de Matriculación Vehicular

[![Language: C](https://img.shields.io/badge/language-C-blue.svg)](https://github.com/Kikeszn/Sistema-Integral-de-Matriculacion-Vehicular)  
Simulación de un sistema para registrar, verificar y matricular vehículos en C. :contentReference[oaicite:0]{index=0}

---

## Contenidos

1. [Descripción](#descripción)  
2. [Requisitos](#requisitos)  
3. [Instalación](#instalación)  
4. [Uso](#uso)  
5. [Estructura del Proyecto](#estructura-del-proyecto)  
6. [Características Principales](#características-principales)  
7. [Configuración](#configuración)  
8. [Ejemplos de Ejecución](#ejemplos-de-ejecución)  
9. [Contribución](#contribución)  
10. [Historial de Versiones](#historial-de-versiones)  
11. [Licencia](#licencia)  
12. [Autor / Contacto](#autor--contacto)

---

## Descripción

Este proyecto es una **simulación** en C de un sistema de matriculación vehicular, que incluye:

- **Login** de usuarios almacenados en `usuarios.txt`.  
- **Registro** de propietarios y sus vehículos.  
- **Revisión vehicular** (emisión de gases, suspensión, frenos, luces).  
- **Cálculo** del valor de la matrícula según tarifas y recargos.  
- **Generación** de comprobantes en consola y en archivo de texto. :contentReference[oaicite:1]{index=1}

---

## Requisitos

- GCC (o cualquier compilador de C compatible).  
- Sistema operativo tipo UNIX (Linux, macOS) o Windows con entorno compatible.  
- Terminal (shell) para compilar y ejecutar.  

---

## Instalación

```bash
# 1. Clonar el repositorio
git clone https://github.com/Kikeszn/Sistema-Integral-de-Matriculacion-Vehicular.git

# 2. Entrar al directorio
cd Sistema-Integral-de-Matriculacion-Vehicular

# 3. Compilar todos los módulos
gcc main.c login.c matricula.c registrar_vehiculos_propietario.c revision_vehicular.c -o matriculacion

## Uso

# Ejecutar la aplicación
./matriculacion

- Al iniciar, se muestra un menú con las siguientes opciones:

- 1.Iniciar sesión

- 2.Registrar propietario y vehículo

- 3.Realizar revisión vehicular

- 4.Calcular y generar matrícula

- 5.Salir

Sigue las instrucciones en pantalla para navegar y completar cada operación.


