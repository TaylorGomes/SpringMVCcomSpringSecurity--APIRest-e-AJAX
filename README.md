# SpringMVCcomSpringSecurity, APIRest-e-AJAX

E nesse pacote API estamos trabalhando com Rest, então a consulta que ele faz ao banco de dados, por exemplo, quando está pegando alguma informação, ele já serializa isso para JSON e retorna para a interface gráfica, para uma aplicação de front-end ou uma aplicação mobile, ou outra aplicação back-end que quiser informações de pedidos no estado aguardando. É só chamar esse endpoint e ela vai conseguir essas informações.(getPedidosAguardandoOferta)

No banco de dados trabalhamos com JPA e depois instalamos o Spring Data JPA, que simplifica bastante. Nós trabalhamos com interfaces e automaticamente ele implementa isso para nós
E quando temos uma consulta um pouco mais complexa, um pouco diferente, podemos escrevê-la usando essa anotação @Query, associando essa consulta à essa declaração de método aqui na interface.

Então é isso! Nós configuramos tudo isso no front-end, a Thymeleaf e o Vue.js. No Vue.js trabalhamos com o Axios para fazermos essas requisições Ajax para os nossos endpoints Rest aqui, para buscar os dados.

 
