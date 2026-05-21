# 🎨 Plan de Contenido del Portfolio — antoniocortazar.dev

> Basado en: `banco-de-ideas/index.md`, `portafolio.md`, `perfil-profesional.md`, `cv-harvard.md`
>
> Este documento define qué dice cada sección del portfolio.

---

## 1. HERO

### Qué se ve
- Tu nombre: **Antonio Cortázar**
- Título / tagline principal
- Subtítulo descriptivo
- Botones CTA (Call to Action)
- Animación de fondo o elemento visual

### Contenido

**Nombre:** Antonio Cortázar

**Tagline principal:**
> Full-Stack Developer & Software Engineering Student

**Subtítulo:**
> Construyo experiencias digitales premium — desde landing pages inmobiliarias con mapas interactivos hasta arquitecturas cloud con Kubernetes.

**Botones CTA:**
- **Primario:** "Ver proyectos" → scroll a sección Projects
- **Secundario:** "Contacto" → scroll a Contact / link a email

**Keywords a incluir en meta tags:** Full-Stack Developer, Astro, Next.js, React, AWS, Kubernetes, Cancún

---

## 2. ABOUT (Sobre mí)

### Qué se ve
- Foto personal
- Párrafo biográfico
- Datos rápidos (stats o cards)
- Posible botón "Descargar CV"

### Contenido

**Párrafo principal:**
> Soy estudiante de Ingeniería en Desarrollo de Software en **Tecmilenio** (Cancún) y trabajo como **Auxiliar de TI y Web** en Onix Living, donde construyo landing pages inmobiliarias con mapas interactivos de disponibilidad y herramientas de gestión de activos. Me apasiona construir cosas que resuelvan problemas reales — desde interfaces que se sientan bien hasta la infraestructura cloud que las mantiene vivas.

**Stats / Datos rápidos:**
- **3+** Proyectos reales en producción (Koa Towers, Aldea Savia, CRZR)
- **100+** Activos gestionados con sistema Snipe-IT
- **7+** Certificaciones (AWS Data Engineering, IBM Big Data, EF SET C1)
- **2+** Años de experiencia profesional (Office Depot + Onix Living)

**Datos adicionales (si hay espacio):**
- 🎓 Tecmilenio — Ing. Desarrollo de Software (2023 – Actualidad)
- 🌐 English C1 (67/100 EF SET)
- 📍 Cancún, México

---

## 3. SKILLS (Habilidades)

### Qué se ve
- Categorías de tecnologías (cards o grid)
- Tags/badges por cada tecnología
- Posible indicador de nivel

### Contenido

**Frontend:**
> Interfaces modernas, responsivas y con animaciones fluidas
- Astro 6 · Next.js 15/16 · React 19 · Vue 3
- TypeScript · JavaScript ES6+
- Tailwind CSS 4 · Framer Motion · Swiper · Gridstack · Lottie
- Leaflet (mapas interactivos)

**Backend:**
> APIs REST, microservicios y bases de datos
- Java · Spring Boot · Node.js · Express · PHP · Laravel
- MySQL

**Infraestructura & DevOps:**
> Cloud, contenedores, orquestación y CI/CD
- AWS (Amazon Web Services) · Amazon S3
- Docker · Docker Compose · Kubernetes · Helm
- GitHub Actions · Ansible
- Cloudflare · Tailscale

**Otros:**
> Herramientas y tecnologías complementarias
- Firebase (Realtime DB, Admin SDK, Auth)
- PWA · Capacitor (APK Android)
- Git / GitHub
- Snipe-IT
- Figma · Adobe Suite

---

## 4. PROJECTS (Proyectos destacados)

### Qué se ve
- Cards de proyectos con imagen/screenshot
- Nombre del proyecto, descripción corta
- Stack tecnológico (tags)
- Links: demo en vivo + GitHub

### Proyectos a incluir (ordenados por prioridad)

---

### Proyecto 1: Koa Towers — Interactive Availability Map
**Tipo:** Proyecto real (Onix Living)
**Descripción:**
> Landing page inmobiliaria para Koa Towers con mapa interactivo SVG de disponibilidad de unidades. Datos en vivo desde Google Sheets, scroll cinematográfico y diseño premium.
**Stack:** Astro 6 · HTML · CSS · Google Sheets API · Amazon S3
**Links:**
- Demo: https://mapas-onix-living.vercel.app
- GitHub: (repo privado — Onix Living)
**Lo que demuestra:** Desarrollo de sitios estáticos profesionales, mapas interactivos, diseño inmobiliario

