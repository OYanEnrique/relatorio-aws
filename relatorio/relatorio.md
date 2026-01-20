# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 19 de janeiro de 2026
Empresa: Farmácia Saúde & Vida
Responsável: Yan Enrique

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Farmácia Saúde & Vida, realizado por Yan Enrique. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos na infraestrutura de TI da farmácia.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon EC2 Auto Scaling
- Dimensionamento automático de recursos para plataforma de e-commerce
- Implementação de políticas de auto scaling no sistema de vendas online da farmácia para ajustar automaticamente a capacidade de instâncias EC2 conforme picos de acesso (horários de maior movimento e promoções), eliminando recursos ociosos durante a madrugada e reduzindo custos operacionais em aproximadamente 35%.

Etapa 2: 
- Amazon S3 Intelligent-Tiering
- Otimização de armazenamento de receitas médicas digitalizadas e documentos fiscais
- Migração de receitas médicas digitalizadas e notas fiscais arquivadas no S3 para camadas de acesso mais econômicas (Infrequent Access para documentos com mais de 90 dias e Archive para registros com mais de 1 ano), baseado em padrões de acesso e requisitos legais, resultando em economia de até 40% nos custos de armazenamento sem comprometer a conformidade regulatória.

Etapa 3: 
- AWS Cost Explorer com Budget Alerts
- Monitoramento e análise de custos da infraestrutura farmacêutica
- Configuração de dashboards personalizados para acompanhar custos de diferentes departamentos (vendas online, sistema de gestão de estoque, backup de dados) e alertas automáticos quando gastos excederem 80% do orçamento mensal, permitindo ações corretivas imediatas e garantindo que recursos de TI não comprometam o orçamento destinado à aquisição de medicamentos.



## Conclusão
A implementação de ferramentas na empresa *Farmácia Saúde & Vida tem como esperado uma redução de custos operacionais de TI na ordem de 38% nos primeiros seis meses, além de proporcionar maior controle financeiro, otimização de recursos e escalabilidade inteligente da infraestrutura de vendas online e gestão documental*, o que aumentará a eficiência operacional e permitirá maior investimento em estoque de medicamentos e atendimento ao cliente. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da farmácia.

## Anexos

- [Documentação AWS EC2 Auto Scaling](https://aws.amazon.com/ec2/autoscaling/) - Guia oficial de configuração e melhores práticas
- [Amazon S3 Intelligent-Tiering](https://aws.amazon.com/s3/storage-classes/intelligent-tiering/) - Detalhes sobre otimização automática de armazenamento
- [AWS Cost Explorer](https://aws.amazon.com/aws-cost-management/aws-cost-explorer/) - Ferramenta de análise e visualização de custos
- [AWS Well-Architected Framework](https://aws.amazon.com/architecture/well-architected/) - Framework de boas práticas para otimização de custos
- [AWS Pricing Calculator](https://calculator.aws/) - Calculadora para estimativa e comparação de custos

Responsável pelo Projeto:

Yan Enrique
