BASE URL
http://localhost:8083/api/profesionales
GET - Listar profesionales
http://localhost:8083/api/profesionales
GET por ID
http://localhost:8083/api/profesionales/1
POST - Crear profesional

{
  "nombre": "Ana Martínez",
  "especialidad": "Barbería",
  "telefono": "912345678",
  "correo": "ana@gmail.com",
  "estado": "ACTIVO"
}
{
  "nombre": "Luis Pérez",
  "especialidad": "Masajes",
  "telefono": "923456789",
  "correo": "luis@gmail.com",
  "estado": "ACTIVO"
}
{
  "nombre": "Camila Torres",
  "especialidad": "Belleza",
  "telefono": "934567890",
  "correo": "camila@gmail.com",
  "estado": "ACTIVO"
}
PUT - Actualizar profesional
http://localhost:8083/api/profesionales/1
{
  "nombre": "Ana Martínez Actualizada",
  "especialidad": "Barbería Premium",
  "telefono": "912345678",
  "correo": "ana.actualizada@gmail.com",
  "estado": "ACTIVO"
}
DELETE - Eliminar profesional
http://localhost:8083/api/profesionales/1
