<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,30:8B5CF6,60:3B82F6,80:F59E0B,100:06B6D4&height=220&section=header&text=VYNTRIX%20MVP&fontSize=48&fontColor=8B5CF6&animation=fadeIn&fontAlignY=35&desc=ECOSISTEMA%20DEPORTIVO%20%E2%80%A2%20GAMIFICACION%20%E2%80%A2%20RANKINGS%20COMPETITIVOS&descSize=14&descAlignY=55&descAlign=center" width="100%" />

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&duration=3000&pause=1000&color=8B5CF6&center=true&vCenter=true&multiline=true&repeat=true&width=600&height=100&lines=Seguimiento+de+entrenamiento;Gamificaci%C3%B3n+y+logros;Rankings+competitivos+en+tiempo+real" alt="Typing SVG" />

<br/>

<img src="https://img.shields.io/badge/Estado-Planificaci%C3%B3n-8B5CF6?style=for-the-badge&logo=rocket&logoColor=white" />
<img src="https://img.shields.io/badge/Version-1.0-3B82F6?style=for-the-badge&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/PLAN--EQ--001-F59E0B?style=for-the-badge&logo=databricks&logoColor=black" />
<img src="https://img.shields.io/badge/REQ--MVP--001-06B6D4?style=for-the-badge&logo=markdown&logoColor=white" />

</div>

<br/>

---

## Sobre Vyntrix

> [!IMPORTANT]
> Plataforma deportiva que combina **seguimiento de entrenamiento**, **gamificación** y **rankings competitivos** para llevar tu rendimiento al siguiente nivel.

Vyntrix permite a los deportistas registrar sus entrenamientos, ganar puntos y niveles, competir en rankings y enfrentarse a retos. Todo en una experiencia móvil fluida construida con **Flutter** y potenciada por **NestJS** sobre **PostgreSQL**.

<div align="center">

<img src="https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white" />
<img src="https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white" />
<img src="https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white" />
<img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=black" />

</div>

<br/>

---

## Stack Tecnológico

<div align="center">

| | | | | | | | |
|---|---|---|---|---|---|---|---|
| <img src="https://skillicons.dev/icons?i=flutter" width="48" /><br/>Flutter | <img src="https://skillicons.dev/icons?i=dart" width="48" /><br/>Dart | <img src="https://skillicons.dev/icons?i=nestjs" width="48" /><br/>NestJS | <img src="https://skillicons.dev/icons?i=nodejs" width="48" /><br/>Node.js | <img src="https://skillicons.dev/icons?i=ts" width="48" /><br/>TypeScript | <img src="https://skillicons.dev/icons?i=postgres" width="48" /><br/>PostgreSQL | <img src="https://skillicons.dev/icons?i=docker" width="48" /><br/>Docker | <img src="https://skillicons.dev/icons?i=aws" width="48" /><br/>AWS/Azure |

</div>

<br/>

---

## Arquitectura

```mermaid
flowchart LR
    subgraph Frontend["Frontend Móvil"]
        FL[Flutter]
    end
    subgraph Backend["Backend API"]
        NJ[NestJS]
        JW[JWT / OAuth2]
    end
    subgraph Datos["Base de Datos"]
        PG[(PostgreSQL)]
    end
    FL -->|HTTP REST| NJ
    NJ -->|TypeORM| PG
    NJ --> JW
    FL -.->|"Token"| JW
```

<br/>

---

## Equipos de Trabajo

<div align="center">

