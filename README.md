# 🏹 CLUB SAETAS VALIENTES

### Sistema Integral de Gestión Deportiva

\<p align="center">
&#x20; \<strong>TRABAJO FINAL – ESTRUCTURAS DE DATOS\</strong>
\</p>

\<p align="center">
&#x20; \<img src="[https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white](https://img.shields.io/badge/Python-3.x-blue?logo=python\&logoColor=white)" />
&#x20; \<img src="[https://img.shields.io/badge/Interfaz-Gradio-orange](https://img.shields.io/badge/Interfaz-Gradio-orange)" />
&#x20; \<img src="[https://img.shields.io/badge/Entorno-Google%20Colab-yellow?logo=googlecolab&logoColor=white](https://img.shields.io/badge/Entorno-Google%20Colab-yellow?logo=googlecolab\&logoColor=white)" />
&#x20; \<img src="[https://img.shields.io/badge/Estado-Proyecto%20académico-success](https://img.shields.io/badge/Estado-Proyecto%20académico-success)" />
\</p>

---

---

## 📖 Descripción del proyecto

**Club Saetas Valientes** es un sistema de gestión deportiva desarrollado en Python como proyecto académico para la asignatura de Estructuras de Datos.

Su propósito es facilitar la administración de la información de un club deportivo, permitiendo organizar los datos de los deportistas y gestionar diferentes aspectos de su actividad dentro de la institución.

El proyecto integra estructuras de datos y programación orientada a objetos con una interfaz gráfica desarrollada mediante Gradio, buscando que la administración de la información sea más organizada, sencilla y accesible.

El sistema contempla tres disciplinas deportivas: boxeo, baloncesto y patinaje.

## 🎯 Objetivos

**Objetivo general**

Desarrollar un sistema de gestión deportiva que permita administrar la información de los deportistas y sus actividades, aplicando los conceptos de programación y las estructuras de datos estudiadas durante el curso.

**Objetivos específicos**

- Organizar la información de los deportistas.
- Facilitar el registro, consulta y modificación de datos.
- Gestionar información relacionada con pagos, lesiones y asistencia.
- Aplicar diferentes estructuras de datos en situaciones prácticas.
- Implementar una interfaz gráfica que facilite el uso del sistema.

## 🏅 Disciplinas deportivas

El sistema está orientado a la gestión de tres disciplinas:

| Disciplina    | Descripción                                |
| ------------- | ------------------------------------------ |
| 🥊 Boxeo      | Administración de deportistas de boxeo.    |
| 🏀 Baloncesto | Organización de deportistas de baloncesto. |
| 🛼 Patinaje   | Administración de deportistas de patinaje. |

## ⚙️ Funcionalidades principales

El sistema reúne diferentes opciones para la gestión deportiva:

| Funcionalidad           | Descripción                                              |
| ----------------------- | -------------------------------------------------------- |
| Registro de deportistas | Permite ingresar información de nuevos deportistas.      |
| Consulta                | Facilita la búsqueda y visualización de información.     |
| Modificación            | Permite actualizar los datos registrados.                |
| Listado de deportistas  | Presenta la información organizada.                      |
| Historial de pagos      | Permite gestionar información relacionada con los pagos. |
| Historial de lesiones   | Organiza los registros de lesiones.                      |
| Control de asistencia   | Permite administrar los registros de asistencia.         |

## 🧠 Estructuras de datos implementadas

Uno de los componentes centrales del proyecto es la aplicación de estructuras de datos para organizar y administrar la información.

