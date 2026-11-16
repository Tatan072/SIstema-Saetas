# 🏹 CLUB SAETAS VALIENTES

## Sistema Integral de Gestión Deportiva

### TRABAJO FINAL – ESTRUCTURAS DE DATOS

**Integrantes:**
- Tomas Vergara
- Jhonatan Oquendo

**Programa:** Ingeniería en Ciencia de Datos  
**Institución:** Instituto Tecnológico Metropolitano (ITM)  
**Tecnologías:** Python · Gradio · Google Colab  
**Año:** 2026

---

## 📌 Descripción del proyecto

Club Saetas Valientes es un sistema desarrollado en Python para apoyar la gestión administrativa y deportiva de un club. Permite organizar la información de los deportistas, las disciplinas, los pagos, las lesiones y la asistencia mediante diferentes estructuras de datos.

El sistema cuenta con una interfaz gráfica desarrollada con Gradio, que facilita la interacción con sus funcionalidades.

## 🎯 Objetivo general

Desarrollar un sistema de gestión deportiva que permita administrar de manera organizada la información de los deportistas y las actividades del club, aplicando los conceptos y estructuras de datos estudiados durante el curso.

## 🏅 Disciplinas deportivas

El sistema contempla tres disciplinas:

- Boxeo.
- Baloncesto.
- Patinaje.

## ⚙️ Funcionalidades principales

- Registro de nuevos deportistas.
- Consulta y modificación de información.
- Visualización de deportistas registrados.
- Registro e historial de pagos.
- Registro e historial de lesiones.
- Control de asistencia.
- Organización de la información por disciplina.

## 🧩 Estructuras de datos implementadas

Para el desarrollo del proyecto se aplican diferentes estructuras de datos:

| Estructura | Aplicación |
|---|---|
| Lista simplemente enlazada | Organización de registros. |
| Lista doblemente enlazada | Recorrido y administración de información en ambos sentidos. |
| Pilas (LIFO) | Manejo de información con el último elemento ingresado como primero en salir. |
| Colas (FIFO) | Organización de elementos según su orden de llegada. |
| Árbol binario de búsqueda | Organización y búsqueda de información. |

## 🖥️ Interfaz del sistema

La aplicación utiliza Gradio para presentar las funcionalidades mediante pestañas:

- Listado de deportistas.
- Registro y modificación.
- Torneos e historiales.
- Control de asistencia.

## 🛠️ Tecnologías utilizadas

- **Python:** lenguaje de programación principal.
- **Gradio:** desarrollo de la interfaz gráfica.
- **Google Colab:** entorno de desarrollo y ejecución.
- **Programación orientada a objetos:** organización del código y sus funcionalidades.

## 📁 Estructura del repositorio

```text
Sistema-Saetas/
│
├── SaetasValientes.ipynb
└── README.md
```

## ▶️ Ejecución del proyecto

### Opción 1. Google Colab

1. Ingresar a Google Colab.
2. Abrir el archivo `SaetasValientes.ipynb`.
3. Ejecutar las celdas del notebook en orden.
4. Esperar a que se inicialice la aplicación.
5. Ingresar a la interfaz de Gradio desde el enlace generado.

### Opción 2. Entorno local

Instalar Gradio:

```bash
pip install gradio
```

Después, abrir y ejecutar el notebook en un entorno compatible con Python.

## 💾 Almacenamiento de información

La información se administra durante la ejecución del programa mediante las estructuras de datos implementadas. No se utiliza una base de datos permanente, por lo que los datos pueden perderse al finalizar la sesión.



