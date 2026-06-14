# PROMPT_LOG

## Entrada 1 — Arquitetura evolutiva 
- **Objetivo do prompt:** Obter uma definição prática e exemplos acionáveis para iniciantes, alinhados ao propósito do segundo cérebro.  
- **Prompt original:**  
```
Defina "arquitetura evolutiva" em 5 bullets claros; inclua 2 exemplos práticos de migração incremental de monolito para microserviços; cite as fontes usadas entre as fontes carregadas no NotebookLM.  
```
- **Variações testadas:** pedir anti‑padrões; pedir checklist de passos; limitar a "máx. 150 palavras".  
- **Resposta obtida (resumo):** 5 pontos: adaptabilidade; modularidade; testes automatizados; Continuous Delivery; refatoração incremental; exemplos de extração por domínio e desacoplamento de dependências.  
- **Fontes citadas pela IA:** Martin Fowler; DORA; materiais do NotebookLM (GOTO/InfoQ/AWS).  
- **O que funcionou:** formato em bullets e exemplos práticos facilitaram compreensão para iniciantes.  
- **O que falhou / limitações:** faltaram anti‑padrões com pseudocódigo e passos operacionais detalhados.  
- **Ação de troubleshooting:** reexecutar com "Inclua 3 anti‑padrões com pseudocódigo e um checklist de 5 passos para iniciar a extração de um domínio."  
- **Prompt final reutilizável:**
```
Defina "arquitetura evolutiva" em 5 bullets; inclua 2 exemplos práticos de migração incremental de monolito para microserviços; adicione 3 anti‑padrões com pseudocódigo e um checklist de 5 passos iniciais; cite as fontes usadas.
```
---

## Entrada 2 — Checklist de alta disponibilidade 
- **Objetivo do prompt:** Gerar checklist aplicável em AWS com serviço associado e comando/snippet mínimo.  
- **Prompt original:**  
```
 Gere um checklist de 8 práticas para alta disponibilidade em sistemas distribuídos; associe cada prática a um serviço AWS ou ferramenta equivalente e forneça um comando AWS CLI ou snippet CloudFormation/terraform mínimo.``  
```
- **Variações testadas:** pedir apenas serviços; pedir estimativa de custo; pedir exemplos serverless.  
- **Resposta obtida (resumo):** práticas listadas (replicação, autoscaling, backups, observabilidade, WAF, serverless, CD); faltaram comandos CLI específicos.  
- **Fontes citadas pela IA:** AWS blogs; All Things Distributed; materiais do NotebookLM.  
- **O que funcionou:** lista de práticas aplicáveis e mapeamento para serviços AWS.  
- **O que falhou / limitações:** ausência de comandos/snippets prontos.  
- **Ação de troubleshooting:** reexecutar com "Inclua o comando AWS CLI ou snippet CloudFormation/terraform para cada item; indique permissões mínimas necessárias."  
- **Prompt final reutilizável:**  
```
 Gere um checklist de 8 práticas para alta disponibilidade; associe cada prática a um serviço AWS e inclua um comando AWS CLI ou snippet CloudFormation/terraform mínimo e as permissões IAM necessárias; cite fontes.
```
---

## Entrada 3 — Mapeamento de capacidades e event‑storming 
- **Objetivo do prompt:** Entender o processo e gerar um passo a passo prático para aplicar mapeamento de capacidades + event‑storming em um monolito.  
- **Prompt original:**  
```
Explique o processo de mapeamento de capacidades para microserviços em 6 passos; inclua como integrar event‑storming e como priorizar incrementos de modernização; cite fontes.  
```
- **Variações testadas:** pedir template de workshop; pedir exemplos de artefatos (mapas, tickets).  
- **Resposta obtida (resumo):** visão de plano diretor; critérios Build vs Buy; definição de incrementos; sinergia com event‑storming; redução de dependências.  
- **Fontes citadas pela IA:** Thoughtworks; Martin Fowler; materiais do NotebookLM.  
- **O que funcionou:** passos estratégicos e justificativa para priorização.  
- **O que falhou / limitações:** faltaram templates prontos de artefatos e exemplos de tickets para backlog.  
- **Ação de troubleshooting:** reexecutar com "Forneça 3 templates: mapa de capacidades (exemplo), roteiro de event‑storming (agenda) e modelo de ticket para extração de domínio."  
- **Prompt final reutilizável:**  
```
Explique o processo de mapeamento de capacidades para microserviços em 6 passos; inclua um template de mapa de capacidades, uma agenda de event‑storming e um modelo de ticket para priorizar incrementos; cite fontes.
```
---

## Entrada 4 — Plano de estudos 4 semanas 
- **Objetivo do prompt:** Gerar um plano prático, com leituras, exercícios e prompts de revisão para o NotebookLM.  
- **Prompt original:**  
```
Monte um plano de estudos de 4 semanas para um desenvolvedor iniciante aprender arquitetura evolutiva e sistemas distribuídos; inclua leituras das fontes carregadas, exercícios práticos semanais e 2 prompts de revisão por semana para usar no NotebookLM.  
```
- **Variações testadas:** plano de 8 semanas; incluir projetos de portfólio.  
- **Resposta obtida (resumo):** plano com leituras semanais, exercícios práticos (modularizar código, CI, diagrama AZs, Lambda) e prompts de revisão; faltaram prompts prontos por semana.  
- **Fontes citadas pela IA:** Martin Fowler; GOTO; InfoQ; AWS.  
- **O que funcionou:** sequência de aprendizado clara e exercícios aplicáveis.  
- **O que falhou / limitações:** prompts de revisão não estavam prontos para copiar/colar.  
- **Ação de troubleshooting:** reexecutar com "Adicione 2 prompts prontos por semana, prontos para colar no NotebookLM."  
- **Prompt final reutilizável:**  
```
Monte um plano de estudos de 4 semanas com leituras das fontes carregadas, exercícios práticos semanais e 2 prompts prontos por semana para revisão no NotebookLM; cite fontes.
```
---
