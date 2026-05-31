# 🦜 Beyond Mist Nets
## Aves Habituadas Neotropicales — Tracker colaborativo

> Base de datos colaborativa de aves cebadas activamente en el Neotrópico, con mapa interactivo de avance por país y departamento.

🌐 **Página web:** [setase24.github.io/beyond_mist_nets](https://setase24.github.io/beyond_mist_nets/)
📊 **Datos en tiempo real:** Google Sheets (actualización automática)
📄 **Artículo en preparación:** *Beyond Mist Nets* — Methods in Ecology and Evolution

---

## ¿Qué es esto?

Un inventario sistemático de aves silvestres neotropicales habituadas activamente mediante interacción directa con una persona (el "cebador"), sin la cual el ave no se aproximaría. La base de datos documenta su potencial como sujetos experimentales únicos para ecología conductual, bioacústica, parasitología y más.

## Estructura del repositorio

```
beyond_mist_nets/
├── index.html                         # Tracker interactivo (mapa + heatmap)
├── data/
│   ├── neotropical_countries.geojson  # 26 países neotropicales (WGS84)
│   ├── admin1_neotropical.geojson     # 457 departamentos/estados
│   └── admin1/                        # GeoJSONs por país (carga lazy)
│       ├── co.geojson                 # Colombia
│       ├── mx.geojson                 # México
│       └── ...                        # 26 países
└── README.md
```

## Cómo contribuir

Si conoces o mantienes un ave habituada activamente en el Neotrópico, tu registro es valioso. Consulta el protocolo completo en la página web.

---

*Iniciativa del grupo de investigación en ecología neotropical — 2026*