<table>
  <tr>
    <td width="25%" style="background: linear-gradient(135deg, #1a1a2e 0%, #16213e 100%); border-radius: 16px; padding: 20px; border: 2px solid #8B5CF6;">
      <div align="center">
        <img src="https://img.shields.io/badge/01-8B5CF6?style=for-the-badge&logo=fire&logoColor=white" />
        <br/><br/>
        <img src="https://img.shields.io/badge/Gabriel-8B5CF6?style=flat&logo=github&logoColor=white" />
        <br/>
        <sub>Full‑Stack · Coordinador</sub>
        <br/><br/>
        <img src="https://img.shields.io/badge/RF--01_%7C_RF--06-3B82F6?style=flat" />
        <br/>
        <sub>Perfil · Estadísticas</sub>
      </div>
    </td>
    <td width="25%" style="background: linear-gradient(135deg, #1a1a2e 0%, #16213e 100%); border-radius: 16px; padding: 20px; border: 2px solid #3B82F6;">
      <div align="center">
        <img src="https://img.shields.io/badge/02-3B82F6?style=for-the-badge&logo=users&logoColor=white" />
        <br/><br/>
        <img src="https://img.shields.io/badge/Pablo_%C2%B7_Crist%C3%B3bal-3B82F6?style=flat&logo=flutter&logoColor=white" />
        <br/>
        <sub>Frontend Flutter</sub>
        <br/><br/>
        <img src="https://img.shields.io/badge/RF--03_%7C_RF--04-F59E0B?style=flat" />
        <br/>
        <sub>Gamificación · Rankings</sub>
      </div>
    </td>
    <td width="25%" style="background: linear-gradient(135deg, #1a1a2e 0%, #16213e 100%); border-radius: 16px; padding: 20px; border: 2px solid #F59E0B;">
      <div align="center">
        <img src="https://img.shields.io/badge/03-F59E0B?style=for-the-badge&logo=nestjs&logoColor=white" />
        <br/><br/>
        <img src="https://img.shields.io/badge/Vicente_%C2%B7_Gabriel-F59E0B?style=flat&logo=nestjs&logoColor=white" />
        <br/>
        <sub>Backend NestJS</sub>
        <br/><br/>
        <img src="https://img.shields.io/badge/RF--02_%7C_RF--05-06B6D4?style=flat" />
        <br/>
        <sub>Entrenamientos · Retos</sub>
      </div>
    </td>
    <td width="25%" style="background: linear-gradient(135deg, #1a1a2e 0%, #16213e 100%); border-radius: 16px; padding: 20px; border: 2px solid #06B6D4;">
      <div align="center">
        <img src="https://img.shields.io/badge/04-06B6D4?style=for-the-badge&logo=postgresql&logoColor=white" />
        <br/><br/>
        <img src="https://img.shields.io/badge/Fernando_%C2%B7_Gabriel-06B6D4?style=flat&logo=postgresql&logoColor=white" />
        <br/>
        <sub>Base de Datos</sub>
        <br/><br/>
        <img src="https://img.shields.io/badge/ALL--RF-22C55E?style=flat" />
        <br/>
        <sub>PostgreSQL</sub>
      </div>
    </td>
  </tr>
</table>

</div>

<br/>

---

## Módulos Funcionales

<div align="center">

<table>
  <tr>
    <td width="10%" align="center"><img src="https://img.shields.io/badge/RF--01-8B5CF6?style=for-the-badge&logo=key&logoColor=white" /></td>
    <td width="25%"><b>Cuenta y Perfil Deportivo</b></td>
    <td width="65%">Registro, autenticación JWT/OAuth y perfil deportivo del usuario</td>
  </tr>
  <tr>
    <td align="center"><img src="https://img.shields.io/badge/RF--02-3B82F6?style=for-the-badge&logo=strava&logoColor=white" /></td>
    <td><b>Registro de Entrenamientos</b></td>
    <td>Creación, edición y consulta de sesiones con tipo, duración e intensidad</td>
  </tr>
  <tr>
    <td align="center"><img src="https://img.shields.io/badge/RF--03-F59E0B?style=for-the-badge&logo=levelsdotfyi&logoColor=white" /></td>
    <td><b>Puntos, Niveles y Logros</b></td>
    <td>Sistema de gamificación que recompensa la consistencia y el rendimiento</td>
  </tr>
  <tr>
    <td align="center"><img src="https://img.shields.io/badge/RF--04-06B6D4?style=for-the-badge&logo=leaderprice&logoColor=white" /></td>
    <td><b>Rankings Competitivos</b></td>
    <td>Tablas de clasificación semanales, mensuales y globales</td>
  </tr>
  <tr>
    <td align="center"><img src="https://img.shields.io/badge/RF--05-22C55E?style=for-the-badge&logo=target&logoColor=white" /></td>
    <td><b>Sistema de Retos</b></td>
    <td>Desafíos entre usuarios con objetivos y recompensas</td>
  </tr>
  <tr>
    <td align="center"><img src="https://img.shields.io/badge/RF--06-EF4444?style=for-the-badge&logo=chartbar&logoColor=white" /></td>
    <td><b>Panel de Rendimiento</b></td>
    <td>Dashboard con estadísticas, gráficos y evolución del deportista</td>
  </tr>
</table>

</div>

<br/>

---

## Dependencias entre Módulos

```mermaid
flowchart TD
    DB[(Migraciones DB)] --> RF01[RF-01 Auth / Perfil]
    RF01 --> RF02[RF-02 Entrenamientos]
    RF02 --> RF03[RF-03 Puntos / Niveles]
    RF01 --> RF04[RF-04 Rankings]
    RF02 --> RF04
    RF03 --> RF04
    RF01 --> RF05[RF-05 Retos]
    RF02 --> RF05
    RF02 --> RF06[RF-06 Estadísticas]
    RF03 --> RF06
```

<br/>

---

## Hoja de Ruta

<div align="center">

