# Ruta de Navidad 2026

Itinerario familiar con votos y sugerencias. Sitio estático para GitHub Pages.

## Subirlo

Crea un repo, sube todo lo que está en esta carpeta a la raíz y en Settings > Pages elige "Deploy from a branch", rama main, carpeta / (root).

## Conectar los votos (Google Form + Sheet)

1. Crea un Google Form con dos preguntas de respuesta corta: `quien` y `voto`. En configuración, quita "Recopilar correos" y "Limitar a 1 respuesta".
2. Tres puntitos > Obtener enlace prellenado. Escribe `quien` en la primera y `voto` en la segunda, dale Obtener enlace y cópialo.
3. Pestaña Respuestas > Vincular con Hojas de cálculo.
4. En la hoja: Archivo > Compartir > Publicar en la web > la hoja de respuestas > Valores separados por comas (.csv) > Publicar. Copia ese link.
5. Pega los dos links en `config.js` y sube el cambio.

Sin esos links la página funciona igual, solo que los votos se mandan por WhatsApp.
