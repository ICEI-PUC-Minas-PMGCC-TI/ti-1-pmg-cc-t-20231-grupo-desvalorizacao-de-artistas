# Informações do Projeto
`TÍTULO DO PROJETO`  

StreamWave

`CURSO` 

Ciência da Computação | Tarde | Puc Minas Coração Eucaristico

## Participantes

 - Henrique Saldanha Mendes Veloso
 - Lucas Soares Tavares
 - Rafael Fagundes Silva Reis
 - Gabriel Lara Martins Lana
 - Mario Wagner Resende Finelli Junior

# Estrutura do Documento

- [Informações do Projeto](#informações-do-projeto)
  - [Participantes](#participantes)
- [Estrutura do Documento](#estrutura-do-documento)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
  - [Justificativa](#justificativa)
  - [Público-Alvo](#público-alvo)
- [Especificações do Projeto](#especificações-do-projeto)
  - [Personas, Empatia e Proposta de Valor](#personas-empatia-e-proposta-de-valor)
  - [Histórias de Usuários](#histórias-de-usuários)
  - [Requisitos](#requisitos)
    - [Requisitos Funcionais](#requisitos-funcionais)
    - [Requisitos não Funcionais](#requisitos-não-funcionais)
  - [Restrições](#restrições)
- [Projeto de Interface](#projeto-de-interface)
  - [User Flow](#user-flow)
  - [Wireframes](#wireframes)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)
  - [Controle de Versão](#controle-de-versão)
- [**############## SPRINT 1 ACABA AQUI #############**](#-sprint-1-acaba-aqui-)
- [Projeto da Solução](#projeto-da-solução)
  - [Tecnologias Utilizadas](#tecnologias-utilizadas)
  - [Arquitetura da solução](#arquitetura-da-solução)
- [Avaliação da Aplicação](#avaliação-da-aplicação)
  - [Plano de Testes](#plano-de-testes)
  - [Ferramentas de Testes (Opcional)](#ferramentas-de-testes-opcional)
  - [Registros de Testes](#registros-de-testes)
- [Referências](#referências)


# Introdução


## Problema

 A desvalorização dos artistas na música é um problema em que muitos artistas se sentem subestimados e não recebem o devido reconhecimento e remuneração por seu trabalho criativo. Isso pode ocorrer devido a baixos cachês, royalties inadequados, contratos desfavoráveis, falta de reconhecimento artístico, saturação do mercado musical e pressão comercial. Isso pode ter um impacto negativo na saúde mental e emocional dos artistas, levando ao esgotamento e frustração. É importante que a indústria musical reconheça o valor dos artistas e trabalhe para garantir sua justa valorização em termos de remuneração e reconhecimento artístico.

## Objetivos

 O objetivo desse projeto é desenvolver um softaware capaz de melhorar a qualidade de trabalho para artistas que ainda não são muito reconhecidos no meio musical. Também queremos que os novos artistas tenham onde se divulgar de maneira justa para os usuarios do software, fazendo assim com que eles tenham uma maneira muito mais simples de crescer e viver de sua música. 

## Justificativa

Nós temos um interesse pessoal na música e nos desafios enfrentados pelos artistas em sua indústria. Somos fãs de música e estamos preocupados com a forma como os artistas são tratados em termos de reconhecimento, remuneração e oportunidades de carreira. Além de acreditarmos que é um problema atual e digno de discussão.

## Público-Alvo

 O público alvo desse projeto são os artistas que amam a musica mas não tem a visibilidade que merecem e querem viver e se sustentar com a musica produziada pro eles. Essas pessoas não tem uma posição alta o suficiente na hierarquia para poder se divulgar e ter sua música descoberta por ouvintes

![image](https://user-images.githubusercontent.com/130800957/232355531-5ffd9738-8b3d-42e4-875f-ab8a902728d8.png)
 
# Especificações do Projeto

 Agora iremos apresentar as personas que entrevistamos, os quadros de empatia e as propostas de valor. Utilizamos as seguintes ferramentas: Miro, this person do not exist e as entrevistas qualitativas.

## Personas, Empatia e Proposta de Valor

 Persona 1
![image](https://user-images.githubusercontent.com/130800957/232359753-635d55b1-4719-45e9-8d0f-e5af8e47ae08.png)
![image](https://user-images.githubusercontent.com/130800957/232359769-c5a487de-8c62-488a-8dbd-c8a1d52068b3.png)

 Persona 2
![image](https://user-images.githubusercontent.com/130800957/232359858-583346f9-f9b6-451c-977b-0b79297e26c7.png)
![image](https://user-images.githubusercontent.com/130800957/232359875-b9b33fab-0f4d-44e5-9bf2-c4885c95b813.png)

  Persona 3
![image](https://user-images.githubusercontent.com/130800957/232359923-d0e4d271-5204-4103-b611-b8d1a55481f4.png)
![image](https://user-images.githubusercontent.com/130800957/232359945-795958bc-fa5a-4f5a-8a28-9252a839c43e.png)


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Artista             |Serviço de distribuição de música   | Compartilhar suas músicas.             |
|                    |Plataforma de apoio financeiro      | Financiar suas músicas                 |
|--------------------|------------------------------------|----------------------------------------|
|Produtor            |Encontrar novos talentos            | Produzir e trabalhar em novos projetos |
|--------------------|------------------------------------|----------------------------------------|
|Fã                  |Serviço com ampla variedade         | Encontrar novos artistas               |
|--------------------|------------------------------------|----------------------------------------|


## Requisitos

### Requisitos Funcionais

|ID    | Descrição do Requisito                          | Prioridade |
|------|-------------------------------------------------|------------|
|RF-001| Permitir que o usuário compartilhe suas musicas | ALTA       | 
|RF-002| Receba dinheiro com seu trabalho                | MÉDIA      |
|RF-003| Deve ter uma ampla variedade de musicas         | ALTA       |
|RF-004| O usario deve poder achar novoso musicos        | MÉDIA      |    

### Requisitos não Funcionais

|ID     | Descrição do Requisito                                |Prioridade |
|-------|-------------------------------------------------------|-----------|
|RNF-001| O serviço deve ter um bom tempo de resposta           |   ALTA    | 
|RNF-002| O serviço deve suportar IOS e android                 |   BAIXA   | 

 
## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O tempo para desenvolver o serviço                    |
|02| A grande variedade de funcionalidades                 |
|03| Dificuldade de organização do grupo                   |
|04| Gestão de tempo                                       |


# Projeto de Interface


Neste projeto de interface para um app de suporte a artistas independentes, nosso objetivo é criar uma experiência de usuário intuitiva e atrativa. Buscamos oferecer uma plataforma justa e igualitária, onde artistas independentes possam compartilhar sua música e alcançar visibilidade, enquanto os ouvintes possam descobrir novos talentos de forma simples e envolvente. Estamos empenhados em desenvolver uma interface acessível e esteticamente agradável, priorizando a interação entre artistas e ouvintes para fortalecer a comunidade musical independente.


## User Flow

......  INCLUA AQUI O DIAGRAMA COM O FLUXO DO USUÁRIO NA APLICAÇÃO ......

> Fluxo de usuário (User Flow) é uma técnica que permite ao desenvolvedor
> mapear todo fluxo de telas do site ou app. Essa técnica funciona
> para alinhar os caminhos e as possíveis ações que o usuário pode
> fazer junto com os membros de sua equipe.
>
> **Links Úteis**:
> - [User Flow: O Quê É e Como Fazer?](https://medium.com/7bits/fluxo-de-usu%C3%A1rio-user-flow-o-que-%C3%A9-como-fazer-79d965872534)
> - [User Flow vs Site Maps](http://designr.com.br/sitemap-e-user-flow-quais-as-diferencas-e-quando-usar-cada-um/)
> - [Top 25 User Flow Tools & Templates for Smooth](https://www.mockplus.com/blog/post/user-flow-tools)
>
> **Exemplo**:
> 
> ![Exemplo de UserFlow](images/userflow.jpg)


## Wireframes

......  INCLUA AQUI OS WIREFRAMES DAS TELAS DA APLICAÇÃO COM UM BREVE DESCRITIVO ......

> Wireframes são protótipos das telas da aplicação usados em design de interface para sugerir a
> estrutura de um site web e seu relacionamentos entre suas
> páginas. Um wireframe web é uma ilustração semelhante ao
> layout de elementos fundamentais na interface.
> 
> **Links Úteis**:
> - [Ferramentas de Wireframes](https://rockcontent.com/blog/wireframes/)
> - [Figma](https://www.figma.com/)
> - [Adobe XD](https://www.adobe.com/br/products/xd.html#scroll)
> - [MarvelApp](https://marvelapp.com/developers/documentation/tutorials/)
> 
> **Exemplo**:
> 
> ![Exemplo de Wireframe](images/wireframe-example.png)


# Metodologia

Desenvolvedor: Lucas e Henrique​

Teste de qualidade: Rafael​

Interface de usuário: Mario


## Divisão de Papéis

- Henrique Saldanha Mendes Veloso: Miro, GitHub.
- Lucas Soares Tavares: Miro, GitHub.
- Rafael Fagundes Silva Reis: Miro.
- Gabriel Lara Martins Lana: Miro.
- Mario Wagner Resende Finelli Junior: Miro.


## Ferramentas


| Ambiente  | Plataforma              |Link de Acesso |
|-----------|-------------------------|---------------|
|Processo de Design Thinkgin  | Miro |  https://miro.com/app/board/uXjVMYDaO64=/ | 
|Repositório de código | GitHub | https://github.com/ICEI-PUC-Minas-PMGCC-TI/ti-1-pmg-cc-t-20231-tiaw-desvalorizacao-de-artistas | 
|Hospedagem do site | Replit |  https://XXXXXXX.herokuapp.com | 
|Protótipo Interativo | MavelApp ou Figma | https://figma.com/XXXXXXX | 


# Projeto da Solução

Vamos oferecer a eles uma plataforma para alcançar um público maior com ausência de métricas visíveis. O que ajudará a democratizar a indústria musical, permitindo que artistas menos conhecidos tenham mais visibilidade.

## Tecnologias Utilizadas

Desenvolvimento Web:
Linguagens: HTML5, CSS3 e JavaScript para a construção da interface do usuário e interatividade.

## Arquitetura da solução

......  COLOQUE AQUI O SEU TEXTO E O DIAGRAMA DE ARQUITETURA .......

> Inclua um diagrama da solução e descreva os módulos e as tecnologias
> que fazem parte da solução. Discorra sobre o diagrama.
> 
> **Exemplo do diagrama de Arquitetura**:
> 
> ![Exemplo de Arquitetura](images/arquitetura-exemplo.png)


# Avaliação da Aplicação

1. Teste de registro de usuário:
Cenário: O usuário entra na plataforma
Ação: O usuário preenche os campos obrigatórios do formulário de registro e envia as informações.
Resultado esperado: As informações são passadas corretamente para dentro da app.
2. Teste de upload de músicas:
Cenário: O usuário se registrou como artista plataforma.
Ação: O usuário adiciona uma música preenchendo todos os campos obrigatórios.
Resultado esperado: A música é adicionada com as informções corretas, o usuário é direcionado para a
Home e a música adicionada começa a tocar.
3. Teste das funcionalidades do app no geral:
Cenário: O usuário tem mais de uma música adicionada.
Ação: O usuário testa a search page, botões da home page e todas as listas e botões do profile.
Resultado esperado: Tudo funcionará corretamente.

## Plano de Testes

Foram selecionados os testes 1, 2 e 3

## Registros de Testes

1. Teste de registro de usuário:
  Todos os testes correram perfeitamente

2. Teste de upload de músicas:
  Todos os testes correram perfeitamente

3. Teste das funcionalidades do app no geral:
   Todos os testes correram perfeitamente


# Referências

......  COLOQUE AQUI O SEU TEXTO ......

> Inclua todas as referências (livros, artigos, sites, etc) utilizados
> no desenvolvimento do trabalho.
> 
> **Links Úteis**:
> - [Formato ABNT](https://www.normastecnicas.com/abnt/trabalhos-academicos/referencias/)
> - [Referências Bibliográficas da ABNT](https://comunidade.rockcontent.com/referencia-bibliografica-abnt/)
