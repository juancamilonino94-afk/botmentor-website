# BotMentor — Sitio Web

Landing page de BotMentor: bots de Telegram con IA para mentores independientes
de opciones binarias en LATAM.

## Estado actual

- **Fase 1 (en curso):** landing page estática — presentación del servicio,
  cómo funciona, precios y contacto directo por Telegram.
- **Fase 2 (pendiente):** login de mentores + dashboard con estado de
  suscripción y pago. Depende de la decisión del procesador de pagos
  (Stripe / MercadoPago / Paddle) documentada en el Project de BotMentor.

## Stack

- HTML / CSS / JS vanilla, un solo archivo (`index.html`).
- Sin build step por ahora — se sirve tal cual.
- Cuando arranque la Fase 2 (login + dashboard), esto migra a Next.js para
  aprovechar las funciones de servidor de Vercel.

## Desarrollo local

Solo abre `index.html` en el navegador. No requiere instalar nada.

## Deploy

- **Hosting:** Vercel — plan **Pro** (uso comercial, no calificamos para Hobby).
- **Dominio:** registrado en Cloudflare, DNS apuntando a Vercel
  (registro `A` + `CNAME` para `www`).
- Cada `git push` a `main` dispara un deploy automático en Vercel.

## Marca

Paleta, tipografías y logo (carita de robot) siguen el Manual de Marca de
BotMentor. Colores base:

| Uso | Color |
|---|---|
| Fondo principal | `#1E0E3F` (violeta noche) |
| Acento / CTA | `#FF6B35` (naranja fuego) |
| Secundario | `#7C3AED` (violeta medio) |
| Fondo claro | `#F5F3FF` (lavanda suave) |

Tipografías: Space Grotesk (títulos), Inter (cuerpo y UI).

## Contacto de soporte

Telegram: [@botmentorsupport](https://t.me/botmentorsupport)
