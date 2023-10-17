<h1 align="center" >5º Semestre (2023.2)</h1>

## Sobre o projeto 

<p align="justify">
Como parte das atividades das áreas de engenharia de empresas de Saneamento, Elétrica, Telecomunicações e outros tipos de negócios em que as áreas demandam a realização de obras e manutenção de equipamentos em campo, se faz necessário utilizar uma aplicação móvel onde seja possível realizar a gestão dos dados relativos aos equipamentos (ativos) da companhia, via aplicativo móvel, possibilitando manter o cadastro dos ativos atualizados.

Este recurso é amplamente utilizado em processos de manobras, onde um equipamento precisa ser desativado para que seja realizada uma manutenção. Durante esta etapa de manutenção parte da rede de serviços pode ser afetada, e por sua vez afetar os clientes conectados a ela, e ter o cadastro destes ativos atualizados em campo em tempo real é primordial para que a qualidade dos serviços prestados para os consumidores.

Dessa forma, o projeto consiste no desenvolvimento de um aplicativo mobile que permita o gerenciamento (online e offline) de equipamentos públicos em campo (Ativos) para a Imagem Geosistemas. Esse aplicativo deve ainda ser capaz de garantir a gestão desses equipamentos (consultar, atualizar, desativar e cadastrar), permitindo a conexão com sensores e comunicação a serviços externos e exibindo esses equipamentos em tempo real nos mapas (conforme a posição geográfica do usuário em um raio de 10km).
</p>

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
<img src="https://github.com/peonia-api/API_5_Semestre/blob/main/images/Backlog%20priorizado%20-%202ª%20Sprint.png"/>



### Cadastro de usuário
![](https://github.com/peonia-api/API_5_Semestre/blob/main/videos/Cadastro_Usu%C3%A1rio.gif)

### Login e operação
![](https://github.com/peonia-api/API_5_Semestre/blob/main/videos/Login_Opera%C3%A7%C3%A3o.gif)

<a href="https://github.com/peonia-api/API_5_Semestre">Github da Equipe</a>


## Tecnologias utilizadas

| Tecnologia | Descrição |
|--------|-----------|
| [![My Skills](https://skillicons.dev/icons?i=postgres)](https://skillicons.dev)  | Foi utilizado no armazenamento dos dados. |
| <img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg"/> | Foi utilizado na criação das páginas. |
| <img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg"/>  | Foi utilizado para a estilização do site.|
| [![My Skills](https://skillicons.dev/icons?i=react)](https://skillicons.dev) | Foi utilizado na criação do site.|
| <a href="https://github.com/EquipeApolo/API_1SEM" ><img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg"/> </a> | Foi utilizado para a hospedagem do código. |
| [![My Skills](https://skillicons.dev/icons?i=nodejs)](https://skillicons.dev)  | Foi utilizado para desenvolver o Back-end do site.| 
| <img width="50 rem" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg"/> |Foi ultilizado para o desenvolvimento do código. |
| [![My Skills](https://skillicons.dev/icons?i=typescript)](https://skillicons.dev) | Foi ultilizado para o desenvolver o Back-end do site. |
|  [![My Skills](https://skillicons.dev/icons?i=figma)](https://skillicons.dev)  | Foi ultilizado para a prototipagem das telas. |
| <img width="50 rem" src="https://cdn.icon-icons.com/icons2/3053/PNG/512/microsoft_teams_alt_macos_bigsur_icon_189961.png" /> | Foi ultilizado para a comunicação. |
|  [![My Skills](https://skillicons.dev/icons?i=gcp)](https://skillicons.dev)  | Foi ultilizado para a hospedagem do site. |

## Contribuições pessoais
<p align="justify">
Ao longo do projeto, desempenhei um papel versátil e abrangente, que abarcou desde a criação de um servidor utilizando Express com TypeScript até a implementação de uma API REST para facilitar a comunicação eficaz entre o servidor e o cliente, garantindo o funcionamento integral do sistema. Além disso, assumi a responsabilidade de ser o Scrum Master da equipe.
</p>

## Hard Skills
* Desenvolvimento de um servidor com Express: Sei fazer com autonomia.
* Criação de uma REST API para facilitar a comunicação entre o servidor e o cliente: Sei fazer com autonomia.
* Ligação do servidor com o front-end: Sei fazer com autonomia.



## Soft Skills
 * Comunicação: A comunicação foi essencial para facilitar a compreensão do projeto e para disseminar ideias de maneira eficaz.
 * Colaboração: A colaboração desempenhou um papel fundamental ao estimular a criação de ideias, proporcionar suporte aos membros da equipe e garantir a distribuição justa de responsabilidades entre todos os participantes.
 * Empatia: A empatia desempenhou um papel fundamental ao permitir o entendimento dos conhecimentos individuais de cada membro e ao facilitar o apoio mútuo durante o processo de desenvolvimento.
 * Flexibilidade: A flexibilidade foi essencial para a incorporação de melhorias e novas funcionalidades.
 * Comprometimento: O comprometimento desempenhou um papel crucial na garantia do cumprimento das responsabilidades de cada membro da equipe.




