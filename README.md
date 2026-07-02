# 🔥 RETO 180 — App de Transformación Corporal

App web personal para seguir un plan de transformación de 6 meses (180 días): entrenamiento de gym 5 días/semana, nutrición con déficit calórico, hidratación, peso corporal y un sistema de racha estilo **contribution graph de GitHub** — cada día cumplido es un commit verde de disciplina.

## ✨ Qué incluye

- **HOY** — Rutina del día automática según el día de la semana, con checkbox por ejercicio, campo para anotar el peso (lb), cardio, las 5 comidas del día (menú A o B estilo dominicano) y contador de 12 vasos de agua.
- **RETO** — Racha de días cumplidos 🔥, grid de 180 días estilo GitHub, estadísticas de cumplimiento y el contrato de reglas innegociables. Las faltas por salud o compromiso se marcan como **justificadas** y no rompen la racha.
- **PROGRESO** — Registro de peso con gráfica, línea de meta (84 kg), recordatorio de foto cada 14 días y cronograma mes a mes.
- **PLAN** — Todo el plan de referencia: fases y calorías (2,250 → 2,150 → 2,100 kcal), macros (185g proteína), rutina semanal completa, alimentos permitidos/eliminados y suplementos.

Los datos se guardan **en tu navegador** (localStorage). Usa el botón **Exportar** en la pestaña RETO para respaldos.

## 🚀 Cómo publicarla en GitHub Pages

1. Crea un repositorio nuevo en GitHub (ej. `reto-180`).
2. Sube estos dos archivos (`index.html` y `README.md`).
3. Ve a **Settings → Pages → Source: Deploy from a branch → main / root → Save**.
4. En 1-2 minutos tu app estará en `https://TU-USUARIO.github.io/reto-180/`.
5. Ábrela en el celular → **Compartir → Agregar a pantalla de inicio** = ícono como app. 📱

## ⚙️ Personalizar

Todo el plan vive en constantes al inicio del `<script>` en `index.html`:

| Constante | Qué controla |
|---|---|
| `WORKOUTS` | Ejercicios, series y reps por día de la semana |
| `MEALS` | Menús día A y día B |
| `PHASES` / `CARBS_BY_PHASE` | Calorías y carbos por fase |
| `RULES` | Las reglas del contrato |
| `TOTAL_DAYS` | Duración del reto (180) |

## ⚠️ Nota

Plan de referencia general (base: 96 kg, 1.75 m, hombre adulto). No sustituye la evaluación de un médico o nutricionista, especialmente si tienes alguna condición de salud.

---

**En 6 meses el espejo te lo paga. Dale con todo. 💪**
