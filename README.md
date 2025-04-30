# 🚀 Projeto AWS Containerizado – Arquitetura Escalável com ECS + EC2

![GitHub repo size](https://img.shields.io/github/repo-size/aryaneandrade/aws-containerized-project)
![GitHub stars](https://img.shields.io/github/stars/aryaneandrade/aws-containerized-project?style=social)
![GitHub last commit](https://img.shields.io/github/last-commit/aryaneandrade/aws-containerized-project)
![AWS](https://img.shields.io/badge/built%20with-AWS-orange?logo=amazonaws&logoColor=white)



Este repositório documenta todas as etapas do projeto prático que desenvolvi durante o **Bootcamp Imersão AWS**, ministrado por **Henrylle Maia**. Todos os recursos e configurações foram aplicados **na prática, utilizando minha própria conta AWS**, garantindo uma vivência real com os principais serviços da nuvem da Amazon.

---

## 🧠 Objetivo

Construir uma aplicação fullstack escalável e resiliente, utilizando orquestração de contêineres com **Amazon ECS (EC2 Launch Type)**, banco de dados relacional com **Amazon RDS**, balanceamento de carga com **ALB**, automação de deploy e **escalabilidade horizontal** com Auto Scaling.

---

## 📊 Arquitetura da Solução

Abaixo está o diagrama que representa a arquitetura completa desenvolvida na minha conta AWS durante o projeto:

![Arquitetura da Solução](caminho/para/seu-diagrama.png)

---

## 📌 Etapas do Projeto

### Aula 1 – Ambiente de Trabalho e Introdução à Alta Disponibilidade
- Configuração do ambiente via **CloudShell** e **Systems Manager (SSM)**.
- Estabelecimento de conexão segura com os recursos.
- Apresentação da arquitetura de **Alta Disponibilidade (HA)** que seria construída ao longo do projeto.

---

### Aula 2 – Cluster ECS, Banco de Dados e Deploy Automatizado
- Criação de **Cluster ECS com EC2 Launch Type** para gerenciamento de contêineres.
- Configuração de banco de dados **Amazon RDS (PostgreSQL)**.
- Execução de **migrations** para estruturação do ambiente.
- Ajuste dos **Security Groups** para garantir comunicação segura.
- Upload da imagem Docker para o **Amazon ECR**.
- Deploy automatizado via **script personalizado**.

---

### Aula 3 – Aplicação Fullstack com Balanceamento de Carga e HTTPS
- Deploy de aplicação **Node + React** com múltiplas tasks no ECS.
- Implementação do **Application Load Balancer (ALB)** e **Target Group**.
- Deploy contínuo **sem downtime**.
- Configuração de **domínio personalizado com HTTPS**, garantindo segurança e profissionalismo ao ambiente.

---

### Aula Final – Escalabilidade Horizontal e Resiliência
- Utilização do **ECS com EC2 Launch Type**.
- Simulação de cenário de alta demanda (**Black Friday**).
- Configuração de **Auto Scaling**: de 2 para 4 tasks, com capacidade para até 8.
- Arquitetura distribuída com **Multi-AZ** e **Health Checks** ativos.
- Isolamento da infraestrutura com **VPC personalizada** e políticas de segurança.

---

## 🛠️ Tecnologias e Serviços Utilizados

| Categoria      | Tecnologias                                                                 |
|----------------|------------------------------------------------------------------------------|
| Containers     | Amazon ECS (EC2 Launch Type), Docker, Amazon ECR                            |
| Compute        | Amazon EC2, Auto Scaling Group                                               |
| Networking     | VPC, Subnets, Security Groups, ALB                                           |
| Banco de Dados | Amazon RDS (PostgreSQL Multi-AZ)                                             |
| Deploy         | AWS CloudShell, Systems Manager (SSM), scripts de automação                 |
| Segurança      | HTTPS, Security Groups, IAM                                                  |

---

## ✅ Resultados Obtidos

- Aplicação fullstack em produção com alta disponibilidade.
- Deploy automatizado e seguro via ECS e ECR.
- **Escalabilidade horizontal simulada com base em cenário de Black Friday.**
- Arquitetura resiliente, segura e pronta para produção em nuvem.

---

## 📷 Capturas de Tela

*(Inclua aqui prints do Console AWS, ECS, RDS, ALB ou da aplicação rodando, caso deseje)*

---

## 📄 Licença

Este projeto foi desenvolvido exclusivamente para fins educacionais e não possui fins comerciais.

---

## 💬 Contato

Caso queira trocar experiências sobre arquitetura em nuvem ou tenha dúvidas sobre este projeto, sinta-se à vontade para me chamar:

- LinkedIn: www.linkedin.com/in/aryane-andrade
- Email: aryaneands@gmail.com

---

> 🔥 Desenvolvido por Aryane, praticando diretamente na AWS com foco em Cloud Architecture, Containers e Alta Disponibilidade.
