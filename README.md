<span id="topo">

# Data Forest - ByteLabs

![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![Jira](https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)

<span id="indice">

## Índice 📎

- [Índice 📎](#indice)
- [Sobre 📚](#sobre)
- [Backlog do Produto 📍](#backlog-do-produto)
- [Cronograma de Entrega 🗓](#cronograma-de-entrega)
- [Equipe 👩‍💻👨‍💻](#equipe)

<span id="sobre">

## Sobre 📚

<p align="center">
        <a href="#problema">O Problema 🤔</a> | 
        <a href="#objetivo">Objetivo do Projeto 🎯</a> | 
        <a href="#requisitos">Requisitos Funcionais do Projeto 📝</a> | 
        <a href="#desenvolvimento"> Regras de Desenvolvimento 📏</a>
</p>

<p align="justify">
A projeto Data Forest da equipe ByteLabs é resultado do Aprendizado por Projetos Integrados da Faculdade de Tecnologia do Estado de São Paulo (FATEC) de São José dos Campos. A cada semestre, os alunos são desafiados a desenvolver um projeto de software, com base em um problema real apresentado pela empresa parceira Kersys. O projeto é desenvolvido em sprints, com entregas parciais e um produto final que atenda às necessidades do cliente.
</p>

<span id="problema">

### O Problema 🤔

<p align="justify">
O problema apresentado está relacionado ao meio ambiente e o processo de reflorestamento de uma área. Precisamos atuar como facilitadores no processo de reflorestamento, desde a visualização da área do projeto em um mapa, até nas próprias estratégias de reflorestamento e no acompanhamento do processo como um todo.
</p>

<span id="objetivo">

### Objetivo do Projeto 🎯

<p align="justify">
A solução proposta pela equipe é desenvolver uma plataforma web, que permite o cadastro de uma área geográfica, e a partir dela, fazer um cruzamento com nossa base de dados e nossos modelos de inteligência artificial. O resultado desse cruzamento será um acompanhamento em tempo real e estratégias personalizadas para garantir a minimização de riscos e a maior taxa de sucesso possível para o projeto de reflorestamento. Além de insights valiosos como: 
</p>

- <p align="justify">Métricas de saúde florestal da área. (ex. oxigenação, hidratação e tempo de vida do plantio).</p>
- <p align="justify">Identificação de riscos e cuidados a ser tomados a partir de dados geográficos e climáticos da área.</p>
- <p align="justify">Indicação de espécies de plantas para o plantio, baseados na época do ano e na longevidade desejada.</p>
- <p align="justify">Geração de relatórios para acompanhamento retroativo do processo de reflorestamento.</p>

<p align="justify">
A plataforma será voltada para produtores agrícolas, engenheiros ambientais e parceiros da empresa.
</p>

<span id="requisitos">

### Requisitos Funcionais do Projeto 📝

[Acesse a documentação completa dos requisitos](https://github.com/bytelabss/ByteLabs-API6Sem/wiki/Proposta-de-Solu%C3%A7%C3%A3o:-Projeto-Dataforest#requisitos)

<table>
        <tr>
                <td>
                        1.
                </td>
                <td>
                        Implementação de um sistema de predição, se utilizando de modelos de Machine Learning, capaz de analisar uma área geográfica cadastrada, e retornar qual a melhor espécie para plantio, e qual a melhor estratégia a ser seguida para o processo de reflorestamento, se baseando em dados reais da área no Brasil ao longo do tempo.
                </td>
        </tr>
        <tr>
                <td>
                        2.
                </td>
                <td>
                        Área para cadastro e visualização de áreas, se utilizando de coordenadas geográficas do Brasil.
                </td>
        </tr>
        <tr>
                <td>
                        3.
                </td>
                <td>
                        Banco de dados com dados reais geográficos das áreas do Brasil, para ser usado para treinamento e utilização dos modelos de Machine Learning.
                </td>
        </tr>
        <tr>
                <td>
                        4.
                </td>
                <td>
                        Área para visualização das áreas cadastradas pelo usuário, além de relatórios a respeito das espécies a serem plantadas, e alertas para caso a área precise de atenção ou esteja sob risco de alterações climáticas.
                </td>
        </tr>
</table>

<span id="desenvolvimento">

### Requisitos Não funcionais do Projeto

[Acesse a documentação completa dos requisitos](https://github.com/bytelabss/ByteLabs-API6Sem/wiki/Proposta-de-Solu%C3%A7%C3%A3o:-Projeto-Dataforest#requisitos)

<table>
        <tr>
                <td>
                        1.
                </td>
                <td>
                        Documentação das tecnologias e banco de dados escolhidos para o projeto, com justificativas, e documentação das rotas da API criada no backend.
                </td>
        </tr>
        <tr>
                <td>
                        2.
                </td>
                <td>
                        Implementação de aspectos da LGPD para garantir a segurança e a proteção do usuário durante a manipulação de seus dados.
                </td>
        </tr>
        <tr>
                <td>
                        3.
                </td>
                <td>
                        Criação de um repositório de documentação especial sobre o produto.
                </td>
        </tr>
        <tr>
                <td>
                        4.
                </td>
                <td>
                        Criação do modelo MER do banco de dados relacional.
                </td>
        </tr>
</table>

### Regras de Desenvolvimento 📏

[Regras de Desenvolvimento](https://github.com/bytelabss/ByteLabss-API5sem/wiki/Regras-de-Desenvolvimento)

<span id="backlog-do-produto">

### Definition of Ready (D.O.R)

Critérios gerais:
- A user story foi detalhada e compreendida por todos os envolvidos.
- Os critérios de aceitação estão claramente definidos.
- O backlog contém todas as informações necessárias.
- O design básico da interface com a ideia principal.
- O ambiente de desenvolvimento está preparado para implementação.


## Backlog do Produto 📍

<body>
        <div align="center">
                <table>
                        <thead>
                                <th>ID</th>
                                <th>Requisito <b> funcional</b></th>
                                <th>User Story</th>
                                <th>Sprint</th>
                                <th>Jira Link</th>
                        </thead>
                        <tbody>
                                <tr>
                                        <td>US01</td>
                                        <td>2</td>
                                        <td align="justify">Como engenheiro ambiental, quero cadastrar, editar e visualizar novas áreas reflorestadas com informações detalhadas, para que o sistema possa monitorá-las corretamente.</td>
                                        <td>1</td>
                                        <td><a href="https://bytelabss.atlassian.net/browse/LABS-1">LABS-1</a></td>
                                </tr>
                                <tr>
                                        <td>US02</td>
                                        <td>2</td>
                                        <td align="justify">Como produtor, quero visualizar minhas áreas de plantio atualizadas em um mapa interativo, para acompanhar a distribuição geográfica e evolução.</td>
                                        <td>1</td>
                                        <td><a href="https://bytelabss.atlassian.net/browse/LABS-3">LABS-3</a></td>
                                </tr>
                                <tr>
                                        <td>US03</td>
                                        <td>-</td>
                                        <td align="justify">Como administrador, quero definir permissões de acesso para diferentes usuários (engenheiro ambiental e produtores), para garantir segurança e conformidade com a LGPD.</td>
                                        <td>2</td>
                                        <td><a href="https://bytelabss.atlassian.net/browse/LABS-4">LABS-4</a></td>
                                </tr>
                                <tr>
                                        <td>US04</td>
                                        <td>3</td>
                                        <td align="justify">Como engenheiro ambiental, quero ter acesso a uma base de dados confiável sobre reflorestamento do Brasil com dados sobre características do solo e da área, para compreender as necessidades e possibilidades de um terreno para reflorestamento.</td>
                                        <td>1</td>
                                        <td><a href="https://bytelabss.atlassian.net/browse/LABS-2">LABS-2</a></td>
                                </tr>
                                <tr>
                                        <td>US05</td>
                                        <td>-</td>
                                        <td align="justify">Como um engenheiro ambiental, quero que as ações do sistema estejam em conformidade com a LGPD.</td>
                                        <td>-</td>
                                        <td><a href="https://bytelabss.atlassian.net/browse/LABS-26">LABS-26</a></td>
                                </tr>
                                <tr>
                                        <td>US06</td>
                                        <td>1</td>
                                        <td align="justify">Como um engenheiro ambiental, quero receber recomendações sobre as melhores espécies para cada área, considerando as condições climáticas e características do solo, para garantir um reflorestamento eficiente.</td>
                                        <td>2</td>
                                        <td><a href="https://bytelabss.atlassian.net/browse/LABS-31">LABS-31</a></td>
                                </tr>
                                <tr>
                                        <td>US07</td>
                                        <td>4</td>
                                        <td align="justify">Como um engenheiro ambiental, quero identificar áreas sob risco de condições ambientais adversas, para tomar medidas preventivas.</td>
                                        <td>3</td>
                                        <td><a href="https://bytelabss.atlassian.net/browse/LABS-32">LABS-32</a></td>
                                </tr>
                                <tr>
                                        <td>US08</td>
                                        <td>1</td>
                                        <td align="justify">Como um produtor, quero visualizar diferentes estratégias de plantio, para avaliar seus impactos antes de implementar mudanças.</td>
                                        <td>2</td>
                                        <td><a href="https://bytelabss.atlassian.net/browse/LABS-33">LABS-33</a></td>
                                </tr>
                                <tr>
                                        <td>US09</td>
                                        <td>4</td>
                                        <td align="justify">Como um analista ambiental, quero visualizar indicadores-chave de reflorestamento de áreas sob riscos, para facilitar a tomada de decisão.</td>
                                        <td>3</td>
                                        <td><a href="https://bytelabss.atlassian.net/browse/LABS-35">LABS-35</a></td>
                                </tr>
                                <tr>
                                        <td>US10</td>
                                        <td>4</td>
                                        <td align="justify">Como um analista ambiental, quero gerar relatórios sobre o reflorestamento.</td>
                                        <td>3</td>
                                        <td><a href="https://bytelabss.atlassian.net/browse/LABS-36">LABS-36</a></td>
                                </tr>
                        </tbody>
                </table>
        </div>
</body>

<span id="cronograma-de-entrega">

## Cronograma de Entrega 🗓

| *Sprints*  | *Cronograma*             | 
| ---------- | ----------               | 
|  [Sprint 1](https://github.com/bytelabss/ByteLabs-API6Sem/wiki/Sprint-1)  |  10/03 a 30/03           | 
|  [Sprint 2](https://github.com/bytelabss/ByteLabs-API6Sem/wiki/Sprint-2)  |  07/04 a 27/04           | 
|  [Sprint 3](https://github.com/bytelabss/ByteLabs-API6Sem/wiki/Sprint-3)  |  05/05 a 25/05           |    

<span id="equipe">

## Equipe 👩‍💻👨‍💻

<body>
        <div align="center">
                <table>
                        <thead>
                                <th>Alec Rondel - Scrum Master</th>
                                <th>Cauana Dias - Product Owner</th>
                                <th>Antônio Zago - Developer</th>
                                <th>Jhonny Dutra - Developer</th>
                                <th>Larissa Reis - Developer</th>
                        <thead>
                        <tbody>
                                <tr>
                                        <th>
                                                <a href="https://github.com/aleclr">
                                                        <img src="https://avatars.githubusercontent.com/u/43094055?v=4" width="75px" height="75px"/>
                                                </a>
                                        </th>
                                        <th>
                                                <a href="https://github.com/Cauana">
                                                        <img src="https://avatars.githubusercontent.com/u/77700346?v=4" width="75px" height="75px"/>
                                                </a>
                                        </th>
                                        <th>
                                                <a href="https://github.com/Antonio-Zago">
                                                        <img src="https://avatars.githubusercontent.com/u/80283126?v=4" width="75px" height="75px"/>
                                                </a>
                                        </th>
                                        <th>
                                                <a href="https://github.com/dutrajy">
                                                        <img src="https://avatars.githubusercontent.com/u/122806886?v=4" width="75px" height="75px"/>
                                                </a>
                                        </th>
                                        <th>
                                                <a href="https://github.com/larissa-fernanda">
                                                        <img src="https://avatars.githubusercontent.com/u/111530654?v=4" width="75px" height="75px"/>
                                                </a>
                                        </th>
                                </tr>
                                <tr>
                                        <th>
                                                <a href="linkedin.com/in/alecrondel">
                                                        <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
                                                </a>
                                        </th>
                                        <th>
                                                <a href="https://www.linkedin.com/in/cauanadias?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">
                                                        <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
                                                </a>
                                        </th>
                                        <th>
                                                <a href="https://www.linkedin.com/in/antonio-zago-24230b206">
                                                        <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
                                                </a>
                                        </th>
                                        <th>
                                                <a href="https://www.linkedin.com/in/dutrajy?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">
                                                        <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
                                                </a>
                                        </th>
                                        <th>
                                                <a href="https://www.linkedin.com/in/larissa-reis-693568250">
                                                        <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
                                                </a>
                                        </th>
                                </tr>
                        <tbody>
                </table>
        </div>
</body>

→ [Voltar ao topo](#topo)
