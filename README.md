# guia-ai-notbooklm
Repositório com a intenção de aprofundar os conhecimentos de IA e utilização do notbooklm 

## Contexo
Ideia é a utilização do NotebookLM para criar um segundo cérebro, baseado nos melhores desenvolvedores de software e pesquisadores de engenharia de software modernos e da atualidade. 
Com o Objetivo de auxiliar nos estudos de AI de desenvolvedores iniciantes.

## Fontes Utilizadas:
Foram utilizados fontes baseadas em textos e canais do youtube como:

- https://www.youtube.com/watch?v=e0KKcsgs1Oc
- https://www.youtube.com/@GOTOconferences
- https://www.youtube.com/@infoq
- https://www.youtube.com/@AmazonWebServices
- https://martinfowler.com/
- https://www.allthingsdistributed.com/

## Como usar este repositório
1. Leia o [miniguide.md](miniguide.md) para o resumo consolidado e os prompts reutilizáveis.  
2. Abra [PROMPT_LOG.md](PROMPT_LOG.md) para ver os prompts testados, variações e troubleshooting.
3. Na pasta [sumario](sumario) deve conter respostas completas do NotebookLM (um arquivo por entrada, nomeados como `entrada-01.md`, `entrada-02.md`, ...).

## Engenharia de Prompts e Cicatrizes
**Princípios rápidos**
- Sempre inclua contexto “com base nas fontes carregadas no NotebookLM”.  
- Defina formato “em 5 bullets”, “máx. 150 palavras”, “incluir comando CLI”.  
- Peça fontes “cite as fontes usadas e trechos relevantes”.  
- Itere: registre variações e ações de troubleshooting.

**Template de registro PROMPT_LOG.md
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
