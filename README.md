# 🍰 Confitería Dulce Delicia — Sitio Web Colaborativo

Proyecto web desarrollado **en equipo** por tres integrantes, aplicando control de versiones
con **Git y GitHub**: ramas independientes, commits descriptivos, Pull Requests y revisión
de código entre compañeros.

---

## 🎯 Objetivo

Diseñar y publicar un sitio web básico que presente la información de la empresa **Confitería Dulce Delicia**:
su página principal, los servicios que ofrece y el equipo de trabajo que la conforma.

---

## 👥 Integrantes y roles

| Rol | Integrante | Usuario de GitHub | Rama de trabajo | Archivo | Estado |
| --- | --- | --- | --- | --- | --- |
| Estudiante 1 — Página principal | Tony | [@punky3211](https://github.com/punky3211) | `pagina_principal` | `index.html` | ✅ Integrado en `main` (PR #1) |
| Estudiante 2 — Sección de servicios | Romel Yauri Artica | [@arisu84863-alt](https://github.com/arisu84863-alt) | `seccion-servicios` | `servicios.html` | 🔄 Pull Request en revisión |
| Estudiante 3 — Sección de equipo | Jhoshimar | [@Josimar2004](https://github.com/Josimar2004) | `seccion-equipo` | `equipo.html` | 🔄 En desarrollo |

---

## 🗂️ Secciones del sitio

| Archivo | Contenido |
| --- | --- |
| `index.html` | Página principal: título, descripción de la empresa y menú de navegación. |
| `servicios.html` | Servicios que ofrece la empresa (mínimo tres). |
| `equipo.html` | Perfiles del equipo de trabajo (mínimo tres). |
| `style.css` | Hoja de estilos compartida: estilos base de `index.html` + componentes del equipo (tarjetas, franjas y diseño adaptable). |

---

## 🔀 Flujo de trabajo con Git y GitHub

1. La rama `main` contiene siempre la versión integrada y estable del sitio.
2. Ningún integrante sube cambios directamente a `main`.
3. Cada integrante desarrolla su sección en su propia rama:
   `pagina_principal`, `seccion-servicios` y `seccion-equipo`.
4. Los avances se registran con commits descriptivos (`git status` antes de cada commit).
5. Cada sección se integra a `main` mediante un **Pull Request** revisado por otro integrante.
6. Tras cada integración, el equipo actualiza su repositorio local con `git pull`.

---

## 🚀 Cómo visualizar el sitio

```bash
git clone https://github.com/punky3211/confiteria.
cd confiteria.
```

Luego abre `index.html` en el navegador y navega entre las tres secciones.
