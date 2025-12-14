# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 14/12/2025
**Empresa:** Abstergo Industries
**Responsável:** Lucas Gabriel Santiago

## Introdução

Este relatório apresenta o processo de implementação de serviços da Amazon Web Services (AWS) na empresa **Abstergo Industries**, realizado por **Lucas Ferreira**. O objetivo principal do projeto foi selecionar e implementar **três serviços AWS** com foco em **redução imediata de custos operacionais**, sem comprometer a disponibilidade, a segurança e o desempenho dos ambientes em nuvem.

## Descrição do Projeto

O projeto de implementação foi dividido em três etapas, cada uma contemplando um serviço AWS específico, alinhado às melhores práticas de otimização de custos do AWS Well-Architected Framework.

### Etapa 1: AWS Cost Explorer

* **Foco da ferramenta:** Visibilidade e análise de custos
* **Descrição do caso de uso:**
  O AWS Cost Explorer foi utilizado para analisar detalhadamente os gastos da conta AWS, permitindo identificar quais serviços, regiões e recursos estavam gerando maior impacto financeiro. A ferramenta possibilitou a visualização de tendências de consumo, a identificação de picos inesperados e a criação de previsões de gastos. Com base nessas informações, foi possível tomar decisões rápidas para eliminar desperdícios e ajustar recursos superdimensionados.

### Etapa 2: AWS Trusted Advisor

* **Foco da ferramenta:** Recomendações automáticas de otimização
* **Descrição do caso de uso:**
  O AWS Trusted Advisor foi empregado para avaliar o ambiente AWS e fornecer recomendações relacionadas à redução de custos, segurança, desempenho e tolerância a falhas. No contexto de custos, a ferramenta identificou recursos ociosos, como instâncias EC2 subutilizadas e volumes EBS não anexados, possibilitando sua remoção ou redimensionamento imediato, resultando em economia direta.

### Etapa 3: Amazon S3 – Políticas de Ciclo de Vida (Lifecycle)

* **Foco da ferramenta:** Otimização de armazenamento
* **Descrição do caso de uso:**
  Foram configuradas políticas de ciclo de vida no Amazon S3 para mover automaticamente objetos pouco acessados para classes de armazenamento mais econômicas, como S3 Standard-IA e S3 Glacier. Essa estratégia reduziu significativamente os custos de armazenamento de dados históricos e arquivos de backup, mantendo a conformidade e a disponibilidade quando necessário.

## Conclusão

A implementação dos serviços AWS na empresa **Abstergo Industries** tem como resultado esperado a **redução imediata de custos operacionais**, maior controle financeiro sobre os recursos em nuvem e a adoção de boas práticas de governança. Além da economia, as ferramentas proporcionam maior visibilidade, previsibilidade e eficiência operacional.

Recomenda-se a continuidade do uso das ferramentas implementadas, bem como a avaliação futura de soluções adicionais, como **Savings Plans**, **Reserved Instances** e **Auto Scaling**, visando ampliar ainda mais a otimização de custos e a maturidade da infraestrutura em nuvem.

## Anexos

* Relatórios do AWS Cost Explorer
* Recomendações do AWS Trusted Advisor
* Documentação das políticas de ciclo de vida do Amazon S3

---

**Assinatura do Responsável pelo Projeto:**

Lucas Gabriel Santiago Ferreira
