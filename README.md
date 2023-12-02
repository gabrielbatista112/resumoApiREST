# Api REST e RESTFul
API REST é um conjunto de princípios arquiteturais que define como recursos web podem ser criados e interconectados. Ela utiliza uma abordagem stateless, o que significa que cada solicitação do cliente contém toda a informação necessária para entender e processar a requisição. As APIs RESTful são implementações específicas que seguem os princípios REST.

# Diferenças entre REST e RESTFul
A principal diferença entre REST e RESTFul está na aderência aos princípios da arquitetura REST. Uma API RESTful segue estritamente esses princípios, enquanto uma API REST pode ter flexibilidade na implementação. As APIs RESTful são mais padronizadas, preconizando a utilização de URIs para identificação dos recursos, o uso apropriado dos verbos HTTP e a representação de recursos no formato desejado (como JSON ou XML).

# HTTP verbs
Os verbos HTTP, como definidos pela especificação HTTP/1.1, são utilizados para indicar a ação a ser realizada em um recurso identificado. Alguns dos verbos mais comuns são:

GET: Recupera um recurso. POST: Cria um novo recurso. PUT: Atualiza um recurso existente. DELETE: Remove um recurso. PATCH: Aplica modificações parciais a um recurso. A escolha do verbo adequado é crucial para manter a semântica e integridade da API.

# HTTP Status Code
Os códigos de status HTTP são retornados como parte da resposta de uma requisição para indicar o resultado da operação. Alguns códigos comuns incluem:

200 OK: Indica sucesso na requisição. 201 Created: Usado ao criar um novo recurso com sucesso. 204 No Content: Indica sucesso, mas não há conteúdo para enviar. 400 Bad Request: Indica que a requisição do cliente é inválida. 401 Unauthorized: Indica falha na autenticação ou falta de autorização. 404 Not Found: Indica que o recurso não foi encontrado.
