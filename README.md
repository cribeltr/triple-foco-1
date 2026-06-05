# 🎯 Triple Foco

Aplicación web de productividad **de un solo archivo** (`index.html`, sin dependencias) que combina tres metodologías probadas en un único flujo de trabajo: de la claridad a la acción.

> **Clasifica · Planifica · Ejecuta**

## Las tres metodologías

| # | Método | Para qué sirve |
|---|--------|----------------|
| **1** | **Matriz de Eisenhower** | Clasifica cada tarea por **urgencia** e **importancia** en cuatro cuadrantes: *Hazlo ya*, *Planifica*, *Delega* y *Elimina*. Gana claridad y separa el ruido de lo esencial. |
| **2** | **Método Ivy Lee** | Elige las **6 tareas más importantes** del día y **ordénalas por prioridad**. La restricción de seis te obliga a decidir. Después trabajas de una en una, sin saltarte el orden. |
| **3** | **Cómete el Sapo** (Brian Tracy) | Tu «sapo» es la tarea más importante y difícil: la **#1** de tu plan. Cómetela a primera hora, cuando tu energía es máxima. |

El hilo que las une: **Eisenhower** te da claridad → **Ivy Lee** la convierte en un plan ordenado → **Cómete el Sapo** lo convierte en acción, empezando por lo más importante.

## Características

- 🔲 **Matriz interactiva** con arrastrar y soltar para reclasificar tareas entre cuadrantes.
- 📋 **Plan diario** con tope de 6 tareas, reordenables arrastrando o con botones (la #1 se marca como 🐸 sapo).
- 🐸 **Vista de ejecución** que destaca el sapo, resalta la tarea en foco, muestra el progreso del día e incluye un **cronómetro** de concentración.
- 🌅 **Empezar nuevo día**: archiva lo completado y conserva lo pendiente (arrastre al estilo Ivy Lee).
- 💾 **Persistencia local** (localStorage), **exportar/importar** en JSON. Nada sale de tu navegador.
- 🌗 **Tema claro/oscuro**, diseño **responsive** y atajos de teclado (`1` / `2` / `3` para cambiar de vista).

## Uso

Abre `index.html` en cualquier navegador moderno. No requiere instalación, servidor ni conexión a internet.

```
# opcionalmente, sírvelo en local
python3 -m http.server
# y visita http://localhost:8000
```

## Privacidad

Toda la información se guarda únicamente en el `localStorage` de tu navegador. La aplicación no realiza ninguna petición de red.
