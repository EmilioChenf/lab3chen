# lab3chen
# El rescate de Memín 🏰🌲🔥  
**Historia interactiva en HTML (Elige tu propia aventura)**

Una aventura de texto donde la princesa **Mariandré** se adentra en un bosque peligroso y luego en un castillo para rescatar al príncipe **Memín**.  
Cada página es una escena y cada decisión cambia el rumbo de la historia.

---

## ✅ Reglas del proyecto (según el laboratorio)
- **Solo HTML** (sin CSS y sin JavaScript).
- **Varias páginas** conectadas por links.
- **No es lineal**: hay decisiones que llevan a caminos diferentes.
- **Incluye al menos un loop** (regresar a una escena anterior usando `..`).
- **Incluye al menos una imagen** en la carpeta `images/` con `figure`, `img` y `figcaption`.
- En los **finales** hay un link para regresar al inicio.

---

## 🧭 Cómo jugar
1. Abre `index.html` (inicio).
2. Elige una opción.
3. Explora rutas diferentes para encontrar:
   - **Final bueno (Rescate)** ✅
   - **Final neutral (Fuga)** 🟡
   - **Final malo (Derrota)** ❌

> Tip: Si caes en un final malo, vuelve al inicio y prueba otra ruta.

---

## 🗺️ Estructura del proyecto
```txt
lab3chen/
├─ index.html
├─ bosque/
│  ├─ claro.html
│  ├─ sendero.html
│  ├─ rio.html
│  └─ cueva/
│     ├─ entrada.html
│     └─ oscuridad.html
├─ castillo/
│  ├─ puente.html
│  ├─ patio.html
│  └─ torre/
│     ├─ pasillo.html
│     ├─ celda.html
│     └─ trampa.html
├─ finales/
│  ├─ rescate.html
│  ├─ fuga.html
│  └─ derrota.html
└─ images/
   └─ guardian.jpg
