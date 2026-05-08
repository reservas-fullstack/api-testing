# Usuarios Service

## BASE URL
http://localhost:8081/api/usuarios

POST - Crear usuario
{
  "nombre": "Carlos Rojas",
  "correo": "carlos@gmail.com",
  "password": "123456",
  "rol": "CLIENTE",
  "telefono": "912345678",
  "estado": "ACTIVO",
  "fechaRegistro": "2026-05-07"
}

{
  "nombre": "María Soto",
  "correo": "maria@gmail.com",
  "password": "123456",
  "rol": "ADMIN",
  "telefono": "987654321",
  "estado": "ACTIVO",
  "fechaRegistro": "2026-05-07"
}

{
  "nombre": "Pedro González",
  "correo": "pedro@gmail.com",
  "password": "123456",
  "rol": "CLIENTE",
  "telefono": "956321478",
  "estado": "ACTIVO",
  "fechaRegistro": "2026-05-08"
}

{
  "nombre": "Camila Herrera",
  "correo": "camila@gmail.com",
  "password": "123456",
  "rol": "OPERADOR",
  "telefono": "912112233",
  "estado": "INACTIVO",
  "fechaRegistro": "2026-05-08"
}

{
  "nombre": "Diego Morales",
  "correo": "diego@gmail.com",
  "password": "123456",
  "rol": "CLIENTE",
  "telefono": "923456789",
  "estado": "ACTIVO",
  "fechaRegistro": "2026-05-09"
}

{
  "nombre": "Valentina Ríos",
  "correo": "valentina@gmail.com",
  "password": "123456",
  "rol": "ADMIN",
  "telefono": "934567891",
  "estado": "ACTIVO",
  "fechaRegistro": "2026-05-09"
}

PUT - Actualizar usuario
http://localhost:8081/api/usuarios/1
{
  "nombre": "Carlos Actualizado",
  "correo": "carlos2@gmail.com",
  "password": "123456",
  "rol": "ADMIN",
  "telefono": "999999999",
  "estado": "ACTIVO",
  "fechaRegistro": "2026-05-07"
}
DELETE - Eliminar usuario
http://localhost:8081/api/usuarios/1
