# TechBairro

Sistema desktop de cadastro de clientes para a associação de moradores do
bairro. Permite cadastrar, consultar, alterar e excluir clientes, com
validação dos dados digitados.

**Versão atual:** 3.3.2 · Histórico de mudanças no [CHANGELOG](CHANGELOG.md)

## Funcionalidades

- Cadastrar clientes (nome, telefone, e-mail e endereço) com validação.
- Consultar a lista de clientes cadastrados.
- Alterar os dados de um cliente.
- Excluir um cliente, com pedido de confirmação.

## Requisitos para execução

| Item | Requisito |
|---|---|
| Sistema operacional | Windows 10 ou 11  |
| Python | 3.10 ou superior (versão testada: 3.12.0) |
| Tkinter | Já vem com o Python|
| Bibliotecas externas | Nenhuma  |
| Internet | Não é necessária para usar; só para baixar o projeto |

## Instalação

1. Baixe o projeto de uma das duas formas.

   Com Git:
   ```
   git clone https://github.com/eduardomarqq-dot/techbairro
   ```
   Sem Git: na página do repositório clique em **Code**, depois em
   **Download ZIP**, extraia o arquivo e abra um terminal dentro da pasta
   extraída.

2. Confira o Python e o Tkinter:
   ```
   python --version
   python -m tkinter
   ```
   Na segunda linha deve abrir uma janelinha de teste; feche-a.

3. O arquivo `requirements.txt` não lista pacotes (o projeto não tem
   dependências externas). Se quiser conferir, rode
   `pip install -r requirements.txt`: termina sem instalar nada.

4. Execute o programa:
   ```
   python techbairro.py
   ```
   Deve abrir a janela da TechBairro, com a versão v3.3.2 no canto, e o
   terminal deve mostrar a mensagem "c:\Users\eduardo63408746\OneDrive - SENAC DF\Documentos\TechBairro-3.3.1\techbairro.db" 

## Configuração do banco de dados

O banco é um arquivo SQLite, `techbairro.db`,criado automaticamente ao abrir o programa pela primeira vez, 
se não existir. Uma pasta nova começa com banco vazio e contador em 0. O caminho do
banco em uso aparece na mensagem "Banco em uso" do terminal. O arquivo não
vem no repositório porque guarda dados pessoais dos moradores (LGPD) e é
diferente em cada instalação; o `.gitignore` o deixa de fora. Para fazer
cópia de segurança, feche o programa e copie o `techbairro.db` para outra
pasta ou pen drive, de preferência com a data no nome.

## Como usar

O passo a passo está no [Manual de uso](docs/manual_de_uso.md).

## Estrutura do projeto

- `techbairro.py`: arquivo principal; abre a janela e define a `VERSAO`.
- `testar_validacao.py`: testes automáticos das regras de validação.
- `requirements.txt`: dependências (nenhuma externa).
- `CHANGELOG.md`: histórico de versões.
- `scripts/gerar_pacote.py`: gera o .zip de entrega em `dist/`.
- `scripts/importar_planilha_antiga.py`: importa clientes da planilha antiga.
- `docs/`: manual de uso, registro de testes e entrega final.
- `.gitignore`: deixa fora o banco, `__pycache__` e `dist`.


## Autor
Eduardo Marques, tecnico em desenvolvimentos de sistemas, SENAC