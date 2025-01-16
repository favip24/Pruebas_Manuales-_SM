# PMS - 8
# Registro de Nuevos Usuarios - Caso de Prueba Negativo
# Descripción
- Validar que el sistema muestre mensajes de error y no permita el registro cuando se intente ingresar con datos inválidos, incompletos o no correspondiente .

# Prioridad
- Alta

# Ambiente de Prueba
- Local - https://www.dinoonline.com.ar

# Responsable
- Favio Palermo

# Precondiciones
1. Acceso al sitio web.
2. Correo electrónico inválido o ya registrado.
3. Contraseña que no cumpla con los requisitos establecidos.

# Datos de Entrada
* Escenario 1:
- Correo Electrónico: testsupermami (sin @ ni dominio válido).
- Nombre: Anakin.
- Apellido: Skywalker.
- Contraseña: padme (menos de 8 caracteres y sin números).

* Escenario 2:
- Correo Electrónico: testsupermami@gmail.com (ya registrado).
- Nombre: Anakin.
- Apellido: Skywalker.
- Contraseña: amidalapadme04 (válida).

* Escenario 3:
- Campos vacíos para todos los datos.

# Pasos
1. Ingresar a la URL: https://www.dinoonline.com.ar/super/login.
2. Hacer click en el botón 'Crear una Cuenta'.
3. Probar cada uno de los siguientes escenarios:
   - Escenario 1: Ingresar un correo electrónico inválido y una contraseña no válida, dejando los demás campos en blanco.
   - Escenario 2: Ingresar un correo electrónico ya registrado.
   - Escenario 3: Dejar todos los campos vacíos.
4. Hacer click en el botón 'Crear mi Cuenta' tras cada escenario.
5. Verificar los mensajes de error correspondientes.

# Resultado Esperado
* Escenario 1:
- Mostrar un mensaje de error: "Correo electrónico inválido" y "La contraseña debe tener al menos 8 caracteres, incluyendo una mayúscula, una minúscula y un número."

* Escenario 2:
- Mostrar un mensaje de error: "El correo electrónico ya está registrado."

* Escenario 3:
- Mostrar un mensaje de error: "Todos los campos son obligatorios."

# Resultado Obtenido
- (Pendiente de prueba)

# Estado
- (Pendiente de prueba)