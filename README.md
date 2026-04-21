# <div align="center"> 💃 Caseta La Manivela — Portal Oficial de Socios </div>

<div align="center">

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![TypeScript](https://img.shields.io/badge/typescript-%23007acc.svg?style=for-the-badge&logo=typescript&logoColor=white) ![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens) ![Motion](https://img.shields.io/badge/Motion-000000?style=for-the-badge&logo=framer&logoColor=white) ![Hosting](https://img.shields.io/badge/Hosting-0A66C2?style=for-the-badge&logo=cloudflare&logoColor=white)

</div>
<br>

> [!NOTE]
> **Repositorio de gestión interna** — Este proyecto ha sido desarrollado para digitalizar la gestión de la caseta "La Manivela" de la Feria de Sevilla. Sirve como plataforma centralizada para socios, permitiendo el acceso a documentos oficiales, noticias y galería de recuerdos.

<br>

---

### 🚀 Tecnologías utilizadas

| Frontend | Backend | Infraestructura |
|:---:|:---:|:---:|
| React 18 (Vite) | PHP 8.x (API REST) | Hosting |
| TypeScript | **JWT Authentication** | MySQL Database |
| Tailwind CSS v4 | Prepared Statements | Apache / .htaccess |

<br>

---

### ✨ Características

| **Plataforma General** |
|:---|
| ⚡ SPA optimizada con **React Router** y Lazy Loading |
| 🏰 UI/UX inspirada en la Feria de Sevilla (Colores rojo, albero y marino) |
| 📱 Full Responsive — Experiencia fluida en móviles, tablets y PC |
| 🎭 Animaciones interactivas con **Motion** (Framer Motion) |
| 🌓 Pantalla de Landing con **Cuenta Atrás** para la próxima Feria (13 Abr 2027) |
| 🛠️ Componentes modulares basados en **Shadcn UI** y **Radix UI** |

<br>

| **Secciones del Portal** |
|:---|
| 📰 **Noticias** — Sistema de blog para anuncios de la Junta y socios |
| 📸 **Galería** — Espacio interactivo con fotos, sistema de **Likes** y **Comentarios** |
| 💬 **Sugerencias** — Foro de comunidad con hilos de respuestas anidadas |
| 📂 **Documentos** — Gestión de Convocatorias, Presupuestos y Cuentas (PDF) |
| 🔐 **Dashboard** — Panel de control personalizado según el rol del usuario |

<br>

| **Gestión de Usuarios (Roles)** |
|:---|
| 👑 **Administrador** — Control total (Moderación, subida de documentos oficiales) |
| 🤝 **Socio** — Acceso completo a contenidos, publicación de noticias y fotos |
| 👤 **Usuario** — Visualización limitada y participación en secciones comunes |
| ✅ Sistema de permisos granular protegidos en el cliente y servidor |

<br>

---

### 🔒 Seguridad & Performance

| Cabecera / Método | Protección / Optimización |
|:---|:---|
| `X-Frame-Options` | Previene ataques de Clickjacking (SAMEORIGIN) |
| `X-Content-Type-Options` | Evita el sniffing de tipos MIME (nosniff) |
| `X-XSS-Protection` | Activado con modo de bloqueo para navegadores antiguos |
| `JWT Auth` | Sesiones seguras sin almacenamiento de contraseñas en plano |
| `.env Protection` | Bloqueo estricto vía `.htaccess` para archivos sensibles |
| `MySQL Prepared Statements` | Protección total contra ataques de Inyección SQL |

<br>

---

### 🔍 SEO & RRSS

| **Optimización de Presencia** |
|:---|
| ✅ Meta tags completos con soporte para **Open Graph** (Facebook/WhatsApp) |
| ✅ **Twitter Cards** configuradas para visualización impactante en redes |
| ✅ Soporte para **Schema.org** (Local Business / Organization) |
| ✅ Favicons multi-dispositivo y manifest PWA ready |

<br>

---

<sub>Hecho con ❤️ para los socios de La Manivela 🏮</sub>
