# 📌 División en complemento a 9

> ⚠️ Estado: ***EN DESARROLLO*** Versión académica

Se implementa divisiones enteras entre dos números extremadamente grandes (hasta 350,000 dígitos), sin recurrir a los operadores de división, utilizando aritmética basada en el complemento a 9, técnica usada para restar números de manera más eficiente, transformando la sustracción en una suma con el complemento del sustraendo. La división se realiza mediante restas sucesivas: se resta repetidamente el divisor al dividendo, hasta que el dividendo es menor que el divisor

---

## 👥 Autores
GERARDO OSPINA HERNANDEZ

- [JUAN SEBASTIÁN GUAYAZÁN CLAVIJO](https://github.com/JuanGuayazanC) → [juan.guayazan-c@mail.escuelaing.edu.co](mailto:juan.guayazan-c@mail.escuelaing.edu.co)

Organización de los Sistemas de Cómputo (ISIS ODSC-1 y ODSC-101)      
Decanatura Ingeniería de Sistemas → Centro de Estudios de Arquitectura Tecnológica y Seguridad     
Ingeniería de Sistemas    
Escuela Colombiana de Ingeniería Julio Garavito     
2025-i

---

## 🧠 Índice

- 📌 [Nombre del Proyecto](#-división-en-complemento-a-9)
- 🚀 [Características](#-características)
- ⚙️ [Tecnologías](#️-tecnologías)
- 📦 [Instalación](#-instalación-y-requisitos)
- ▶️ [Uso](#️-uso)
- 🧪 [Pruebas](#-pruebas)
- 📁 [Estructura del Proyecto](#-estructura-del-proyecto)
- 📌 [TODOs / Funcionalidades Futuras](#-todos--funcionalidades-futuras)
- 👥 [Autores](#-autores)
- 📄 Licencia](#-licencia)

---

## 🚀 Características

- ✅ Soporta números de hasta 350,000 dígitos
- ✅ Realiza divisiones enteras utilizando operaciones de resta y complemento a 9
- ✅ Compatible con compiladores estándar de C como `gcc`
- ✅ Uso eficiente de memoria para operaciones con enteros grandes representados como arreglos

---

## ⚙️ Tecnologías

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white) ![GCC](https://img.shields.io/badge/GCC-A8B9CC?style=flat-square&logo=gnu&logoColor=white)

- Lenguaje: `C`
- Herramientas: `GCC`, `onlinegdb`
- Dependencias: Ninguna externa (usa solo la biblioteca estándar)

---

## 📦 Instalación y Requisitos

### Clonar el repositorio

```bash
git clone  https://github.com/JuanGuayazanC/Division-entera-Complemento-9-ODSC.git
cd Division-entera-Complemento-9-ODSC
````

### Requisitos

* Compilador de C (`gcc` o compatible)
* Sistema operativo tipo UNIX o Windows con terminal compatible
* Editor de texto (VSCode, Vim, etc.)

### Instalación

```bash
gcc division.c -o division
```

---

## ▶️ Uso

Ejecuta el programa desde la terminal y proporciona la entrada por consola:

```bash
./division
```


> \[!NOTE]
> La entrada debe contener el número de casos, seguido por pares de líneas: dividendo y divisor en base 10.

> \[!WARNING]
> El programa no usa `div` ni `/`. Realiza la división simulando operaciones matemáticas en base al complemento a 9.

---

## 🧪 Pruebas

Puede probar manualmente con:

### Ejemplo de entrada:

```
3
123
12
123
111
12
8
```

### Ejemplo de salida esperada:

```
10
3
12
3
13
7
```


---

## 📁 Estructura del Proyecto

```bash
📦 Division-entera-Complemento-9-ODSC
 ┗ 📜 division.c
```

---

## 📌 TODOs / Funcionalidades Futuras

* [ ] Implementar manejo de números negativos
* [ ] Permitir divisiones con decimales
* [ ] Crear interfaz gráfica (opcional)
* [ ] Agregar pruebas automatizadas con `assert`

---

## 📄 Licencia

Este proyecto está licenciado bajo propósitos académicos y educativos. Puedes consultar el archivo [LICENSE](./LICENSE) para más información.
