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

BUG-001 — Compra permitida con carrito vacío

Prioridad: Media
Severidad: Media
Estado: Reproducido

Entorno

- Aplicación: DemoBlaze
- Fecha: 02/09/2026
- Navegador: [Chrome]

Pasos para reproducir

1. Entrar en DemoBlaze.
2. Ir a "Cart" sin productos.
3. Pulsar "Place Order".
4. Completar el formulario con datos de prueba.
5. Pulsar "Purchase".

Resultado esperado

El sistema debería impedir la compra y mostrar un mensaje indicando que el carrito está vacío.

Resultado obtenido

El sistema permite completar la compra y muestra "Purchase successful" con un total de 0.

Evidencia

Se verificó el comportamiento realizando nuevamente los pasos anteriores y el resultado se reprodujo.