| Estructura                 | Concepto                                                     | Aplicación en el proyecto                                            |
| -------------------------- | ------------------------------------------------------------ | -------------------------------------------------------------------- |
| Lista simplemente enlazada | Conecta nodos mediante referencias al siguiente elemento.    | Organización de registros.                                           |
| Lista doblemente enlazada  | Permite recorrer los elementos hacia adelante y hacia atrás. | Administración de información mediante recorridos en ambos sentidos. |
| Pila (LIFO)                | El último elemento en entrar es el primero en salir.         | Manejo de información mediante el comportamiento de una pila.        |
| Cola (FIFO)                | El primero en entrar es el primero en salir.                 | Organización de elementos según su orden de llegada.                 |
| Árbol binario de búsqueda  | Organiza elementos mediante relaciones entre nodos.          | Organización y búsqueda de información.                              |

Estas estructuras permiten aplicar los conceptos vistos en clase y comprender cómo se pueden utilizar para resolver necesidades de organización y administración de datos.

## 🖥️ Interfaz gráfica

El proyecto utiliza **Gradio** para ofrecer una interfaz gráfica que permite interactuar con las funcionalidades del sistema.

La interfaz organiza las opciones de trabajo en diferentes secciones, entre ellas:

- Listado de deportistas.
- Registro y modificación de información.
- Torneos e historiales.
- Control de asistencia.

La intención es facilitar el acceso a las opciones del sistema sin necesidad de interactuar directamente con el código.

> **Nota:** En esta sección se pueden agregar capturas de pantalla de la aplicación para mostrar su funcionamiento.

## 🛠️ Tecnologías utilizadas

| Tecnología                       | Uso                                                |
| -------------------------------- | -------------------------------------------------- |
| Python                           | Desarrollo de la lógica del sistema.               |
| Gradio                           | Construcción de la interfaz gráfica.               |
| Google Colab                     | Entorno para desarrollar y ejecutar el notebook.   |
| Programación orientada a objetos | Organización del código mediante clases y objetos. |

## 📂 Organización del repositorio

```text
Sistema-Saetas/
│
├── SaetasValientes.ipynb
│
└── README.md
```

**Archivos principales:**

- `SaetasValientes.ipynb`: contiene el desarrollo del sistema.
- `README.md`: presenta la documentación general del proyecto.

## ▶️ Instalación y ejecución

### Opción 1. Ejecutar desde Google Colab

1. Ingresar a Google Colab.
2. Abrir el archivo `SaetasValientes.ipynb`.
3. Ejecutar las celdas en el orden establecido.
4. Esperar a que se instalen o inicialicen las dependencias necesarias.
5. Cuando se ejecute Gradio, utilizar el enlace generado para abrir la interfaz.

### Opción 2. Ejecutar en un entorno local

Primero, instalar Python y abrir una terminal en el equipo.

Instalar Gradio:

```bash
pip install gradio
```

Después, abrir el notebook `SaetasValientes.ipynb` en un entorno compatible y ejecutar sus celdas en orden.

## 💾 Almacenamiento de información

El sistema administra la información mediante las estructuras de datos implementadas en el programa.

La información se conserva durante la ejecución de acuerdo con el funcionamiento del código. El proyecto no documenta una base de datos permanente, por lo que no debe asumirse que los registros se conservan después de cerrar la sesión.

## 🚀 Mejoras futuras

Como posibles ampliaciones del proyecto se plantean:

- Incorporar una base de datos para conservar los registros.
- Ampliar las opciones de consulta y búsqueda.
- Generar reportes estadísticos de los deportistas.
- Incorporar nuevas disciplinas deportivas.
- Mejorar la presentación visual de la interfaz.

## 👨‍💻 Integrantes

**Desarrollado por:**

- **Tomas Vergara**
- **Jhonatan Oquendo**

**Programa:** Ingeniería en Ciencia de Datos
**Institución:** Instituto Tecnológico Metropolitano (ITM)
**Asignatura:** Estructuras de Datos
**Proyecto:** Trabajo final
**Año:** 2026

---

\<p align="center">   \<strong>CLUB SAETAS VALIENTES\</strong>\<br/>   Sistema Integral de Gestión Deportiva\<br/>   \<em>Aplicando estructuras de datos a la gestión deportiva.\</em> \</p>
