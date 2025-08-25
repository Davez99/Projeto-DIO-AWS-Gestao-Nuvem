# Relatório de Implementação de Serviços AWS

**Data:** 25/08/2025
**Empresa:** Abstergo Industries
**Responsável:** Davi Terres (@Davez99)

## Introdução
Este relatório detalha o processo de implementação de soluções na Amazon Web Services (AWS) para a empresa Abstergo Industries. O objetivo principal do projeto foi **identificar e aplicar três serviços AWS para alcançar uma redução imediata e significativa nos custos operacionais** de computação e armazenamento.

## Descrição do Projeto
O projeto foi dividido em três etapas estratégicas, cada uma focada na aplicação de uma ferramenta específica para otimização de custos.

### Etapa 1: Implementação de Savings Plans
Nesta etapa, focamos em otimizar os custos de computação de cargas de trabalho com uso previsível.

* **O que é:** O **Savings Plans** é um modelo de precificação flexível que oferece descontos substanciais (até 72%) em troca de um compromisso de uso contínuo por um ou três anos.
* **Ações:** Foi realizada uma análise do histórico de uso das instâncias EC2 e Lambda para determinar o nível de compromisso ideal. Com base nisso, foi adquirido um plano que cobriu a maior parte das cargas de trabalho estáveis, garantindo a redução de custos sem a complexidade de gerenciar instâncias reservadas.
* **Benefício Esperado:** Redução imediata e previsível nos custos de computação.

### Etapa 2: Otimização com AWS Trusted Advisor
Esta etapa se concentrou na identificação de oportunidades de economia por meio de auditoria e análise de melhores práticas.

* **O que é:** O **AWS Trusted Advisor** é uma ferramenta de consultoria online que analisa o ambiente AWS e fornece recomendações para otimizar custos, segurança, desempenho e tolerância a falhas.
* **Ações:** O Trusted Advisor foi configurado para gerar relatórios regulares. Suas recomendações foram seguidas para identificar e desligar recursos ociosos (como instâncias não utilizadas ou volumes EBS desanexados) e para redimensionar instâncias superdimensionadas que geravam gastos desnecessários.
* **Benefício Esperado:** Redução de custos ao eliminar desperdícios e ajustar recursos subutilizados.

### Etapa 3: Adoção de AWS Spot Instances
Nesta fase, a estratégia foi utilizar capacidade de computação não utilizada para cargas de trabalho flexíveis, maximizando a economia.

* **O que é:** As **AWS Spot Instances** são instâncias de computação que permitem o uso de capacidade não utilizada da AWS com descontos de até 90% em comparação com o preço sob demanda. São ideais para cargas de trabalho que podem ser interrompidas e reiniciadas sem impactar o serviço, como processamento em lote ou testes.
* **Ações:** Identificamos as cargas de trabalho da Abstergo Industries que poderiam ser executadas em instâncias Spot sem riscos, como o processamento de dados analíticos e a execução de testes de integração. A automação foi implementada para gerenciar o ciclo de vida dessas instâncias, garantindo que fossem utilizadas de forma eficiente.
* **Benefício Esperado:** Grande potencial de economia para cargas de trabalho flexíveis e esporádicas.

---

## Conclusão
A implementação conjunta das ferramentas **AWS Savings Plans**, **Trusted Advisor** e **Spot Instances** na Abstergo Industries resultou em uma estratégia de otimização de custos robusta e multifacetada. O projeto não apenas alcançou a meta de **reduzir os custos operacionais de forma imediata**, mas também estabeleceu uma base sólida para a gestão contínua e eficiente dos recursos em nuvem. A utilização dessas ferramentas aumentará a eficiência e a produtividade da empresa, liberando recursos financeiros para serem investidos em outras áreas estratégicas.

Recomenda-se a continuidade da utilização dessas ferramentas e a avaliação periódica de novas tecnologias que possam melhorar ainda mais os processos e a eficiência financeira da empresa.

---

**Assinatura do Responsável do Projeto:**
Davi Terres - Desenvolvedor .NET C# - @Davez99