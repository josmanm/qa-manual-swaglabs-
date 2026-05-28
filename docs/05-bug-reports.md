# Bug Report 001

## ID

BUG-001

## Título

Mensaje de validación poco claro al continuar checkout sin código postal.

## Ambiente

- Navegador: Google Chrome.
- Sistema operativo: Windows 10.
- Aplicación: Swag Labs / Sauce Demo.
- Módulo: Checkout.

## Precondición

El usuario debe estar autenticado y tener al menos un producto en el carrito.

## Pasos para reproducir

1. Iniciar sesión con un usuario válido.
2. Agregar un producto al carrito.
3. Ingresar al carrito.
4. Hacer clic en Checkout.
5. Ingresar nombre.
6. Ingresar apellido.
7. Dejar vacío el campo Zip/Postal Code.
8. Hacer clic en Continue.

## Resultado esperado

El sistema debe mostrar un mensaje claro indicando que el campo Zip/Postal Code es obligatorio.

## Resultado actual

El sistema no permite continuar, pero el mensaje mostrado no es suficientemente claro para el usuario.

## Severidad

Media.

## Prioridad

Media.

## Estado

Open.

## Evidencia

`evidence/screenshots/bug-001-checkout-zip-empty.png`