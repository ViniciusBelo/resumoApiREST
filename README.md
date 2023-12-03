# resumoApiREST

# Api REST e RESTFul

Uma API REST, ou API RESTful, é uma interface de programação de aplicações que segue os princípios de design da arquitetura REST (Representational State Transfer), definida por Roy Fielding em 2000. Essas APIs são flexíveis e comumente utilizadas para conectar componentes e aplicativos em arquiteturas de microsserviços.

## Diferenças entre REST e RESTFul

Enquanto REST refere-se às restrições arquiteturais, RESTful é usado para descrever APIs que seguem essas restrições. As APIs RESTful devem aderir a seis princípios de design, incluindo uma interface uniforme, desacoplamento do cliente-servidor, ausência de estado definido, capacidade de armazenamento em cache, arquitetura em camadas e a opção de código sob demanda.

## HTTP verbs

Os verbos HTTP desempenham um papel crucial em APIs RESTful. Alguns exemplos incluem:
  * GET: Recupera um recurso.
  * POST: Cria um novo recurso.
  * PUT: Substitui todas as representações de um recurso.
  * DELETE: Remove um recurso.
  * PATCH: Aplica modificações parciais em um recurso.

## HTTP Status Code

Os códigos de status HTTP indicam o resultado de uma operação. Exemplos incluem:
  * 200 OK: Sucesso na requisição.
  * 201 Created: Criação bem-sucedida de um novo recurso.
  * 404 Not Found: Recurso não encontrado.
  * 500 Internal Server Error: Erro interno no servidor.

## Como as APIs de REST funcionam

As APIs de REST utilizam solicitações HTTP para realizar operações CRUD (Criar, Ler, Atualizar, Excluir) em recursos. Por exemplo, GET para recuperar, POST para criar, PUT para atualizar e DELETE para excluir. As respostas podem ser em formatos como JSON, HTML, XML, entre outros. A flexibilidade das APIs de REST permite diversas abordagens, mas é crucial seguir melhores práticas. A OpenAPI Specification (OAS) facilita a descrição detalhada da API. A segurança é essencial, envolvendo HTTPS, algoritmos de hashing e estruturas de autorização como OAuth 2.0.

## Métodos de requisição HTTP

Os métodos HTTP, também chamados de verbos HTTP, indicam a ação a ser executada em um recurso:
* GET: Recupera a representação de um recurso.
* POST: Submete uma entidade a um recurso, causando alterações.
* PUT: Substitui todas as representações de um recurso.
* DELETE: Remove um recurso.
* PATCH: Aplica modificações parciais em um recurso.

Em resumo, as APIs REST proporcionam uma maneira eficiente e flexível de interação entre sistemas, seguindo princípios como verbos HTTP, códigos de status e respeitando as restrições da arquitetura REST.
    
---

Autor do resumo: Vinícius Belo - 01555920
