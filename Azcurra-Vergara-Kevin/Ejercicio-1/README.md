# Ejercicio 1 - API de Rectángulos

## Descripción

Se desarrolló una API REST utilizando ExpressJS para realizar consultas
sobre rectángulos.

La API permite obtener:

- Perímetro.
- Superficie.
- Determinar si un rectángulo también es un cuadrado.

## Modelo

Un rectángulo se representa mediante dos valores:

- `base`
- `altura`

Ambos valores deben ser números mayores que 0.

Ejemplo:

```json
{
    "base": 10,
    "altura": 5
}