# Vyntrix — MVP

Ecosistema deportivo que combina seguimiento de entrenamiento, gamificación y rankings competitivos.

## Stack tecnologico

| Tecnologia | Version | Proposito |
|------------|---------|-----------|
| Flutter | 3.x | Frontend movil (iOS / Android) |
| Dart | 3.x | Lenguaje de programacion |
| NestJS | 10.x | Backend (APIs REST) |
| Node.js | 20.x | Entorno de ejecucion |
| TypeScript | 5.x | Tipado del backend |
| PostgreSQL | 16.x | Base de datos relacional |
| JWT / OAuth | — | Autenticacion y autorizacion |
| Docker | — | Contenedores y entorno de desarrollo |
| AWS / Azure | — | Infraestructura cloud |

## Equipos de trabajo

| Grupo | Integrantes | Especialidad | Modulos |
|-------|-------------|--------------|---------|
| 01 | Gabriel | Full-Stack (coordinador) | RF-01 (Perfil), RF-06 (Estadisticas) |
| 02 | Pablo, Cristobal | Frontend (Flutter) | RF-03 (Gamificacion), RF-04 (Rankings) |
| 03 | Vicente, Gabriel | Backend (NestJS) | RF-02 (Entrenamientos), RF-05 (Retos) |
| 04 | Fernando, Gabriel | Base de Datos (PostgreSQL) | Todos los modulos |

## Modulos funcionales

- **RF-01** — Cuenta y perfil deportivo
- **RF-02** — Registro de entrenamientos
- **RF-03** — Puntos, niveles y logros
- **RF-04** — Rankings competitivos
- **RF-05** — Sistema de retos
- **RF-06** — Panel de rendimiento

## Sprints

| Sprint | Semanas | Contenido |
|--------|---------|-----------|
| 1 | 1-2 | DB: tablas, migraciones. Backend: API entrenamientos. Frontend: Home. Full-Stack: registro. |
| 2 | 3-4 | DB: consultas optimizadas. Backend: API retos y puntos. Frontend: Perfil y Ranking. Full-Stack: panel estadisticas. |
| 3 | 5-6 | Integracion frontend-backend, QA, ajustes y deploy. |

## Como empezar

1. Clona el repositorio
2. Revisa la planificacion completa en `index.html`
3. Cada equipo revisa sus modulos asignados y dependencias
4. El grupo DB entrega primero las migraciones
5. Backend construye las APIs
6. Frontend consume las APIs

## Recursos de aprendizaje

Cada tecnologia tiene su seccion de documentacion oficial y videos recomendados en el archivo `index.html`.

---

**Vyntrix** — PLAN-EQ-001 v1.0 — Basado en REQ-MVP-001
