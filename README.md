# 📊 Sistema de Gestión de Nómina para Administradores con Interfaz Gráfica en Java

Una aplicación de escritorio desarrollada en Java con Swing para gestionar la nómina de empleados. Usa estructuras de datos como listas ligadas, pilas y colas, y almacena información en archivos de texto simulando una base de datos.

---

## 🎯 Objetivo General

Diseñar y desarrollar una aplicación robusta en Java que permita a un administrador gestionar empleados y su nómina, con almacenamiento persistente y estructuras dinámicas en memoria.

---

## 🎯 Objetivos Específicos

1. Implementar login y registro de administradores.
2. CRUD completo de empleados con interfaz gráfica.
3. Uso de **listas ligadas** para la gestión de empleados.
4. Uso de **pila** para historial de eliminaciones.
5. Uso de **cola** para solicitudes de actualización.
6. Almacenamiento de datos en archivos `.txt`.
7. Generar entregables: `.jar`, manual de usuario, video y documentación.

---

## 🧱 Estructura del Proyecto

- **Pantalla de Login/Registro:** Validación con expresiones regulares.
- **Panel Principal:** Registro, edición, eliminación, consultas, pila y cola.
- **Lista Ligada:** Gestión dinámica de empleados en memoria.
- **Pila:** Historial de eliminaciones.
- **Cola:** Solicitudes de edición pendientes.
- **Archivos `.txt`:** Almacenamiento de datos persistente.

---

## 📁 Estructura de Datos

| Estructura     | Uso                                                  |
|----------------|-------------------------------------------------------|
| Lista Ligada   | Representación dinámica de empleados                 |
| Pila           | Historial de empleados eliminados                    |
| Cola           | Seguimiento de actualizaciones recientes             |

---

## 📝 Base de Datos (Simulada en archivo `.txt`)

### Tabla `administradores`
- `id_admin` (INT)
- `usuario` (VARCHAR)
- `password` (HASHED)

### Tabla `empleados`
- `id_trabajador` (CHAR(6))
- `nombre`, `ap_paterno`, `ap_materno`
- `sexo`, `edad`, `direccion`, `telefono`
- `puesto`, `departamento`
- `horas_trabajadas`, `costo_hora`, `sueldo`

---

## ☕ Requisitos del Sistema

Para ejecutar esta aplicación correctamente, asegúrate de contar con:

- ✅ **Java JDK 22.0.1 o superior** instalado en tu sistema.
  - Puedes descargarlo desde el sitio oficial: [https://jdk.java.net/22/](https://jdk.java.net/22/)
- ✅ Sistema operativo compatible con Java (Windows, Linux, macOS).
- ✅ IDE recomendado (opcional): IntelliJ IDEA, Eclipse o NetBeans.

### ⚠️ Compatibilidad de Versiones

Este proyecto fue desarrollado usando **JDK 22.0.1**. Si intentas ejecutar el archivo `.jar` con una versión anterior (como Java 8 o 17), podrías obtener un error de compatibilidad como: Unsupported major.minor version


#### Opciones para solucionarlo:

1. 📥 **Actualiza tu Java a la versión 22.0.1 o superior.**
2. 🔧 El desarrollador puede volver a compilar el proyecto con una versión más antigua (por ejemplo, Java 8 o Java 11) usando el comando:
   ```bash
   javac --release 8 -d out src/*.java
   jar cfe MiApp.jar MainClass -C out .

👨‍💻 Autores
Nombre: [Cristhian Rios Hernández]

Correo: [rh202365605@alm.buap.mx]

Nombre: [Jennyfer Méndez Salas]

Correo: [ms202347729@alm.buap.mx]

Nombre: [Nani Herrera Luis Antonio]

Correo: [nh202340561@alm.buap.mx]

Nombre: [Díaz Cadena Guadalupe]

Correo: [dc202325812@alm.buap.mx]

Nombre: [Hernández Rosiles Cecilia Sarai]

Correo: [hr202336814@alm.buap.mx]

Nombre: [Valerio Palacios Dulce Liliana]

Correo: [vp202368039@alm.buap.mx]

Universidad / Curso: POO II – [Benemérita Universidad Autónoma de Puebla]
