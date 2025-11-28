Olá\! Que ótimo projeto para aprimorar suas habilidades em **Docker e Microsserviços**\!

Com base nas informações fornecidas, preparei um texto em Markdown que você pode usar como **README** para o seu repositório no GitHub. Ele está organizado para ser informativo e atraente.

-----

# 🐳 Projeto: Docker: Utilização Prática no Cenário de Microsserviços

## 🚀 Visão Geral do Desafio

Este projeto faz parte do curso **Microsoft - Azure Advanced \#2** da **Digital Innovation One (DIO)** e tem como objetivo explorar a utilização prática do **Docker** e da tecnologia de **Containers** no desenvolvimento e implantação de uma arquitetura de **Microsserviços**.

A tecnologia de containers revoluciona as operações de TI, proporcionando a **abstração de ambientes** e otimizando o **consumo de recursos**. Neste desafio, implementaremos uma estrutura de Microsserviços seguindo as melhores práticas do mercado, visando alcançar **independência entre as aplicações e a infraestrutura**.

A Live Coding original foi conduzida pelo Expert Instructor **Denilson Bonatti**.

## 🎯 Objetivos de Aprendizagem

  * Entender a **função crítica** dos containers (Docker) em um cenário de Microsserviços.
  * Implementar e orquestrar **Microsserviços** utilizando a plataforma Docker.
  * Aplicar **melhores práticas** de isolamento e empacotamento de aplicações.
  * Ganhar familiaridade com a integração entre **Docker** e serviços de nuvem (**AWS** e contexto **Azure** do curso).

## 💡 Cenário Prático (Inspiração TOSHIRO SHIBAKITA)

Inspirado na jornada de **Toshiro Shibakita**, este projeto visa replicar e evoluir uma solução de Microsserviços que ilustre como o Docker pode resolver problemas de **dependência** e **consistência de ambiente**.

> **Qual a real função de um container no cenário de microsserviços?**
>
> Um container atua como uma **unidade de implantação** padronizada. Ele empacota a aplicação e todas as suas dependências (bibliotecas, configurações, *runtime*) em um **ambiente isolado e portátil**. Isso garante que o microsserviço funcione de forma idêntica em qualquer lugar, desde a máquina do desenvolvedor até o ambiente de produção na nuvem.

## 🛠️ Tecnologias e Pré-requisitos

Para replicar e aprimorar este projeto, é necessário ter:

### **Pré-requisitos de Conhecimento:**

  * Conhecimentos básicos em **Linux**.
  * Conhecimentos básicos em **Docker** (criação de imagens, Dockerfile, comandos básicos).
  * Conhecimentos básicos em **AWS** (para o contexto de infraestrutura de nuvem).

### **Ferramentas Necessárias:**

  * **Docker Desktop** (ou Engine) instalado e rodando.
  * **Git** instalado.
  * Um editor de código (VS Code, etc.).

## 📂 Estrutura do Projeto (Exemplo)

```text
.
├── app-service-a/             # Microsserviço A (ex: backend API)
│   ├── Dockerfile             # Definição do container para o Serviço A
│   └── src/                   # Código-fonte do Serviço A
├── app-service-b/             # Microsserviço B (ex: frontend/gateway)
│   ├── Dockerfile             # Definição do container para o Serviço B
│   └── src/                   # Código-fonte do Serviço B
├── docker-compose.yml         # Definição da orquestração dos Microsserviços
└── README.md                  # Este arquivo
```

## ⚙️ Como Executar o Projeto

1.  **Clone o repositório:**

    ```bash
    git clone [LINK_DO_SEU_REPOSITORIO]
    cd [pasta-do-seu-repositorio]
    ```

2.  **Construa e Suba os Containers:**
    Utilize o `docker-compose` para construir as imagens e iniciar todos os serviços definidos na arquitetura de Microsserviços.

    ```bash
    docker-compose up --build
    ```

3.  **Verifique os Serviços:**
    Após o *deploy*, você deve conseguir acessar os endpoints dos microsserviços. (Ex: Acessar `http://localhost:[PORTA_SERVICO_B]`).

4.  **Encerre os Containers:**

    ```bash
    docker-compose down
    ```

## 🔗 Referências

  * **Live Coding Original (DIO):** Docker: Utilização prática no cenário de Microsserviços - Denilson Bonatti.
  * **Repositório Base (Guia "Melzinho na Chupeta"):** [https://github.com/denilsonbonatti/toshiro-shibakita/forksRepositório] 
  * **Digital Innovation One (DIO):** [https://web.dio.me/lab/docker-utilizacao-pratica-no-cenario-de-microsservicos/learning/d151f94a-d53c-4ad3-b35a-333307faaf24?back=/track/microsoft-azure-advanced-2]