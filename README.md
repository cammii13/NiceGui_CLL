# NiceGui_CLL
Interfaz Web con Python 

# Calculadora Interactiva con NiceGUI

Este proyecto es una aplicación web de calculadora desarrollada en **Python** utilizando el framework **NiceGUI**. Con una interfaz de usuario moderna basada en componentes web y Tailwind CSS.

## Explicación

| Elemento | Propósito | Clase CSS Principal |
| :--- | :--- | :--- |
| `ui.card` | Contenedor principal | `w-60 m-auto` |
| `ui.input` | Entrada de números | `w-full` |
| `ui.button`| Ejecutor de funciones | `bg-blue-500` |
| `ui.label` | Visualización de resultado | `text-center` |

w-60 m-auto provienen de Tailwind CSS y se aplican al contenedor principal son las responsables de que la calculadora no ocupe toda la pantalla y se mantenga centrada.

w-full significa "width: 100%". Su objetivo principal es obligar al elemento a expandirse hasta ocupar todo el ancho disponible de su contenedor padre.

La clase bg-blue-500 es una utilidad de Tailwind CSS que define el color de fondo de un elemento.