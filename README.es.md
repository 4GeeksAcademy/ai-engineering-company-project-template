# Proyecto de Ingeniería de IA — Plantilla para estudiantes

[![4Geeks Academy](https://img.shields.io/badge/4Geeks-Academy-blue)](https://4geeksacademy.com)
[![AI Engineering](https://img.shields.io/badge/track-AI%20Engineering-green)](https://4geeksacademy.com/es/programas-de-carrera/ingenieria-ia)

_Plantilla base para proyectos transversales del Programa de Carrera en Ingeniería de IA — 4Geeks Academy._

_Las instrucciones están [disponibles en inglés](./README.md)._

---

## Propósito

Este repositorio es la **plantilla de inicio** para los proyectos transversales. Trabajarás con escenarios de empresas reales (Brasaland, TrackFlow, Nexova) construyendo entregables que se corresponden con los hitos del curso (Web, Programación, Backend, Telemetría, RAG, Agentes, Workflows, Tiempo real).

- **Crea una plantilla** a partir de este repo (no clones el repositorio específico del hito).
- Lee tu archivo **CONTEXT** de la empresa asignada — define datos de dominio, campos y restricciones.
- Usa la carpeta **skills/** para que los agentes de IA te asistan de forma coherente.

---

## Estructura del repositorio

```text
ai-engineering-project-template/
├── README.es.md              # Este archivo
├── AGENTS.md                 # Índice para agentes de IA: qué skills existen y cuándo usarlas (lo añadirás en el futuro)
├── CONTEXT.md                # Contexto de tu empresa (Brasaland | TrackFlow | Nexova) — añadir tras la asignación
├── apps/                     # Tus aplicaciones (web, API, dashboards)
├── packages/
│   └── shared-types/         # Tipos TypeScript/JSON compartidos entre apps
├── pipelines/
│   └── data/                 # ETL, ingesta o configs/scripts de pipelines de datos
└── skills/                   # Skills de agentes (SKILL.md + ejemplos, scripts, plantillas opcionales)
    ├── research/
    ├── data-analysis/
    ├── web-scraping/
    ├── code-review/
    └── math-reasoning/
```

---

## Cómo empezar

1. Haz **fork** de este repositorio a tu cuenta de GitHub.
2. **Clona** tu fork (o ábrelo en GitHub Codespaces).
3. **Añade tu CONTEXT**: copia el `CONTEXT-<empresa>.md` de tu empresa asignada en la raíz como `CONTEXT.md`.
4. **Lee** `AGENTS.md` para saber qué skills tienes disponibles al trabajar con IA.
5. **Construye** los entregables de cada hito dentro de `apps/`, reutilizando `packages/shared-types` y `pipelines/data` cuando convenga.

---

## Hitos (referencia)

| Hito | Enfoque       | Entregables típicos                              |
| ---- | ------------- | ------------------------------------------------ |
| 0    | Prework       | Configuración del entorno, primeros prompts      |
| 1    | Web           | Sitio corporativo, formularios, SEO              |
| 2    | Programación  | Lógica de negocio, puntuación, cálculos          |
| 3    | UI con IA     | Interfaces generadas con IA                      |
| 4    | Next.js       | Portales, app de fidelización, UI de operaciones |
| 5    | Backend       | API central (ubicaciones, menús, ventas, etc.)   |
| 6    | Telemetría    | Pipeline de datos, dashboards                    |
| 7    | RAG y memoria | Base de conocimiento semántica, búsqueda         |
| 8    | Agentes       | Agentes de soporte, onboarding, formación        |
| 9    | Workflows     | Automatizaciones con n8n                         |
| 10   | Tiempo real   | Dashboards en vivo, alertas, streaming           |

---

## Enlaces

- [4Geeks Academy — Ingeniería de IA](https://4geeksacademy.com/es/programas-de-carrera/ingenieria-ia)
- [Cómo empezar un proyecto de código](https://4geeks.com/lesson/how-to-start-a-coding-project)

---

## Contribuidores

Esta plantilla fue creada como parte del Programa de Carrera de Ingeniería de IA de 4Geeks Academy por [@marcogonzalo](https://www.linkedin.com/in/marcogonzalo) y [@alezanchezr](https://x.com/alesanchezr), junto a otros muchos colaboradores. Descubre más sobre nuestro [Curso de Ingeniería de IA](https://4geeksacademy.com/es/programas-de-carrera/ingenieria-ia) y sobre [otros cursos](https://4geeksacademy.com/compare-programs).

Puedes encontrar otras plantillas y recursos similares en la [página de GitHub de 4Geeks Academy](https://github.com/4geeksacademy).

_Esta plantilla la mantiene 4Geeks Academy para el track de Ingeniería de IA. Uso exclusivo del programa._
