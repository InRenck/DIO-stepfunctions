# Desafio DIO — AWS Step Functions

![AWS](https://img.shields.io/badge/AWS-Cloud-orange?logo=amazon-aws)
![Step Functions](https://img.shields.io/badge/AWS-Step%20Functions-FF9900?logo=amazon-aws)
![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?logo=github)

## 📖 Sobre o desafio

Este repositório faz parte de um desafio da **DIO (Digital Innovation One)** sobre o serviço **AWS Step Functions**.

Neste desafio, acompanhei as aulas e demonstrações apresentadas, buscando compreender o funcionamento do serviço e os principais conceitos relacionados à criação e organização de **workflows na AWS**.

---

## 📚 Índice

* [☁️ Sobre o AWS Step Functions](#️-sobre-o-aws-step-functions)
* [🧠 O que aprendi](#-o-que-aprendi)
* [🔄 Workflows](#-workflows)
* [⚙️ State Machine](#️-state-machine)
* [🔹 States](#-states)
* [🔗 Integração com serviços AWS](#-integração-com-serviços-aws)
* [💡 Principais aprendizados](#-principais-aprendizados)
* [🎯 Conclusão](#-conclusão)
* [🔗 Links úteis](#-links-úteis)

---

## ☁️ Sobre o AWS Step Functions

O **AWS Step Functions** é um serviço da AWS utilizado para criar e gerenciar workflows por meio de **máquinas de estado**.

Ele permite organizar processos em diferentes etapas, definindo a ordem de execução e o comportamento do fluxo de acordo com cada situação.

Uma característica interessante do serviço é a possibilidade de visualizar o fluxo de execução, facilitando o acompanhamento de processos que possuem várias etapas.

---

## 🧠 O que aprendi

Durante o acompanhamento do desafio, pude conhecer conceitos importantes relacionados ao AWS Step Functions:

* 🔄 Criação e organização de workflows;
* ⚙️ Funcionamento de máquinas de estado;
* 🔹 Utilização de diferentes tipos de estados;
* 🔀 Criação de decisões dentro de um fluxo;
* 🔗 Integração com outros serviços da AWS;
* ▶️ Organização da sequência de execução de tarefas;
* ☁️ Conceitos relacionados à computação em nuvem.

---

## 🔄 Workflows

Um **workflow** representa uma sequência de etapas que precisam ser executadas para alcançar determinado resultado.

O Step Functions permite organizar essas etapas e definir como o processo deve avançar.

Um exemplo simplificado seria:

```text
        ┌─────────┐
        │  Início │
        └────┬────┘
             ↓
       ┌─────────────┐
       │    Tarefa   │
       └──────┬──────┘
              ↓
       ┌─────────────┐
       │   Decisão   │
       └──────┬──────┘
          ↙       ↘
       Sim         Não
        ↓           ↓
   ┌────────┐   ┌──────────┐
   │  Fim   │   │  Tarefa  │
   └────────┘   └────┬─────┘
                      ↓
                   ┌─────┐
                   │ Fim │
                   └─────┘
```

Esse tipo de organização ajuda a tornar processos complexos mais estruturados e fáceis de acompanhar.

---

## ⚙️ State Machine

A **State Machine (máquina de estados)** é responsável por definir a estrutura do workflow.

Ela determina:

* Quais etapas fazem parte do processo;
* Qual é a sequência de execução;
* Quais decisões podem ser tomadas;
* Para qual estado o fluxo deve seguir;
* Quando o processo deve ser finalizado.

A máquina de estados funciona, portanto, como uma espécie de "mapa" que define o comportamento do workflow.

---

## 🔹 States

Os **States (estados)** representam as etapas individuais dentro de uma State Machine.

Cada estado possui uma função específica dentro do workflow.

Dependendo do tipo de estado, ele pode ser utilizado para:

* Executar uma tarefa;
* Fazer uma escolha ou decisão;
* Aguardar determinado período;
* Executar etapas em paralelo;
* Passar informações para outro estado;
* Encerrar o fluxo.

Essa estrutura permite criar workflows mais organizados e com diferentes possibilidades de execução.

---

## 🎯 Conclusão

Acompanhar este desafio foi uma oportunidade de conhecer melhor o **AWS Step Functions** e entender como ele pode ser utilizado para criar e orquestrar workflows.

Apesar de não ter realizado a implementação prática, o conteúdo contribuiu para ampliar minha compreensão sobre **Cloud Computing, workflows, máquinas de estado e integração entre serviços da AWS**.

Este repositório representa mais uma etapa da minha jornada de aprendizado e serve como registro dos conhecimentos adquiridos durante o desafio da DIO. 🚀

---

## 🔗 Links úteis

### 📘 AWS Step Functions

https://aws.amazon.com/pt/step-functions/

### 💻 AWS Step Functions Examples

https://github.com/aws-samples/aws-stepfunctions-examples

### 🤖 Serverless + Amazon Bedrock

https://aws.amazon.com/pt/blogs/aws-brasil/como-criar-um-assistente-virtual-de-baixa-latencia-com-multiplos-modelos-usando-serverless-e-amazon-bedrock/

---

⭐ **Desafio acompanhado durante minha jornada de estudos na DIO.**
