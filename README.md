<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="ChatGPT Image 14 may 2026, 20_52_02.png?font=Fira+Code&weight=600&size=28&pause=1000&color=FF6F00&center=true&vCenter=true&width=700&lines=Hi+👋,+I'm+Julio+Cesar;Senior+AI+Software+Engineer;Especialista+en+Automatización+%26+BI;Full+Stack+Developer" alt="Typing SVG" />
  </a>
</div>

<p align="center">
  <img src="https://raw.githubusercontent.com/Julio-73/Julio-73/main/banner.png" alt="Julio Cesar Senior AI Engineer Banner" width="100%" style="border-radius: 12px; box-shadow: 0 8px 20px rgba(0,0,0,0.4);" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/julio-cesar-quispe-garrido/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-%230A66C2.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://julio-73.github.io/landing-Page-Julio/" target="_blank"><img src="https://img.shields.io/badge/Portfolio-julio--73.github.io-FF6F00?style=for-the-badge&logo=github&logoColor=white" alt="Portfolio"/></a>
  <a href="mailto:julioquispegarrido132@gmail.com"><img src="https://img.shields.io/badge/Email-julioquispegarrido132%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://github.com/Julio-73"><img src="https://img.shields.io/github/followers/Julio-73?label=Followers&style=for-the-badge&logo=github&color=24292e" alt="GitHub Followers"/></a>
</p>

---

## 🚀 System Boot

<p align="center">
  <img src="https://raw.githubusercontent.com/Julio-73/Julio-73/main/terminal.svg" alt="Julio Cesar Terminal Skills" width="100%" />
</p>

> Operando como **Full Stack Developer Freelance** y Consultor de Automatización. Estudiante de Ingeniería de Software con IA en SENATI. Especialista en orquestar agentes inteligentes, optimizar procesos con código puro y construir arquitecturas corporativas con un diseño minimalista inspirado en Silicon Valley.

---

## 🛠️ Stack Tecnológico

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,js,ts,html,css,react,flutter,nodejs,fastapi,pytorch,tensorflow,docker,kubernetes,aws,gcp,firebase,postgres,mongodb,git,vscode&theme=dark" alt="Tech Stack" />
  </a>
</p>

---

## 💼 Proyectos Destacados

<table bordercolor="#30363d">
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🧠 Cerebro Veterinario MVP</h3>
      <p>Asistente inteligente basado en RAG para medicina veterinaria. Responde preguntas utilizando documentos contextuales mediante embeddings de FAISS, sentence-transformers y LLMs impulsados por Groq.</p>
      <p><strong>Stack:</strong> <code>Python</code> <code>FAISS</code> <code>Groq</code> <code>Streamlit</code> <code>Ollama</code></p>
      <div align="center">
        <a href="https://github.com/julio-73/-CEREBRO-VETERINARIO-MVP"><strong>🔗 Ver Código »</strong></a>
      </div>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🚚 Dashboard Operativo Logístico</h3>
      <p>Dashboard corporativo para el análisis de operaciones logísticas en tiempo real. Transforma datos en decisiones estratégicas, reduciendo más de 15 horas semanales de reportes manuales.</p>
      <p><strong>Stack:</strong> <code>Python 3.11</code> <code>Streamlit</code> <code>Pandas</code> <code>Plotly</code></p>
      <div align="center">
        <a href="https://github.com/julio-73/Sistema-Inteligente-de-Control-Operativo-Logistico"><strong>🔗 Ver Código »</strong></a>
      </div>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🧬 NutriMind AI (Arquitectura)</h3>
      <p>Diseño Blueprint y arquitectura profesional para una aplicación inteligente de nutrición. Frontend móvil con integración backend serverless y modelos de lenguaje avanzados.</p>
      <p><strong>Stack:</strong> <code>Flutter</code> <code>Firebase</code> <code>Google Gemini</code></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">⚡ PWA Educativa Offline</h3>
      <p>Aplicación web progresiva (PWA) 100% interactiva con buscador de alta velocidad y capacidad de funcionar completamente sin conexión a internet.</p>
      <p><strong>Stack:</strong> <code>JavaScript (ES6+)</code> <code>HTML5</code> <code>CSS3</code></p>
    </td>
  </tr>
</table>

---

## 🏛️ Arquitectura de IA: Cerebro Veterinario

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#0d1117', 'primaryTextColor': '#c9d1d9', 'primaryBorderColor': '#30363d', 'lineColor': '#FF6F00', 'tertiaryColor': '#161b22'}}}%%
graph TD
    subgraph UI [Frontend Interface]
        A[👨‍⚕️ Usuario / Veterinario] -->|Consulta Clínica| B(Streamlit Dashboard)
    end

    subgraph RAG_Engine [Motor RAG & Base Vectorial]
        B -->|Texto a Vector| C{Sentence-Transformers}
        C -->|Búsqueda de Similitud| D[(FAISS Index DB)]
        D -.->|Documentos Contextuales| C
    end

    subgraph LLM_Core [Procesamiento IA]
        C -->|Contexto + Prompt| E[Groq API / Ollama Phi]
        E -->|Respuesta Sintetizada| B
    end

    style A fill:#0d1117,stroke:#FF6F00,stroke-width:2px,color:#c9d1d9
    style B fill:#161b22,stroke:#30363d,stroke-width:2px,color:#c9d1d9
    style C fill:#161b22,stroke:#30363d,stroke-width:2px,color:#c9d1d9
    style D fill:#161b22,stroke:#3fb950,stroke-width:2px,color:#c9d1d9
    style E fill:#161b22,stroke:#79c0ff,stroke-width:2px,color:#c9d1d9
