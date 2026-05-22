# Documentación de Comandos de GitHub CLI (gh)

## Tabla Resumen de Comandos Seleccionados

| Comando | Descripción |
|---|---|
| `gh auth login` | Autenticación de cuenta en GitHub. |
| `gh repo create` | Creación de nuevos repositorios remotos. |
| `gh repo clone` | Clonado de repositorios a la máquina local. |
| `gh repo view` | Visualización de detalles de un proyecto. |
| `gh issue create` | Creación de nuevas incidencias (issues). |
| `gh issue list` | Listado de incidencias abiertas. |
| `gh pr create` | Creación de un Pull Request. |
| `gh pr merge` | Fusión de un Pull Request aprobado. |
| `gh gist create` | Creación de un fragmento de código (Gist). |
| `gh release create` | Creación de un nuevo lanzamiento de versión. |
| `gh workflow run` | Ejecución manual de GitHub Actions. |
| `gh codespace create` | Creación de un entorno de desarrollo en la nube. |

---

## Detalles y Ejemplos de Uso

### 1. gh auth login
* **Descripción general:** Permite iniciar sesión y autenticarse en GitHub desde la línea de comandos.
* **Propósito:** Es el primer paso necesario para configurar la CLI y autorizarla a interactuar con tu cuenta de GitHub de forma segura.
* **Sintaxis básica:** ```bash
  gh auth login [flags]