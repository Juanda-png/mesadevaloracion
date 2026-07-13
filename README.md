# Mesa de Valoración · Partners Finance

Aplicación web de una sola página para valorar acciones con la metodología de Partners Finance
(value investing): múltiplos forward, FCF *owner earnings*, ROIC, despliegue de capital,
diagnóstico de los estados financieros y análisis de múltiplos por sector, a partir de datos de TIKR.

Todo corre en el navegador. No hay servidor ni base de datos: cada persona guarda sus valoraciones
localmente en su propio navegador.

---

## Publicar en GitHub Pages

1. Crea un repositorio nuevo (por ejemplo `mesa-de-valoracion`) y márcalo como **público**.
2. Sube **`index.html`** a la raíz del repositorio (y opcionalmente este `README.md`).
3. Ve a **Settings → Pages**.
4. En **Source**, elige la rama `main` y la carpeta `/ (root)`. Guarda.
5. Espera ~1 minuto. GitHub te dará la URL pública:
   `https://TU-USUARIO.github.io/mesa-de-valoracion/`
6. Comparte ese enlace. Cada persona que lo abra empieza con la mesa vacía.

Para actualizar la app en el futuro, reemplaza `index.html` en el repo; el enlace queda igual.

---

## Cómo se usa

1. **Nueva valoración** → identidad (nombre, ticker, **sector/tipo de negocio**, moneda) y pega las
   **cuatro tablas de TIKR** (en inglés): Income Statement, Balance Sheet, Cash Flow y **Valuation**.
   Con Valuation, los múltiplos de salida arrancan con la **mediana histórica** de la empresa.
2. Revisa **Fundamentales y estados financieros**: ingresos, cash flow, ratios y endeudamiento,
   despliegue de capital. Las partidas marcadas **"a proyectar"** son los supuestos que defines.
3. Revisa el **Diagnóstico**: semáforo sobre los tres estados financieros y veredicto general.
4. En **Valoración**, ajusta los supuestos (te apoyas en las **sugerencias** con promedios de 3 y 5
   años, o rellenas con las **estimaciones de analistas** de TIKR partida por partida).
5. Contrasta tus múltiplos de salida con los **rangos de referencia de su sector** y con la mediana.
6. Lee **"¿Qué te diría Juanda?"**: lectura de la valoración según los criterios de la mesa
   (precio = múltiplo × indicador).
7. Consulta el **Resumen**: precios objetivo por múltiplo y proyección.

---

## Datos y respaldo

- Las valoraciones se guardan en el **almacenamiento local del navegador**, por lo que son
  distintas en cada navegador, equipo o ubicación del archivo.
- Usa **Exportar** para descargar un `.json` con todas tus valoraciones (tu respaldo real) e
  **Importar** para recuperarlas en otro navegador o tras actualizar la app.
- Exporta con regularidad.

---

## Revalorar una empresa

Cuando quieras actualizarla con los estados de un nuevo año: entra a la empresa →
pestaña **Valoración** → panel de múltiplos → pega las tablas actualizadas de TIKR y pulsa
**Actualizar valoración**. Refresca el año base, los datos base, los múltiplos y las estimaciones,
manteniendo tu precio de entrada, tu tesis y tus ajustes.

---

## Aviso

Esta es una herramienta construida por el equipo de Partners Finance. No representa recomendación
alguna de compra o venta. Se asume que quien la utiliza es responsable de sus propias decisiones
de inversión.