<table>
  <tr>
    <td width="33%" style="background: linear-gradient(135deg, #1a1a2e 0%, #16213e 100%); border-radius: 16px; padding: 20px; border: 2px solid #8B5CF6;" valign="top">
      <div align="center">
        <img src="https://img.shields.io/badge/Sprint_1-Fundaci%C3%B3n-8B5CF6?style=for-the-badge" />
        <br/>
        <img src="https://img.shields.io/badge/Semanas_1--2-3B82F6?style=flat" />
        <br/><br/>
        :white_check_mark: Esquema DB y migraciones<br/>
        :hourglass: API REST entrenamientos<br/>
        :hourglass: Pantalla Home Flutter<br/>
        :hourglass: Registro y autenticación<br/>
      </div>
    </td>
    <td width="33%" style="background: linear-gradient(135deg, #1a1a2e 0%, #16213e 100%); border-radius: 16px; padding: 20px; border: 2px solid #F59E0B;" valign="top">
      <div align="center">
        <img src="https://img.shields.io/badge/Sprint_2-Gamificaci%C3%B3n-F59E0B?style=for-the-badge" />
        <br/>
        <img src="https://img.shields.io/badge/Semanas_3--4-06B6D4?style=flat" />
        <br/><br/>
        :hourglass: API retos y sistema de puntos<br/>
        :hourglass: Perfil de usuario y rankings<br/>
        :hourglass: Panel de estadísticas<br/>
        :hourglass: Consultas optimizadas<br/>
      </div>
    </td>
    <td width="33%" style="background: linear-gradient(135deg, #1a1a2e 0%, #16213e 100%); border-radius: 16px; padding: 20px; border: 2px solid #06B6D4;" valign="top">
      <div align="center">
        <img src="https://img.shields.io/badge/Sprint_3-Integraci%C3%B3n-06B6D4?style=for-the-badge" />
        <br/>
        <img src="https://img.shields.io/badge/Semanas_5--6-22C55E?style=flat" />
        <br/><br/>
        :hourglass: Integración front‑back<br/>
        :hourglass: QA y pruebas de usuario<br/>
        :hourglass: Ajustes finales<br/>
        :hourglass: Despliegue<br/>
      </div>
    </td>
  </tr>
</table>

</div>

<br/>

---

## Onboarding y Flujo de Trabajo

<div align="center">

<table>
  <tr>
    <td width="50%" style="background: linear-gradient(135deg, #1a1a2e 0%, #16213e 100%); border-radius: 16px; padding: 24px; border: 2px solid #8B5CF6;">
      <div align="center">
        <img src="https://img.shields.io/badge/GitHub_Flow-8B5CF6?style=for-the-badge&logo=github&logoColor=white" />
        <br/><br/>
        <sub>Guía completa de uso con terminal y GitHub Desktop</sub>
        <br/><br/>
        <a href="GITHUB_FLOW.md">
          <img src="https://img.shields.io/badge/Ver_Gu%C3%ADa-8B5CF6?style=flat&logo=readthedocs&logoColor=white" />
        </a>
      </div>
    </td>
    <td width="50%" style="background: linear-gradient(135deg, #1a1a2e 0%, #16213e 100%); border-radius: 16px; padding: 24px; border: 2px solid #F59E0B;">
      <div align="center">
        <img src="https://img.shields.io/badge/Onboarding_T%C3%A9cnico-F59E0B?style=for-the-badge&logo=readthedocs&logoColor=black" />
        <br/><br/>
        <sub>Plan de incorporación full‑stack: PostgreSQL, React, NestJS y patrones</sub>
        <br/><br/>
        <a href="ONBOARDING.md">
          <img src="https://img.shields.io/badge/Ver_Plan-F59E0B?style=flat&logo=bookstack&logoColor=black" />
        </a>
      </div>
    </td>
  </tr>
</table>

</div>

<br/>

---

## Recursos Tecnológicos

<div align="center">

