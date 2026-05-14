# ISY0101 — Agente RAG para Gestión de Reclamos — Ripley Chile

Evaluación Parcial N°1 — Ingeniería de Soluciones con IA — DuocUC 2025

## Descripción
Sistema basado en LLM y RAG que automatiza la clasificación y respuesta 
de reclamos postventa de Ripley Chile, integrando políticas internas y 
la Ley 19.496 del Consumidor.

## Requisitos
- Cuenta en [Groq](https://console.groq.com) para obtener API Key gratuita
- Google Colab (no requiere instalación local)

## Cómo ejecutar
1. Abre el notebook en Google Colab:  
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Misa323/ISY0101-RAG-Ripley/blob/main/ISY0101_RAG_Ripley_GitHub.ipynb)

2. Ejecuta las celdas en orden (1 → 10)

3. En la Celda 2 ingresa tu GROQ_API_KEY cuando se solicite

## Estructura del proyecto
| Archivo | Descripción |
|---|---|
| `ISY0101_RAG_Ripley_GitHub.ipynb` | Notebook principal con pipeline completo |
| `README.md` | Este archivo |

## Stack tecnológico
- **LLM:** Llama 3.3 70B via Groq API
- **Framework:** LangChain
- **Vector Store:** FAISS (local)
- **Embeddings:** sentence-transformers/paraphrase-multilingual-MiniLM-L12-v2
- **Fuentes:** CSV, TXT (datos simulados)

## Uso de IA
Claude (Anthropic) fue usado como apoyo en diseño y depuración.
Citación: https://bibliotecas.duoc.cl/ia
