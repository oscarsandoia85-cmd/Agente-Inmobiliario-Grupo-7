# Agente-Inmobiliario-Grupo-7
Proyecto académico de agente inmobiliario automatizado con n8n
# Diagrama de arquitectura

```text
                Usuario
                   │
                   │ Mensaje
                   ▼
               WhatsApp
                   │
                   ▼
            Evolution API
                   │
                   ▼
             Webhook (n8n)
                   │
                   ▼
             AI Agent (OpenAI)
                   │
        ┌──────────┼──────────┐
        │          │          │
        ▼          ▼          ▼
   Propiedades   Cercanías   Crédito
  (Base datos)   (Overpass)  (Simulación)
        │
        ▼
  Envío de Imágenes
        │
        ▼
   Registro de Leads
   (Google Sheets)
        │
        ▼
     Respuesta final
        │
        ▼
        Usuario
```
