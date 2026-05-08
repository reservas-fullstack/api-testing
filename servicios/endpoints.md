BASE URL
http://localhost:8082/api/servicios
GET por ID
http://localhost:8082/api/servicios/1
POST - Crear servicio
{
  "nombre": "Corte de cabello",
  "descripcion": "Servicio de corte de cabello clásico",
  "precio": 12000,
  "duracionMinutos": 45,
  "categoria": "Barbería",
  "estado": "ACTIVO"
}

{
  "nombre": "Masaje relajante",
  "descripcion": "Masaje corporal de relajación",
  "precio": 25000,
  "duracionMinutos": 60,
  "categoria": "Masajes",
  "estado": "ACTIVO"
}

{
  "nombre": "Manicure básica",
  "descripcion": "Servicio de manicure tradicional",
  "precio": 10000,
  "duracionMinutos": 40,
  "categoria": "Belleza",
  "estado": "ACTIVO"
}

PUT - Actualizar servicio
{
  "nombre": "Corte de cabello premium",
  "descripcion": "Servicio de corte con lavado incluido",
  "precio": 15000,
  "duracionMinutos": 60,
  "categoria": "Barbería",
  "estado": "ACTIVO"
}

DELETE - Eliminar servicio
http://localhost:8082/api/servicios/1
