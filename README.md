# Desafio Front-end do Agenda Edu


## Introdução

Estamos muito felizes que você tenha chegado nessa etapa do nosso processo seletivo, para essa fase, desejamos que você resolva um desafio básico.


## Desafio

Nosso líder técnico Renon Guirgel deseja exibir uma aplicação web no telão principal da empresa, aonde será possível visualizar os principais repositórios de cada linguagem de programação utilizada na empresa, utilizando a [API do GitHub](https://developer.github.com/v3/). Ele deseja que os principais repositórios de cada linguagem sejam acessados por tabs. A idéia é motivar o time de desenvolvimento, mostrando as maiores tendências no mundo da programação. Como nosso líder técnico é apaixonado por performance, é extratamente necessário que a aplicação utilize paginação para exibição dos dados(utilizar o esquema de paginação fornecido pela [API do GitHub](https://developer.github.com/v3/). É necessário que seja possível favoritar repositórios e que eles sejam de fácil acesso.


## Requisítos

- Deve ser um PWA
- Não é obrigatório o uso de um framework específico, mas recomendamos utilizar [React.js][reactjs-url], [Preact.js][preactjs-url] ou [Angular][angular-url]
- Não é obrigatório o uso de um framework de controle de estado específico, mas recomendamos utilizar [Redux.js][reduxjs-url]
- Necessário o uso de rotas
- A lista de repositórios devem ser armazenadas em cache, para funcionamento offline, caso não exista dados no cache, a API deve ser consultada. Utilizar a [Web API de cache][cache-api-url].
- Os repositórios favoritados devem ser salvos utilizando o API [Realtime Database do Firebase][firebase-database-url] e no cache, utilizando a [Web API de cache][cache-api-url], o carregamento dos favoritos deve seguir o mesmo padrão do carregamento de repositórios citado acima.


## Requisitos bonus

**Esses requisitos não são obrigatórios, mas seram levados em consideração como pontos extras no momento da avaliação.**

- Boa qualidade de UI/UX
- Baixo tempo de renderização
- Renderização de listas on-demand, exemplo: Dado que a lista tem 100 items, não renderizar a lista completa, renderizar apenas os items visíveis na tela e alguns extras para evitar engasgos de scroll.
- Teste unitários, pode utilizar qualquer framework de teste, sugerimos utilizar [Jest][jest-url] ou [Mocha.js][mocha-url].


## Critérios de avaliação

- Organização do projeto: Avalia a estrutura do projeto, documentação e uso de controle de versão;
- Inovação tecnológica: Avalia o uso de tecnologias mais recentes, desde que estáveis;
- Coerência: Avalia se os requisitos foram atendidos;
- Boas práticas: Avalia se o projeto segue boas práticas de desenvolvimento, incluindo segurança e otimização;
- Controle de Qualidade: Avalia se o projeto possui qualidade assegurada por testes automatizados (por exemplo [Jest][jest-url] ou [Mocha.js][mocha-url]) e integração contínua (por exemplo [Travis][travis-ci-url]).


## Processo de submissão

O desafio deve ser entregue pelo [GitHub][github-url]. A aplicação deve estar hospedada no ([Heroku][heroku-url], [Firebase][firebase-url], [AWS][aws-url], [gh-pages][gh-pages-url], etc) As URLs devem ser enviadas por email.

Qualquer dúvida em relação ao desafio, responderemos por e-mail.

Bom trabalho!

[reactjs-url]: https://reactjs.org/
[preactjs-url]: https://preactjs.com/
[angular-url]: https://angular.io/
[reduxjs-url]: https://redux.js.org/
[cache-api-url]: https://developer.mozilla.org/en-US/docs/Web/API/Cache
[jest-url]: https://facebook.github.io/jest/
[mocha-url]: https://mochajs.org/
[github-url]: https://github.com
[heroku-url]: https://www.heroku.com/
[firebase-url]: https://www.firebase.com/
[aws-url]: https://aws.amazon.com/
[gh-pages-url]: https://pages.github.com/
[firebase-database-url]: https://firebase.google.com/docs/database/
[travis-ci-url]: https://travis-ci.com/

