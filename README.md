# Sobre o projeto
Esquema de banco de dados para um E-commerce. Desenvolvido no treinamento Database Experience da DIO.

### Escopo

- Venda de Produtos

### Produtos
- Os produtos são vendidos por uma única plataforma online. Contudo, estes podem ter vendedores distintos (terceiros)
- Cada produto possui um fornecedor
- Um ou mais produtos podem compor um pedido

### Cliente
- O cliente pode se cadastrar no site com seu CPF ou CNPJ
- O Endereço do cliente irá determinar o valor do frete
- Um cliente pode compar mais de um pedido. Este tem um periodo de carência para devolução do produto

### Pedido
- Os pedidos são criados por clientes e possuem informações de compra, endereço e status da entrega
- Um produto ou mais compoem o pedido
- O pedido pode ser cancelado

### Esquema
<img src="./assets/Banco_E-Commerce.png" >

