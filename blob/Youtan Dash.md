<div align="center"><h1>Youtan Dash</h1></div>

**4º Semestre • Projeto Integrador Fatec-SJC • [Repositório GitHub](https://github.com/CauevSilv/dashflow-2025-1)**  
**Empresa Parceira:** [Youtan](https://youtan.com.br/)

![alt text](/blob/imageYouthan.png)

O objetivo do projeto é desenvolver uma plataforma integrada a ferramenta de gestão de projetos Taiga, com o intuito de gerar e visualizar indicadores relacionados ao andamento de projetos. A plataforma deve fornecer um dashboard que permita a extração e análise de métricas importantes, como a quantidade de cards criados e finalizados em um período, tempo médio de execução de cards, distribuição de cards por colaborador, e outros indicadores relevantes para a gestão de projetos. A plataforma deve oferecer diferentes níveis de acesso para usuários, como Operador, Gestor e Admin, garantindo que cada perfil tenha acesso apenas às informações pertinentes ao seu papel. O projeto visa facilitar a visualização e o monitoramento do progresso dos projetos, tornando o processo mais eficiente, transparente e acessível para todos os envolvidos.

### Funcionalidades
* Integração com a API do Taiga e do Jira, por meio de um ETL;
* Dashboards dinâmicos e responsivos, projetados até para celulares;
* Gerenciamento de usuários, podendo definir permissões de acordo com o cargo;
* Integração dos usuários da aplicação com os usuários do Taiga; 

#### Tecnologias Utilizadas
- HTML: linguagem de programação para criação de páginas Web;
- CSS: linguagem para aplicação de estilos em códigos HTML;
- TypeScript: linguagem variante de JavaScript que adiciona tipagem ao código;
- Vue.js: framework JavaScript para o desenvolvimento de SPA (Single Page Application) e facilitador na criação de códigos reutilzáveis;
- Java: linguagem de programação orientada a objetos;
- Spring Boot: framework Java para desenvolvimento de Rest APIs;
- ApacheSpark: ferramenta utilizada para realização do ETL;
- PostgresSql: banco de dados com schemas para o DW e para a aplicação.
- Oracle: banco de dados do ambiente de produção;
- IntelliJ IDEA: IDE para desenvolvimento Java;
- WebStorm: IDE da JetBrains focado em front-end. Utilizado para desenvolvimento do front end e para facilitar o debug. Possuí uma ótima integração com o Vue.js;
- Docker: ferramenta de gerenciamento de containers. Utilizado para o deploy;
- DBeaver: ferramenta utilizada para facilitar a visualização do banco;
- Figma: ferramenta utilizada para desenvolvimento de Mockups e Wireframes;
- Discord: ferramenta para comunicação interna do grupo;
- Slack: ferramenta para comunicação com o cliente

#### Contribuições Pessoais
- Desenvolvi diversos componentes do front-end, como a SideBar, formulário de criação de usuários, tabela de usuários, etc..
-  ![img.png](imgYtDash.png) ![img.png](imgYtDashUserTable.png)

- Implementei toda a responsividade da aplicação, tornando ela utilizável diversos formatos de telas;
- ![img.png](imgYtRespo1.png) ![img.png](imgYtRespo2.png)

- Criei os componentes de gráficos responsivos e com ações integradas, como os filtros;
- ![img.png](imgYTIssueChart.png)
- Desenvolvi diversas chamadas a API, recebendo e tratando os dados para utilização nos dashboards;
- Fui responsável pelo deploy automático, processo que disponibiliza automaticamente a aplicação em um ambiente de produção totalmente diferente do ambiente de desenvolvimento. Realizei diversos ajustes para que a aplicação funcione no banco Oracle (originalmente era em Postgresql);
- Desenvolvi a tela de Profile, responável por exibir dados básicos do usuário logado;
- Implementei o gerenciamento de estado com o Pinia.
- Ajustei alguns controllers do backend com dados sem sentido ou incorretos, e também algumas consultas desatualizadas.

#### Hard Skills
- Java: sei fazer com autonomia;
- SQL:  sei fazer com autonomia e consigo ajudar outros membros da equipe;
- Spring Boot: sei fazer com autonomia, tanto a parte de Security quanto o Core e consigo ajudar outros membros;
- Oracle: sei fazer com ajuda/consulta;
- TypeScript: sei fazer com autonomia e consigo ajudar outros membros;
- Vue.Js: sei fazer com autonomia e consigo ajudar os outros membros;
- CI: sei fazer com consulta;
- Responsividade: sei fazer com autonomia;
- Docker: sei fazer com autonomia;

#### Soft Skills
- Iniciativa: tomei a frente do front-end do projeto com os componentes complexos, responsividade e fui responsável pelo deploy;
- Flexibilidade: atuei em todas as áreas da aplicação, sempre buscando autonomia sem comprometer o trabalho em equipe;
- Comunicação: participei das reuniões semanais da equipe para discutir diversos pontos do projeto;
- Gerenciamento de demandas: negociei demandas com outros membros da equipe para focar me uma demanda maior, e também troquei com outros para ajudá-los em situações parecidas.
- Gerenciamento de tempo: ganhei ainda mais conehcimento com gerenciamento de tempo com diversas tasks.