# Bug Report — Email sin arroba es aceptado

**ID:** BR-002  
**Título:** El sistema permite un email sin símbolo @  
**Severidad:** High  
**Prioridad:** High  
**Componente:** Validación de email  
**URL probada:** https://demoqa.com/login

## Pasos para reproducir
1. Abrir el formulario de login.  
2. Ingresar: `usuario.dominio.com`  
3. Clic en "Login".

## Resultado actual
El formulario acepta el valor como válido.

## Resultado esperado
Debe mostrarse mensaje de error "Formato de email inválido".

---
