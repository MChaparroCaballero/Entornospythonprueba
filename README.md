# 🧪 Entorno de Pruebas de Python (Sandbox)

Este repositorio ha sido creado para servir como un **entorno de pruebas (Sandbox)** dedicado a la experimentación con Python, entornos virtuales (`venv`), y la gestión de dependencias.

---

## 🎯 Objetivo Principal

El propósito de este proyecto es practicar y validar los siguientes conceptos, sin afectar proyectos productivos:

1.  **Creación y activación de Entornos Virtuales:** Asegurar el aislamiento de las dependencias.
2.  **Instalación de paquetes:** Gestionar la librería requerida en `requirements.txt`.
3.  **Configuración de Git:** Entender la función del archivo `.gitignore` para excluir carpetas grandes como `.venv/` y `.vscode/`.

---

## ⚙️ Configuración Inicial

Para trabajar en este entorno, es **fundamental** seguir estos dos pasos:

### 1. Recrear el Entorno Virtual

Antes de ejecutar cualquier script, debes crear y activar el entorno virtual localmente. Esto garantiza que las dependencias se instalen correctamente sin interferir con otras instalaciones de Python en tu sistema.

**Comando de Creación:**

```bash
python -m venv .venv