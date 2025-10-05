# Projeto Farmácia — DIO

## Relatório de Implementação de Serviços AWS

**Data:** 05/2025  
**Empresa:** Abstergo Industries  
**Responsável:** Ramon Lucas  

---

## 1. Introdução

Este relatório apresenta o processo de implementação de serviços na **Abstergo Industries**, conduzido por **Ramon Lucas**.  

O objetivo principal do projeto foi **identificar e implementar três serviços da AWS** que proporcionassem **redução imediata de custos operacionais**, especialmente nas áreas de **armazenamento, computação e arquivamento de dados**.

---

## ⚙️ 2. Descrição do Projeto

O projeto foi estruturado em **três etapas**, cada uma voltada para otimizar um aspecto específico da infraestrutura em nuvem da empresa.

---

### Etapa 1 — Otimização de Armazenamento de Arquivos

- **Serviço Utilizado:** Amazon S3 (Classe Intelligent-Tiering)  
- **Objetivo:** Diminuir os custos de armazenamento de dados com padrões de acesso imprevisíveis.  
- **Descrição do Caso de Uso:**  
  Foi realizada a **migração de backups e arquivos grandes**, anteriormente armazenados em volumes EBS, para o **Amazon S3**.  
  A classe **Intelligent-Tiering** permite mover automaticamente dados inativos para camadas de menor custo, otimizando os gastos de armazenamento.

---

### Etapa 2 — Redução de Custos de Computação

- **Serviço Utilizado:** Amazon Virtual Private Cloud (Amazon VPC)  
- **Objetivo:** Criar uma rede privada para comunicação interna e controle do ambiente de forma segura e escalável.  
- **Descrição do Caso de Uso:**  
  A **VPC** fornece **isolamento e controle de tráfego** entre recursos AWS, reduzindo custos indiretos com segurança e infraestrutura.  
  Essa implementação possibilita **gerenciar os recursos com segurança**, garantindo comunicação interna eficiente e controlada.

---

### Etapa 3 — Arquivamen
