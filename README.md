# FARMACIA---DIO-


RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS
Data: 05/2025
 Empresa: Abstergo Industries
 Responsável: Ramon Lucas

1. Introdução
Este relatório apresenta o processo de implementação de serviços na Abstergo Industries, conduzido por Ramon Lucas.
O objetivo principal do projeto foi identificar e implementar três serviços da AWS que proporcionasse redução imediata de custos operacionais, especialmente nas áreas de armazenamento, computação e arquivamento de dados.

2. Descrição do Projeto
O projeto foi estruturado em três etapas, cada uma voltada para otimizar um aspecto específico da infraestrutura em nuvem da empresa.

Etapa 1 — Otimização de Armazenamento de Arquivos
Serviço Utilizado: Amazon S3 (Classe Intelligent-Tiering)


Objetivo: Diminuir os  custos de armazenamento de dados com padrões de acesso imprevisíveis.


Descrição do Caso de Uso: Realização de realizada a migração de backups e arquivos grandes, anteriormente armazenados em volumes EBS, para o Amazon S3.



Etapa 2 — Redução de Custos de Computação
Serviço Utilizado: Amazon Virtual Private Cloud (Amazon VPC)


Objetivo: Criar uma rede privada para comunicação interna e controle de ambiente.


Descrição do Caso de Uso: A redução de custos inclui também pensar em segurança, dessa forma, a VPC da amazon provê essa proteção com controle dos recursos de rede.

Etapa 3 — Arquivamento de Longo Prazo
Serviço Utilizado:  S3 One Zone – Infrequent Access


Objetivo: Como o objetivo é redução de custos foi optado por esta opção mais barata,  mas que fornece o mesmo armazenamento do Standard padrão.


Descrição do Caso de Uso: O amazon s3 vai servir aqui como um serviço de armazenamento durável, escalável e seguro.



3. Resultados e Benefícios Esperados
A adoção dessas ferramentas permitiu à Abstergo Industries:
Reduzir significativamente os custos de armazenamento e computação;


Gerenciar os recursos com segurança da VPC;


Garantir armazenamento confiável e escalável.

4. Conclusão
A implementação dos serviços da AWS proporcionou melhor aproveitamento dos recursos existentes e redução de custos operacionais imediatos.
Recomenda-se a continuidade no uso das soluções implantadas e a avaliação periódica de novos serviços AWS que possam complementar ou otimizar ainda mais os processos tecnológicos da Abstergo Industries.



