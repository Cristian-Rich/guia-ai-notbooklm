Com base nos documentos fornecidos, a alta disponibilidade (HA) em sistemas distribuídos é alcançada através de uma combinação de infraestrutura resiliente, automação e práticas de observabilidade. Abaixo está um checklist de 8 práticas essenciais:

1.  **Replicação de Dados em Múltiplas Zonas de Disponibilidade (AZs):** Para garantir que o sistema continue operando mesmo em caso de falha em um data center, os dados devem ser replicados automaticamente entre diferentes zonas.
    *   **Serviço AWS:** **Amazon ElastiCache Serverless** (que replica dados automaticamente entre AZs).
2.  **Escalabilidade Automática (Vertical e Horizontal):** O sistema deve ser capaz de monitorar a utilização de computação, memória e rede para escalar instantaneamente e atender à demanda sem tempo de inatividade.
    *   **Serviço AWS:** **AWS Lambda** ou **Amazon ElastiCache Serverless**.
3.  **Gestão Centralizada de Backups:** Implementar políticas de backup automatizadas para garantir a recuperação de dados em caso de desastres ou falhas críticas.
    *   **Serviço AWS:** **AWS Backup**.
4.  **Monitoramento e Observabilidade Centralizada:** Estabelecer uma camada de observabilidade para obter visibilidade em tempo real do que está acontecendo no sistema e detectar falhas precocemente.
    *   **Ferramenta/Conceito:** **Capacidades DORA** de monitoramento e observabilidade.
5.  **Atualizações e Patches Automáticos:** Reduzir janelas de manutenção e riscos de segurança através de atualizações automáticas de versões menores em bancos de dados.
    *   **Serviço AWS:** **Amazon RDS / Aurora** (políticas de upgrade automático).
6.  **Proteção de Borda e Filtragem de Tráfego:** Utilizar firewalls de aplicação para criar regras que protejam o sistema contra ataques e gerenciem picos de tráfego malicioso.
    *   **Serviço AWS:** **AWS WAF (Web Application Firewall)**.
7.  **Arquiteturas Serverless para Redução de Gerenciamento:** Adotar modelos serverless para eliminar a necessidade de provisionamento de infraestrutura, permitindo que a plataforma gerencie a disponibilidade e a escalabilidade.
    *   **Serviço AWS:** **AWS Lambda**.
8.  **Entrega Contínua (Continuous Delivery) e Automação de Implantação:** Remover gargalos manuais e garantir que novas versões do software sejam lançadas de forma segura e frequente, apoiadas por testes automatizados.
    *   **Prática/Ferramenta:** **Continuous Delivery** com bases sólidas de teste.
