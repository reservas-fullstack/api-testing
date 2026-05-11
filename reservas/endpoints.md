POST
http://localhost:8085/api/reservas
{
  "usuarioId": 1,
  "profesionalId": 1,
  "servicioId": 1,
  "fecha": "2026-05-11",
  "hora": "15:00:00",
  "estado": "PENDIENTE"
}

{
  "usuarioId": 2,
  "profesionalId": 2,
  "servicioId": 1,
  "fecha": "2026-05-12",
  "hora": "10:30:00",
  "estado": "CONFIRMADA"
}

{
  "usuarioId": 3,
  "profesionalId": 1,
  "servicioId": 2,
  "fecha": "2026-05-13",
  "hora": "12:00:00",
  "estado": "PENDIENTE"
}

{
  "usuarioId": 4,
  "profesionalId": 3,
  "servicioId": 2,
  "fecha": "2026-05-14",
  "hora": "17:00:00",
  "estado": "CANCELADA"
}

PUT
http://localhost:8085/api/reservas/1
{
  "usuarioId": 1,
  "profesionalId": 1,
  "servicioId": 1,
  "fecha": "2026-05-12",
  "hora": "16:00:00",
  "estado": "CONFIRMADA"
}

PUT
http://localhost:8085/api/reservas/2
{
  "usuarioId": 2,
  "profesionalId": 2,
  "servicioId": 2,
  "fecha": "2026-05-13",
  "hora": "11:30:00",
  "estado": "PENDIENTE"
}

PUT
http://localhost:8085/api/reservas/3
{
  "usuarioId": 3,
  "profesionalId": 1,
  "servicioId": 3,
  "fecha": "2026-05-14",
  "hora": "18:00:00",
  "estado": "CANCELADA"
}

PUT
http://localhost:8085/api/reservas/4
{
  "usuarioId": 4,
  "profesionalId": 3,
  "servicioId": 2,
  "fecha": "2026-05-15",
  "hora": "09:00:00",
  "estado": "CONFIRMADA"
}
