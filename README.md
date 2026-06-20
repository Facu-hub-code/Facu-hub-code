<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0ea5e9,100:6366f1&height=120&section=header&text=Facundo%20Lorenzo&fontSize=42&fontColor=ffffff&animation=fadeIn" width="100%"/>

# 👋 Hola, soy Facundo Lorenzo 🇦🇷

### **Founder & Builder @ Suplai Sales · Backend & AI Engineer · Ex CTO**

*Peligrosamente optimista.*  
Hoy construyo el futuro de la venta B2B para distribuidoras — por WhatsApp, con IA y en producción.

[![Suplai Sales](https://img.shields.io/badge/Suplai_Sales-suplaisales.com-6366f1?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJ3aGl0ZSI+PHBhdGggZD0iTTEyIDJMMTMuMDkgOC4yNkwyMCA5TDEzLjA5IDE1Ljc0TDEyIDIyTDEwLjkxIDE1Ljc0TDQgOUwxMC45MSA4LjI2TDEyIDJaIi8+PC9zdmc+)](https://suplaisales.com)
[![Website](https://img.shields.io/badge/FK_Software-fk--software.com-0ea5e9?style=for-the-badge&logo=googlechrome&logoColor=white)](https://fk-software.com)
[![X](https://img.shields.io/badge/X-@facundo__l77-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/facundo_l77)

📍 Córdoba, Argentina

</div>

---

## 🚀 Hoy: 100% Suplai Sales

**[Suplai Sales](https://suplaisales.com)** es la plataforma de IA para **distribuidoras de consumo masivo** que quieren vender más, atender mejor y operar con menos fricción.


| Producto | Qué hace |
|----------|----------|
| 🤖 **Agente conversacional** | Toma pedidos, responde consultas y recomienda por WhatsApp |
| 🛒 **[Tienda B2B](https://tienda.suplaisales.com)** | Catálogo web con link directo desde el agente |
| 📱 **[Suplai Field](https://field.suplaisales.com)** | App mobile-first para vendedores: cartera, tareas y torneos |
| 🏢 **Back office** | Configura catálogo, promos, reglas y red comercial |
| 🧠 **Sales Engine** | ML de co-ocurrencia y frecuencia de compra por PdV |
| 📡 **Sniffer** | Análisis de conversaciones reales vendedor–cliente vía Kommo |

> *De un mensaje de WhatsApp a un pedido cerrado — sin llamadas, sin planillas, sin fricción.*

---

## 🏗️ Arquitectura que estoy construyendo

```mermaid
flowchart LR
    WA[WhatsApp] --> AG[Agente LangGraph]
    AG --> API[Backend FastAPI]
    API --> DB[(Supabase PostgreSQL)]
    AG --> TIENDA[Tienda Next.js]
    AG --> FIELD[Suplai Field]
    BO[Back office] --> API
    ML[Sales Engine] --> DB
    N8N[n8n workflows] --> API
```

**Stack del producto:**
- **Agente:** Python · FastAPI · LangGraph · OpenAI
- **Backend:** FastAPI · asyncpg · arquitectura multi-tenant por schema
- **Frontends:** Next.js · React
- **Data:** PostgreSQL / Supabase · modelos ML con scikit-learn
- **Infra:** Railway · Vercel · Docker · n8n para integraciones ERP

---

## 🧠 Background que trae valor al producto

| Experiencia | Cómo se traduce en Suplai |
|-------------|---------------------------|
| 💼 **Ex CTO de Clickie** | Producto, equipo y velocidad de iteración |
| 🛒 **IA para mayoristas** | Entiendo el rubro: pedidos, listas, promos, rutas |
| 🔒 **SIEM · Docker · K8s** | Infra observable y deploys confiables |
| 🏭 **MES industrial** | Sistemas críticos que no pueden caerse |
| 📊 **Data · MetroGAS · YPF** | Análisis a escala en operaciones complejas |
| 📦 **ERP Java** | Integraciones profundas con sistemas legacy |

---

## 🛠️ Stack técnico

<details open>
<summary><b>Lenguajes</b></summary>

<br>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

</details>

<details>
<summary><b>Backend & AI</b></summary>

<br>

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-412991?style=flat-square&logo=openai&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_Agents-412991?style=flat-square&logo=openai&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-Automations-EA4B71?style=flat-square&logo=n8n&logoColor=white)

</details>

<details>
<summary><b>Infra & Data</b></summary>

<br>

![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-Deploy-0B0D0E?style=flat-square&logo=railway&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-Frontend-000000?style=flat-square&logo=vercel&logoColor=white)

</details>

---

## 📈 GitHub en números

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Facu-hub-code&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Facu-hub-code&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages"/>

<br><br>


</div>

---

## 💡 Cómo construyo producto

```diff
+ Problema real del distribuidor → MVP en producción → métricas → iteración
```

- 🎯 **WhatsApp primero** — donde ya está el cliente, ahí vendemos  
- 🏢 **Multi-tenant desde el día uno** — un producto, muchas distribuidoras  
- 📐 **Arquitectura clara** — repos separados, contratos explícitos, deploy independiente  
- 🔭 **Observable** — logs, healthchecks y E2E antes de cada release  
- 🚢 **Ship fast** — PRs chicos, Railway + Vercel, feedback real de operadores  

---

## 📬 Contacto

¿Sos distribuidora, integrador o inversor y querés ver Suplai en acción?

<div align="center">

[![Suplai Sales](https://img.shields.io/badge/🚀_Suplai_Sales-Conocé_la_plataforma-6366f1?style=for-the-badge)](https://suplaisales.com)
[![Tienda demo](https://img.shields.io/badge/🛒_Tienda_B2B-Ver_demo-0ea5e9?style=for-the-badge)](https://tienda.suplaisales.com)
[![GitHub](https://img.shields.io/badge/GitHub-Facu--hub--code-181717?style=for-the-badge&logo=github)](https://github.com/Facu-hub-code)

</div>

---

<div align="center">

```diff
+ Construyendo el canal de ventas B2B que las distribuidoras merecen.
```

⭐️ *De Córdoba para el mundo — mate, código y pedidos por WhatsApp.*

</div>
