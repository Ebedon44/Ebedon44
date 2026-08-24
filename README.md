<h1 align="center">¡Hola! Soy Erick Bedón 👋</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=2E9EF7&center=true&vCenter=true&width=650&lines=Desarrollador+Full+Stack;Backend+en+Node.js+%2B+TypeScript+%2B+Java;Constructor+de+agentes+de+IA+con+n8n+%2B+LLMs;Arquitecturas+limpias%2C+TDD+y+ADRs" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Ebedon44&label=Visitas+al+perfil&color=2E9EF7&style=flat" alt="profile views" />
</p>

---

### 🧭 Sobre mí

Construyo software de punta a punta: desde backends en **Node.js/TypeScript** y **Java/Spring**, hasta **agentes de IA conversacionales** que atienden clientes reales por WhatsApp y automatizan flujos de negocio con **n8n** y **LLMs**. Me interesa el código que se sostiene en el tiempo: arquitecturas con límites claros, tests que prueban comportamiento real (no implementación) y decisiones documentadas.

Algunos de los sistemas en los que he trabajado:

- 🤖 **Agentes conversacionales de WhatsApp** multi-tenant con tool-calling sobre LLMs (OpenAI/Groq), integrados a Google Sheets/Calendar.
- ⚙️ **Automatizaciones con n8n**: desde publicación asistida en LinkedIn hasta bots de agendamiento con transcripción de voz.
- 🏗️ **Motores de renderizado/animación** con arquitectura hexagonal, boundaries de dependencias verificados por tests, y TDD estricto.
- 🏦 **Microservicios bancarios** reactivos en Spring Boot (WebFlux) con mensajería asíncrona vía RabbitMQ.
- 🖥️ Frontends en **Angular** y **Next.js/React** para productos reales (tesis universitaria, e-commerce, paneles administrativos).

---

### 🛠️ Stack técnico

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,java,nodejs,react,nextjs,angular,nestjs,spring,express,fastify,tailwind,postgres,mongodb,redis,sqlite,rabbitmq,docker,git,githubactions,aws,figma&perline=11" alt="Skills" />
</p>

<table align="center">
<tr>
<td valign="top" width="50%">

