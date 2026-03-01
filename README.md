# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 01 de março de 2026

Empresa: Absertgo Industries

Responsável: Vinícius Crispim

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Absertgo Industries, realizado por Vinícius Crispim. O objetivo do projeto foi elencar 3 serviços AWS com a finalidade de promover redução imediata de custos operacionais, aumento de escalabilidade e melhoria na conformidade regulatória, considerando as exigências do setor farmacêutico (BPF, rastreabilidade e retenção documental).

## Descrição do Projeto

O projeto de implementação foi estruturado em três etapas estratégicas, priorizando otimização de infraestrutura, governança de dados laboratoriais e modernização de sistemas internos.

Etapa 1:

Nome da ferramenta: Amazon EC2

Foco da ferramenta: Otimização da infraestrutura computacional e substituição de servidores físicos
Descrição de caso de uso:

A empresa utilizava servidores on-premises para:
- Sistema ERP farmacêutico
- Controle de qualidade (CQ)
- Gestão de pesquisa e desenvolvimento

Foi realizada migração para instâncias EC2 com:

- Instâncias Reservadas para cargas previsíveis
- Auto Scaling para ambientes de testes
- Desativação gradual do parque físico

Resultado esperado:
Redução de custos com manutenção, energia elétrica, refrigeração e contratos de suporte de hardware, além de maior elasticidade operacional.

Etapa 2:

Nome da ferramenta: Amazon S3

Foco da ferramenta: Armazenamento seguro e escalável de dados regulatórios e laboratoriais

Descrição de caso de uso:

A Absertgo Industries armazena grande volume de:

- Documentação regulatória
- Dados de ensaios clínicos
- Registros de produção e controle de lotes
- Backups de relatórios laboratoriais

Foi implementado:

S3 Standard para dados ativos

S3 Glacier para arquivamento de longo prazo

Versionamento e criptografia automática

Resultado esperado:
Redução significativa de custos com storage tradicional e maior segurança na retenção de documentos exigidos por órgãos reguladores.

Etapa 3:

Nome da ferramenta: Amazon RDS

Foco da ferramenta: Gerenciamento otimizado de banco de dados para sistemas críticos

Descrição de caso de uso:

O sistema de rastreabilidade de medicamentos e controle de produção operava em banco de dados local com alto custo de administração.

Foi realizada migração para Amazon RDS com:

- Backups automáticos
- Alta disponibilidade (Multi-AZ)
- Monitoramento integrado

Resultado esperado:
Diminuição de custos com administração manual de banco de dados, maior confiabilidade e redução do risco de indisponibilidade operacional.

Conclusão

A implementação das ferramentas na empresa Absertgo Industries tem como esperado:

Redução imediata de custos operacionais

Aumento da escalabilidade para projetos de P&D

Maior segurança e governança de dados sensíveis

Melhor conformidade regulatória

Recomenda-se a continuidade da modernização da arquitetura em nuvem, com futura adoção de soluções de automação, monitoramento avançado e análise de dados aplicada à pesquisa farmacêutica.


Assinatura do Responsável pelo Projeto:

Vinícius Crispim
Gerente do Projeto Cloud
