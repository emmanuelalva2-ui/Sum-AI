# SUM AI V1 — Sandbox

Prototipo standalone para probar el agente de atención a clientes de Grupo SUM.

## Estado
- Sandbox independiente
- Datos 100% ficticios
- Sin conexión al ERP real
- Sin conexión a WhatsApp
- Sin API/LLM externo todavía

## Probar localmente
No requiere instalación.

Opción 1: abre `index.html` directamente en un navegador.

Opción 2 (recomendada):
```bash
python3 -m http.server 8080
```
Después abre `http://localhost:8080`.

## Publicar
Al ser una web estática, el repositorio se puede publicar directamente con GitHub Pages, Netlify, Cloudflare Pages o Vercel.

## Alcance V1
Incluye laboratorio conversacional, memoria local, simulador de clientes/pagos/inscripciones/cotizaciones, guardrails, privacidad, escalamiento humano, trazabilidad, métricas, feedback humano y QA.
