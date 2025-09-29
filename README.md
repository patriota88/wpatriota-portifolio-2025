# Projeto: Portfólio Estático com AWS S3

Este repositório contém os arquivos e a documentação do meu primeiro projeto prático em computação em nuvem, focado na jornada de estudos para a certificação AWS.

## 🎯 Objetivo do Projeto

O objetivo principal é demonstrar as habilidades fundamentais em nuvem, configurando e publicando um site estático de forma segura, escalável e de baixo custo utilizando o Amazon S3. Este projeto serve como um marco inicial no meu desenvolvimento de competências em AWS.

## 🚀 Sobre a Arquitetura

A solução consiste em um site simples (HTML/CSS) cujos arquivos são armazenados em um bucket no Amazon S3. O bucket foi configurado para funcionar como um servidor web para conteúdo estático, com uma política de acesso que permite a leitura pública dos objetos via internet.

### Diagrama
![Arquitetura do Projeto]([URL_DA_SUA_IMAGEM_DO_DIAGRAMA_AQUI](https://github.com/patriota88/wpatriota-portifolio-2025/blob/main/Diagrama%20Meu_Portifolio_S3.png))

## 🛠️ Serviços e Tecnologias Utilizadas

* **AWS S3 (Simple Storage Service):** Para armazenamento dos objetos (arquivos do site) e para a funcionalidade de hospedagem de site estático.
* **AWS IAM (Identity and Access Management):** Utilizado implicitamente na configuração da política de segurança (Bucket Policy) para garantir o acesso público controlado.
* **HTML5 e CSS3:** Para a estrutura e estilização do site.

## 📜 Principais Conceitos Aprendidos

Ao realizar este projeto, adquiri experiência prática com:
- Criação e configuração de buckets S3.
- Gerenciamento de objetos (upload, permissões).
- Habilitação da funcionalidade de *Static Website Hosting*.
- Escrita e aplicação de *Bucket Policies* em JSON para liberar o acesso público (`s3:GetObject`).
- Entendimento do fluxo de uma requisição web para um conteúdo estático na nuvem.
