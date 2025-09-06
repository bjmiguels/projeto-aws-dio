# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS
Data: 05 de Setembro de 2025
Empresa: Abstergo Industries
Responsável: Bruno Joaquim da Silva

## Introdução
Este relatório apresenta uma proposta estratégica para a implementação de três 
serviços da Amazon Web Services (AWS) na Abstergo Industries. O objetivo do projeto 
é demonstrar como a adoção destes serviços pode gerar uma diminuição de custos 
imediata e significativa, ao mesmo tempo que aumenta a agilidade e a capacidade 
de inovação da empresa no setor farmacêutico.

## Descrição do Projeto
O projeto de otimização de custos foi distribuído em 3 etapas, cada uma focada em 
um pilar crítico da infraestrutura de TI de uma empresa farmacêutica.


### Etapa 1: Otimização Radical de Armazenamento de Dados
Nome da ferramenta: Amazon S3 (com S3 Intelligent-Tiering e S3 Glacier Deep Archive)

Foco da ferramenta: Armazenamento de dados de baixo custo, seguro e escalável.

Descrição do caso de uso: A indústria farmacêutica gera petabytes de dados (dados 
genômicos, resultados de ensaios clínicos, imagens de pesquisa, documentação 
regulatória) que precisam ser armazenados por muitos anos. Manter esses dados em sistemas de armazenamento caros (on-premises) é ineficiente. Com o Amazon S3, os dados podem ser armazenados de forma segura e durável. Usando o S3 Intelligent-Tiering, os dados menos acessados são movidos automaticamente para camadas mais baratas, sem nenhuma intervenção. Para arquivamento de longo prazo (dados que precisam ser guardados por 10+ anos por questões regulatórias), o S3 Glacier Deep Archive oferece um custo drasticamente menor, liberando capital que antes era gasto em discos e manutenção.

### Etapa 2: Supercomputação para Pesquisa sob Demanda
Nome da ferramenta: Amazon EC2 Spot Instances

Foco da ferramenta: Computação de alto desempenho com até 90% de desconto.

Descrição do caso de uso: Pesquisa e desenvolvimento (P&D) em farmácia, como modelagem molecular, simulações de descoberta de medicamentos e análise genômica, exigem um poder computacional massivo, mas que não é necessário 24/7. Manter um cluster de supercomputação local é extremamente caro. Com as EC2 Spot Instances, a Abstergo pode acessar uma capacidade computacional gigantesca pagando apenas pela capacidade ociosa da AWS, com um desconto de até 90% em comparação ao preço normal. Isso permite que os pesquisadores rodem análises complexas em horas, em vez de dias, por uma fração do custo de manter uma infraestrutura própria.

### Etapa 3: Análise de Dados Inteligente e sem Servidor
Nome da ferramenta: Amazon Athena

Foco da ferramenta: Análise de dados interativa diretamente no Amazon S3, pagando apenas pela consulta.

Descrição do caso de uso: Após armazenar todos os dados de pesquisa e operacionais no Amazon S3 (Etapa 1), surge a necessidade de analisá-los. Em vez de construir e manter um Data Warehouse caro, o Amazon Athena permite que analistas e cientistas de dados usem linguagem SQL padrão para consultar os dados diretamente onde eles estão. Não há infraestrutura para gerenciar e o custo é baseado apenas nos dados escaneados pela consulta. Isso permite, por exemplo, cruzar dados de ensaios clínicos de diferentes anos de forma rápida e barata, sem a necessidade de um projeto complexo de Big Data.

## Conclusão
A implementação conjunta de Amazon S3, EC2 Spot Instances e Athena na Abstergo Industries tem como resultado esperado uma redução significativa nos custos de armazenamento e processamento de dados, maior agilidade nas pesquisas científicas e otimização da análise de dados em larga escala. A adoção desses serviços não apenas economiza dinheiro, mas também posiciona a empresa para inovar mais rapidamente. Recomenda-se a implementação de um projeto piloto para validar os benefícios e a busca contínua por otimizações na nuvem AWS.

#### Assinatura do responsável pelo projeto:
*Bruno Joaquim da Silva*
