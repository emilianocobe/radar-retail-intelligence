# 📡 Radar Retail Intelligence

Reporte de análisis competitivo del sector de *retail intelligence* / conteo de personas, con **Euler Labs** como marca focal frente a cuatro competidores:

| Marca | Sitio | Perfil |
|---|---|---|
| Euler Labs | [eulerlabs.tech](https://www.eulerlabs.tech/) | Challenger · plataforma unificada (Dataview, EulerAudit, Eulergy, EulerIA) |
| Keengo | [keengo.net](https://keengo.net/) | Integrador local (AR) · hardware + datos |
| RetailNext | [retailnext.net](https://retailnext.net/) | Líder global · plataforma IA |
| RetailCheck | [retailcheck.net](https://retailcheck.net/) | Especialista regional · medición (CL + 5 países) |
| Sensormatic ShopperTrak | [sensormatic.com](https://www.sensormatic.com/es_es/traffic-insights) | Incumbente global · Johnson Controls |

## Contenido

Página única y autocontenida (`index.html`, sin dependencias externas salvo Google Fonts):

- Hero animado con simulación de conteo de personas (canvas)
- Resumen ejecutivo con 6 insights
- Dashboard de mercado (people counting: US$ 2.120M en 2025 → US$ 4.360M en 2030)
- 5 dossiers de marca con storytelling, citas y chips de capacidades
- Matriz de 12 capacidades × 5 marcas + índice de amplitud de portafolio
- Mapa de posicionamiento competitivo (SVG)
- Línea de tiempo del sector 1966–2026
- FODA de Euler Labs, jugadas recomendadas y preguntas disparadoras
- Glosario visual de 10 términos con iconografía propia
- Códigos QR escaneables de los cinco sitios analizados
- Temas claro y oscuro · paleta validada para daltonismo (CVD ΔE ≥ 8)

## Uso

Abrir `index.html` en cualquier navegador, o servirlo estáticamente:

```bash
python -m http.server 8000
```

## Metodología y límites

Análisis documental sobre información pública declarada por cada marca (relevada el 24-08-2026), más fuentes de mercado citadas dentro del propio reporte. Las posiciones del mapa competitivo son cualitativas; no incluye pruebas de producto ni datos de clientes.
