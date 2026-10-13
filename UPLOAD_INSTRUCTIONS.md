# Cómo subir el archivo de simulación completo

El archivo principal **LQ2_Material_Flow_Simulation_standalone.html** es autocontenido (incluye el layout de planta embebido) y tiene un tamaño de ~320 KB.

## Opción más fácil (recomendado)

1. Abre el repositorio: https://github.com/lvalenciajasso-sys/LQ2-Material-Flow-Simulation
2. Haz clic en el botón verde **Add file** → **Upload files**
3. Arrastra o selecciona el archivo `LQ2_Material_Flow_Simulation_standalone.html`
4. Escribe un mensaje de commit (ej. "Add full interactive simulation") y haz clic en **Commit changes**

## Opción con Git (local)

```bash
git clone https://github.com/lvalenciajasso-sys/LQ2-Material-Flow-Simulation.git
cd LQ2-Material-Flow-Simulation
# Copia el archivo standalone aquí
git add LQ2_Material_Flow_Simulation_standalone.html
git commit -m "Add full interactive simulation with embedded layout"
git push origin main
```

Una vez subido, podrás abrir el HTML directamente desde GitHub o habilitar **GitHub Pages** para compartirlo como sitio web.
