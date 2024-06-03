<h1 align="center" >6º Semestre (2024.1)</h1>

## Sobre o projeto 
<details> <summary>Sobre o projeto</summary>

<p align="justify">
Na indústria petrolífera e em embarcações de exploração de petróleo existem locais de acesso restrito denominados Red Zone. Por segurança, nestas Red Zones deve haver o monitoramento da quantidade de acessos, que é feito atualmente por meio de câmeras nos locais. Essas imagens são monitoradas por guardas e todos os registros de entrada e saída desses locais são lançados manualmente em planilhas.

Por ser um trabalho manual, como dito anteriormente, as anotações estão suscetíveis a falha humana e a geração de relatórios acaba sendo trabalhosa. Por esse motivo, a Altave Intelligent Monitoring, empresa parceira, propôs o desenvolvimento de um sistema automático para contabilização do número de pessoas que entram e saem de cada Red Zone. Importante lembrar ainda que a câmera utilizada para o monitoramento desses locais cobre todos os pontos de entrada e saída, mas pode não alcançar toda a área da Red Zone.

Diante desse contexto, o sistema deverá fornecer uma interface que possibilite ao usuário visualizar a quantidade pessoas em tempo real no local, bem como consultar a movimentação naquela região em determinado período de tempo a ser selecionado pelo usuário. Além disso, o sistema poderá monitorar diversas Red Zones em cada departamento, portanto, será necessário que o acesso seja restrito a cada guarda de cada departamento, de modo que apenas o gerente de segurança terá acesso aos dados de todos os locais. 
</p>
</details>


## Requistos funcionais
- [x] Desenvolver uma interface web intuitiva para visualização dos registros em forma de relatórios;
- [x] Permitir exportação de relatórios contendo os registros do monitoramento realizado;
- [x] Implementar modelo de machine learning para automatizar o monitoramento das red zones;
- [x] Implementar método de autenticação de usuários;
- [x] Criar seção para gestão de usuários;
- [x] Permitir a inclusão e exclusão de usuários no sistema;
- [x] Criar seção para gestão de red zones, permitindo a inclusão e exclusão de red zones do sistema;
- [x] Desenvolver um dashboard com indicadores por períodos;
- [x] Permitir que o usuário aplique filtros por períodos para análise dos dados.

## Requisitos não funcionais

- [x] Manual do Usuário;
- [x] Documentação do sistema;
- [x] Guia de instalação; Front - Back - IA;
- [x] Acesso a organização do desenvolvimento (kanban, git...);

<h2>Backlog do produto</h2>
<image src="https://github.com/peonia-api/API_5_Semestre/blob/main/images/Backlog%20Priorizado%201ª%20Sprint.png"/>
<image src="https://github.com/peonia-api/API_5_Semestre/blob/main/images/Backlog%20priorizado%202ª%20Sprint.png"/>
<image src="https://github.com/peonia-api/API_5_Semestre/blob/main/images/Backlog%20Priorizado%203ª%20Sprint.png"/>



### Cadastro de usuário
![](https://github.com/peonia-api/API_5_Semestre/blob/main/videos/Cadastro_Usu%C3%A1rio.gif)

### Login e operação
![](https://github.com/peonia-api/API_5_Semestre/blob/main/videos/Login_Opera%C3%A7%C3%A3o.gif)

<a href="https://github.com/peonia-api/API_5_Semestre">Github da Equipe</a>


## Tecnologias utilizadas

| Tecnologia | Descrição |
|--------|-----------|
| [![My Skills](https://skillicons.dev/icons?i=postgres)](https://skillicons.dev)  | Foi utilizado no armazenamento dos dados. |
| [![My Skills](https://skillicons.dev/icons?i=mongo)](https://skillicons.dev)  | Foi utilizado no armazenamento dos dados. |
| <img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg"/> | Foi utilizado na criação das páginas. |
| <img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg"/>  | Foi utilizado para a estilização do site.|
| [![My Skills](https://skillicons.dev/icons?i=react)](https://skillicons.dev) | Foi utilizado na criação do site.|
| <a href="https://github.com/EquipeApolo/API_1SEM" ><img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg"/> </a> | Foi utilizado para a hospedagem do código. |
| [![My Skills](https://skillicons.dev/icons?i=nodejs)](https://skillicons.dev)  | Foi utilizado para desenvolver o Back-end do site.| 
| <img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg"/> |Foi ultilizado para o desenvolvimento do código. |
| [![My Skills](https://skillicons.dev/icons?i=typescript)](https://skillicons.dev) | Foi ultilizado para o desenvolver o Back-end do site. |
|  [![My Skills](https://skillicons.dev/icons?i=figma)](https://skillicons.dev)  | Foi ultilizado para a prototipagem das telas. |
| <img width="50 rem" src="https://cdn.icon-icons.com/icons2/3053/PNG/512/microsoft_teams_alt_macos_bigsur_icon_189961.png" /> | Foi ultilizado para a comunicação. |
|  [![My Skills](https://skillicons.dev/icons?i=azure)](https://skillicons.dev)  | Foi ultilizado para a hospedagem dos micro serviços. |
| <img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg"/>  | Foi utilizado para desenvolver a authenticator 2fa.| 
| <img width="50 rem" src="https://camo.githubusercontent.com/f3d50fa050625f1e9f27ca9a22a022a289f09fcf17d3fa23055c1ea61df5d0cc/68747470733a2f2f69636f6e732d666f722d667265652e636f6d2f69636f6e66696c65732f706e672f3531322f466c61736b2d313332343838383731393531313036353434372e706e67"/> | Foi ultilizado para desenvolver a authenticator 2fa. |

## Contribuições pessoais
<p align="justify">
Durante o projeto, assumi a liderança no gerenciamento do servidor da aplicação, organizando bancos de dados para uma arquitetura poliglota e desenvolvendo micro serviços para uma abordagem versátil. Minhas responsabilidades abrangeram a criação de micro serviços com Express, TypeScript, e integração com bancos relacionais, como o PostgreSQL, e não relacionais, como o MongoDB. Além disso, desenvolvi micro serviços dedicados ao CRUD de usuários da aplicação e outro para autenticação de 2FA, utilizando Python e Flask. Essa abordagem abrangente foi fundamental para o sucesso do projeto.
</p>

## Hard Skills
* Desenvolvimento de micro serviços: Sei fazer com autonomia.
* Desenvolvimento da arquitetura poliglota: Sei fazer com autonomia.
* Gerenciamento do servidor e banco de dados: Sei fazer com autonomia.


## Soft Skills
* Comunicação: Durante as reuniões de equipe, apresentei minhas ideias de forma clara e concisa. 
* Flexibilidade: Durante o projeto, busquei ser flexível para incorporar melhorias e novas funcionalidades.
* Colaboração: Ao longo do processo de desenvolvimento, desempenhamos um papel crucial ao fomentar a criação de ideias, oferecer suporte aos membros da equipe e assegurar uma distribuição equitativa de responsabilidades entre todos os participantes.



