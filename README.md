## 🚀 Desafios Práticos de AWS Serverless & Infraestrutura como Código (IaC)

Este repositório documenta as atividades e anotações dos desafios práticos de AWS, focando na tecnologia **AWS CloudFormation**.

O material foi desenvolvido como parte do **Bootcamp Santander Code Girls 2025** da [Digital Innovation One (DIO)](https://www.dio.me/), refletindo meu compromisso em aprimorar habilidades em arquitetura **Serverless** e **DevOps**.

---

### 🌟 Visão Geral do Projeto

O objetivo principal é demonstrar proficiência na orquestração de microsserviços e no gerenciamento automatizado da infraestrutura, habilidades cruciais para um Desenvolvedor Júnior focado em ambientes Cloud.

| Área de Foco | Serviço Principal | Habilidades Demonstradas |
| :--- | :--- | :--- |
| **Orquestração Serverless** | **AWS Step Functions** | Gestão de estado, lógica condicional (`Choice State`), tratamento de erros e integração com AWS Lambda. |
| **Infraestrutura como Código (IaC)** | **AWS CloudFormation** | Criação, atualização e exclusão de **Stacks** (ambientes), definição de recursos e segurança (`Security Group`) via *templates* YAML. |

---

#### 1. Orquestração Serverless (AWS Step Functions)

| Pasta | Descrição |
| :--- | :--- |
| **Conhecendo AWS step functions** | Conceitos fundamentais de Máquina de Estado, Task e ASL. |
| **Benefícios e projeto modelo...** | Vantagens do serviço e o modelo de pipeline de processamento de pedidos. |
| **Realizando validações...** | Uso do **Estado Choice** e padrões declarativos de tratamento de fluxo. |
| **Criando e executando lambda...** | Configuração do **Task State** para invocar AWS Lambda de forma síncrona. |

#### 2. Infraestrutura como Código (AWS CloudFormation)

| Pasta | Conteúdo | Descrição |
| :--- | :--- | :--- |
| **anotacoes/** | [01-conceito-AWS-cloudformation.md](anotacoes/01-conceito-AWS-cloudformation.md) | Introdução ao IaC, componentes de um *template* (Resources, Parameters, Outputs). |
| | [02-criando-stacks-AWS-cloudformation.md](anotacoes/02-criando-stacks-AWS-cloudformation.md) | O ciclo de vida da **Stack** (Create, Update, Delete) e o fluxo de deploy. |
| | [03-criando-stacks-firewall-cloudformation.md](anotacoes/03-criando-stacks-firewall-cloudformation.md) | Exemplo de IaC para segurança: provisionando um **Security Group** (Firewall). |

#### 3. Assets

- **assets/images/**: Diagramas de fluxo de trabalho e diagramas conceituais (CloudFormation).
- **assets/templates/**: Templates real em YAML, com modelo de **Security Group** pronto para deploy.

---

### 🔗 Referências e Documentação Oficial

- [AWS Step Functions - Documentação Oficial](https://docs.aws.amazon.com/pt_br/step-functions/latest/dg/welcome.html)
- [AWS CloudFormation - Documentação Oficial](https://docs.aws.amazon.com/pt_br/AWSCloudFormation/latest/UserGuide/Welcome.html)
- [Padrões de Integração Otimizados (Step Functions)](https://docs.aws.amazon.com/pt_br/step-functions/latest/dg/connect-resource.html)
- [Digital Innovation One (DIO)](https://www.dio.me/)