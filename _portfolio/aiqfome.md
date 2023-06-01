---
title: "Processo de exclusão de contas"
excerpt: "Usando UX Design para atingir redução de custos em processos operacionais"
date: 2023-05-29T10:13:02-05:00
sidebar:
  - title: "Período"
    text: "Primeiro semestre de 2022"
  - title: "Responsabilidades"
    text: "Utilizar metodologias de UX Design para criar funcionalidades e processos que gerem valor para os usuários da empresa"
header:
  image: /assets/images/Aiqfome/cover-aiq.png
  teaser: /assets/images/Aiqfome/preview-aiq.png
  alt: "Imagem de um desenho de um gramado cartunizado com algumas moitas e árvores ao longe"
related: false
categories:
  - portfolio
---
Com base em uma [determinação da Apple](https://developer.apple.com/pt/support/offering-account-deletion-in-your-app/), era **necessário permitir que os usuários do aplicativo Aiqfome excluíssem sua conta de forma automatizada pelo próprio aplicativo**, sem depender do chat para abrir essa solicitação.

Atuando como UX Designer no Aiqfome, fiquei responsável por criar a parte que iria **receber e aprovar as solicitações de exclusão de conta dentro do produto interno** utilizado pelos funcionários de vários setores da empresa.

**Por questões de sigilo não posso revelar detalhadamente (ou utilizar imagens de telas) sobre essa funcionalidade, dado que ela possui papel importante na prevenção de fraudes contra a empresa.**
{: .notice--primary}

# Desafio enfrentado
> Como podemos criar um novo processo que **reduza o tempo gasto pelos funcionários do suporte** durante a aprovação da exclusão de contas de usuários do aplicativo Aiqfome?

# Sobre o problema
Entrevistei alguns funcionários do suporte sobre o funcionamento atual do processo de exclusão, e esses eram os passos necessários até o momento:

Usuário entrava em contato exclusão da conta via chat do aplicativo >  Suporte levantava informações existentes sobre o usuário na plataforma interna > Suporte comparava informações com banco de informações sobre fraudadores anteriores > Voltava na plataforma interna para realizar a exclusão

# Hipótese
Com base nas informações levantadas, construímos a seguinte hipótese:

> Considerando que o time de suporte precisa **constantemente acessar o banco de dados para cada uma das solicitações** e comparar informações para decidir sobre a exclusão, não seria **mais rápido já trazer todos os comparativos necessários prontos para ele precise apenas decidir?** 

# Solução
Após a construção da hipótese e posterior validação com o time de suporte, **o novo processo de exclusão de contas ficou da seguinte forma:**

Funcionário vê a listagem de solicitações pendentes, com os mais suspeitos destacados > Abre em detalhes uma solicitação, vendo um comparativo automático sobre indícios suspeitos da conta > Aprova ou restringe a solicitação

A solução criada **dispensa consulta ao banco de dados, pois já traz uma análise automatizada** alertando o suporte sobre os possíveis indícios daquela conta ser um fraudador. Apesar disso, **todo o poder da decisão final continuou nas mãos dos funcionários,** que com apenas dois cliques pode escolher entre restringir ou aprovar a exclusão da conta. 


# Resultados
A partir da implementação da solução, os **resultados obtidos** pela empresa foram:
-  Usuários do aplicativo Aiqfome podem solicitar exclusão de suas contas de forma automatizada, **sem precisar interagir com o chat do aplicativo**
-  **Mais funcionários do suporte** podem realizar o processo de aprovação, já que **não depende mais de permissões** para acessar manualmente o banco de dados
- 