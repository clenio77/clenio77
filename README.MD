<div align="center">
  <img src="imagens/Capa_github.png" alt="Header" width="100%"/>
</div>

<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&center=true&vCenter=true&width=600&height=70&duration=4000&lines=Olá!+👋;Sou+o+Clênio+Oliveira!;AI+Engineer+%26+SaaS+Founder;Arquiteturas+Multiagente+%26+RAG;" />
</h1>

<div align="center">

  [![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/clenio-oliveira)
  [![Instagram](https://img.shields.io/badge/-Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/afonso.clenio/)
  [![Genesys](https://img.shields.io/badge/-Genesys_Tecnologia-7928CA?style=flat-square&logo=openai&logoColor=white)](https://genesys.ia.br)
  [![Profile Views](https://komarev.com/ghpvc/?username=clenio77&color=blue&style=flat-square)](https://github.com/clenio77)

</div>

---

## 🚀 Perfil Profissional

**AI Agent Engineer | Arquiteto de Sistemas SaaS | Cientista de Dados**

Especializado no desenvolvimento de ecossistemas inteligentes corporativos e soluções completas ponta a ponta (SaaS). Atuo com foco em modelagem preditiva, engenharia de prompts avançada (Chain-of-Thought) e orquestração de sistemas multiagente autônomos para setores regulados de alta complexidade, como **LegalTech**, **GovTech** e **HealthTech**.

- 🔭 **Fundador**: [Kermartin](https://kermartin.onrender.com) (SaaS de Jurimetria Preditiva & Defesa Criminal) e [Genesys Tecnologia](https://genesys.ia.br) (Consultoria em IA & Compliance).
- 🎓 **Formação**: Bacharel em Sistemas de Informação (2018).
- 🤖 **Especialidades em IA**: Orquestração Multiagente (CrewAI), RAG Avançado, Modelagem Preditiva e Edge AI para processamento local de dados clínicos.
- 🛡️ **Segurança e Conformidade**: Pipelines locais de anonimização sob conformidade com a LGPD e auditoria de APIs.

---

## 🤖 Arquitetura de Agentes Inteligentes

Especialista no design de sistemas de agentes autônomos distribuídos que cooperam para resolver fluxos de trabalho empresariais complexos:

```mermaid
graph TD
    %% Fontes de Entrada
    Input[Fontes de Dados: Diários Oficiais, PJe, Editais, APIs] --> Scraper[Agentes de Ingestão: Playwright / BeautifulSoup]
    
    %% Pipeline de Processamento e Vetorização
    Scraper --> Clean[Camada de Higienização e Tokenização Local]
    Clean --> RAG[RAG Engine: Pinecone / ChromaDB / Vetores de Jurisprudência]
    
    %% Orquestrador Central
    RAG --> AgentOrch{Orquestrador de Agentes}
    
    %% Agentes Especialistas
    AgentOrch --> AgentLaw[Agente de Análise Jurídica: Especialista em Júri / Penal]
    AgentOrch --> AgentComp[Agente de Compliance & Editais: Auditor de Riscos]
    AgentOrch --> AgentClin[Agente Clínico: Auditoria MDU & CoT]
    
    %% Validação e Human-in-the-Loop
    AgentLaw & AgentComp & AgentClin --> Val[Validador de Segurança & Human-in-the-Loop]
    
    %% Saída
    Val --> Action[Action Agents: Disparo de Alertas, Geração de Relatórios FHIR/PDF]
```

### 🧠 Abordagem Técnica de IA
* **Agentes de Ingestão**: Web scrapers assíncronos e pipelines robustos estruturados para extração de dados públicos respeitando limites de requisições.
* **Agentes Analistas (Cognição)**: Integração com LLMs avançados operando sob lógica estruturada de prompts, controle estrito de contexto e orquestração modular.
* **Agentes Executores (Ação)**: Geração de entregáveis estruturados (FHIR JSON, relatórios PDF detalhados) e alertas automatizados em canais de comunicação.

---

## 🏆 Projetos em Destaque

<div align="center">
  <h3>🚀 SaaS & Soluções Comerciais</h3>
</div>

<table>
<tr>
<td width="50%">

**⚖️ [Kermartin IA](https://kermartin.onrender.com)**
> **SaaS de Jurimetria Preditiva & Análise Processual**
- **Escopo**: Análise automatizada de processos de rito especial do Júri e decote de qualificadoras (Art. 121, CP).
- **Stack**: Django, React (Vite), Celery, Redis, PostgreSQL, CrewAI (orquestração via prompts em YAML).
- **Diferencial**: Adapters dogmáticos modulares, pipeline local de anonimização LGPD e processamento assíncrono distribuído.
- **Status**: 🟢 Produção (Ativo)

</td>
<td width="50%">

**🏛️ [Licita-AI](https://github.com/clenio77/licita-ai)**
> **GovTech para Compliance de Editais Públicos**
- **Escopo**: Automação do fluxo de requisições e análise inteligente de risco em contratações governamentais.
- **Stack**: Microsoft 365, SharePoint Lists, Power Automate, Azure Functions (Node.js/Graph API), OpenAI API.
- **Diferencial**: Dashboard analítico em Power BI com Row-Level Security e controle completo de auditoria baseado em roles.
- **Status**: 🟢 Produção (Implementado)

</td>
</tr>
</table>

<div align="center">
  <h3>🧪 Pesquisa, IA Local & Open Source</h3>
</div>

<table>
<tr>
<td width="50%">

**🛡️ [MedGemma Guardian](https://github.com/clenio77/MedGemma)**
> **Agente de Auditoria Clínica e Segurança do Paciente**
- **Escopo**: Auditoria automatizada de prescrições médicas para mitigação de hepatotoxicidade (Google Health Impact).
- **Stack**: MedGemma (2b quantizado 4-bit), Python, Chain-of-Thought (CoT), FHIR JSON.
- **Diferencial**: Processamento local em Edge AI (rodando com 4GB VRAM) garantindo privacidade offline absoluta dos pacientes.

</td>
<td width="50%">

**🔒 [Genesys Security Auditor](https://github.com/clenio77/genesys-seguranca-auditoria)**
> **API de Auditoria de Segurança Web & LGPD**
- **Escopo**: Varredura passiva de conformidade de infraestrutura pública e vulnerabilidades de rede.
- **Stack**: FastAPI, BeautifulSoup, SSL Module.
- **Diferencial**: Motor assíncrono focado em análise rápida de cabeçalhos HTTP e validade criptográfica de certificados SSL/TLS.

</td>
</tr>
<tr>
<td width="50%">

**🎵 [SonicStream](https://github.com/clenio77/video-extractor)**
> **Extrator de Áudio & Vídeo com Interface PWA**
- **Escopo**: Conversão assíncrona e download de mídias de plataformas de vídeo.
- **Stack**: FastAPI, yt-dlp, Docker, PWA (Frontend responsivo).
- **Diferencial**: Empacotamento Docker otimizado para deploy simplificado em servidores VPS (DigitalOcean).

</td>
<td width="50%">

**🎯 [Agente Concurseiro](https://github.com/clenio77/agente_concurseiro)**
> **Tutor Inteligente de Estudos com RAG**
- **Escopo**: Assistente de estudos baseado nos editais de exames públicos e materiais de referência.
- **Stack**: LangChain, OpenAI API, Vector Databases.
- **Diferencial**: Geração aumentada de recuperação estruturada para fornecer respostas precisas e referenciadas em leis.

</td>
</tr>
</table>

---

## 🛠️ Stack Tecnológica

<div align="center">

### Engenharia de IA & Orquestração
![CrewAI](https://img.shields.io/badge/-CrewAI-FF6B35?style=flat-square&logo=robot&logoColor=white)
![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![HuggingFace](https://img.shields.io/badge/-HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

### Backend & Engenharia de Dados
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/-Django-092E20?style=flat-square&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

### Automação & Crawlers
![Playwright](https://img.shields.io/badge/-Playwright-45ba4b?style=flat-square&logo=Playwright&logoColor=white)
![Selenium](https://img.shields.io/badge/-Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

### Bancos Vetoriais & Cloud Infrastructure
![Pinecone](https://img.shields.io/badge/-Pinecone-000000?style=flat-square&logo=pinecone&logoColor=white)
![ChromaDB](https://img.shields.io/badge/-ChromaDB-FF6B6B?style=flat-square&logo=database&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Render](https://img.shields.io/badge/-Render-46E3B7?style=flat-square&logo=render&logoColor=white)

</div>

---

## 💼 Linha do Tempo Profissional

<div align="center">

```mermaid
timeline
    title Trajetória e Evolução de Carreira
    2018 : Conclusão de Bacharelado
         : Sistemas de Informação
    2020 : Especialização em Dados
         : Machine Learning & Ciência de Dados (Data Science Academy)
    2024 : Engenharia de IA Avançada
         : Sistemas Multiagente (CrewAI) & RAG (Retrieval-Augmented Generation)
    2025 : Fundador & Arquiteto SaaS
         : Lançamento do Kermartin (SaaS LegalTech) & Genesys Tecnologia (Consultoria)
    2026 : Ecossistemas Inteligentes & Edge AI
         : MedGemma Impact Challenge (Google Health AI)
         : Licita-AI (SharePoint/Power Automate/Azure Functions)
```

</div>

---

## 📊 Estatísticas do GitHub

<div align="center">
  <img height="180" src="https://github-readme-stats-eight-theta.vercel.app/api?username=clenio77&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
  <img height="180" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=clenio77&layout=compact&langs_count=8&theme=tokyonight&hide=html,css"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=clenio77&theme=tokyonight" alt="GitHub Streak"/>
</div>
