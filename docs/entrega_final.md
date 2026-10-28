# Entrega final da TechBairro
Aluno(a): Eduardo Marques Braga de Faria · Versão entregue: 3.3.2
Por que esse número de versão: A versão 3.3.2 foi escolhida porque as alterações previstas para esta entrega
são principalmente de documentação, testes e organização do pacote.
Como nao ouve grandes mudanças em relaçao ao 3.3.1, entao somente um último número é somado na versão e incrementado em relação à 3.3.1.

| # | Item | Evidência |
|---|---|---|
| 1 | A aplicação funciona: os 6 casos de teste passaram | docs/registro_de_testes.md |
| 2 | A versão aparece na janela e é a mesma do CHANGELOG e do README | sim |
| 3 | O pacote foi testado numa pasta limpa | sim |
| 4 | Tag e release publicadas, com o .zip anexado | (https://github.com/eduardomarqq-dot/techbairro/releases) |
| 5 | O repositório não tem banco, __pycache__ nem dist | nao tem |
| 6 | O histórico tem commits com mensagens claras |  https://github.com/eduardomarqq-dot/techbairro/commits/main/ |
| 7 | README, manual de uso e requirements.txt estão no repositório | nao |
| 8 | A Issue "Teste do README" (Aula 26) está fechada |sim |
| 9 | O vídeo está publicado e o link abre sem pedir login | ____ (link do vídeo) |

## Roteiro do vídeo
1. Apresentação 

Olá! Meu nome é Eduardo e vou apresentar a TechBairro, 
um sistema desenvolvido em Python para ajudar uma associação de moradores a gerenciar seus clientes,
permitindo cadastrar, consultar, editar e excluir informações.

2. Demonstração do sistema 

Cadastro: vou cadastrar um cliente utilizando dados fictícios.

Consulta: vou mostrar como visualizar os clientes cadastrados.

Edição: vou alterar o telefone de um cliente e salvar.

Validação: vou tentar salvar um cadastro com um campo obrigatório vazio para demonstrar a validação.

Exclusão: vou mostrar a confirmação de exclusão, selecionando primeiro “Não” e depois “Sim”.

3. Como foi desenvolvido 

A TechBairro foi desenvolvida em Python e utiliza SQLite para armazenar os dados. O projeto possui validações, testes e documentação. O código está disponível no GitHub, junto aos arquivos necessários para orientar o uso do sistema.

4. Aprendizado e conclusão 

Durante o desenvolvimento, aprendi a importância dos testes, da validação de dados e da documentação. Como melhoria futura, gostaria de adicionar novos recursos de pesquisa e relatórios para facilitar o gerenciamento dos clientes.

## Perguntas
Por que o arquivo techbairro.db não está no GitHub?
O arquivo techbairro.db não deve ser versionado porque contém os dados armazenados pela aplicação. Cada usuário deve poder criar seu próprio banco de dados local, sem compartilhar dados de clientes ou sobrescrever informações de outras instalações. O arquivo também pode mudar durante o uso, por isso deve ser excluído do controle de versão pelo .gitignore.

Qual caso de teste identificou um defeito real? Qual era o defeito?
A resposta será preenchida após a execução dos testes. Vou identificar o caso que apresentou um comportamento incorreto, explicar o defeito encontrado, como foi corrigido e registrar o commit correspondente. Se nenhum defeito for encontrado nesta entrega, informarei isso e, se aplicável, relatarei um defeito identificado em testes anteriores.

Se o voluntário tiver apenas o link do repositório, como poderá instalar e executar a TechBairro?
O voluntário poderá acessar o repositório no GitHub e consultar o README e o manual de uso. Depois, deverá baixar o projeto ou clonar o repositório, instalar a versão compatível do Python e as dependências listadas em requirements.txt, se necessárias, e seguir as instruções de configuração e execução. Como alternativa, poderá baixar o pacote ZIP da release, extrair os arquivos e executar a aplicação conforme o manual.

## Autoavaliação
Considero importante demonstrar as principais funcionalidades da TechBairro de forma clara e objetiva, mostrando o funcionamento real da aplicação.
Eu procuraria melhorar a gravação com uma narração natural, tela legível e tempo bem distribuído.
Aprendi que testes, validação, documentação e controle de versão são fundamentais para entregar um sistema organizado e facilitar sua utilização por outras pessoas.
