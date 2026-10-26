# Manual de uso da TechBairro

## A tela principal
Ao abrir o programa aparece uma janela com os campos **Nome**, **Telefone**,
**E-mail** e **Endereço**, os botões **Salvar**, **Editar** e **Excluir**,
a lista de clientes cadastrados e um contador com o total de clientes. Mensagens
de aviso aparecem em janelinhas. No canto da janela aparece o número da versão.

## Cadastrar um cliente
1. Clique no campo **Nome** e digite o nome do cliente.
2. Preencha **Telefone**, **E-mail** e **Endereço**.
3. Clique em **Salvar**.
4. Aparece uma mensagem de sucesso e o cliente entra na lista. O contador sobe 1.

## Consultar os clientes cadastrados
1. Olhe a lista na janela principal: todos os clientes aparecem nela.
2. Para achar alguém, use o campo de busca **[se existir]** ou procure o nome na lista.

## Alterar os dados de um cliente
1. Clique no cliente na lista.
2. Clique em **Editar**. Os dados vão para os campos.
3. Troque o que precisar (por exemplo, o telefone).
4. Clique em **Salvar**. A lista mostra os dados novos.

## Excluir um cliente
1. Clique no cliente na lista.
2. Clique em **Excluir**.
3. Aparece uma pergunta de confirmação. Clique em **Não** para manter o
   cliente ou em **Sim** para apagá-lo de vez.

## Regras de preenchimento
| Campo | Obrigatório? | Regra |
|---|---|---|
| Nome | Sim | Não pode ficar vazio |
| Telefone | Sim | Pode ter espaços, como 61 9999 0000; o sistema ajusta |
| E-mail | Sim | Precisa ter @ e um ponto depois dele, como ana@email.com |
| Endereço | Sim | Não pode ficar vazio |

## Mensagens do sistema
| Mensagem | O que significa | O que fazer |
|---|---|---|
| Cliente salvo com sucesso | O cadastro foi gravado | Nada, pode continuar |
| Nome e Endereço são obrigatórios | Algum desses campos está vazio | Preencha e salve de novo |
| Telefone inválido | O telefone não tem o formato esperado | Confira os números e digite de novo |
| E-mail inválido | Falta @ ou o ponto no e-mail | Corrija, por exemplo ana@email.com |
| Cliente atualizado | A alteração foi gravada | Nada, pode continuar |
| Deseja excluir este cliente? | O sistema pede confirmação | Clique em Sim para apagar ou Não para manter |
| Selecione um cliente | Você clicou em Editar/Excluir sem escolher ninguém | Clique em um cliente da lista primeiro |

## Dúvidas frequentes
**Apaguei um cliente sem querer. Dá para recuperar?**
Não. Depois do Sim, o cliente é removido. Por isso o sistema pergunta antes.

**Por que o sistema não aceitou o e-mail?**
Ele precisa ter @ e um ponto depois dele (ana@email.com).

**Posso digitar o telefone com espaços?**
Pode. O sistema ajusta sozinho.

**Os dados ficam guardados quando fecho o programa?**
Sim, ficam no arquivo do banco, no próprio computador.