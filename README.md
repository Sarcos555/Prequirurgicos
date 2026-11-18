# Prequirúrgicos · Intérprete de laboratorio prequirúrgico

App web (PWA) que funciona sin conexión. Parámetros, en este orden: hemograma completo, coagulograma, glucemia, urea, creatinina, grupo y Rh, hepatograma completo, albúmina, ionograma completo, serología HIV, hepatitis B (HBsAg, anti-HBs, anti-HBc total), hepatitis C (anticuerpos), β-hCG cualitativa y TSH.

> Herramienta educativa y orientativa. No emite autorización quirúrgica ni sustituye el juicio clínico. Usar solo datos anonimizados. No guarda ni envía datos.

## Publicar
1. Crea un repositorio público (por ejemplo `Prequirurgicos`) y sube `index.html`, `manifest.webmanifest`, `sw.js` y este README.
2. Settings → Pages → Deploy from a branch → `main` / `(root)` → Save.
3. Abre la URL en Safari (iPhone) → Compartir → Añadir a pantalla de inicio.

## Ajustar
Los rangos y valores críticos están en el arreglo `P` y los textos en el objeto `T` de `index.html`. Adáptalos a los del laboratorio local.
