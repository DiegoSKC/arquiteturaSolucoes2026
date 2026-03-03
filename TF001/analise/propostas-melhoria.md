# Propostas de Melhoria 1

- Problema: Dependência crítica do serviço de autenticação.

- Solução: Implementar redundância e fallback para login offline temporário.

- Benefício: Usuários poderiam acessar biblioteca mesmo em falhas de login.

- Trade-off: Maior risco de pirataria se não houver controle rígido.
 
# Proposta de melhoria 2

- Problema: Cliente Steam é pesado e monolítico.

- Solução: Modularizar o cliente em micro-aplicativos (ex: biblioteca, chat, marketplace).

- Benefício: Melhor performance e menor consumo de recursos.

- Trade-off: Maior complexidade de integração entre módulos.