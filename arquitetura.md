Proposta de Arquitetura
Visão Geral

Para melhorar a organização, manutenção e escalabilidade do sistema de pedidos online da pizzaria, propõe-se uma arquitetura baseada no padrão MVC (Model-View-Controller), com separação clara de responsabilidades.

Essa abordagem facilita o desenvolvimento e a evolução do sistema, tornando-o mais próximo de aplicações profissionais.

Organização em Camadas

O sistema pode ser dividido em quatro camadas:

Camada de Apresentação (View)
Responsável pela interface com o usuário.
Funções: exibir cardápio, produtos, carrinho, navegação e telas de login e pedido.

Camada de Controle (Controller)
Responsável por receber e processar as ações do usuário.
Funções: tratar requisições, validar dados e acionar a lógica do sistema.

Camada de Modelo (Model)
Responsável pelos dados e regras de negócio.
Entidades: Usuário, Produto, Categoria, Pedido, Item do Pedido e Carrinho.

Camada de Dados
Responsável pelo armazenamento das informações.
Armazena produtos, pedidos, usuários e categorias.

Separação de Responsabilidades

Cada camada possui uma função específica:
a interface trata a interação com o usuário, o controller gerencia as ações, o model cuida da lógica e o banco armazena os dados. Isso reduz o acoplamento e melhora a organização.

Componentes Principais

O sistema é composto por:

Frontend (interface)
Backend (lógica)
Banco de dados (armazenamento)
Benefícios
Melhor organização do código
Facilidade de manutenção
Maior escalabilidade
Reutilização de componentes
Facilidade para adicionar funcionalidades
