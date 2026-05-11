POST
http://localhost:8084/api/horarios
{
  "profesionalId": 1,
  "fecha": "2026-05-11",
  "horaInicio": "09:00:00",
  "horaFin": "10:00:00",
  "estado": "DISPONIBLE"
}

{
  "profesionalId": 2,
  "fecha": "2026-05-11",
  "horaInicio": "10:00:00",
  "horaFin": "11:00:00",
  "estado": "DISPONIBLE"
}

{
  "profesionalId": 3,
  "fecha": "2026-05-12",
  "horaInicio": "14:00:00",
  "horaFin": "15:00:00",
  "estado": "OCUPADO"
}

{
  "profesionalId": 1,
  "fecha": "2026-05-13",
  "horaInicio": "16:00:00",
  "horaFin": "17:00:00",
  "estado": "CANCELADO"
}

PUT
http://localhost:8084/api/horarios/1
{
  "profesionalId": 1,
  "fecha": "2026-05-12",
  "horaInicio": "11:00:00",
  "horaFin": "12:00:00",
  "estado": "OCUPADO"
}

PUT
http://localhost:8084/api/horarios/2
{
  "profesionalId": 2,
  "fecha": "2026-05-13",
  "horaInicio": "09:30:00",
  "horaFin": "10:30:00",
  "estado": "DISPONIBLE"
}

PUT
http://localhost:8084/api/horarios/3
{
  "profesionalId": 3,
  "fecha": "2026-05-14",
  "horaInicio": "15:00:00",
  "horaFin": "16:00:00",
  "estado": "CANCELADO"
}