<table>
  <tr>
    <td align="center" style="background: rgba(139, 92, 246, 0.1); border: 1px solid #8B5CF6; border-radius: 12px; padding: 16px; width: 50%;">
      <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
      <br/><br/>
      <a href="https://docs.flutter.dev/"><img src="https://img.shields.io/badge/Docs-8B5CF6?style=flat&logo=bookstack&logoColor=white" /></a>
      <a href="https://www.youtube.com/watch?v=1ukSR1GRtMU&list=PL4cUxeGkcC9jLYyp2Aoh6hcWuxFDX6PBJ"><img src="https://img.shields.io/badge/Curso-FF0000?style=flat&logo=youtube&logoColor=white" /></a>
    </td>
    <td align="center" style="background: rgba(59, 130, 246, 0.1); border: 1px solid #3B82F6; border-radius: 12px; padding: 16px; width: 50%;">
      <img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" />
      <br/><br/>
      <a href="https://docs.nestjs.com/"><img src="https://img.shields.io/badge/Docs-3B82F6?style=flat&logo=bookstack&logoColor=white" /></a>
      <a href="https://www.youtube.com/watch?v=0M1Hv1m7s9M"><img src="https://img.shields.io/badge/Curso-FF0000?style=flat&logo=youtube&logoColor=white" /></a>
    </td>
  </tr>
  <tr>
    <td align="center" style="background: rgba(245, 158, 11, 0.1); border: 1px solid #F59E0B; border-radius: 12px; padding: 16px;">
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
      <br/><br/>
      <a href="https://www.postgresql.org/docs/"><img src="https://img.shields.io/badge/Docs-F59E0B?style=flat&logo=bookstack&logoColor=black" /></a>
      <a href="https://www.youtube.com/watch?v=85pG_pDkITY"><img src="https://img.shields.io/badge/Curso-FF0000?style=flat&logo=youtube&logoColor=white" /></a>
    </td>
    <td align="center" style="background: rgba(6, 182, 212, 0.1); border: 1px solid #06B6D4; border-radius: 12px; padding: 16px;">
      <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
      <br/><br/>
      <a href="https://docs.docker.com/"><img src="https://img.shields.io/badge/Docs-06B6D4?style=flat&logo=bookstack&logoColor=white" /></a>
      <a href="https://www.youtube.com/watch?v=3c_iOE5w0hM"><img src="https://img.shields.io/badge/Curso-FF0000?style=flat&logo=youtube&logoColor=white" /></a>
    </td>
  </tr>
  <tr>
    <td align="center" style="background: rgba(239, 68, 68, 0.1); border: 1px solid #EF4444; border-radius: 12px; padding: 16px;" colspan="2">
      <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
      <br/><br/>
      <a href="https://nodejs.org/en/docs/"><img src="https://img.shields.io/badge/Docs_Node-339933?style=flat&logo=bookstack&logoColor=white" /></a>
      <a href="https://www.typescriptlang.org/docs/"><img src="https://img.shields.io/badge/Docs_TS-3178C6?style=flat&logo=bookstack&logoColor=white" /></a>
      <a href="https://react.dev/learn"><img src="https://img.shields.io/badge/Docs_React-61DAFB?style=flat&logo=react&logoColor=black" /></a>
    </td>
  </tr>
</table>

</div>

<br/>

---

## Guías del Repositorio

| Guía | Descripción |
|------|-------------|
| [`GITHUB_FLOW.md`](GITHUB_FLOW.md) | Flujo de trabajo con ramas, PRs y despliegue continuo |
| [`ONBOARDING.md`](ONBOARDING.md) | Plan de incorporación técnica full-stack |

<br/>

---

## Contacto

<div align="center">

<table>
  <tr>
    <td style="background: linear-gradient(135deg, #8B5CF6 0%, #3B82F6 100%); border-radius: 16px; padding: 24px;">
      <table>
        <tr>
          <td align="center" style="padding: 10px 20px;">
            <a href="https://linkedin.com/in/gabriel-pedreros-995935364">
              <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
              <br/>
              <sub style="color: white;">Gabriel Pedreros</sub>
            </a>
          </td>
          <td align="center" style="padding: 10px 20px;">
            <a href="mailto:gabriel.pedreros.dev@gmail.com">
              <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
              <br/>
              <sub style="color: white;">Contáctame</sub>
            </a>
          </td>
          <td align="center" style="padding: 10px 20px;">
            <a href="https://gpb-portfolio.pages.dev/">
              <img src="https://img.shields.io/badge/Portfolio-8B5CF6?style=for-the-badge&logo=googlechrome&logoColor=white" />
              <br/>
              <sub style="color: white;">Proyectos</sub>
            </a>
          </td>
          <td align="center" style="padding: 10px 20px;">
            <a href="https://github.com/gpb-codes/Vyntrix">
              <img src="https://img.shields.io/badge/Repo-181717?style=for-the-badge&logo=github&logoColor=white" />
              <br/>
              <sub style="color: white;">Vyntrix</sub>
            </a>
          </td>
        </tr>
      </table>
    </td>
  </tr>
</table>

</div>

<br/>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,25:8B5CF6,50:3B82F6,75:F59E0B,100:06B6D4&height=100&section=footer" width="100%" />

<br/>

<sub><b>v1.0</b> · Basado en REQ-MVP-001 · Julio 2026</sub>
<br/>
<sub>
<img src="https://img.shields.io/badge/GITHUB_FLOW-181717?style=flat&logo=github&logoColor=white" />
·
<a href="GITHUB_FLOW.md">Ver guía</a>
</sub>

</div>
