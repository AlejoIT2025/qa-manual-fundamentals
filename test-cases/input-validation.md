# Test Cases — Validación de Campos (Email)

## TC-01 — Validar formato correcto de email
**Given** que el usuario está en el formulario  
**When** ingresa un email válido `usuario@dominio.com`  
**Then** el sistema debe aceptar el valor sin mostrar errores  

---

## TC-02 — Rechazar email sin símbolo @
**Given** que el usuario está en el formulario  
**When** ingresa un email sin `@` (ej: `usuario.dominio.com`)  
**Then** el sistema debe mostrar un mensaje indicando que el formato es inválido  

---

## TC-03 — Rechazar email con espacios al inicio o final
**Given** que el usuario está en el formulario  
**When** ingresa un email con espacios (ej: `"  test@mail.com  "`)  
**Then** el sistema debe limpiar o rechazar la entrada mostrando error  

---
