# Einbürgerungstest · Leben in Deutschland

Página web para practicar el examen de naturalización alemán **„Leben in Deutschland“**.

**Página en vivo:** https://rocioadc.github.io/einbuergerungstest/

## Funciones

- Las 460 preguntas oficiales: 300 generales y 10 por cada estado federado (*Bundesland*), con imágenes.
- Alemán a la izquierda y traducción a la derecha en 7 idiomas: English, Türkçe, Русский, Українська, Français, العربية, हिन्दी.
- Explicación (*Kontext*) para cada pregunta.
- Vocabulario B1 subrayado, con su traducción al inglés.
- Pestaña **Fehler & Statistik**: lista de errores, gráfico de aciertos y fallos, categorías recomendadas para repasar y el vocabulario más frecuente en tus errores.
- Al terminar una ronda se muestra un informe automático.
- Modo claro y oscuro con los colores de la bandera alemana.
- El progreso se guarda en el navegador (`localStorage`) y la página funciona sin conexión después de la primera carga.
- Atajos de teclado: `1–4` / `A–D` para responder, `←` `→` para navegar.

## Fuente de datos

Las preguntas, respuestas, traducciones, explicaciones e imágenes se cargan en vivo desde el repositorio
[leben-in-deutschland/leben-in-deutschland-app](https://github.com/leben-in-deutschland/leben-in-deutschland-app)
(licencia MIT, © 2026 lebenindeutschland). Este proyecto solo **lee** esos archivos y no los modifica:

- `src/web/data/questions-core.json`: preguntas y soluciones
- `src/web/public/data/context/<idioma>.json`: explicaciones
- `src/web/public/data/translations/<idioma>.json`: traducciones
- `src/web/public/questions/<num>.webp`: imágenes

La lista de vocabulario B1 es propia de esta página.

## Estructura

```
index.html    la página completa (HTML, CSS y JavaScript en un solo archivo)
favicon.svg   icono
.nojekyll     indica a GitHub Pages que publique los archivos tal cual
```

No hace falta instalar nada ni compilar.

## Usarla en tu ordenador

Abre `index.html` en el navegador. La primera vez necesita internet para descargar las preguntas.
