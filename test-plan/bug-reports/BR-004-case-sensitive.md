# Bug Report — Filtrado es case-sensitive

**ID:** BR-004  
**Título:** El filtro distingue mayúsculas y minúsculas  
**Severidad:** Low  
**Prioridad:** Medium  
**Componente:** Filtro de búsqueda  
**URL probada:** https://demoqa.com/webtables

## Pasos para reproducir
1. Abrir la tabla.  
2. Buscar un nombre que esté en mayúscula (ej: "Carlos").  
3. Ingresar "carlos".

## Resultado actual
No se devuelve ningún resultado.

## Resultado esperado
El filtro debe ignorar mayúsculas/minúsculas (case-insensitive).

---
