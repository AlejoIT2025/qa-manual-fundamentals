# Test Cases — Árbol de Checkboxes (Jerarquía)

## TC-07 — Seleccionar checkbox padre selecciona a todos los hijos
**Given** que existe un árbol de opciones con jerarquía  
**When** el usuario marca el checkbox padre  
**Then** todos los checkbox hijos deben quedar marcados  

---

## TC-08 — Desmarcar un checkbox hijo actualiza el estado del padre
**Given** que el checkbox padre y todos los hijos están seleccionados  
**When** el usuario desmarca un checkbox hijo  
**Then** el checkbox padre debe pasar a estado “indeterminado”  

---

## TC-09 — Error — Selección del padre no marca todos los hijos
**Given** que el usuario marca el checkbox padre  
**When** solo algunos hijos cambian a seleccionado  
**Then** se debe reportar como bug  

---

## TC-10 — Error — Seleccionar todos los hijos no marca el padre
**Given** que todos los hijos están seleccionados manualmente  
**When** el padre permanece sin seleccionar  
**Then** se debe registrar como bug  

---
