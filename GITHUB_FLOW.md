# GitHub Flow — Guía de uso

## ¿Qué es GitHub Flow?

Flujo de trabajo basado en ramas ligeras. Un solo branch principal (`main`) y ramas temporales para cada funcionalidad o fix.

```
main ──●──────────●──────────●────────
         \        /          /
          ●──●──●           /
fix/login  \       \       /
             ●──●──●──●──●
feature/rankings
```

---

## Reglas base

- Todo cambio parte de una rama nueva creada desde `main`
- La rama efímera se elimina después de mergear
- Nunca se hace commit directo a `main`
- Todo cambio entra vía Pull Request revisado

---

## 1. Desde la terminal

### 1.1 Sincronizar `main`

```bash
git checkout main
git pull origin main
```

### 1.2 Crear rama de trabajo

```bash
git checkout -b fix/login-error
```

Convención de nombres:
- `feature/descripcion` — nueva funcionalidad
- `fix/descripcion` — corrección de bug
- `refactor/descripcion` — refactorización
- `docs/descripcion` — documentación
- `chore/descripcion` — tareas de mantenimiento

### 1.3 Hacer cambios y commitear

```bash
git add archivo.modificado.ts
git commit -m "fix: corrige validación de email en login"
```

Estructura del mensaje:
```
<tipo>: <descripción imperativa>
```
Ejemplos: `feat: agrega ranking semanal`, `fix: corrige error 500 en entrenamientos`.

### 1.4 Publicar rama

```bash
git push origin fix/login-error
```

### 1.5 Crear Pull Request desde GitHub

- Ve al repo → pestaña **Pull Requests** → **New PR**
- Base: `main` ← Compare: `fix/login-error`
- Título descriptivo. Cuerpo incluye: qué hace, por qué, cómo se probó.
- Asigna reviewer si aplica.

### 1.6 Revisar y mergear

- Se revisa el código
- Se resuelven comentarios
- Se mergea (preferir **Squash and merge** para mantener historial limpio)

### 1.7 Limpiar rama local

```bash
git checkout main
git pull origin main
git branch -d fix/login-error
```

---

## 2. Desde GitHub Desktop

### 2.1 Sincronizar

- Abre GitHub Desktop
- Dale a **Fetch origin** para traer cambios
- Cambia a `main` y haz **Pull**

### 2.2 Crear rama

- **Branch** → **New Branch**
- Nombre: `feature/rankings`
- Base: `main` (por defecto)

### 2.3 Commitear cambios

- Editas archivos en tu editor
- GitHub Desktop muestra los cambios
- Abajo escribe **Summary** y **Description**
- Dale a **Commit to feature/rankings**

### 2.4 Publicar y abrir PR

- **Publish branch**
- **Branch** → **Create Pull Request** (abre el navegador)
- Completa título y descripción
- Envía el PR

### 2.5 Después del merge

- **Branch** → **Switch to main**
- **Repository** → **Pull**
- **Branch** → **Delete...** (seleccionas la rama mergeada)

---

## Resumen rápido

| Paso | Terminal | GitHub Desktop |
|------|----------|----------------|
| 1 | `git pull origin main` | Fetch origin + Pull |
| 2 | `git checkout -b fix/x` | Branch → New Branch |
| 3 | `git add . && git commit -m "msg"` | Escribir summary + Commit |
| 4 | `git push origin fix/x` | Publish branch |
| 5 | Crear PR desde GitHub | Branch → Create PR |
| 6 | Mergear desde GitHub | Mergear desde GitHub |
| 7 | `git branch -d fix/x` | Branch → Delete... |

---

## Notas

- **Squash and merge**: une todos los commits de la rama en uno solo sobre `main`. Historial más limpio.
- **Pull Request pequeño**: entre más pequeña la rama, más fácil de revisar. Ideal: una funcionalidad o fix por rama.
- **Nunca olvides borrar la rama** después de mergear, tanto local como remota.

```
git push origin --delete fix/login-error   # borrar rama remota
git branch -d fix/login-error               # borrar rama local
```
