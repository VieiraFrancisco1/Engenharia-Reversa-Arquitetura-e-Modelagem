Parte 7 – Problemas Identificados

Durante a análise do sistema, foram identificados alguns possíveis problemas:

Limitações de arquitetura
A arquitetura não é totalmente visível, o que pode indicar falta de uma separação clara entre frontend e backend.
Alto acoplamento
As funcionalidades (produto, carrinho e pedido) estão fortemente conectadas, o que pode dificultar alterações no sistema.
Dificuldade de manutenção
Sem uma estrutura bem definida, a manutenção pode se tornar mais complexa com o crescimento do sistema.
Escalabilidade limitada
O sistema pode ter dificuldades para crescer, como suportar muitos usuários simultaneamente ou novas funcionalidades.
Parte 8 – Proposta de Arquitetura

Para melhorar o sistema, propõe-se a adoção de uma arquitetura baseada no padrão MVC, com separação em camadas:

View (Apresentação): interface do usuário (telas e navegação)
Controller (Controle): processamento das ações do usuário
Model (Dados e regras de negócio): manipulação dos dados
Banco de Dados: armazenamento das informações

Essa organização melhora a clareza do sistema, reduz o acoplamento e facilita a manutenção.

Parte 9 – Aplicação de Padrões
Factory

O padrão Factory pode ser aplicado na criação de diferentes tipos de produtos, como pizzas, bebidas e combos.
Isso permite criar objetos sem depender de várias condições no código, facilitando a expansão do sistema.

Singleton

O padrão Singleton pode ser aplicado para garantir uma única instância de elementos importantes, como:

Carrinho de compras
Sessão do usuário

Isso evita inconsistências e melhora o controle do sistema.
