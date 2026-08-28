1. Antes de desenhar o Modelo Entidade-Relacionamento de um sistema de vendas, a equipe entrevista os funcionários da loja para levantar quais informações precisam ser armazenadas (produtos, clientes, pedidos) e quais regras de negócio existem (ex.: um pedido não pode ser fechado sem pelo menos um produto). Qual etapa do projeto de banco de dados corresponde a esse levantamento?

(x) Análise de requisitos, etapa de levantamento de informações e regras junto aos usuários
b) Modelo físico
c) Linguagem SQL, pois é a ferramenta usada para entrevistar os usuários e registrar as regras de negócio do sistema
d) DML, pois manipula os dados armazenados
e) Nenhuma etapa de levantamento é necessária: basta desenhar diretamente o Modelo Entidade-Relacionamento a partir da experiência da equipe
Justificativa:   É nessa etapa que a equipe conversa com os usuários para saber quais dados precisam ser armazenados e quais regras o sistema deve seguir.

2. No Modelo Entidade-Relacionamento de uma loja, a entidade “Pedido” se relaciona com a entidade “Produto”: um pedido pode conter vários produtos, e um mesmo produto pode aparecer em vários pedidos diferentes. Que tipo de relacionamento é esse?

a) Relacionamento um-para-um (1:1), pois cada pedido está associado a exatamente um único produto, e vice-versa
b) Relacionamento um-para-muitos (1:N), pois um produto só pode estar em um único pedido
c) Não existe relacionamento entre essas entidades
(x) Relacionamento muitos-para-muitos (N:N)
e) Relacionamento muitos-para-um, pois um produto sempre pertence a um único pedido dentro do sistema de vendas
Justificativa:É muitos-para-muitos porque um pedido pode ter vários produtos e um produto pode estar em vários pedidos.
