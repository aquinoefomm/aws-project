# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS
Data: 19/12/2025
Empresa: Abstergo Industries
Responsável: Everton de Aquino Peres

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Everton de Aquino Peres. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do projeto
O projeto de implementação de ferramentas foi divido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1:
•	Nome da ferramenta: AWS Cost Explorer
•	Foco da ferramenta: Análise e controle de custos
•	Descrição de caso de uso:
O AWS Cost Explorer foi utilizado para identificar serviços com maior consumo financeiro, recursos subutilizados e picos de gasto inesperados. A ferramenta permitiu a visualização detalhada dos custos por serviço, conta e período, possibilitando decisões rápidas como desligamento de recursos ociosos e revisão de dimensionamento de instâncias, resultando em redução imediata de despesas.

Etapa 2:
•	Nome da ferramenta: Amazon EC2 Auto Scaling com instâncias Spot
•	Foco da ferramenta: Otimização de custos de processamento
•	Descrição de caso de uso:
A implementação de Auto Scaling associada ao uso de instâncias Spot permitiu ajustar automaticamente a capacidade computacional conforme a demanda. Para cargas de trabalho não críticas, como processamento de dados, testes e ambientes de homologação, as instâncias Spot proporcionaram redução significativa de custos em comparação às instâncias sob demanda, sem comprometer a operação principal da empresa.

Etapa 3:
•	Nome da ferramenta: Amazon S3 Intelligent-Tiering
•	Foco da ferramenta: Otimização de custos de armazenamento
•	Descrição de caso de uso:
O Amazon S3 Intelligent-Tiering foi aplicado para armazenar grandes volumes de dados laboratoriais, relatórios e históricos regulatórios. O serviço move automaticamente os dados entre camadas de acesso frequente e infrequente, conforme o padrão de uso, eliminando a necessidade de gerenciamento manual e reduzindo custos de armazenamento a médio e longo prazo.


## Conclusão 
A implementação das ferramentas na empresa Abstergo Industries tem como resultado esperado a redução imediata e sustentável de custos operacionais, maior visibilidade financeira, melhor aproveitamento dos recursos computacionais e otimização do armazenamento de dados. Essas melhorias aumentam a eficiência operacional e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a avaliação periódica de novos serviços AWS que possam ampliar ainda mais a eficiência e a redução de custos.

## Anexos
- AWS Cost Explorer Documentation: https://docs.aws.amazon.com/cost-management/latest/userguide/ce-what-is.html  
- Amazon EC2 Auto Scaling Documentation: https://docs.aws.amazon.com/autoscaling/  
- AWS Spot Instances User Guide: https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-spot-instances.html  
- Amazon S3 Intelligent-Tiering User Guide: https://docs.aws.amazon.com/AmazonS3/latest/userguide/intelligent-tiering.html  


Assinatura do Responsável pelo Projeto:

Everton de Aquino Peres





