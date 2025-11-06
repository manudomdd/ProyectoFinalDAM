<div align="center">

# 🏋️ GymTrack

### *Tu compañero definitivo para la gestión de gimnasios*

![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white)

[📱 Características](#-características-principales) • [🎯 Objetivos](#-objetivos-del-proyecto) • [🛠️ Tecnologías](#️-tecnologías-utilizadas) • [👥 Roles](#-sistema-de-roles)

---

</div>

## 💡 Sobre el Proyecto

**GymTrack** es una aplicación móvil Android diseñada para revolucionar la gestión de gimnasios pequeños y entrenadores personales. Desarrollada en Java con Android Studio, ofrece una solución completa y local para el seguimiento personalizado de clientes, rutinas y progreso físico.

### 🎯 El Problema

La mayoría de gimnasios pequeños dependen de métodos obsoletos:
- 📄 Hojas de papel dispersas
- 📊 Excel desorganizado
- ❌ Falta de seguimiento adecuado
- 🚫 Información propensa a pérdidas

### ✨ La Solución

GymTrack centraliza toda la información en una base de datos SQL local, proporcionando:
- ✅ Gestión eficiente de clientes
- ✅ Seguimiento detallado del progreso
- ✅ Interfaz intuitiva y profesional
- ✅ Almacenamiento seguro y persistente

---

## 🚀 Características Principales

<table align="center">
<tr>
<td width="50%">

### 👥 Gestión de Usuarios
- Sistema de roles diferenciados
- Perfiles completos de clientes
- Autenticación segura
- Datos personalizados (edad, peso, altura, objetivos)

</td>
<td width="50%">

### 🏋️‍♂️ Rutinas de Entrenamiento
- Creación de rutinas genéricas y personalizadas
- Registro de ejercicios, series y repeticiones
- Control de peso y RIR
- Historial completo de entrenamientos

</td>
</tr>
<tr>
<td width="50%">

### 🥗 Planes Nutricionales
- Registro de dietas personalizadas
- Seguimiento de comidas
- Historial nutricional
- Adaptación a objetivos individuales

</td>
<td width="50%">

### 📊 Análisis y Progreso
- Estadísticas detalladas por cliente
- Resúmenes de evolución
- Gráficos de progreso
- Informes personalizados

</td>
</tr>
</table>

---

## 🎯 Objetivos del Proyecto

### Objetivo General

Desarrollar una aplicación Android completa que permita a gimnasios y entrenadores gestionar clientes de manera eficiente, registrando y siguiendo sus entrenamientos y dietas con almacenamiento seguro mediante SQL.

### Objetivos Específicos

| Objetivo | Descripción |
|----------|-------------|
| 🧩 **Interfaz Intuitiva** | Diseñar una UI clara y fácil de usar para todos los roles |
| 🗄️ **Base de Datos Robusta** | Crear estructura SQL optimizada para los datos necesarios |
| 🔁 **Operaciones CRUD** | Implementar todas las operaciones de gestión de datos |
| 🏋️ **Asignación Inteligente** | Permitir asignar rutinas y dietas personalizadas |
| 📊 **Seguimiento Detallado** | Generar resúmenes de evolución por cliente |
| ✅ **Validación de Datos** | Asegurar la integridad de toda la información |
| 📝 **Documentación Completa** | Documentar el desarrollo y funcionalidades |

---

## 🛠️ Tecnologías Utilizadas

<div align="center">

| Tecnología | Propósito | Justificación |
|:----------:|-----------|---------------|
| ![Android Studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=flat&logo=android-studio&logoColor=white) | **Entorno de Desarrollo** | Herramienta oficial y completa para aplicaciones Android |
| ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white) | **Lenguaje Principal** | POO sólida y ampliamente usado en Android |
| ![SQLite](https://img.shields.io/badge/SQLite-07405E?style=flat&logo=sqlite&logoColor=white) | **Base de Datos** | Gestión eficiente y local de datos persistentes |
| ![XML](https://img.shields.io/badge/XML-FF6600?style=flat&logo=xml&logoColor=white) | **Diseño de UI** | Interfaces claras, estructuradas y adaptables |

</div>

---

## 👥 Sistema de Roles

GymTrack implementa un sistema de roles robusto que diferencia las funcionalidades según el tipo de usuario:

### 🌐 Público / Anónimo

```
✓ Acceso limitado a información general
✓ Visualización de rutinas y dietas de ejemplo
✓ Tutoriales y guías básicas
✗ Sin capacidad de edición
✗ Sin acceso a datos personales
```

**Pantallas disponibles:** `Inicio` • `Rutinas de Ejemplo` • `Dietas de Ejemplo`

---

### 🧑‍💻 Usuario Registrado (Cliente)

```
✓ Visualización de rutinas y dietas asignadas
✓ Registro de progresos personales
✓ Consulta de historial completo
✓ Edición de perfil propio
✗ Sin acceso a otros usuarios
✗ Sin capacidades administrativas
```

**Pantallas disponibles:** `Inicio` • `Mi Perfil` • `Mis Rutinas` • `Mis Dietas` • `Historial`

---

### 🧑‍🏫 Administrador / Entrenador

```
✓ Gestión completa de clientes
✓ Creación y asignación de rutinas
✓ Diseño de planes nutricionales
✓ Acceso a estadísticas globales
✓ Configuración de la aplicación
✓ Eliminación y modificación de registros
```

**Pantallas disponibles:** `Inicio` • `Clientes` • `Rutinas` • `Dietas` • `Estadísticas` • `Configuración`

---

## 📋 Justificación Académica

Este proyecto demuestra competencias clave del ciclo de **Desarrollo de Aplicaciones Multiplataforma (DAM)**:

- ✅ Programación en Java orientada a objetos
- ✅ Diseño de interfaces en Android Studio
- ✅ Gestión de bases de datos SQL
- ✅ Operaciones CRUD avanzadas
- ✅ Manejo de datos y lógica de negocio
- ✅ Arquitectura de software escalable

---

## 📊 Modelo de Datos

### Entidad Usuario
```
• id (clave primaria)
• nombre
• correo
• contraseña (cifrada)
• rol (público/cliente/administrador)
```

### Entidad Cliente
```
• id (clave primaria)
• nombre
• edad
• peso
• altura
• objetivos
```

*Más entidades para rutinas, dietas, ejercicios y registros de progreso*

---

<div align="center">

## 🎓 Proyecto Académico

Desarrollado como parte del ciclo formativo de **Desarrollo de Aplicaciones Multiplataforma (DAM)**

---

### 💪 GymTrack - Gestión profesional al alcance de tu mano

*Hecho con ❤️ para transformar la gestión de gimnasios*

</di
