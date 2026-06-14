# guia-ai-notebooklm

Repositório para aprofundar conhecimentos em IA usando o NotebookLM como um "segundo cérebro".

## Contexto
Objetivo: usar o NotebookLM para consolidar estudos sobre arquitetura evolutiva, sistemas distribuídos e boas práticas de engenharia, criando material reutilizável para desenvolvedores iniciantes.

## Fontes utilizadas (3–5)
As seguintes fontes foram usadas como base e carregadas no NotebookLM:
- https://www.youtube.com/watch?v=e0KKcsgs1Oc
- https://www.youtube.com/@GOTOconferences
- https://www.youtube.com/@infoq
- https://www.youtube.com/@AmazonWebServices
- https://martinfowler.com/
- https://www.allthingsdistributed.com/

## Estrutura do repositório
- **README.md** — visão geral e instruções de entrega.  
- **MINIGUIDE.md** — resumos, prompts reutilizáveis e glossário.  
- **PROMPT_LOG.md** — registro de prompts, variações, troubleshooting e link para respostas completas.  
- **summaries/** — respostas completas do NotebookLM (um arquivo por entrada, ex.: `entrada-01.md`).  

## Como usar este repositório
1. Leia o [MINIGUIDE.md](MINIGUIDE.md) para o resumo consolidado e prompts reutilizáveis.  
2. Consulte o [PROMPT_LOG.md](PROMPT_LOG.md) para ver os prompts testados, variações e troubleshooting.  
3. Abra a pasta `sumarios/` para ver as respostas completas do NotebookLM (cada arquivo inclui `Fontes usadas:`).

## Engenharia de Prompts (template)
Use este template no `PROMPT_LOG.md` para cada experimento:
```markdown
**Título:**  
**Data:**  
**Objetivo do prompt:**  
**Prompt original:**  
**Variações testadas:**  
**Resposta obtida (resumo):**  
**Fontes citadas pela IA:**  
**O que funcionou:**  
**O que falhou / limitações:**  
**Ação de troubleshooting:**  
**Prompt final reutilizável:**  
**Resposta completa:** summaries/entrada-XX.md