---

### Proyecto 2: Aldea Savia — Real Estate Landing + Availability
**Tipo:** Proyecto real (Onix Living)
**Descripción:**
> Landing page premium para Aldea Savia con páginas de brochure, contacto, multimedia, ubicación y página de disponibilidad de unidades con mapa interactivo por fases. Deploy en dominio personalizado.
**Stack:** Astro 6 · HTML · CSS · Google Sheets API
**Links:**
- Demo: https://aldeasavia.onixliving.mx
- GitHub: (repo privado — Onix Living)
**Lo que demuestra:** Sitios multi-página, integración de datos en tiempo real, deploy custom domain

---

### Proyecto 3: Microservices Architecture — Docker + K8s + Helm
**Tipo:** Proyecto académico
**Descripción:**
> Arquitectura de microservicios completa: backend Node.js/Express con MySQL, frontend nginx con reverse-proxy, orquestado con Kubernetes y Helm charts. CI/CD automatizado con GitHub Actions para publicación en Docker Hub.
**Stack:** Docker · Docker Compose · Kubernetes · Helm · GitHub Actions · MySQL · nginx · Node.js · Express
**Links:**
- GitHub: `clientes-back` · `clientes-front` · `clientes-helm`
**Lo que demuestra:** DevOps, contenedores, orquestación, CI/CD, arquitectura distribuida

---

### Proyecto 4: Pocky — Virtual Pet PWA
**Tipo:** Proyecto personal
**Descripción:**
> Mascota virtual compartida entre dos personas con sincronización en tiempo real vía Firebase. Funciona como PWA en iPhone (Safari) y APK en Android (Capacitor). Sistema de degradación 24/7, mascotas ASCII animadas con Lottie, Web Push notifications.
**Stack:** Next.js 16 · React 19 · Firebase · Zustand · Lottie · Capacitor · PWA · Web Push
**Links:**
- Demo: https://pocky-next.vercel.app
- GitHub: (repo privado)
**Lo que demuestra:** PWA, Firebase realtime, cross-platform, state management

---

### Proyecto 5: OnixDashTI — Internal IT Dashboard
**Tipo:** Proyecto real (Onix Living)
**Descripción:**
> Dashboard interno para el área de TI con widgets arrastrables para visualización de datos operativos. Autenticación con next-auth, containerizado con Docker Compose.
**Stack:** Next.js 16 · React 19 · TypeScript · Gridstack · next-auth · Docker · Tailwind CSS 4
**Links:**
- GitHub: (repo privado — Onix Living)
**Lo que demuestra:** Dashboards interactivos, Docker, autenticación, Gridstack

---

### Proyecto 6: CRZ-Tech — Dark Mode Portfolio
**Tipo:** Proyecto personal
**Descripción:**
> Portfolio web con estética dark mode, detalles ciberespaciales, cursor personalizado, fondo canvas interactivo y animaciones fluidas con Framer Motion y smooth scroll.
**Stack:** Next.js 16 · React 19 · TypeScript · Framer Motion · react-lenis · Tailwind CSS 4
**Links:**
- Demo: https://crzr-tech.vercel.app
- GitHub: (repo privado)
**Lo que demuestra:** Diseño avanzado, animaciones, smooth scroll

---

### Proyecto 7: Big Data Dashboard
**Tipo:** Proyecto académico/personal
**Descripción:**
> Dashboard de visualización de datos con Next.js y Recharts, conecta con certificaciones de Big Data (IBM, AWS).
**Stack:** Next.js 16 · React 19 · TypeScript · Tailwind CSS 4 · Recharts
**Links:**
- Demo: https://win95-bigdata-project.vercel.app
- GitHub: `win95-bigdata-project`
**Lo que demuestra:** Aplicación práctica de certs Big Data, visualización de datos

---

## 5. EXPERIENCE (Experiencia)

### Qué se ve
- Timeline con cada puesto
- Empresa, rol, período
- Descripción de responsabilidades y logros
- Tags de tecnologías usadas

### Contenido

---

