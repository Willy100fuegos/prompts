# Gemini PRD Architect - Prompt Engineering 🧠

> **Librería de instrucciones de sistema (System Prompts) para Google Gemini.**
> *Meta-programación diseñada para estandarizar la generación de Documentos de Requerimientos de Producto (PRD) y arquitectura de software.*

<div align="center">
  <img src="https://img.shields.io/badge/AI_Model-Gemini_1.5_Pro-4285F4?style=for-the-badge&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/Version-3.0_Adaptive-success?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Focus-Software_Architecture-blueviolet?style=for-the-badge" />
</div>

---

## 🎯 Objetivo del Repositorio

Este repositorio aloja la evolución del **"Prompt Maestro"** utilizado para convertir ideas abstractas en especificaciones técnicas listas para desarrollo. Actúa como un *driver* que configura a la IA con un rol específico: **Arquitecto de Software Senior**.

El objetivo es eliminar la ambigüedad en el desarrollo asistido por IA, forzando estándares de industria, seguridad y estructura de carpetas desde el primer token generado.

---

## 🧬 Evolución de Versiones (Changelog)

El prompt ha pasado por un proceso de refactorización basado en la experiencia de campo.

### 🌟 v3.0 - Arquitectura Adaptativa (Current)
> **"El estratega inteligente"**
* **Lógica:** Implementa un árbol de decisión interno. Ya no asume un stack, sino que evalúa la complejidad.
* **Decision Tree:**
    * *Camino A (Dashboard/Visual):* HTML5 + Tailwind + Vanilla JS (Sin Backend complejo).
    * *Camino B (App Transaccional):* Stack LAMP Estricto (PHP 8.1, MySQL, Apache).
* **Filosofía:** Aplica el principio **KISS** (Keep It Simple, Stupid) para evitar la sobre-ingeniería en proyectos pequeños.
* **Rol:** Desarrollador Senior Políglota con enfoque en eficiencia.

### 🛡️ v2.0 - Especialista LAMP (Legacy)
> **"El purista del Backend"**
* **Lógica:** Fuerza bruta hacia el desarrollo web tradicional robusto.
* **Stack:** Estrictamente PHP 8.1+, MySQL 8.0 y Apache.
* **Enfoque:** Seguridad (Prepared Statements), Patrón MVC manual y estructura de carpetas `public/` para servidores Linux/cPanel.

### 👶 v1.0 - MVP Generalist (Deprecated)
> **"El explorador"**
* **Lógica:** Product Manager general.
* **Stack:** Flexible/Agnóstico (Node, React, Python, etc.).
* **Uso:** Prototipado rápido sin restricciones de infraestructura.

---

## 📂 Estructura del Repositorio

```bash
/prompts
├── current_prompt.md         # La versión activa (v3.0) lista para copiar
├── versions/
│   ├── v1_base_manager.md    # Histórico: Enfoque MVP
│   ├── v2_lamp_strict.md     # Histórico: Enfoque SysAdmin/PHP
│   └── v3_adaptive.md        # Snapshot de la versión actual
├── contracts/
│   └── architecture.md       # Reglas de negocio inyectadas al prompt
├── CHANGELOG.md              # Registro detallado de cambios
└── README.md

## 🚀 Guía de Implementación
Para utilizar este "Cerebro" en una nueva sesión de Gemini:

Navega al archivo current_prompt.md.

Copia el bloque de código completo (Raw).

Pégalo en Gemini Advanced / AI Studio como primera instrucción.

Input: "Hola, quiero desarrollar un sistema para [Tu Idea]".

Output: La IA actuará automáticamente como el Arquitecto v3.0, te hará preguntas de Deep Dive y generará el PRD técnico.

## 🛠️ Ingeniería del Prompt
Los prompts están diseñados utilizando técnicas avanzadas de NLP:

Chain-of-Thought (CoT): Se obliga a la IA a pensar paso a paso (Plan de Ejecución).

Role Prompting: Se define una personalidad estricta (Arquitecto vs PM).

Constraint Setting: Restricciones negativas (e.g., "No uses frameworks de JS si no es necesario").

Desarrollado por: William Velázquez Valenzuela | Director de Tecnologías
