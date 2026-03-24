# Trainity

Trainity es una plataforma de fitness para entrenadores, clientes y atletas independientes.
Centraliza rutinas, sesiones y métricas para que el entrenamiento sea claro, rápido y accionable.

## Roles
- **Trainer (Entrenador)**: crea rutinas, asigna clientes y revisa progreso.
- **Client (Cliente)**: recibe rutinas, registra sesiones y reporta RPE/notas.
- **Independent (Atleta independiente)**: gestiona sus propias rutinas y sesiones.

## MVP (estado actual)
- Registro/login con selección de rol.
- Creación/edición de rutinas.
- Asignación de rutinas a clientes.
- Registro de sesiones (series, reps, peso, RPE, notas).
- Dashboard con métricas semanales (volumen, adherencia, progreso).
- Historial y progreso por ejercicio.
- Alertas simples de inactividad/adherencia.

## Principios de producto
- **Desktop‑first** para entrenadores en gestión/reporting.
- **Mobile‑first** para logging de sesiones (todos los roles).
- Interacciones rápidas (logging en segundos).
- Diseño premium, claro y consistente.

## Tech Stack
- **Frontend**: React 19 + Vite + Tailwind CSS v4
- **Backend**: Node.js + Express 5
- **DB**: MongoDB Atlas (Mongoose)
- **IA (local)**: Ollama (modelos locales)
- **Deploy**: Vercel (frontend) + hosting gratuito (backend)

## Estructura del repo
Este repo actúa como workspace AI‑native sin destruir tus repos originales:

- `src/trainity-web/` → frontend (repo existente)
- `src/trainity-api/` → backend (repo existente)
- `src/shared/` → tipos/contratos compartidos (futuro)
- `context/` → arquitectura, UX/UI, seguridad y compliance
- `ai/` → planificación y memoria de tareas
- `.claude/` → commands, agents, skills
- `tools/prompts/` → prompts de apoyo

## Cómo arrancar
### Frontend
```bash
cd src/trainity-web
npm install
npm run dev
```

### Backend
```bash
cd src/trainity-api
npm install
npm run dev
```

## Seguridad y compliance
Ver:
- `context/security.md`
- `context/compliance.md`
- `context/accessibility.md`

## Nota importante
Este workspace no reemplaza tus repos originales. Sirve para trabajar con Claude Code + Ollama
con una capa extra de documentación y skills.
