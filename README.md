# Projeto de Automação RPA: Processamento de Faturas e Envio de E-mails

## Descrição do Projeto

Este projeto foi desenvolvido para automatizar o processo de leitura de faturas, extração de códigos de clientes e geração de valores de desconto, culminando no envio de e-mails com as faturas processadas. O fluxo de trabalho foi dividido em duas partes principais:

1. **Leitura de Faturas e Cálculo de Descontos**
2. **Criação de Rascunhos de E-mail e Anexos**

## Estrutura do Projeto

### Parte 1: Leitura de Faturas e Cálculo de Descontos

- **Objetivo**: Ler valores de células em um arquivo Excel e calcular descontos a partir de um aplicativo web.
- **Atividades Realizadas**:
  - Recuperação e filtragem de e-mails não lidos no Outlook.
  - Leitura de códigos de clientes a partir de uma planilha Excel.
  - Interação com o aplicativo web "ACME" para geração de descontos.
  - Atualização das planilhas Excel com os valores de desconto.
  - Implementação de pontos de interrupção para depuração.

### Parte 2: Criação de Rascunhos de E-mail e Anexos

- **Objetivo**: Enviar e-mails com as faturas processadas e incluir informações relevantes no corpo do e-mail.
- **Atividades Realizadas**:
  - Uso da atividade "If" para verificar condições de descontos.
  - Criação de rascunhos de e-mail utilizando o Outlook.
  - Anexação das faturas processadas aos e-mails.
  - Mensagens informativas sobre o processamento dos e-mails.

## Tecnologias Utilizadas

- **UiPath**: Plataforma de automação de processos robóticos.
- **Microsoft Excel**: Para manipulação e armazenamento de dados de faturas.
- **Microsoft Outlook**: Para o envio de e-mails.

## Instruções para Execução

1. **Pré-requisitos**:
   - Microsoft Office instalado (Excel e Outlook).
   - Acesso ao aplicativo web "ACME".
   - Permissões para ler e enviar e-mails através do Outlook.

2. **Configuração**:
   - Certifique-se de que o UiPath Studio está instalado e configurado corretamente.
   - Abra o projeto no UiPath Studio.

3. **Execução do Projeto**:
   - Execute o fluxo de trabalho a partir do UiPath Studio.
   - Acompanhe as mensagens de log para verificar o andamento do processamento.

## Aprendizados

Neste projeto, você aprendeu a:

- **Ler e escrever em planilhas Excel** utilizando o UiPath.
- **Interagir com aplicativos web** e extrair informações relevantes.
- **Gerenciar fluxos de controle** com a atividade "If".
- **Enviar e-mails com anexos** através do Outlook.

## Conclusão

Este projeto demonstra como a automação pode simplificar e agilizar processos administrativos, reduzindo a necessidade de intervenção manual e aumentando a eficiência. Sinta-se à vontade para adaptar e expandir o projeto conforme necessário!

---

**Obrigado por acompanhar! Boa automação!**
# Processamento-de-Faturas-e-Envio-de-E-mails
