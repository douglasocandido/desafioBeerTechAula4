# beetech desafio

deadline: 09/10/2020

Analisem a imagem abaixo, este wireframe representa um site de busca e reserva de hotéis em todo mundo, tome-se base um site como [Booking](https://www.booking.com/%5D).

Ele terá as seguintes funcionalidades:

1. Ao abrir o site a exibição de Hoteis parceiros reconhecendo a localização atual da pessoa acessante.
2. Ter um campo de busca onde ao digitar palavras chaves como "New York, central park"
3. A busca deverá ler o texto digitado e repassar para a api que deve retornar uma lista de sugestões em dropdown
4. Após a seleção da sugestão os cards de hoteis deverá atualizar para as sugestões de hoteis da região
5. A apresentação de cards dos hoteis deverá possibilitar paginação

![https://github.com/leoqbc/beertech-react/raw/master/Aula4_SOLID/tela_mock.png](https://github.com/leoqbc/beertech-react/raw/master/Aula4_SOLID/tela_mock.png)

Debatam entre vocês quais elementos, classes, funções, ferramentas deverão ser usadas no projeto, detalhem os componentes visuais e seus eventos, pode ser feito um desenho, ou até mesmo escrito, definindo quais elementos vocês julgam importantes ter neste projeto frontend.

Exemplos de perguntas importantes:

- **Como será a padronização de código?**
    - Componentes funcionais.
    - Responsabilidade única.
    - Boas práticas de acessibilidade.
- **Quais libs/ferramentas serão usadas?**
    - *TypeScript*
    - *React*
    - *Jest - testes*
    - [*Material UI](https://material-ui.com/) - estilização*
    - *Sass - estilização*
    - *Yarn - gerenciamento de pacotes*
    - *Webpack - module bundler*
    - *eslint - padronização de código*
    - [*Git](https://github.com/douglasocandido/desafioBeerTechAula4) - versionamento*
- **Quais componentes visuais existirão?**
    1. Card
    2. Campo de busca
    3. Dropdown de resultados
    4. Live search
    5. Paginação
    6. Header
    7. Navbar
    8. Banner
    9. Footer
- **Como será a interação entre Frontend e Backend?**
    - HTTP Request.
    - API geolocalização.
