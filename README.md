<!-- Fondo y Rejilla Neuronal -->
<rect width="100%" height="100%" fill="url(#cyberGrad)" rx="12"/>
<rect width="100%" height="100%" fill="url(#grid)" rx="12"/>

<!-- Líneas de Circuito y Conexiones -->
<path d="M 0 40 Q 250 80 500 20 T 900 60" fill="none" stroke="#00F0FF" stroke-width="1.2" opacity="0.4" filter="url(#glow)"/>
<path d="M 0 190 Q 350 140 600 210 T 900 170" fill="none" stroke="#FF0080" stroke-width="1.2" opacity="0.3" filter="url(#glow)"/>

<!-- Tipografía Principal -->
<text x="50%" y="42%" text-anchor="middle" fill="#FFFFFF" font-family="'JetBrains Mono', 'Fira Code', monospace" font-size="34" font-weight="900" letter-spacing="8" filter="url(#glow)">JULIO CESAR</text>
<text x="50%" y="60%" text-anchor="middle" fill="url(#neonAccent)" font-family="'JetBrains Mono', monospace" font-size="15" font-weight="700" letter-spacing="4">AI SYSTEMS ARCHITECT & FULL STACK ENGINEER</text>

<!-- Barra de Estado Inferior -->
<rect x="250" y="172" width="400" height="2" fill="url(#neonAccent)"/>
<circle cx="250" cy="173" r="3" fill="#00F0FF" filter="url(#glow)"/>
<circle cx="650" cy="173" r="3" fill="#FF0080" filter="url(#glow)"/>
<text x="50%" y="84%" text-anchor="middle" fill="#7082a6" font-family="'JetBrains Mono', monospace" font-size="11" letter-spacing="2">RAG PIPELINES • AGENTIC WORKFLOWS • SCALABLE BACKENDS</text>
📟 SYSTEM_CORE :: NEURAL RUNTIME INITIALIZEDjulio@autonomous-node:~$ ./deploy_ai_core.sh --prod --verbose

[+] Initializing Neural Network Pipelines........................... [OK]
[+] Loading Vector Store: FAISS Index synchronized (768-dim embeddings)
[+] Connecting LLM Orchestration: Groq Cloud API, Ollama (Local Llama/Phi)
[+] Triggering Autonomous Agents: LangChain & n8n Microservices active
[+] Full-Stack Layer: Next.js / FastAPI high-throughput endpoints online

[SYSTEM STATUS] >> AI Software Engineer Ready for High-Scale Production.
🧠 Capacidades Técnicas y Stack de IngenieríaCapa TecnológicaTecnologías y ModelosInteligencia Artificial & RAG     Backend & Microservicios   Frontend & Dashboards   Automatización y Flujos  🧬 Arquitectura en Producción: Cerebro Veterinario (RAG Pipeline)flowchart LR
    subgraph UI ["🖥️ Capa de Interacción"]
        User(["Veterinario / Investigador"]) -->|Consulta Clínica| Streamlit["Streamlit Dashboard"]
    end

    subgraph VectorEngine ["⚡ Motor Vectorial & RAG"]
        Streamlit -->|Prompt & Texto| Embedder["Sentence Transformers"]
        Embedder -->|Vector de Embeddings| FAISS[("Base de Datos FAISS")]
        Docs[("Corpus Médico Clínico")] -.->|Preprocesamiento & Chunks| FAISS
    end

    subgraph AIInference ["🤖 Inferencia & LLM Core"]
        FAISS -->|Contexto Relevante| Groq["Groq Cloud / Ollama"]
        Streamlit -->|Prompt Directo| Groq
        Groq -->|Diagnóstico Asistido Estructurado| Streamlit
    end

    classDef modern fill:#0a1226,stroke:#00F0FF,stroke-width:1.5px,color:#fff;
    classDef storage fill:#1a0f2b,stroke:#FF0080,stroke-width:1.5px,color:#fff;
    classDef core fill:#042b2b,stroke:#7928CA,stroke-width:1.5px,color:#fff;

    class Streamlit,Embedder modern;
    class FAISS,Docs storage;
    class Groq core;
