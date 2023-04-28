<center> <h1>Atividade Protocolo HTTP</h1></center>

------

O desenvolvimento web é uma área em constante evolução, e uma aplicação web bem desenvolvida deve ter uma arquitetura robusta e organizada. A camada Front-end e a camada Back-end são dois pilares fundamentais de uma aplicação web. O Front-end é responsável pela parte visual e interativa da aplicação, enquanto o Back-end lida com a lógica de negócios e as interações com bancos de dados e outros sistemas. Além disso, existem protocolos que regem a comunicação entre as partes de uma aplicação web, como o HTTP e o HTTPS. Neste README, discutiremos as características de cada uma dessas áreas, bem como as diferenças entre os protocolos HTTP e HTTPS e os tipos de requisições e respostas HTTP mais comuns no desenvolvimento web.



<p align="center">
  <img src="https://blog.hyperiondev.com/wp-content/uploads/2018/10/Blog-Gif.gif" alt="Front, Back e FullStack">
</p>

------

## Descrição das Camadas Front-end e Back-end no Desenvolvimento Web

A camada Front-end é responsável pela apresentação e interação do usuário com a aplicação. Ela é composta por linguagens de marcação (HTML), estilização (CSS) e programação (JavaScript), que trabalham juntas para criar interfaces de usuário atraentes e funcionais. 

A camada Back-end, por sua vez, é responsável por processar e armazenar dados do usuário e da aplicação. Ela é composta por linguagens de programação (como PHP, Python ou Ruby), bancos de dados e servidores, que trabalham juntos para fornecer uma experiência de usuário dinâmica e personalizada.

## Diferença entre as Camadas Front-end e Back-end

A principal diferença entre as duas camadas é que a Front-end se concentra na interação com o usuário e na apresentação de conteúdo, enquanto a Back-end lida com a lógica do negócio, armazenamento de dados e processamento de informações. Em resumo, a camada Front-end é responsável pela aparência e interação do usuário, enquanto a camada Back-end é responsável pelo funcionamento interno da aplicação.

## Descrição do Protocolo HTTP

O Protocolo HTTP (Hypertext Transfer Protocol) é o protocolo de comunicação usado na World Wide Web (WWW). Ele é responsável por permitir a comunicação entre clientes (como navegadores) e servidores da Web. O HTTP é um protocolo de solicitação-resposta, onde o cliente envia uma solicitação ao servidor e espera uma resposta para essa solicitação. Ele utiliza o método de solicitação e os códigos de status para indicar a ação a ser executada pelo servidor.

## Descrição do Protocolo HTTPS

O Protocolo HTTPS (Hypertext Transfer Protocol Secure) é uma versão segura do Protocolo HTTP, onde a comunicação é criptografada por meio de SSL ou TLS. Isso garante que os dados transmitidos entre o cliente e o servidor estejam seguros e protegidos contra ataques de terceiros. É amplamente utilizado em transações bancárias on-line, compras on-line e outras transações seguras na Web.

## Diferença entre os Protocolos HTTP e HTTPS

A principal diferença entre os dois protocolos é que o HTTPS é mais seguro do que o HTTP, pois todos os dados transmitidos entre o cliente e o servidor são criptografados, o que significa que somente o remetente e o destinatário podem ver e acessar esses dados. O HTTP não fornece criptografia, o que significa que os dados são transmitidos em texto simples, o que pode ser facilmente interceptado e lido por terceiros.

## O que é uma HTTP Request (Requisição HTTP)?

Uma HTTP Request é uma solicitação feita por um cliente (como um navegador) a um servidor da Web para obter um recurso específico. A solicitação é enviada usando um método de solicitação, como GET, POST, PUT ou DELETE, que indica a ação a ser executada pelo servidor.

## O que é uma HTTP Response (Resposta HTTP)?

Uma HTTP Response (Resposta HTTP) é a resposta enviada pelo servidor da Web em resposta a uma solicitação feita pelo cliente. Ela contém informações sobre o status da solicitação, como o código de status, que indica se a solicitação foi bem-sucedida ou não, e também pode incluir o recurso solicitado, como uma página HTML, imagem ou arquivo de áudio. Além disso, a resposta pode conter informações adicionais, como cabeçalhos de resposta, que fornecem informações adicionais sobre o recurso solicitado ou sobre a resposta em si. Existem vários códigos de status que podem ser retornados em uma resposta HTTP, cada um com um significado específico.

## Tipos de Requisições HTTP (Verbos) mais utilizados no Desenvolvimento WEB

Os principais tipos de requisições HTTP (verbos) mais utilizados no desenvolvimento web são:

- GET: Solicitação para obter um recurso específico. É usado para solicitar dados do servidor.
- POST: Solicitação para enviar dados do cliente para o servidor. É usado para enviar informações e atualizar um recurso existente ou criar um novo.
- PUT: Solicitação para atualizar um recurso existente com dados do cliente.
- DELETE: Solicitação para excluir um recurso específico.

## Tipos de Respostas HTTP (Status code) mais utilizados no Desenvolvimento WEB

Os principais tipos de respostas HTTP (códigos de status) mais utilizados no desenvolvimento web são:

- 200 OK: indica que a solicitação foi bem-sucedida e que o servidor retornou os dados solicitados.
- 201 Created: indica que a solicitação foi bem-sucedida e que o servidor criou um novo recurso.
- 400 Bad Request: indica que a solicitação foi mal-formada ou incompreensível pelo servidor.
- 404 Not Found: indica que o servidor não encontrou o recurso solicitado.
- 500 Internal Server Error: indica que ocorreu um erro interno no servidor.

Compreender a camada Front-end e Back-end, bem como os protocolos HTTP e HTTPS, e os verbos e códigos de status HTTP é fundamental para o desenvolvimento de aplicativos web seguros e funcionais.



<p align="center">
  <img src="https://meneguite.com/2017/10/01/golang-desbravando-uma-linguagem-de-programacao-parte-1/001.gif" alt="Front, Back e FullStack">
</p>
