# Changelog da TechBairro

## Em desenvolvimento
### Adicionado
- Código publicado no GitHub, com histórico de versões.

## v3.3.1 (Aula 21)

- Organização do sistema em módulos separados.
- Criação dos arquivos cliente.py e banco.py.
- Criação da classe ValidadorCliente no arquivo validacao.py.
- Criação de testes automatizados das regras de validação.
- Manutenção do comportamento da versão anterior.

## v3.3.0 (Aula 20)

### Adicionado
- Modo de edição visível, com o botão alterando para “Salvar edição”.
- Edição de cliente por duplo clique na lista da Consulta.
- Proteção para impedir edição ou exclusão de linhas informativas.
- Mensagens específicas ao cancelar uma edição.

### Corrigido
- Edição e exclusão passam a usar o cliente correspondente à linha selecionada na tela.
- O sistema confere se o banco realmente atualizou ou removeu o cliente.
- Aviso quando o cliente já não existe mais no banco.
- Lista da Consulta atualizada após tentativas de exclusão de registros inexistentes.

## v3.2.1 (Aula 18)

### Alterado
- O número da versão passou a ficar ______________________________.
### Adicionado
- Script scripts/gerar_pacote.py, que ______________________________.
- Arquivo COMO_EXECUTAR.txt, com ______________________________.

## v3.2 (Aula 16)
### Alterado
- O banco agora é aberto pelo caminho completo (os.path + __file__),
  sempre na pasta do projeto, não importa de onde o programa seja executado.
### Adicionado
- Mensagem "Banco em uso" no terminal, mostrando qual arquivo de banco está sendo usado.

## v3.1 (Aula 15)
### Corrigido
- O Endereço voltou a ser obrigatório no cadastro.
- A validação de e-mail passou a recusar e-mail sem nome antes do @ ou sem ponto depois do @.
- A Consulta voltou a listar os clientes em ordem alfabética.
- A edição de um cliente passou a ser gravada no banco (faltava o commit).
- A exclusão só acontece quando o usuário responde Sim na confirmação.

## v3.0 (Aula 14)
### Alterado
- O GerenciadorClientes deixou de guardar os clientes numa lista em memória
  e passou a gravar no banco SQLite techbairro.db.
- Editar e excluir passaram a usar o id do cliente no banco (id_em_edicao),
  e não mais a posição na lista (indice_em_edicao).
- O contador de clientes passou a vir do banco ao abrir a aplicação.
### Adicionado
- Tratamento de erros do banco com try/except sqlite3.Error.

## v2.0 (Aulas 11 e 12)
### Adicionado
- Classes Cliente e GerenciadorClientes.
- Tela de Consulta com a lista de clientes e os botões Editar e Excluir.
- Confirmação antes de excluir um cliente.

## Antes da v2.0 (Aulas 5 a 10)
- Janela de cadastro com Tkinter, eventos dos botões e validação dos campos.

