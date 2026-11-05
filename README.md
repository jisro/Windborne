# Windborne

A breath-controlled game where you fly a bird using your actual breathing.

**Built for:** Graduation project exploring alternative game input methods
**Control method:** Arduino + wind sensor + respiration belt

## What it does

You control a bird's flight with your breath:
- **Inhale** → the bird rises
- **Exhale** → the bird glides down
- **Breath depth** controls ascent/descent speed

The physical interface uses:
- Arduino microcontroller
- Wind sensor (measures airflow)
- Respiration belt (tracks chest expansion)

## Why this exists

The original concept was a full narrative game that gradually builds breathing awareness — teaching techniques through gameplay. During development, I focused on nailing the core mechanic: making breath feel like a natural, tactile input method.

What remains is that core — a meditative flying experience where your breathing **is** the controller.

## Tech stack

- **Unity** (game engine)
- **Arduino** (sensor interface)
- **C#** (game logic)
- **Serial communication** (Arduino → Unity data stream)

## What I learned

- Physical input design is **hard** — breath is inconsistent, personal, and context-dependent
- Calibration is everything (what feels natural for one person doesn't for another)
- The mechanic itself is more interesting than I expected — even without a full game around it, breath-as-input creates a unique mindfulness experience

---

This was a graduation project exploring embodied interaction and alternative game control systems.