**Backend & APIs**
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/-Java%2021-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![NestJS](https://img.shields.io/badge/-NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Fastify](https://img.shields.io/badge/-Fastify-000000?style=flat-square&logo=fastify&logoColor=white)
![Express](https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express&logoColor=white)

**IA & Automatización**
![n8n](https://img.shields.io/badge/-n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![OpenAI](https://img.shields.io/badge/-OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white)
![Groq](https://img.shields.io/badge/-Groq-F55036?style=flat-square)
![WhatsApp](https://img.shields.io/badge/-WhatsApp%20Cloud%20API-25D366?style=flat-square&logo=whatsapp&logoColor=white)

</td>
<td valign="top" width="50%">

**Frontend**
![React](https://img.shields.io/badge/-React%2019-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/-Next.js%2016-000000?style=flat-square&logo=next.js&logoColor=white)
![Angular](https://img.shields.io/badge/-Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![Tailwind](https://img.shields.io/badge/-Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Datos, mensajería & DevOps**
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/-RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Testing & calidad**
![Vitest](https://img.shields.io/badge/-Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/-Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Jest](https://img.shields.io/badge/-Jest-C21325?style=flat-square&logo=jest&logoColor=white)

</td>
</tr>
</table>

---

### 🚀 Proyectos destacados

> La mayoría son repos **privados** (trabajo para clientes o proyectos personales en progreso) — el código está disponible bajo petición para procesos de selección.

<table>
<tr>
<td width="50%" valign="top">

**🌭 [Food Animation Engine](https://github.com/Ebedon44/food-animation-engine)** 🔒
Motor de animación *product-agnostic* para configuradores visuales, construido con **TDD estricto** (RED→GREEN→REFACTOR), **ADRs** documentando cada decisión de arquitectura, y **tests de arquitectura** que fallan el build si el motor importa algo de negocio o de UI. Incluye tienda funcional con SQLite, checkout server-priced y testing visual con Playwright.

`Next.js 16` `React 19` `TypeScript` `Vitest` `Playwright` `node:sqlite`

</td>
<td width="50%" valign="top">

**💈 [Peluquerías SaaS](https://github.com/Ebedon44/peluquerias-saas)** 🔒
Backend multi-tenant para un agente conversacional de WhatsApp que agenda citas contra Google Sheets/Calendar. Arquitectura por puertos y adaptadores (el negocio nunca conoce el proveedor de mensajería), agente LLM con **tool-calling**, jobs periódicos de recordatorios y reenganche, consola admin propia.

`Node.js` `TypeScript` `Fastify` `Redis` `Google APIs` `LLM Agents`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🤖 [boot-agendamiento](https://github.com/Ebedon44/boot-agendamiento)** 🔒
Agente de agendamiento por WhatsApp orquestado en **n8n**, con **WAHA** para la capa de mensajería, transcripción de notas de voz vía **Groq**, memoria conversacional en **Redis** y persistencia en **PostgreSQL**. Todo desplegado con Docker Compose.

`n8n` `WAHA` `Groq` `Redis` `PostgreSQL` `Docker`

</td>
<td width="50%" valign="top">

**🏦 [Prueba Técnica NTT Data](https://github.com/Ebedon44/prueba-tecnica-ntt-data)** 🔒
Sistema bancario de microservicios (`persona-cliente`, `cuenta-movimientos`) en **Spring Boot 4 + WebFlux** (reactivo), comunicados vía **RabbitMQ**, con generación de API **contract-first** (OpenAPI → Spring), mapeo con **MapStruct** y **mutation testing** con PIT.

`Java 21` `Spring WebFlux` `RabbitMQ` `PostgreSQL` `OpenAPI` `PIT`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**📝 [n8n-automations](https://github.com/Ebedon44/n8n-automations)** 🔒
Automatización "LinkedIn Publisher": recibe un link por Telegram, extrae el artículo, genera un borrador con **OpenAI**, pide aprobación humana antes de publicar y comenta el link original automáticamente. Con manejo explícito de errores y ramas de cancelación/edición.

`n8n` `OpenAI` `Telegram Bot API` `LinkedIn API`

</td>
<td width="50%" valign="top">

**👕 [back-ropa](https://github.com/Ebedon44/back-ropa)** 🌐 *(público)*
API REST con **NestJS + TypeORM + PostgreSQL**. Es el repo abierto que puedes explorar directamente sin pedir acceso.

`NestJS` `TypeORM` `PostgreSQL`

</td>
</tr>
</table>

<details>
<summary><strong>Ver más proyectos</strong></summary>
<br>

| Proyecto | Descripción | Stack |
|---|---|---|
| **ecommerce-sneakers** | Tienda online con pagos y auth | Next.js · Stripe · Firebase · MongoDB |
| **back-imagenes** | API de galería de imágenes con carga de archivos | Express · TypeScript · MongoDB · Multer |
| **front-tesis** | Aplicación web de tesis universitaria, desplegada en AWS Amplify | Angular · Chart.js · AWS Amplify |
| **proyecto-integrado-steeven** | Aplicación de gestión con generación de reportes PDF | Angular · Angular Material · Jest |
| **proyecto-web** | Sistema JSF/PrimeFaces sobre Java EE | Java 8 · JSF · PrimeFaces · Spring |

</details>

---

### 📊 Estadísticas

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Ebedon44&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ebedon44&layout=compact&theme=tokyonight&hide_border=true&count_private=true" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Ebedon44&theme=tokyonight&hide_border=true" alt="GitHub streak" />
</p>

---

### 📫 Contacto

<p align="center">
  <a href="https://www.linkedin.com/in/ebedon44/"><img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
</p>
