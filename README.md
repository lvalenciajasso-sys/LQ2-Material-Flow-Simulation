# LQ2 Material Flow Simulation

**Lean Six Sigma Project – Improvement of Internal Material Flow on Production Line LQ2**

Simulación visual y animada del proceso de surtimiento de material (Material Handler) para la línea de producción automotriz **LQ2** (LH + RH).

## 🎯 Objetivo

Representar de forma visual e interactiva el movimiento de **1 materialista** asignado a la Line 1 (ambos lados LH/RH), mostrando:

- Movimiento del materialista + carrito de surtimiento sobre el **layout real** de planta
- Hora actual del turno
- Tiempo transcurrido
- Distancia por vuelta y distancia acumulada
- Número de vuelta y de ciclo
- Estado actual: `Waiting` / `Loading` / `Scanning` / `Walking` / `Replenishing` / `Collecting Empty Packaging` / `Break` / `Lunch`
- Producción acumulada vs target de **1,080 piezas** (540 LH + 540 RH)

## 📁 Archivos

| Archivo | Descripción |
|---------|-------------|
| `LQ2_Material_Flow_Simulation_standalone.html` | **Simulación completa y autocontenida** (incluye el layout embebido). Solo abre este archivo en el navegador. |
| `LQ2_Material_Flow_Simulation.html` | Versión original (requiere `lq2_layout.png` en la misma carpeta) |
| `lq2_layout.png` | Layout real del piso de producción (puntos 1, 2, 9, 13, 26, 27) |

## 🚀 Cómo usar

1. Descarga o clona este repositorio.
2. Abre `LQ2_Material_Flow_Simulation_standalone.html` en cualquier navegador moderno (Chrome, Edge, Firefox, Safari).
3. Usa los controles:
   - **▶ Iniciar** → comienza el turno 07:00 – 17:00
   - **⏸ Pausar**
   - **↺ Reset**
   - Control de velocidad (0.5× – 20×)

## 📍 Puntos fijos del layout (no modificados)

- **1** – INJECTION
- **2** – WAREHOUSE MATERIAL
- **9** – SUB ASSY
- **13** – ASSY LINE LH / RH
- **26** – FG LH / RH
- **27** – FG

## ⏱️ Turno y breaks

- **Turno:** 07:00 AM – 05:00 PM (10 horas)
- **1er Break:** 09:30 – 09:40
- **Lunch:** 12:00 – 12:30
- **2do Break:** 14:30 – 14:40

## 📊 Datos de producción

- Target: **1,080 piezas** por turno
- Velocidad nominal: 70 UPH
- Eficiencia de referencia: 85%

## 🛠️ Proyecto Lean Six Sigma

Basado en el proyecto *“Improvement of Internal Material Flow on the Production Floor Applying in Line LQ2”* (SL MEX).

Ruta modelada a partir del análisis de tiempos y distancias (BEFORE ≈ 2.0 km → AFTER 2nd change ≈ 1.4 km).

## 📄 Licencia

Uso interno del proyecto. Todos los derechos reservados.
