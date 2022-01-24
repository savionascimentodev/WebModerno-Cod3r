### Protocolo HTTP

#### Características

- Camada de Aplicação;
- Cliente-Servidor;
- Stateless;
- TCP/IP;
- Html/Css/Js/Mídias...;

#### Fluxo

Usuário informa a Url => Browser gera a requisição tipo Get => Servidor gera a Resposta => Browser exibe a página.

#### Métodos HTTP

- Get;
- Post;
- Delete;
- Put;
- Trace;
- Head;
- Connect;
- Options;

#### Requisição e Resposta

Cliente manda a Url + Params para o servidor => O Servidor retorna Html,Css,Js,Mídias...

#### Método Get X Post

Temos a Url e os Parâmetros da Requisição, os parâmetros vão ná própria requisição no **cabeçalho** e o corpo vai vazio já em um **Método Post** os dados vão no **corpo** da requisição

#### Grupos de Status de Mensagens

- 1XX - Informação;
- 2XX - Sucesso;
- 3XX - Redirecionamento;
- 4XX - Erro no Cliente;
- 5XX - Erro no Servidor;

### Servidores Web

Quando uma máquina cliente tenta acessar o nosso site, temos uma requisição para o site, antes de conseguir chegar de fato no Servidor no qual irá servir a página mostrada no browser é necessário que uma consulta **DNS** seja feita, uma vez que o DNS resolveu o **IP** ele vai para o nosso servidor.
