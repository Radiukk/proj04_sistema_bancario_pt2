# proj04_sistema_bancario_pt2

<h1> Continuação Projeto Banco Virtual em Python </h1>
Este é um projeto prático de sistema bancário desenvolvido em Python. Ele simula as principais operações de um banco digital, incluindo transferência entre contas, e demonstra conceitos importantes como modularização com funções, controle de fluxo, manipulação de dados persistentes com arquivos JSON, e uso de listas e dicionários.

<h2> Funcionalidades Atuais </h2>
O sistema permite que o usuário realize diversas operações bancárias básicas, incluindo:

Consultar Saldo: Exibe o saldo atual da conta.

Depositar: Permite inserir um valor a ser somado ao saldo.

Sacar: Permite retirar um valor da conta, com verificação de saldo suficiente.

Transferir: Permite transferir um valor para outra conta (somente saída), solicitando número da conta de destino.

Exibir Extrato: Mostra o histórico de transações realizadas.

Sair: Encerra a aplicação salvando os dados no arquivo.

<h2> Recursos do Programa </h2>
Persistência de Dados com JSON: Saldo e extrato são armazenados em arquivo (banco_dados.json) e carregados automaticamente ao iniciar.

Validação de Entrada: O sistema garante que o usuário insira valores e opções válidas.

Laço Principal (while True): Mantém o menu em execução até que o usuário opte por sair.

Funções Modulares: Cada operação é separada em funções independentes para melhor organização e reuso.

Uso de Variáveis Globais: O saldo e o extrato são compartilhados entre as funções por meio de variáveis globais.

Feedback Informativo: Mensagens claras informam o usuário sobre o sucesso ou falha de cada operação.

<h2> Estrutura do Código </h2>
O código está organizado em um único arquivo Python (por exemplo, sistema_bancario.py) e dividido nas seguintes partes:

Carregamento de dados do arquivo JSON (ou inicialização com valores padrão)

Funções principais: consultar_saldo(), depositar(), sacar(), transferir(), exibir_extrato()

Menu interativo com validação

Loop principal para execução contínua

Gravação automática dos dados ao sair

<h1> Próximos Passos (Sugestões de Melhorias) </h1>
O projeto pode ser expandido com as seguintes funcionalidades:

Transferência com múltiplos usuários: Implementar autenticação e movimentação real entre contas.

Histórico filtrável: Exibir extrato por período ou tipo de transação.

Sistema de Login: Cadastro e acesso com usuário e senha.

Exportar extrato: Permitir salvar o extrato como .txt ou .csv.

<h1> Contribuição </h1>
Contribuições são bem-vindas! Caso tenha sugestões de melhorias, correções ou queira adicionar novas funcionalidades, fique à vontade para abrir uma issue ou enviar um pull request.

<h1> Autor: Bruno Radiuk </h1>
Este projeto foi desenvolvido como parte de um exercício de aprendizado de programação em Python.
