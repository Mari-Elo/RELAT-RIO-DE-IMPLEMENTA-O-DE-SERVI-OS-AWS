# RELATATORIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 22 de Janeiro de 2026  
**Empresa:** Abstergo Industries  
**Responsável:** Maria Eloísa

## Introdução
Apresento neste relatório de implementação de ferramentas Cloud para a empresa **Abstergo Industries**, com o objetivo do projeto de implantar 3 serviços da AWS para diminuir custos financeiros, garantir segurança dos dados, além de fácil aumentar a eficiência para as farmácias.

## Descrição do Projeto
O projeto de implementação de ferramentas Cloud foi dividido em 3 etapas, cada um explicando sua função. As seguintes etapas são:

### Etapa 1: Otimização de Armazenamento
* **Nome da ferramenta:** Amazon RDS
* **Foco da ferramenta:** Gerenciamento de banco de dados e redução de carga operacional.
* **Descrição de caso de uso:** Migração da base de dados do ERP da farmácia (estoque, vendas e dados fiscais) para a nuvem. Automatizando tarefas como backups, atualizações de software e replicação de dados. Com isso garante que as informações críticas do negócio estejam seguras e disponíveis 24/7, permitindo que a equipe de TI foque no desenvolvimento do sistema em vez de manutenção de servidores.

### Etapa 2: Segurança de Rede
* **Nome da ferramenta:** Amazon VPC
* **Foco da ferramenta:** Segurança, isolamento de rede e controle de tráfego.
* **Descrição de caso de uso:** Criação de uma rede virtual isolada logicamente na nuvem AWS. Permite definir sub-redes públicas e privadas, garantindo que o banco de dados e as aplicações críticas da farmácia não fiquem expostos diretamente à internet pública, aumentando a segurança contra-ataques externos enquanto mantém a conexão segura para as pesquisas na web.

### Etapa 3: Modernização de Aplicações
* **Nome da ferramenta:** Amazon ECS
* **Foco da ferramenta:** Orquestração de containers, portabilidade e escalabilidade de aplicações (SaaS).
* **Descrição de caso de uso:** Conteinerização do sistema de ERP próprio da farmácia. A utilização de containers permite empacotar o código e as dependências da aplicação, facilitando a distribuição e a implantação do software para outras empresas clientes (modelo SaaS). Isso assegura consistência entre ambientes de desenvolvimento e produção, além de permitir a atualização constantes de recursos conforme novos clientes são incluídos.

## Conclusão
Com a implantação dessas ferramentas na empresa **Abstergo Industries** é esperado um aumento da utilização do ERP para informações estejam todas na Cloud, sem risco de perda de dados importantes, além da segurança na web com a ferramenta e possibilidade de expansão da empresa comercializando o ERP especializados para farmácias em breve.

## Anexos

* Diagrama de Arquitetura de Rede (VPC)
* Manual de Deploy do ERP via Amazon ECS
* Relatório de otimização

---
**Assinatura do Responsável pelo Projeto:** Maria Eloísa

______________________________________________
**Maria Eloísa**
