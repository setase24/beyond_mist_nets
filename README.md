# 🦜 Beyond Mist Nets
## Aves Habituadas Neotropicales — Tracker colaborativo

Mapa interactivo del avance de la base de datos de aves cebadas activamente en el Neotrópico.

🌐 **Web:** `https://TU_USUARIO.github.io/beyond_mist_nets/`
📊 **Datos:** Google Sheets (actualización en tiempo real)

### Cómo subir a GitHub Pages

```bash
git init
git add .
git commit -m "🦜 Beyond Mist Nets v1.0"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/beyond_mist_nets.git
git push -u origin main
```

Luego: **Settings → Pages → Branch: main → Save**

### Estructura
```
beyond_mist_nets/
├── index.html                         # App principal
├── data/
│   ├── neotropical_countries.geojson  # 26 países (shapefiles reales)
│   └── admin1_neotropical.geojson     # 457 departamentos/estados
├── .nojekyll                          # Para GitHub Pages
└── README.md
```

### Conexión a Google Sheets
El Sheets ID ya está configurado. Solo asegúrate de que la hoja sea pública:
**Compartir → Cualquier persona con el enlace → Lector**
