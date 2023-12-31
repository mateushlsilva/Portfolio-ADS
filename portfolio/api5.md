<h1 align="center" >5º Semestre (2023.2)</h1>

## Sobre o projeto 
<details> <summary>Sobre o projeto</summary>

<p align="justify">
Como parte das atividades das áreas de engenharia de empresas de Saneamento, Elétrica, Telecomunicações e outros tipos de negócios em que as áreas demandam a realização de obras e manutenção de equipamentos em campo, se faz necessário utilizar uma aplicação móvel onde seja possível realizar a gestão dos dados relativos aos equipamentos (ativos) da companhia, via aplicativo móvel, possibilitando manter o cadastro dos ativos atualizados.

Este recurso é amplamente utilizado em processos de manobras, onde um equipamento precisa ser desativado para que seja realizada uma manutenção. Durante esta etapa de manutenção parte da rede de serviços pode ser afetada, e por sua vez afetar os clientes conectados a ela, e ter o cadastro destes ativos atualizados em campo em tempo real é primordial para que a qualidade dos serviços prestados para os consumidores.

Dessa forma, o projeto consiste no desenvolvimento de um aplicativo mobile que permita o gerenciamento (online e offline) de equipamentos públicos em campo (Ativos) para a Imagem Geosistemas. Esse aplicativo deve ainda ser capaz de garantir a gestão desses equipamentos (consultar, atualizar, desativar e cadastrar), permitindo a conexão com sensores e comunicação a serviços externos e exibindo esses equipamentos em tempo real nos mapas (conforme a posição geográfica do usuário em um raio de 10km).
</p>
</details>


## Requistos funcionais
- [x] Cadastro de equipamentos (Ativos), incluindo foto;
- [x] Ativação e desativação de equipamentos;
- [x] Visualização geográfica dos equipamentos cadastrados (tanto os ativos quanto os inativos);
- [x] Visualização detalhada dos equipamentos disponíveis no raio de ação do App;
- [x] Filtros de busca de equipamentos (baseado no seu tipo);
- [x] Cadastro de usuários, incluindo foto;
- [x] Liberação de usuários mediante processo de autenticação;
- [x] Recuperação de senha por meio de código (6 dígitos);
- [x] Criptografia de senhas;
- [x] Busca de equipamentos cadastrados (raio de 10km) de acordo com posição geográfica do App;
- [x] Sincronização de dados online em até 30 segundos após uso offline da aplicação;

## Requisitos não funcionais
- [x] Aplicação de dois fatores para autenticação em cada acesso (A2F);
- [x] Implementação de persistência poliglota;
- [ ] Condições de iluminação de tela adaptáveis à necessidade do usuário;
- [ ] Segurança das informações em caso de perda do dispositivo móvel;
- [x] Validação dos dados inseridos na aplicação (equipamentos e usuários);
- [ ] Banco de dados mobile para armazenamento dos dados atualizados dos equipamentos durante estado offline do App;

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



