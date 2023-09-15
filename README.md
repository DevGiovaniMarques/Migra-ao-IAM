# Migra-ao-IAM
Migração de usuários de forma automatizada e gerenciamento dos recursos do IAM (Identity and Access Management) da AWS.

Nesse projeto baseado em um cenário real, tive que atuar como Especialista Cloud para realizar a migração de usuários de forma automatizada e gerenciar os recursos do IAM (Identity and Access Management) da AWS.

Haviam 100 usuários que precisaram ser migrados e ter o MFA — Autenticação por múltiplos fatores (Multi-factor Authentication) habilitado nas contas, pois esta é uma melhor prática de segurança.

Para não ser uma tarefa repetitiva e manual na console da AWS, precisei ter o pensamento voltado a automatizar os processos.

Essa é a arquitetura usada no projeto:

![alt text](PORTFOLIOPROJETOAWSMODULO2_ARQUITETURA-220608-211757.png)

Para executar o projeto foi necessário executar um script no AWS CloudShell para automatizar o processo.

Os passos foram:

1º Criar todos os 5 Grupos que serão utilizados dentro do AWS.

![alt text](PORTFOLIOPROJETOAWSMODULO2_ARQUITETURA-220608-211757.png)

