# FamilyChef Backend

API proxy que conecta la app con Claude de forma segura.

## Deploy en Render

1. Sube este repo a GitHub
2. En Render: New → Web Service → conecta el repo
3. En Environment Variables agrega:
   - `ANTHROPIC_API_KEY` = tu key de Anthropic

## Endpoints

- `GET /` — health check
- `POST /api/chat` — chat con Claude
- `POST /api/analyze` — análisis de imágenes (boletas)
