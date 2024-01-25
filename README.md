# Aplicação de Cadastro de Clientes

Esta aplicação em Java oferece funcionalidades básicas para o cadastro, consulta, exclusão e alteração de informações de clientes.

## Funcionalidades

1. **Cadastro de Cliente**
   - Para cadastrar um novo cliente, selecione a opção `1` e forneça os dados solicitados.

2. **Consulta de Cliente**
   - Para consultar informações de um cliente existente, selecione a opção `2` e informe o CPF do cliente.

3. **Exclusão de Cliente**
   - Para excluir um cliente, selecione a opção `3` e siga as instruções.

4. **Alteração de Cliente**
   - Para alterar informações de um cliente, selecione a opção `4` e forneça os novos dados.

5. **Sair da Aplicação**
   - Para sair da aplicação, selecione a opção `5`.

## Como Usar

1. Abra a aplicação.
2. Escolha a opção desejada.
3. Siga as instruções apresentadas na interface gráfica.

## Exemplo de Uso

### Cadastro de Cliente

```java
// Exemplo de cadastro de cliente
String dados = JOptionPane.showInputDialog(null, "Digite os dados do cliente separados por vírgula: Nome, CPF, Tel, Endereço, Número, Cidade e Estado ", "Cadastro", JOptionPane.INFORMATION_MESSAGE);
cadastrar(dados);
