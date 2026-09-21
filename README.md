# 👋 Juan Gutiérrez | Desarrollador Full Stack
## 🚀 Construyo aplicaciones completas — del problema a producción
---

```bash
> whoami
Juan Carlos Gutiérrez Cáceres
> enfoque --fullstack --producto --integracion-ia
✅ Aplicaciones de extremo a extremo (Next.js + FastAPI)
✅ Integración de IA en productos reales
✅ Despliegue, CI/CD y mantenimiento en la nube
> mision
"Del problema del usuario al producto en producción.
Código que se despliega, no que se queda en el repo."
```

---

### 🧠 Sobre mí

Ingeniero Informático con formación previa en Marketing. Esa mezcla rara me deja construir productos completos: entiendo el código y aporto visión de negocio.

🔹 **Ingeniero Informático (4º año)** — Universidad de Alicante
🔹 **Enfoque**: desarrollo de aplicaciones SaaS de principio a fin (frontend, backend, infraestructura, despliegue y mantenimiento).
🔹 **Especialidad**: integración de IA en productos reales y arquitecturas web modernas con Next.js + FastAPI.

---

### 🛠️ Stack Técnico

**Frontend**
- **Frameworks:** Next.js, React, Angular
- **Lenguajes:** TypeScript, JavaScript
- **UI:** Tailwind CSS, diseño responsive, mobile-first

**Backend**
- **Frameworks:** FastAPI (Python), Spring Boot (Java)
- **Bases de datos:** PostgreSQL, MySQL
- **APIs:** REST, JWT, OAuth (Google, Facebook), Stripe

**Despliegue y Nube**
- **Contenedores:** Docker, Docker Compose
- **CI/CD:** GitHub Actions
- **Nube:** Oracle Cloud Infrastructure (OCI)
- **Servidores:** Nginx (proxy reverso, SSL/TLS)

**Buenas prácticas**
- Spec-Driven Development · CI/CD · Git · Modelado seguro de datos

---

### 🌐 Proyectos destacados

#### 🍽️ MenuUnfolded — SaaS de cartas digitales QR · [menuunfolded.com](https://menuunfolded.com)

<img src="https://juanko.com/img/work/menuunfolded/01.jpg" width="600" alt="MenuUnfolded">

SaaS que digitaliza cartas de restaurantes con códigos QR: panel de administración, estadísticas de escaneo y suscripción freemium con Stripe. Incluye un importador de cartas con **IA multimodal** que extrae los platos a partir de fotos o PDFs. Next.js + FastAPI + PostgreSQL, desplegado en Oracle Cloud con CI/CD automatizado. _En producción con su primer cliente._

---

#### 🍛 Cuquita Restaurant — Web estática bilingüe · [vista previa](https://cuquita.juanko.com) · [código](https://github.com/juanko6/cuquita-restaurant-web)

<img src="https://juanko.com/img/work/cuquita/01.jpg" width="600" alt="Cuquita Restaurant">

Sitio para un restaurante colombiano en Pensilvania, en sustitución de un WordPress con Elementor que enviaba 300 KB de HTML y veinte archivos de JavaScript para mostrar texto y fotos. **Astro 7 estático**, bilingüe (español en la raíz, inglés bajo `/en/`) y sin JavaScript salvo donde hace falta.

La carta no se duplica: se lee de la **API pública de MenuUnfolded** durante el build y se cachea en disco, de modo que un fallo de la API nunca publica una carta vacía. El diseño va por tokens, con la paleta muestreada del logo.

**El CI bloquea el merge si un cambio se pasa del presupuesto**: 40 KB de HTML por página, 25 KB de CSS y 15 KB de JS. Tests unitarios con Vitest y end-to-end con Playwright, `main` protegida y todo entrando por pull request con Conventional Commits.

_🔓 Repositorio público — pendiente de aprobación del cliente._

---

#### 🎬 Loomcast — Estudio multimedia con IA generativa 100 % local

<img src="https://juanko.com/img/work/loomcast/01.jpg" width="600" alt="Loomcast">

Genera vídeo, imagen y música ejecutando modelos de IA íntegramente en local, sin APIs de pago. Inferencia con **llama.cpp** sobre ocho modelos cuantizados seleccionables en caliente, con carga y descarga dinámica y orquestación de memoria unificada en Apple Silicon. Python + FastAPI por capas, tres pipelines independientes sobre un núcleo común y cola de jobs con recuperación ante fallo. Interfaz en Astro + Svelte.

---

#### ⏱️ NuxoAsist — Control horario y fichaje laboral

<img src="https://juanko.com/img/work/nuxoasist/05.jpg" width="600" alt="NuxoAsist">

Sistema de registro de jornada alineado con la normativa española: fichaje, pausas intrajornada, horas extra, ausencias y exportación para inspección. Auditoría *append-only* de correcciones con autor, fecha y motivo obligatorio. Node 22 + Fastify 5 + TypeScript sobre PostgreSQL 16, contrato **OpenAPI de 36 endpoints** como fuente de verdad y **178 tests con Vitest** contra base de datos real. _Diseñado API-first y desarrollado con TDD._

---

#### 🧠 MindCheck — Generador de tests con IA · [mindcheck.qzz.io](https://mindcheck.qzz.io)

<img src="https://juanko.com/img/work/mindcheck/01.jpg" width="600" alt="MindCheck">

Plataforma educativa que convierte documentos PDF en tests interactivos de opción múltiple usando IA. Next.js + FastAPI + PostgreSQL, con autenticación JWT, control de sesiones y arquitectura modular.

---

### 📊 Estadísticas de GitHub

<p align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=juanko6&show_icons=true&theme=radical&count_private=true" alt="Estadísticas" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=juanko6&theme=radical" alt="Racha" />
</p>

<p align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=juanko6&layout=compact&theme=tokyonight&langs_count=8" alt="Lenguajes" />
</p>

---

### 🧩 Cómo trabajo

- **De principio a fin**: diseño la especificación, codifico, despliego, mantengo. Si no llega a producción, no está terminado.
- **Producto antes que tecnología**: las decisiones técnicas se justifican por el problema del usuario, no por moda.
- **Visión de negocio**: mi formación previa en Marketing y Publicidad aporta criterio de producto, analítica y conversión, y me ayuda a hablar con devs y con clientes el mismo día.
- **Integración de IA con criterio**: la IA cuando resuelve un problema real, no como decoración.

---

### 📬 Contacto

🟢 Abierto a oportunidades de **Desarrollo Full Stack, Ingeniería de Producto y desarrollo de aplicaciones con IA**.

📧 **juanko6@gmail.com**
🔗 [LinkedIn](https://linkedin.com/in/juanko6)
🌐 [juanko.com](https://juanko.com)

---

> _"Entender el negocio es la mitad del trabajo. La otra mitad es construirlo."_
