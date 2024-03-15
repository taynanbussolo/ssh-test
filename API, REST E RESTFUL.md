# API, REST e RESTFUL

Cliente (client)
Garçon (pedidos) (API)
Cozinha (server)

# REST
Representational State Transfer
Geralmente usando HTTP
Delimita algumas obrigações

# 6 constraints para ser RESTFUL

- _Cliente-server_: separção do cliente e do armazenamento de dados

- _Stateless_: cada requisição que o cliente faz para os ervidor, deverá conter todas as informações necessáriias para o servidor entender e responder (RESPONSE) a requisição (REQUEST). Uso de TOKENS para autenticação.

- _Cacheable_: as respostas para uma request deverão ser explícitas ao dizer se aquela requisição pode ou não ser cacheada pelo cliente.

- _Layered System_: o cliente acessa a um endpoint, sem saber da complexidade dos passos necessários para o servidor responder a requisição ou quais outras camadas o servidor estará lidando, para que a requisição seja respondida.

 _Uniform Interface_: usar o mesmo padrão de formato, informações detalhadas, comunicação clara e efetiva.

- _Code on demand (optional)_: dá a possibildade da nossa aplicação pegar códigos, como o javascript, por exemplo, e executar no cliente


# RESTFUL
Aplicação dos padrões REST

