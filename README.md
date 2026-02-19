# 🦎 Actividad #1: Explorando Distribuciones Linux - openSUSE Leap 15.6

![openSUSE Banner](https://en.opensuse.org/images/0/0b/Leap-desktop-wallpaper-15.6.png)

## 👤 Información del Proyecto
* **Institución:** Antonio José De Sucre
* **Curso:** Sistemas Operativos
* **Docente:** Ing. Jaider Reyes Herazo
* **Estudiante:** Andres Camilo Diaz Ortega
* **Año:** 2026

---

## 🚀 Introducción
Este repositorio contiene la documentación técnica y las evidencias de instalación de la distribución **openSUSE Leap 15.6**. El objetivo es explorar la estructura, gestión de paquetes y componentes clave de este sistema operativo basado en el kernel Linux.

## 📋 Ficha Técnica
| Característica | Detalle |
| :--- | :--- |
| **Distribución** | openSUSE Leap 15.6 |
| **Lanzamiento** | Junio 2024 |
| **Tipo de Soporte** | Fijo (Basado en SUSE Linux Enterprise) |
| **Escritorio por defecto** | KDE Plasma / GNOME |
| **Gestor de Paquetes** | Zypper |
| **Enfoque** | Profesional, Servidores y Estaciones de Trabajo |

---

## 🛠️ Pruebas de Terminal
A continuación, se detallan los comandos básicos ejecutados para la navegación y gestión del sistema:

### 1. Navegación y Archivos
* `pwd`: Muestra la ruta del directorio actual.
* `ls`: Lista el contenido de las carpetas.
* `cd`: Cambia el directorio de trabajo.
* `cat`: Visualiza el contenido de archivos de texto.

### 2. Gestión de Software (Zypper)
En openSUSE, la administración de paquetes se realiza con **Zypper**.
```bash
# Actualizar el sistema
sudo zypper update

# Instalar un paquete
sudo zypper install [nombre_paquete]
