
# Registro de testes da TechBairro
Versão testada: 3.3.1 · Data: 26/10/26 · Responsável: Eduardo Marques
Sistema operacional e versão do Python: 3.12.0
| ID | Requisito | Passos e dados | Esperado | Obtido | Status |
|---|---|---|---|---|---|
| CT01 | RF01 | Cadastrar um cliente com todos os campos certos | ele deve cadastrar os clientes normalmente |conforme o esperado | passou |
| CT02 | RF01 | Salvar com Nome e Endereço vazios | ele deve solicitar o preenchimento dos campos nao preenchidos| conforme o esperado  | passou |
| CT03 | RF02 | Telefone 61 9999 0000 (com espaços) | ele deve solicitar que haja somente numeros | conforme o esperado  | passou  |
| CT04 | RF03 | E-mail ana@email (sem ponto) | ele deve solicitar que voce escreva com o formato (usuario@emai.com) | conforme o esperado  |passou |
| CT05 | RF05 | Editar um cliente, trocar o telefone e salvar | ele deve salvar a alteraçao normalmente | conforme o esperado | passou  |
| CT06 | RF06 | Excluir um cliente: responder Não, depois Sim | na primeira parte ele deve nao excluir normalmente, se voce responder sim ele deve excluir normalmente | conforme o esperado  | passou  |

## Testes automáticos
Saída do `python testar_validacao.py`: 
OK teste_cliente_valido
OK teste_endereco_vazio
OK teste_telefone_com_letras
OK teste_email_sem_ponto
OK teste_nome_e_telefone_vazios
OK teste_email_sem_usuario
Todos os testes passaram.

## Defeitos encontrados
nenhum
