<div align="center">

<h1>Alby Rajesh</h1>

<h3>AI/ML Engineer &nbsp;·&nbsp; LLM Systems &nbsp;·&nbsp; Knowledge Graphs &nbsp;·&nbsp; Retrieval</h3>

<p><b>Turning unstructured data into queryable knowledge</b><br/><sub>Agentic Text-to-SQL &nbsp;•&nbsp; Text-to-Cypher &nbsp;•&nbsp; Graph RAG &nbsp;•&nbsp; Schema-constrained LLM pipelines</sub></p>

<br/>

<a href="https://www.linkedin.com/in/alby-rajesh-187721202"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:albyrajeshwork@gmail.com"><img src="https://img.shields.io/badge/Email-1F2937?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<img src="https://img.shields.io/badge/Kerala,_India-1F2937?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Kerala, India"/>
<img src="https://img.shields.io/badge/Open_to_opportunities-2EA44F?style=for-the-badge" alt="Open to opportunities"/>

</div>

<br/>

## About

I'm an **AI/ML Engineer at Feathersoft Info Solutions**, building production GenAI systems for enterprise clients in agriculture and healthcare. My work sits where language models meet structured data: agents that write SQL and Cypher, pipelines that extract knowledge graphs from documents, and retrieval systems that ground every answer in its source.

<table>
<tr>
<td width="50%" valign="top">

**Focus**
- LLM agents and tool calling
- Knowledge graphs and Graph RAG
- Hybrid retrieval (BM25 + dense)
- Structured, schema-constrained extraction

</td>
<td width="50%" valign="top">

**Principles**
- Every answer traceable to a source
- Schemas over prompt hacks
- Small, tested, observable pipelines
- Ship it, measure it, improve it

</td>
</tr>
</table>

## Featured projects

<table>
<tr>
<td width="50%" valign="top">

### [text2cypher-agent](https://github.com/Alby-Rajesh/text2cypher-agent)

**Agentic Text-to-Cypher** over Neo4j. A QLoRA fine-tuned Qwen2.5-Coder model writes Cypher; a LangGraph agent validates it with `EXPLAIN`, self-corrects on errors and answers from the results. Redis cache and memory, LangSmith tracing and execution-accuracy evals.

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![QLoRA](https://img.shields.io/badge/QLoRA-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

</td>
<td width="50%" valign="top">

### [voice-text2sql](https://github.com/Alby-Rajesh/voice-text2sql)

A **voice data analyst** for Postgres. Ask out loud, hear the answer, see the SQL, table and chart. LangGraph agent with DSPy SQL generation tuned by MIPROv2 on an execution-accuracy metric; sqlglot AST guard plus read-only transactions.

![DSPy](https://img.shields.io/badge/DSPy-8A2BE2?style=flat-square)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Voice](https://img.shields.io/badge/STT_%2F_TTS-FF6F61?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [unstructured-2-kg](https://github.com/Alby-Rajesh/unstructured-2-kg)

PDF → ontology-linked **Neo4j knowledge graph**. Schema-constrained extraction on vLLM, grounded facts, tiered entity resolution and NCBI Taxonomy / ChEBI / LOINC linking. Dockerised, tested in CI.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-30A2FF?style=flat-square)
![Docling](https://img.shields.io/badge/Docling-6E56CF?style=flat-square)

</td>
<td width="50%" valign="top">

### [repo-copilot](https://github.com/Alby-Rajesh/repo-copilot)

An **agent for GitHub repositories**. Searches code, reads files and commit history, answers with `path:line` citations, and drafts issues for human approval.

**[Live demo →](https://repo-copilot.vercel.app)**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square)
![Supabase](https://img.shields.io/badge/pgvector-3FCF8E?style=flat-square&logo=supabase&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [multi-agent-research](https://github.com/Alby-Rajesh/multi-agent-research)

**Cited research reports** from a document collection. LlamaIndex hybrid RAG on pgvector (vector + full-text, RRF) feeding CrewAI crews in three patterns: sequential, manager-led hierarchical, and a self-reviewing reflection Flow. Retrieval and LLM-judge evals.

![CrewAI](https://img.shields.io/badge/CrewAI-FF5A50?style=flat-square)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-8B5CF6?style=flat-square)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)

</td>
<td width="50%" valign="top">

### [hybrid-rag](https://github.com/Alby-Rajesh/hybrid-rag)

**Document Q&A** with keyword and vector search fused by Reciprocal Rank Fusion, cited answers, and a UI that explains why each passage was retrieved.

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Supabase](https://img.shields.io/badge/pgvector-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

</td>
</tr>
</table>

## Experience

**AI/ML Engineer · Feathersoft Info Solutions** &nbsp;·&nbsp; *Jul 2025 – present*

- **Agentic Text-to-SQL assistant and voice agent** for an agriculture enterprise, letting business users query operational data in plain language, by chat or by voice.
- **Patient knowledge graph** for a rheumatology platform, with Text-to-Cypher and Graph RAG over clinical data in Neo4j.
- **Autonomous PDF-to-knowledge-graph agent** that extracts entities and relationships from documents and loads them into a graph database.

## Tech stack

<p align="center">
<img src="https://skillicons.dev/icons?i=py,ts,pytorch,sklearn,postgres,redis,supabase,fastapi,nextjs,docker,githubactions,linux,git&perline=13" alt="Tech stack"/>
</p>

<p align="center">
<img src="https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white" alt="Neo4j"/>
<img src="https://img.shields.io/badge/vLLM-30A2FF?style=flat-square" alt="vLLM"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain"/>
<img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face"/>
<img src="https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white" alt="pgvector"/>
<img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white" alt="Pydantic"/>
<img src="https://img.shields.io/badge/Docling-6E56CF?style=flat-square" alt="Docling"/>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangGraph"/>
<img src="https://img.shields.io/badge/LangSmith-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangSmith"/>
<img src="https://img.shields.io/badge/DSPy-8A2BE2?style=flat-square" alt="DSPy"/>
<img src="https://img.shields.io/badge/CrewAI-FF5A50?style=flat-square" alt="CrewAI"/>
<img src="https://img.shields.io/badge/LlamaIndex-8B5CF6?style=flat-square" alt="LlamaIndex"/>
<img src="https://img.shields.io/badge/QLoRA_fine--tuning-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="QLoRA fine-tuning"/>
</p>

## Credentials

- **Claude Certified Developer – Foundations** · Anthropic · Sep 2026 · score 910 / 1000
- **B.Tech, Electronics and Communication Engineering** · Rajagiri School of Engineering, Kochi · 2021 – 2025

<br/>

<div align="center">

**Open to AI/ML, GenAI and backend engineering roles, in India or abroad.**
<br/>
<a href="mailto:albyrajeshwork@gmail.com">albyrajeshwork@gmail.com</a> &nbsp;·&nbsp; <a href="https://www.linkedin.com/in/alby-rajesh-187721202">LinkedIn</a>


</div>
