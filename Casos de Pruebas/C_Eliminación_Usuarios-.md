# PMS - 10
# Eliminación de Usuarios - Caso de Prueba Negativo
# Descripción
- Validar que el sistema no elimine la cuenta si el usuario no confirma la acción.

# Prioridad
- Alta

# Ambiente de Prueba
- Local - https://www.dinoonline.com.ar

# Responsable
- Favio Palermo

# Precondiciones
- Usuario registrado en el sistema.

# Datos de Entrada
* Escenario 1:
- Usuario: testsupermami@gmail.com
- Contraseña: Amidalapadme04
- Confirmación: "No"

* Escenario 2:
- Usuario: testsupermami@gmail.com
- Contraseña: Amidalapadme04
- Cierre de ventana sin confirmar.

# Pasos
1. Iniciar sesión con el usuario existente.
2. Navegar a la sección de configuración de cuenta.
3. Hacer clic en el botón "Eliminar Cuenta."
4. Probar cada uno de los siguientes escenarios:
    - Escenario 1: No confirmar eliminación.
    - Escenario 2: Cerrar ventana sin confirmar eliminación.
5. Verificar que la cuenta no se elimine.

# Resultado Esperado
- Mensaje: "Acción cancelada."
- La cuenta sigue activa.

# Resultado Obtenido
- (Pendiente de prueba)

# Estado
- (Pendiente de prueba)
