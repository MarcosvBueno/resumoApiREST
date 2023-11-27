## Menu de Navegação

- [API REST e RESTFul](#api-rest-e-restful)
- [Diferenças entre REST e RESTFul](#diferenças-entre-rest-e-restful)
- [HTTP Verbs](#http-verbs)
- [HTTP Status Code](#http-status-code)
- [Referências](#referências)
- [Autor do Resumo](#autor-do-resumo)

# API REST e RESTFul

Uma API REST (Representational State Transfer) é uma abordagem arquitetural para criar serviços web que sejam escaláveis e interoperáveis. Utiliza uma comunicação stateless, ou seja, cada solicitação do cliente contém toda a informação necessária para entender e processar a requisição. Essa arquitetura é baseada em recursos, que são identificados por URLs.

## Diferenças entre REST e RESTFul

RESTFul é uma extensão do conceito REST que define um conjunto de convenções e boas práticas para projetar APIs. Uma API RESTFul segue princípios adicionais, como a utilização adequada dos métodos HTTP e a organização lógica dos recursos. Enquanto o REST define os princípios, o RESTFul oferece diretrizes específicas para implementar esses princípios de maneira mais eficaz.

## HTTP Verbs

Os métodos HTTP (HTTP verbs) são utilizados para indicar a ação desejada em um recurso identificado. Alguns dos principais métodos incluem:

- **GET**: Recupera dados de um recurso.
- **POST**: Cria um novo recurso com os dados fornecidos.
- **PUT**: Atualiza um recurso existente ou cria um novo se não existir.
- **DELETE**: Remove um recurso.
- **PATCH**: Aplica modificações parciais a um recurso.
- **HEAD**: Retorna apenas os cabeçalhos da resposta, sem o corpo da mensagem.
- **OPTIONS**: Descreve as opções de comunicação com o recurso alvo.
- **TRACE**: Executa um teste de loop-back ao longo do caminho para o recurso alvo.

Esses métodos fornecem uma interface uniforme para interação com os recursos da API.

Referências:
- [HTTP Methods - Mozilla Developer Network](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods)
- [HTTP Methods - TutorialsPoint](https://www.tutorialspoint.com/http/http_methods.htm)

## HTTP Status Code

Os códigos de status HTTP indicam o resultado de uma solicitação ao servidor. Alguns códigos comuns incluem:

- **200 OK**: Indica que a solicitação foi bem-sucedida.
- **201 Created**: Indica que a solicitação foi bem-sucedida e resultou na criação de um novo recurso.
- **400 Bad Request**: Indica que a solicitação do cliente é inválida ou malformada.
- **404 Not Found**: Indica que o recurso solicitado não foi encontrado.
- **500 Internal Server Error**: Indica que ocorreu um erro no servidor.

Esses códigos ajudam a entender o status da solicitação e permitem tomar as ações apropriadas.

Referências:
- [HTTP Status Codes - Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)
- [HTTP Status Codes - TutorialsPoint](https://www.tutorialspoint.com/http/http_status_codes.htm)

---

**Autor do resumo:** Marcos Bueno  - 01503130

