# Test Cases — Filtros de Búsqueda

## TC-04 — Filtrar registros por nombre
**Given** que el usuario está en la tabla  
**When** escribe un término existente del nombre en el buscador  
**Then** la tabla debe mostrar únicamente los registros cuyo *nombre* coincida parcial o totalmente  

---

## TC-05 — Filtrar sin distinguir mayúsculas/minúsculas
**Given** que el usuario está en la tabla  
**When** busca “carlos”  
**Then** el sistema debe mostrar resultados que contengan “Carlos”, “CARLOS”, “cArLoS”, etc.  

---

## TC-06 — Error esperado — El filtro solo busca en nombre
**Given** un registro que contiene coincidencia en apellido  
**When** el usuario filtra por ese término  
**Then** no se muestra el resultado (este comportamiento debe reportarse como bug)  

---
