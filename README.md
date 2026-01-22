# RELATATORIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 22 de Janeiro de 2026  
**Empresa:** Abstergo Industries  
**Responsável:** Maria Eloísa

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa **Abstergo Industries**, realizado por **Maria Eloísa**. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar a diminuição de custos imediatos, além de garantir segurança e escalabilidade para as aplicações proprietárias da farmácia.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

### Etapa 1: Otimização de Armazenamento
- **Nome da ferramenta:** Amazon S3 Intelligent-Tiering
- **Foco da ferramenta:** Redução automática de custos de armazenamento e gerenciamento do ciclo de vida dos dados.
- **Descrição de caso de uso:** Implementação do S3 Intelligent-Tiering para o armazenamento de documentos e logs da farmácia. O serviço monitora os padrões de acesso e move automaticamente os objetos entre camadas de acesso frequente e infrequente. Isso garante que arquivos antigos ou pouco acessados não gerem custos elevados, sem a necessidade de intervenção manual ou perda de desempenho na recuperação dos dados.

### Etapa 2: Segurança de Rede
- **Nome da ferramenta:** Amazon VPC (Virtual Private Cloud)
- **Foco da ferramenta:** Segurança, isolamento de rede e controle de tráfego.
- **Descrição de caso de uso:** Criação de uma rede virtual isolada logicamente na nuvem AWS. Esta estrutura permite definir sub-redes públicas e privadas, garantindo que o banco de dados e as aplicações críticas da farmácia não fiquem expostos diretamente à internet pública, aumentando a segurança contra ataques externos enquanto mantém a conectividade segura necessária para as operações web.

### Etapa 3: Modernização de Aplicações
- **Nome da ferramenta:** Amazon ECS (Elastic Container Service)
- **Foco da ferramenta:** Orquestração de containers, portabilidade e escalabilidade de aplicações (SaaS).
- **Descrição de caso de uso:** Containerização do sistema de ERP proprietário da farmácia. A utilização de containers permite empacotar o código e as dependências da aplicação, facilitando a distribuição e a implantação do software para outras empresas clientes (modelo SaaS). Isso assegura consistência entre ambientes de desenvolvimento e produção, além de permitir o escalonamento rápido de recursos conforme novos clientes são adicionados.

## Conclusão
A implementação de ferramentas na empresa **Abstergo Industries** tem como esperado **a redução dos custos operacionais de armazenamento (OpEx), o aumento da segurança dos dados sensíveis e a criação de uma infraestrutura escalável para comercialização do ERP**, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

* Documentação Oficial Amazon S3 Intelligent-Tiering
* Diagrama de Arquitetura de Rede (VPC)
* Manual de Deploy do ERP via Amazon ECS

---
**Assinatura do Responsável pelo Projeto:**

______________________________________________
**Maria Eloísa**
