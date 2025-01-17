# PMS - 8
# Registro de Nuevos Usuarios - Caso de Prueba Positivo
# Descripción
- Validar que el sistema permita al usuario registrarse en la página con un nombres de usuario (correo electrónico) y una contraseña válidos

# Prioridad
- Alta

# Ambiente de Prueba
- Local - https://www.dinoonline.com.ar

# Responsable
- Favio Palermo

# Precondiciones
- Acceso al sitio web
- Correo electrónico válido que no haya sido registrado previamente
- Contraseña válida con al menos 8 caracteres, incluyendo mayúsculas, minúsculas y números.

# Datos de Entrada
- Usuario/Correo Electróníco: testsupermami@gmail.com
- Nombre: Anakin 
- Apellido: Skywalker
- Contraseña: Amidalapadme04

# Pasos
1. Ingresar a la URL https://www.dinoonline.com.ar/super/login
2. Hacer click en el botón 'Crear una Cuenta' 
3. Ingresar los siguientes datos:
    - Nombre: Anakin
    - Apellido: Skywalker
    - Usuario: testsupermami@gmail.com
    - Contraseña: Amidalapadme04
4. Hacer click en el botón 'Crear mi Cuenta'
5. Verificar el mensaje de confirmación de cuenta vía Correo Electrónico: "Activación de Cuenta Correcta"
6. Hacer click en el botón 'Ingresar' y verificar el acceso al sistema.

# Resultado Esperado
- El sistema muestra el mensaje: "Activación de Cuenta Correcta" y redirije a la página de inicio del usuario.

# Resultado Obtenido
- (Pendiente de prueba)

# Estado
- (Pendiente de prueba)