### Onix Living — Auxiliar de TI y Desarrollo Web
**Período:** Ago 2025 – Present
**Descripción:**
> Desarrollo de landing pages inmobiliarias con Astro para proyectos reales (Koa Towers, Aldea Savia, CRZR) con mapas interactivos de disponibilidad. Implementación de Snipe-IT para gestión de 100+ activos fijos. Deploy de aplicaciones en AWS y administración de Amazon S3. Dashboard interno con Next.js + Gridstack.
**Tecnologías:** Astro · Next.js · Gridstack · Snipe-IT · AWS · Amazon S3 · Docker · Google Sheets API
**Métricas de impacto:**
- 3+ landing pages en producción
- 2 mapas interactivos de disponibilidad
- 100+ activos gestionados con Snipe-IT
- Dashboard interno con widgets arrastrables

---

### Office Depot — Supervisor de Área de Tecnología
**Período:** Jun 2024 – Ago 2025
**Descripción:**
> Lideré un equipo de 5 asociados en el departamento de tecnología. Coordinación de personal, capacitación, cierre de ventas, asesoría a clientes sobre hardware/software y manejo de KPIs del departamento (ventas, satisfacción del cliente, inventario).
**Tecnologías:** Soporte técnico nivel 1 y 2, hardware/software
**Habilidades blandas:** Liderazgo · Gestión de equipo · Comunicación · Ventas · KPIs

---

## 6. CERTIFICATIONS (Certificaciones)

### Qué se ve
- Grid o lista de certificaciones
- Nombre, emisor, fecha
- Icono/badge de cada una

### Contenido

| Certificación | Emisor | Fecha |
|---|---|---|
| Big Data 101 | Cognitive Class (IBM) | Abr 2026 |
| Big Data Foundations — Level 1 & 2 | IBM | Abr 2026 |
| Spark — Level 1 | IBM | Abr 2026 |
| Hadoop Foundations — Level 1 | IBM | Abr 2026 |
| AWS Academy Graduate — Data Engineering | Amazon Web Services | Dic 2025 |
| EF SET English Certificate — C1 Advanced (67/100) | EF SET | Jul 2025 |
| Networking Academy Learn-A-Thon 2024 | Cisco | Jun 2024 |
| Figma Avanzado | LinkedIn Learning | — |

---

## 7. CONTACT (Contacto)

### Qué se ve
- Texto de invitación
- Cards de contacto con iconos
- Posible formulario

### Contenido

**Texto de invitación:**
> ¿Trabajamos juntos? Estoy disponible para proyectos freelance y oportunidades laborales. No dudes en contactarme.

**Canales de contacto:**
- 📧 **Email:** Antony_cj12@outlook.com
- 💼 **LinkedIn:** linkedin.com/in/antoniocortazar
- 🐙 **GitHub:** github.com/Antony-potato
- 🌐 **Portfolio:** antoniocortazar.dev
- 📱 **Teléfono:** 81 3511 2848

---

## 8. FOOTER

### Contenido
- © 2026 Antonio Cortázar. Todos los derechos reservados.
- "Construido con Astro + React + Framer Motion"
- Links rápidos: GitHub · LinkedIn · Email
- Toggle de idioma (ES / EN)

---

## 📋 Notas de implementación

### i18n
- **ES (default):** Contenido en español
- **EN:** Traducción al inglés de todas las secciones
- Toggle visible en navbar

### Diseño
- Dark mode (`#0a0a0a`)
- Glassmorphism en cards
- Gradientes indigo/purple
- Noise overlay
- Animaciones con Framer Motion (Hero)
- Smooth scroll
- Responsive (mobile-first)

### Performance
- SSG con Astro (estático)
- Hero como isla React (`client:only="react"`) para Framer Motion
- Resto de secciones en Astro puro (más rápido)
- Imágenes optimizadas (WebP, lazy loading)
- CSS scoped + global para theme

### SEO
- Meta tags (title, description, Open Graph)
- Semantic HTML
- Canonical URL
- Hreflang (ES/EN)

---

## 🚧 Pendiente por definir
- [ ] Foto personal para About y Hero
- [ ] Screenshots reales de cada proyecto (Koa Towers, Aldea Savia, etc.)
- [ ] Métricas cuantificables exactas (KPIs Office Depot, activos Snipe-IT)
- [ ] Traducciones al inglés de todo el contenido
- [ ] Favicon personalizado
- [ ] Dominio configurado (antoniocortazar.dev)
