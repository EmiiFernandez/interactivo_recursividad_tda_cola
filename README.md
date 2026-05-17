# 🍕 Simulador de Cola Recursiva

Aplicación web interactiva que simula el funcionamiento de una **cola (TDA Cola)** y la ejecución de una función recursiva para calcular el monto total de pedidos.

Permite visualizar paso a paso cómo funciona la recursión, incluyendo llamadas, caso base y retornos.

---

## 🚀 Demo

👉 Puedes ejecutar el proyecto abriendo el archivo `index.html` en cualquier navegador.

No requiere instalación ni dependencias.

---

## 🧠 Función principal

La lógica se basa en la siguiente función recursiva:

```
Funcion montoTotalPedidos (val C: TCOLA) : REAL

INICIO
  Si (NO Cvacia(C)) entonces
    Csacar(C, DATO)
    MONTO <- DATO + montoTotalPedidos(C)
    Devolver MONTO
  Sino
    Devolver 0
FinSi

FIN FUNCION
```
---

## 🎯 Objetivo del proyecto

Este proyecto fue creado con fines educativos para:

- Comprender el funcionamiento de una **cola FIFO**
- Visualizar la **recursión paso a paso**
- Entender cómo se acumulan valores en llamadas recursivas
- Practicar lógica de estructuras de datos (TDA Cola)

---

## 🖥️ Interfaz

El proyecto se divide en dos paneles:

### 📌 Panel izquierdo
- Agregar pedidos
- Ver cola de clientes
- Ver cantidad total y monto acumulado

### 📌 Panel derecho
- Visualización del código recursivo
- Ejecución paso a paso
- Trazado de llamadas
- Resultado final del cálculo

<p align="center">
  <img alt="image" src="https://github.com/user-attachments/assets/c675c5d2-1b27-4bb2-8840-937a2da42f87" width="600"/>
</p>

---

## 🧩 Tecnologías usadas

- HTML5
- CSS3
- JavaScript 
- Sin frameworks ni dependencias externas

---

## 🧠 Función principal

La lógica se basa en la siguiente función recursiva:

## 👨‍💻 Autor

Proyecto educativo desarrollado con fines de aprendizaje en estructuras de datos y visualización algorítmica.

---

## 📌 Licencia

Uso libre con fines educativos.
