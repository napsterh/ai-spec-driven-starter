

![Hero Image](hero-image.jpg)

# ⚡ AI Spec-Driven Starter Kit

> **Programa con IA sin perder el control de tu código ni generar código spaghetti.**

---

### 🎨 ¿Cómo funciona este proyecto?
💡 Idea / Función ───► 📋 SPEC.md (Tu plan) ───► 🛡️ CLAUDE.md (Las reglas) ───► 🚀 Código Limpio
---

## ❌ El Problema
Cuando le pides código a la IA sin un plan, genera miles de líneas desordenadas, rompe módulos existentes y crea una "caja negra" imposible de mantener ("Vibe Coding").

## 🎯 La Solución (Spec-Driven Development)
1. **Reglas de juego (`CLAUDE.md` / `.cursorrules`):** Le prohíben a la IA borrar o cambiar código sin tu permiso.
2. **Especificación previa (`SPEC.md`):** Defines en 2 minutos qué quieres construir antes de pedir código.
3. **Desarrollo guiado (`PROMPTS.md`):** Copias y pegas prompts predefinidos para que la IA avance por fases cortas y supervisadas.

---

## 🚀 Inicio Rápido (En 3 simples pasos)

### 1. Clona este proyecto
Haz clic en el botón verde **"Use this template"** en GitHub (o clona este repositorio en tu computadora) y ábrelo en **Cursor, VS Code, Claude Code o Windsurf**.

### 2. Define tu idea en `SPEC.md`
Abre el archivo `SPEC.md` y escribe en lenguaje normal lo que quieres construir.

> **Ejemplo:** *"Quiero un formulario de contacto con nombre, correo y mensaje usando React y Tailwind CSS."*

### 3. Copia y pega el Prompt #1
Abre `PROMPTS.md`, copia el **Prompt 1 (Inicialización)** y pégalo en el chat de tu IA.

```markdown
> "Lee CLAUDE.md y SPEC.md. Acepta las reglas de trabajo y dime en 3 puntos cómo vas a implementar la Fase 1 sin tocar otras partes del proyecto."
```
