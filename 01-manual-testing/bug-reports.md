# 🐞 Bug Reports

## BUG-001 — Login permite continuar sin contraseña

**Severity:** High

**Priority:** High

**Environment:**
- Browser: Chrome
- Platform: Web
- Environment: Testing

### Preconditions
- Usuario registrado.
- Página de login disponible.

### Steps to Reproduce
1. Abrir la página de login.
2. Introducir un email válido.
3. Dejar el campo contraseña vacío.
4. Pulsar "Iniciar sesión".

### Expected Result
El sistema debe impedir el inicio de sesión y mostrar un mensaje indicando que la contraseña es obligatoria.

### Actual Result
El sistema permite continuar sin introducir una contraseña.

### Status
Open
