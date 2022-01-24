### Web Service

Serviços que são disponibilizados pela sua aplicação que rodam em cima das tecnologias da web, rodando em cima do protocolo HTTP e essa comunicação, os dados são trafegados de forma textual **(XML, JSON)** que servem pra retonar os dados a partir de web services.

#### Formato REST

**Representational State Transfer**

Formato usando JSON, http puro, são requisições e respostas, fazendo uma requisição pra uma Url e retornando dependendo do tipo de verbo: Get,Put,Delete

#### Conveções RESTful

| URL          | Método | Descrição           |
| ------------ | ------ | ------------------- |
| /clientes    | GET    | Obtém todos         |
| /clientes/36 | GET    | Obtém cliente 36    |
| /clientes    | POST   | Novo cliente        |
| /clientes/12 | PUT    | Atualiza cliente 12 |
| /clientes/10 | DELETE | Exlui cliente 10    |

#### Escolhas Arquiteturais

**Arquitetura MicroServiços**

Micro serviços acontencem quando pegamos uma aplicação maior e quebramos ela em pequenos módulos auto contidos que você tem um ciclo de vida completo ali dentro, podendo tornar a aplicação mais fácil de evoluir, melhor que uma Monolítica por exemplo.

É muito comum dentro desse ambiente de micro você ter equipes focadas em um único serviço.
Por exemplo no Spotify existe provavelmente uma equipe específica para a criação e manutenção de playlists, você tem uma equipe especializada para cuidar do serviço.

Via de regra nas empresas essa equipe ela cuida do desenvolvimento,dos testes cuida da integração contínua cuida de colocar esse micro serviço em produção.

Então a equipe faz o trabalho de ponta a ponta em cima de algo bastante especifico da sua do seu sistema como o todo.

Então é como se fosse pequenos projetos independentes que somando todos esses serviços você vai acabar formando uma aplicação mais complexa.
