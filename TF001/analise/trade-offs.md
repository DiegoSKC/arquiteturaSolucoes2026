# Trade-offs Analisados

## Performance vs Custo

- Decisão: Investir em servidores globais de distribuição de conteúdo (CDNs).

- Justificativa: Garantir downloads rápidos para milhões de usuários.

- Impacto: Custos elevados de infraestrutura, mas experiência fluida.

## Segurança vs Usabilidade

- Decisão: Autenticação em dois fatores opcional.

- Justificativa: Balancear proteção contra roubo de contas com conveniência.

- Impacto: Usuários menos cuidadosos ficam vulneráveis.

## Escalabilidade vs Complexidade

- Decisão: Arquitetura distribuída com microserviços.

- Justificativa: Suportar milhões de usuários simultâneos.

- Impacto: Maior complexidade de manutenção e integração.

## Requisitos Não Funcionais

- Performance: Downloads rápidos via CDNs, mas gargalos podem ocorrer em lançamentos grandes.

- Escalabilidade: Suporta milhões de usuários simultâneos, arquitetura distribuída.

- Disponibilidade: Alta, mas quedas ocasionais em eventos massivos (ex: promoções).

- Segurança: Proteção com criptografia, autenticação em dois fatores, mas ainda há casos de phishing.

- Usabilidade: Interface intuitiva, mas considerada pesada por alguns usuários.