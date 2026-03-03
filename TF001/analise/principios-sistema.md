# Princípios Arquiteturais

## Separação de Responsabilidades

- Camada de apresentação: Interface gráfica (cliente Steam, app mobile, Site web).

- Camada de aplicação: Serviços de autenticação, marketplace, biblioteca.

- Camada de dados: Banco de dados de usuários, jogos, transações, inventário.

- Exemplo: O módulo de chat é independente do módulo de compras, mas ambos compartilham autenticação.

## Coesão

- Alta coesão: Biblioteca de jogos → funcionalidades relacionadas (instalar, atualizar, jogar).

- Baixa coesão: Marketplace e comunidade dentro do mesmo cliente → poderiam ser mais modularizados.

- Melhoria sugerida: Separar melhor os serviços sociais dos serviços de compra para reduzir complexidade.

## Acoplamento

- Alto acoplamento: Autenticação centralizada → todos os módulos dependem dela.

- Impacto: Se o serviço de login falha, toda a plataforma fica inacessível.

- Baixo acoplamento: Sistema de reviews funciona de forma independente da biblioteca.