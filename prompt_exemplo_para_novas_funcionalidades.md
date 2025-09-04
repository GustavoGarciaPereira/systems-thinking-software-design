Olá! Preciso desenvolver uma nova funcionalidade no meu projeto FastAPI.

1. Objetivo Principal:

(Descreva em uma ou duas frases o que a funcionalidade deve fazer. Ex: "Criar um endpoint que busca o histórico de pedidos de um cliente e retorna um CSV.")

2. Contexto do Projeto (Arquitetura):

Aqui estão os arquivos que representam nosso padrão de arquitetura atual:
Controller/Router: [Cole o código do controller ou descreva sua estrutura]
Service/Use Case: [Cole o código da classe de serviço relevante]
API/Repository/External: [Cole o código da classe que lida com a comunicação externa]

3. Requisitos Detalhados (Critérios de Aceite):

Endpoint: [Ex: GET /v1/clients/{client_id}/history]
Parâmetros de Entrada: [Ex: client_id (path), start_date (query, opcional)]
Lógica de Negócio: [Ex: "O serviço deve chamar a API externa, formatar os dados para CSV e tratar o fuso horário para 'America/Sao_Paulo'."]
Resposta de Sucesso: [Ex: "Deve retornar um arquivo CSV com status 200 OK e o header 'Content-Disposition'."]
Tratamento de Erros: [Ex: "Se o cliente não for encontrado, retornar 404 com a mensagem 'Cliente não localizado'. Se a API externa falhar, retornar 502."]

4. Contratos e Exemplos Externos (Se aplicável):

Exemplo de Requisição Externa (SOAP/REST):
<!-- Cole aqui o corpo da requisição SOAP ou um exemplo de cURL para a API REST -->

Exemplo de Resposta Externa (Sucesso):
<!-- Cole aqui a resposta de sucesso para que eu possa mapear os campos corretamente -->

Exemplo de Resposta Externa (Erro/Ausência de Dados):
<!-- Cole aqui a resposta de erro para que eu possa implementar a validação correta -->


5. Preferências de Arquitetura:

(Esta parte é opcional, mas muito útil)
[Ex: "Prefiro que você crie novos arquivos (Interface, Implementação, Serviço) para esta funcionalidade em vez de alterar os existentes." ou "Pode adicionar os novos métodos às classes existentes."]

Usando este modelo, você me dará uma visão completa do problema, permitindo que eu gere uma solução de alta qualidade e bem arquitetada logo na primeira tentativa.
