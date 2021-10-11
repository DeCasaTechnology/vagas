# Desafio Back-end em C#

Obrigado pelo seu interesse em trabalhar no DeCasa!
Abaixo você encontrará todos as informações necessárias para iniciar o seu teste.

### Descrição Desafio baseado no Pic Pay

- Sistema Bancário

Há 2 tipos de usuários, os comuns e lojistas, ambos têm carteira com dinheiro e realizam transferências entre eles. 

- Para ambos tipos de usuário, precisamos do Nome Completo, CPF/CNPJ, e-mail e Senha. CPF/CNPJ e e-mails devem ser únicos no sistema. Sendo assim, seu sistema deve permitir apenas um cadastro com o mesmo CPF ou endereço de e-mail.

- Usuários podem enviar dinheiro (efetuar transferência) para lojistas e também entre usuários. 

- Lojistas **só recebem** transferências, não enviam dinheiro para ninguém.

- Validar se o usuário tem saldo antes da transferência.

- A operação de transferência deve ser uma transação (ou seja, revertida em qualquer caso de inconsistência) e o dinheiro deve voltar para a carteira do usuário que envia. 

- No recebimento de pagamento, o usuário ou lojista precisa receber notificação (envio de email) enviada por um serviço de terceiro e eventualmente este serviço pode estar indisponível/instável. Por usar qualquer serviõ de envio de email, como por exemplo https://www.mocklab.io/docs/mock-rest-api/

- Este serviço deve ser RESTFul.


### Avaliação

- Apresentar sua API funcionando
- Documentação
- Se for para vaga sênior, foque bastante no **desenho de arquitetura**
- Código limpo e organizado (nomenclatura, etc)
- Conhecimento de padrões (PSRs, design patterns, SOLID)
- Ser consistente e saber argumentar suas escolhas
- Apresentar soluções que domina
- Modelagem de Dados
- Manutenibilidade do Código
- Tratamento de erros
- Cuidado com itens de segurança
- Arquitetura (estruturar o pensamento antes de escrever)
- Carinho em desacoplar componentes (outras camadas, service, repository)

De acordo com os critérios acima, iremos avaliar seu teste para avançarmos para a entrevista técnica.
Caso não tenha atingido aceitavelmente o que estamos propondo acima, não iremos prosseguir com o processo.

### O que será um Diferencial
- Uso de Docker
- Testes de [integração](https://www.atlassian.com/continuous-delivery/software-testing/types-of-software-testing)
- Testes [unitários](https://www.atlassian.com/continuous-delivery/software-testing/types-of-software-testing)
- Uso de Design Patterns
- Documentação
- Proposta de melhoria na arquitetura
