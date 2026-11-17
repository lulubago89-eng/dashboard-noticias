# Actualización desde ChatGPT

Este archivo permite solicitar una actualización del dashboard desde ChatGPT mediante el conector autorizado de GitHub.

## Funcionamiento

El workflow .github/workflows/actualizar.yml se ejecuta con cambios (push) a main. Al crear o actualizar este archivo desde ChatGPT, GitHub Actions inicia la recopilación de noticias RSS, renueva noticias.json y vuelve a publicar GitHub Pages.

- Dashboard: https://lulubago89-eng.github.io/dashboard-noticias/
- Acciones: https://github.com/lulubago89-eng/dashboard-noticias/actions

Última solicitud desde tu LLM: 2026-11-17T15:10:41-06:00

La ejecución de GitHub Actions puede retrasarse o fallar por fuentes externas. Una modificación de este archivo no garantiza por sí sola el éxito del workflow: revisa la marca verde en Actions y la fecha de generated_at en noticias.json.
