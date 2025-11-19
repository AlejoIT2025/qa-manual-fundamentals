# Bug Report — Email acepta espacios en blanco

**ID:** BR-001  
**Título:** El campo email acepta espacios al inicio o al final sin validar  
**Severidad:** Medium  
**Prioridad:** High  
**Componente:** Formulario de Login  
**URL probada:** https://demoqa.com/login

## Pasos para reproducir
1. Abrir el formulario de login.  
2. Ingresar el siguiente valor en el campo email: `"  test@mail.com  "`.  
3. Hacer clic en "Login".

## Resultado actual
El sistema acepta el valor y permite continuar.

## Resultado esperado
El sistema debe eliminar los espacios o mostrar un mensaje indicando que el email es inválido.

## Evidencia
*(Captura opcional cuando practiques)*

---
