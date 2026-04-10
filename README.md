# Portafolio Digital — Gabriela Torres Ceballos

**Quality Control Engineer · QA Automation · Playwright · Selenium · API Testing**

Portafolio técnico personal desarrollado como entregable del módulo _Desarrollo de un Portafolio Digital_ del bootcamp. Muestra proyectos, habilidades, certificaciones, análisis de empresa (Cisco) y caso de estudio técnico.

---

## Vista previa

> Una vez activado GitHub Pages, el portafolio estará disponible en:
> **`https://elationg.github.io/<nombre-del-repo>/`**

---

## Contenido del portafolio

| Sección             | Descripción                                                       |
| ------------------- | ----------------------------------------------------------------- |
| **Hero**            | Presentación, rol actual (Softserve), stack y links               |
| **Sobre mí**        | Bio profesional, experiencia en Globant y STEM                    |
| **Habilidades**     | Stack completo: QA Automation, Backend, Frontend, BD, DevOps      |
| **Certificaciones** | 7 certificaciones (Desafío Latam, Talento Futuro, Code.org, etc.) |
| **Proyectos**       | 8 proyectos: QA automation, desarrollo web, backend y BD          |
| **Empresa — Cisco** | Tabla de análisis, aportes de valor y preguntas para entrevista   |
| **Caso de estudio** | SpringEduManager con métricas, aprendizajes y justificación       |
| **FODA**            | Análisis estratégico del perfil profesional actualizado           |
| **Contacto**        | Links de GitHub, LinkedIn y formulario                            |

---

## Proyectos incluidos

### QA Automation

| Proyecto                           | Tecnologías                                                   | Repositorio                                                    |
| ---------------------------------- | ------------------------------------------------------------- | -------------------------------------------------------------- |
| E2E Testing — Playwright BDD       | Playwright, Cucumber/Gherkin, Postman, Newman, GitHub Actions | [pruebas_front](https://github.com/Elationg/pruebas_front)     |
| API E2E Testing — Postman & Newman | Postman, Newman, CSV, GitHub Actions                          | [pruebas_backAPI](https://github.com/Elationg/pruebas_backAPI) |
| Task App — Jest Testing            | Jest, Babel, JavaScript, GitHub Actions                       | [pruebas_todoAPP](https://github.com/Elationg/pruebas_todoAPP) |

### Desarrollo Backend & Web

| Proyecto                     | Tecnologías                                      | Repositorio                                              |
| ---------------------------- | ------------------------------------------------ | -------------------------------------------------------- |
| SpringEduManager ⭐          | Spring Boot 3, Spring Security 6, JPA, Thymeleaf | [EntregaM6_TD](https://github.com/Elationg/EntregaM6_TD) |
| Biblioteca Digital UNTEC     | Java EE, Servlets, JSP/JSTL, H2, Tomcat          | [EntregaM5_TD](https://github.com/Elationg/EntregaM5_TD) |
| SmartTask                    | Java 21, JUnit 5, JaCoCo, Maven, GitHub Actions  | [EntregaM4_TD](https://github.com/Elationg/EntregaM4_TD) |
| Piggy Wallet — Web App       | HTML5, CSS3, JavaScript, Bootstrap 5, jQuery     | [EntregaM2_TD](https://github.com/Elationg/EntregaM2_TD) |
| Piggy Wallet — Base de datos | MySQL, MySQL Workbench, SQL (DDL), ERD           | [EntregaM3_TD](https://github.com/Elationg/EntregaM3_TD) |

---

## Estructura del repositorio

```
M7/
├── portfolio.html          # Portafolio completo (single-page)
├── css/
│   └── style.css           # Estilos (extraídos por el IDE)
├── .github/
│   └── workflows/
│       └── deploy.yml      # GitHub Actions — deploy automático a GitHub Pages
└── README.md               # Este archivo
```

---

## Cómo personalizar

### Foto de perfil

En [portfolio.html](portfolio.html), busca el elemento `id="profile-avatar"` (aprox. línea 65):

```html
<!-- Opción A — imagen local -->
<img
  src="foto.jpg"
  alt="Gabriela Torres Ceballos"
  style="width:100%;height:100%;object-fit:cover;"
/>

<!-- Opción B — URL pública -->
<img
  src="https://media.licdn.com/dms/..."
  alt="Gabriela Torres Ceballos"
  style="width:100%;height:100%;object-fit:cover;"
/>
```

### Email de contacto

Busca `tu@email.com` en el HTML y reemplázalo con tu correo real.

### Ubicación

Busca `Disponible para trabajo remoto` y agrega tu ciudad/país.

---

## Deploy en GitHub Pages

El archivo [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml) automatiza el deploy con cada push a `main`.

**Activación (una sola vez):**

1. Sube este repositorio a GitHub
2. Ve a **Settings → Pages → Source → GitHub Actions**
3. Haz un push a `main` — el workflow se dispara automáticamente

**URL resultante:** `https://elationg.github.io/<nombre-del-repo>/`

---

## Tecnologías del portafolio en sí

- HTML5 semántico
- CSS3 vanilla con variables CSS y diseño responsive
- JavaScript vanilla (IntersectionObserver para nav activo)
- Google Fonts: Inter + Fira Code
- Sin dependencias externas ni frameworks de UI

---

## Autora

**Gabriela Marina Torres Ceballos**
Quality Control Engineer · Softserve

- GitHub: [github.com/Elationg](https://github.com/Elationg)
- LinkedIn: [linkedin.com/in/gmtorresceballos](https://www.linkedin.com/in/gmtorresceballos/)
