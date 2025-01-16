# PMS - 9
# Edición de Usuarios - Caso de Prueba Negativo
# Descripción
- Validar que el sistema muestre mensajes de error al intentar editar un perfil con datos inválidos.

# Prioridad
- Alta

# Ambiente de Prueba
- Local - https://www.dinoonline.com.ar

# Responsable
- Favio Palermo

# Precondiciones
- Acceso al sitio web
- Usuario registrado en el sistema.

# Datos de Entrada
* Escenario 1:
- Usuario: testsupermami@gmail.com
- Contraseña: Amidalapadme04
- Nombre: (Vacío).
- Apellido: (Vacío).
- Correo Electrónico: (Vacío).

* Escenario 2:
- Usuario: testsupermami@gmail.com
- Contraseña: Amidalapadme04
- Nombre: 1234 (formato inválido).
- Apellido: 8756 (formato inválido).
- Correo Electrónico: jedi@gmail.py (formato inválido).

# Pasos
1. Iniciar sesión con el usuario registrado.
2. Navegar a la sección de perfil de usuario.
3. Hacer click en el botón "Editar Perfil."
4. Probar cada uno de los siguientes escenarios:
    - Escenario 1: Dejar los campos vacíos.
    - Escenario 2: Ingresar datos inválidos.
6. Hacer click en el botón "Guardar Cambios."

# Resultado Esperado
* Escenario 1:
- Mensaje de error: "Todos los campos son obligatorios."

* Escenario 2:
- Mensaje de error: "Correo electrónico no válido."

# Resultado Obtenido
- (Pendiente de prueba)

# Estado
- (Pendiente de prueba)
