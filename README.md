# Mini Proyecto Fintech: Gestor de Cuentas

Este es un mini proyecto de aprendizaje de IA orientado a la simulación de una fintech. El sistema permite la gestión básica de cuentas de usuario, incluyendo creación/acceso, panel de usuario y visualización de movimientos.

## Estructura del Proyecto

- [`index.html`](proyectoIntegrador/index.html): Pantalla de inicio de sesión (login) para acceso o creación de usuario.
- [`user.html`](proyectoIntegrador/user.html): Panel principal del usuario, donde puede ver su saldo, ingresar dinero, transferir y consultar movimientos.
- (Futura) Pantalla de movimientos: Aquí se mostrarán los movimientos realizados por el usuario (aún no implementada).

## Descripción de las Pantallas

### 1. Creación/Acceso de Usuario (`index.html`)
Permite al usuario ingresar su nombre de usuario y contraseña. Si los datos son correctos, accede al panel de usuario. Actualmente, la autenticación es simulada (usuario: `admin`, contraseña: `1234`).

### 2. Panel de Usuario (`user.html`)
Muestra el nombre del usuario y el saldo disponible. Permite:
- **Ingresar Dinero:** Suma un monto al saldo.
- **Transferir Dinero:** Resta un monto del saldo si hay fondos suficientes.
- **Ver Movimientos:** (Pendiente de implementación) Mostrará el historial de transacciones.

### 3. Descripción de Movimientos
Esta funcionalidad está planificada para mostrar un historial de ingresos y transferencias realizados por el usuario.

## ¿Cómo probar el proyecto?

1. Abre [`index.html`](proyectoIntegrador/index.html) en tu navegador.
2. Ingresa el usuario `admin` y la contraseña `1234`.
3. Accede al panel de usuario para simular operaciones.
4. La funcionalidad de movimientos aún no está implementada, pero puedes ver el flujo principal de la app.

## Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript (vanilla)

## Notas

- Este proyecto es solo para fines educativos y de práctica.
- No almacena datos de manera persistente ni implementa seguridad real.
- Puedes extenderlo agregando almacenamiento local, backend o integración con IA para análisis de gastos.

---
¡Explora, aprende y mejora tu gestor de cuentas fintech!