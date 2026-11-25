# Reglas del repositorio

- Sitio de una sola página: `index.html`. Sin PDF ni sección de descargas (decisión del 25/11/2026); no agregarlos.
- Los datos están embebidos en `index.html`: `const COS` (empresas), `const INV` (inversiones), `PROV`, `GEO`, `GEOP`. El mapa se arma solo con esos JSON, pero las tablas y textos del informe (secciones 01 a 08, niveles Resumido, Extendido y Completo) están en HTML estático: cada cambio de dato se lleva también ahí. Editar con scripts, sin reescribir lo que no cambia.
- Flujo: primero maqueta, después aprobación de Franco; solo se hace push a `main` cuando él dice «publica». El artifact de claude.ai (https://claude.ai/artifact/NpTGHv5NzeuL3sUb3tov3k) y este repositorio se publican juntos y quedan iguales.
- Estilo: español rioplatense sin voseo, formal pero accesible, sin opinión ni confrontación, sin nombrar personas. Lo no verificado va con ⚠. Nunca inventar URLs ni cifras.
- Estado y pendientes: documento claude/version-b-empresas-inversiones.md del proyecto «Propuestas Argentina» en claude.ai.
