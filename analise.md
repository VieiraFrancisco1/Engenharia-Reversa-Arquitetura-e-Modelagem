# Engenharia-Reversa-Arquitetura-e-Modelagem

1. Qual é o objetivo do sistema?

O sistema da Tropykaly Pizzas e Lanches tem como objetivo permitir que clientes realizem pedidos online de alimentos, como pizzas, hambúrgueres, bebidas e outros produtos, facilitando o processo de compra e entrega.

2. Quais funcionalidades ele oferece?

O sistema oferece as seguintes funcionalidades:
Visualização do cardápio
Navegação por categorias (pizzas, sanduíches, bebidas, etc.)
Personalização de produtos (ex: tamanho da pizza, borda, sabores)
Adição de itens ao carrinho
Visualização do carrinho de compras
Sistema de login (cliente/admin)
Exibição de promoções e combos

3. Como o usuário interage com o sistema?

O usuário interage de forma simples e direta:
Acessa o site
Navega pelas categorias do cardápio
Seleciona um produto
Personaliza o item (ex: tamanho, sabores, adicionais)
Adiciona ao carrinho
Finaliza o pedido
A interface é baseada em cliques, com menus visuais e listas de opções

4. Como os produtos estão organizados?

Os produtos estão organizados em categorias, como:
Pizzas (divididas por tamanho: P, M, G, GG)
Esfirras (doces e salgadas)
Hambúrgueres artesanais
Sanduíches
Bebidas (sucos, refrigerantes, vitaminas)
Porções
Além disso, há separação por:
Combos
Promoções

Parte 2 – Análise de Arquitetura
Tipo de arquitetura

O sistema aparenta utilizar uma arquitetura Web Cliente-Servidor.

Possível divisão em camadas

É possível identificar uma estrutura em camadas:

Camada de Apresentação (Frontend)
Interface do usuário (cardápio, botões, formulários)
Camada de Lógica (Backend)
Processamento de pedidos, regras de negócio (ex: escolha de sabores)
Camada de Dados
Armazenamento de produtos, pedidos, usuários
Separação de responsabilidades

Existe uma separação básica de responsabilidades:

Interface cuida da interação com o usuário
Sistema processa as escolhas
Dados são armazenados separadamente

Porém, essa separação não é totalmente visível, pois não temos acesso ao código
