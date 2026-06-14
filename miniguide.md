# MINIGUIDE

## Resumo rápido
Este miniguia reúne o essencial sobre arquitetura evolutiva, sistemas distribuídos e boas práticas para quem está começando. Use os prompts no NotebookLM para revisar e praticar.

---

## Arquitetura evolutiva
**O que é:** projetar software para mudar com facilidade.  
**Pontos principais:**  
- **Adaptabilidade:** aceitar mudanças sem reescrever tudo.  
- **Modularidade:** dividir em módulos desacoplados.  
- **Testes automatizados:** proteger refatorações.  
- **Entrega contínua:** deploys frequentes e seguros.  
- **Refatoração incremental:** pequenas mudanças com feedback.  
**Exemplo prático:** extrair uma funcionalidade do monolito como microserviço e testar com contratos.

---

## Sistemas distribuídos
**O que é:** vários serviços ou nós trabalhando juntos.  
**Pontos principais:**  
- **CAP:** entender consistência versus disponibilidade.  
- **Tolerância a falhas:** replicação entre zonas de disponibilidade.  
- **Recuperação:** retries, circuit breaker, backoff exponencial.  
- **Observabilidade:** logs, métricas e tracing.  
- **Escalabilidade:** sharding e replicação.  
**Checklist rápido:** replicação; autoscaling; backups; monitoramento; WAF; pipelines de CD.

---

## Boas práticas de engenharia
**Pontos principais:**  
- **Revisão de código:** code review e colaboração.  
- **Automação:** testes e CI/CD.  
- **Observabilidade:** monitorar e aprender com incidentes.  
- **Design por domínio:** modelar o negócio antes do código.  
- **Aprendizado prático:** exercícios e projetos pequenos.

---

## Prompts prontos (cole no NotebookLM)
- `Defina "arquitetura evolutiva" em 5 bullets; inclua 1 exemplo prático.`  
- `Liste 6 sinais de que um sistema precisa de refatoração e uma ação imediata para cada.`  
- `Gere um checklist de 8 práticas para alta disponibilidade; associe cada item a um serviço AWS.`  
- `Monte um plano de estudos de 4 semanas com leituras e exercícios práticos.`

---

## Glossário
- **Arquitetura evolutiva** — projeto que facilita mudanças contínuas no sistema.  
- **Modularidade** — divisão do sistema em partes independentes.  
- **Microserviço** — serviço pequeno e implantável separadamente.  
- **Monolito** — aplicação única que concentra várias responsabilidades.  
- **Refatoração** — melhorar a estrutura do código sem alterar comportamento.  
- **CI/CD** — integração contínua e entrega contínua.  
- **Testes automatizados** — testes executáveis que evitam regressões.  
- **Observabilidade** — entender o sistema por logs, métricas e traces.  
- **SLO / SLI** — objetivo de nível de serviço e indicador para medir confiabilidade.  
- **CAP** — Consistency, Availability, Partition tolerance.  
- **Alta disponibilidade** — design que minimiza tempo de indisponibilidade.  
- **Sharding** — particionamento horizontal de dados.  
- **Circuit breaker** — padrão para isolar falhas em chamadas remotas.  
- **Backoff exponencial** — aumentar intervalos entre tentativas após falhas.  
- **Idempotência** — operação repetida sem efeitos colaterais.  
- **Event-storming** — técnica para mapear processos de negócio.  
- **Mapeamento de capacidades** — visão de alto nível das funcionalidades do negócio.  
- **Agentic AI** — agentes de IA que executam tarefas com autonomia.  
- **Postmortem** — análise de incidente focada em aprendizado.  
- **Observability pipeline** — fluxo de coleta e processamento de 
