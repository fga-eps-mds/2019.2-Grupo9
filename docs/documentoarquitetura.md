## 1. Introdução
#### 1.1. Objetivo

Este documento tem como finalidade fornecer uma visão geral da arquitetura do projeto Amika, contem informações pertinentes sobre qual o modelo de arquitetura adotado, diagramas que ilustram casos de uso, diagramas de classes, entre outros recursos .

#### 1.2. Escopo

Através desse documento, é possível obter um melhor entendimento da arquitetura do Gaia, permitindo ao leitor compreender o funcionamento de seu sistema, como também a abordagem utilizada para o seu desenvolvimento.

#### 1.3. Definições, Acrônimos e Abreviações

**Acrônimo/Abreviação** | **Definição**
------------------------|-------------------
UnB | Universidade de Brasília.

#### 1.4. Referências Bibliográficas

#### 1.5. Visão Geral

**Tópico** | **Definição**
---------------|-----------------------------
Introdução | Descreve informações sobre a finalidade deste documento.
Representação Arquitetural | Descreve qual é a arquitetura de software, para melhor compreensão de sua estrutura e funcionamento e mostra como ela está sendo representada.
Metas e Restrições | Descreve os requisitos e objetivos do software, e se estes  têm algum impacto sobre a arquitetura.
Visão lógica | Descreve as partes significativas do ponto de vista da arquitetura do modelo de design.

## 2. Representação Arquitetural
#### PWA (Progressive Web App)
Os PWA são páginas web tecnicamente regulares que podem aparecer ao usuário como aplicativos tradicionais ou aplicativos móveis. Em resumo, os PWA ter uma experiência de uso muito próxima da de mobile apps. As principais funcionalidades oferecidas por essas tecnologias são:
-Push Notification
-Ícone na tela home do smartphone
-Splash screen
-Processos rodando em background
-Suporte a funcionamento em modo Offline
-Acesso à camera e galeria
-Acesso à geolocalização
-Acesso à os contatos
-Django
-O Django é um framework com arquitetura baseada no MVC (Model-View-Controller), apesar disso, é descrita como MVT (Model-View-Template).

#### Django REST Framework
O REST é uma extensão do Django Framework que permite implementar API's REST de forma rápida. A arquitetura REST opera por métodos de protocolo HTTP.

## 3. Objetivo e Restrições da arquitetura

#### 3.1. Requisitos para o Amika:
- Funcionar em web.
- Uso do PWA, para funcionar em smartphones.

#### 3.2. Tecnologias utilizadas no Amika:
- Django: Web Framework baseada em Python.
- Django Rest Framework: caixa de ferramentas e APIs para o Django.
- Python: Linguagem utilizada no Django.
- PWA: Software utilizado para implementação do uso em smartphones.
- Angular: Web Framework utilizado no frontend.
- Java Script: Linguagem utilizado junto com o HTML e CSS, para desenvolvimento WEB.
- HTML: Linguagem base utilizado em desenvolvimento WEB.
- CSS: Linguagem usada juntamente com HTML para estilizar a pagina.


## 4. Visão Geral do Produto

## 5. Visão Lógica

***