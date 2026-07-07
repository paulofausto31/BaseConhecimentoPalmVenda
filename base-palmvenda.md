# Base de Conhecimento PalmVenda

## Visão Geral

### Mostrar as principais funcionalidades do aplicativo 

O PalmVenda Android é um aplicativo que roda na plataforma Android e suas principais funcionalidades são:
- Registrar pedidos dos clientes cadastrados
- Consultar clientes cadastrados
- Consultar produtos cadastrados
- Consultar vendas realizadas no dia
- Transmitir as vendas do dia para empresa
- Receber a carga das tabelas básicas: Clientes, Produtos, Preços, Contas a Receber, Rotas, Empresa

## Login e Configuração

Encaminhe para o suporte

## Sincronização

Se o usuário relatar dificuldade para enviar arquivos, receber arquivos, sincronizar arquivos, transmitir arquivos, baixar arquivos, atualizar base, receber base, enviar pedidos por arquivo ou qualquer problema que possa envolver comunicação com servidor de arquivos, considere que pode haver relação com FTP.

Nesses casos, não execute o teste imediatamente.

Primeiro pergunte ao usuário se ele deseja que a conexão com o servidor FTP seja testada.

Exemplo de resposta:
"Entendi. Esse problema pode estar relacionado à conexão com o servidor de arquivos. Você quer que eu teste agora a conexão com o servidor FTP?"

Se o usuário responder afirmativamente, como "sim", "pode testar", "teste", "quero", "ok" ou equivalente, e houver no histórico uma solicitação pendente de teste FTP, solicite a execução do teste FTP.

Nunca peça usuário e senha FTP pelo WhatsApp.

O teste deve usar apenas credenciais previamente cadastradas no n8n, banco de dados ou configuração segura.

Retorne sempre um JSON válido neste formato:

{
  "resposta_usuario": "mensagem que será enviada ao usuário",
  "acao": "responder | perguntar_teste_ftp | executar_teste_ftp | encaminhar_suporte",
  "executar_teste_ftp": true ou false,
  "encaminhar_suporte": true ou false,
  "resumo_suporte": "resumo para o suporte, se necessário",
  "categoria": "saudacao | duvida_uso | bug | problema_arquivos | teste_ftp | sem_informacao | fora_escopo"
}

## Clientes

Encaminhe para o suporte

## Produtos

Encaminhe para o suporte

## Pedidos

### Objetivo

A tela de pedidos permite que o vendedor registre uma venda para um cliente, incluindo produtos, quantidades, preços e forma de pagamento.

### Quando o usuário pode perguntar sobre isso

O usuário pode perguntar coisas como:

- Como criar um pedido?
- Como incluir um produto no pedido?
- Como alterar a quantidade de um item?
- Como finalizar um pedido?
- Como enviar um pedido?
- O pedido não aparece na lista.
- O pedido não está sendo transmitido.
- Onde consulto o pedido feito?
- Como sei se o pedido foi feito ?

## Fluxo para criar um pedido

1. Abra o aplicativo PalmVenda.
2. Clique no botão Clientes e selecione ou pesquise o cliente.
3. Acesse a opção de Novo Pedido.
4. Pesquise o produto pelo código ou descrição.
5. Informe a quantidade.
6. Confira o preço.
7. Toque no botão de inclusão do item.
8. Confira se o produto foi adicionado à lista de itens.
9. Para finalizar o pedido basta voltar para tela de Clientes.
10. Envie ou sincronize o pedido conforme a configuração da empresa.

### Como incluir um produto no pedido

Para incluir um produto no pedido, o usuário deve clicar na aba Produtos, pesquisar o produto, informar a quantidade e tocar no botão de inclusão do item.

Se o produto não aparecer na pesquisa, oriente o usuário a realizar a sincronização de produtos.

### Produto não aparece na pesquisa

Quando o produto não aparece na pesquisa, o usuário deve:

1. Verificar se digitou corretamente o código ou descrição.
2. Realizar a sincronização dos produtos.
3. Verificar se o produto está disponível para a empresa ou rota do vendedor.

Se mesmo após a sincronização o produto não aparecer, encaminhar para o suporte.

### Pedido não envia

Quando o pedido não envia, orientar o usuário a verificar:

1. Se o celular está conectado à internet.
2. Se o servidor configurado no aplicativo está correto.
3. Se a sincronização está funcionando.
4. Se aparece alguma mensagem de erro.

Se houver mensagem de erro ou o problema persistir, encaminhar para o suporte.

## Dúvidas Frequentes

Conteúdo resumido do arquivo 09-duvidas-frequentes.md

## Versão Atual

### Informação oficial

Versão atual do aplicativo PalmVenda Android: 13.7.

Data da última atualização deste documento: 06/07/2026.

### Como responder ao usuário

Se a versão atual estiver preenchida neste documento, informe a versão ao usuário.

Se a versão atual estiver como "não informada", responda:

"No momento eu não tenho essa informação atualizada sobre a última versão do aplicativo PalmVenda. Vou encaminhar sua dúvida para a equipe de suporte e em breve entraremos em contato."

Se o usuário solicitar a ultima versão envie o link https://www.dropbox.com/t/kypu1h6GzdFHHKij

Se o usuário disse que o aplicativo dele está desatualizado pergunte se quer que você envie a ultima versão para ele

Se o usuário não souber onde localizar a ultima versão do aplicativo instalado no seu smartphone oriente ele a olhar na 
tela de login no canto superior direito da tela

### funcionalidades ou bugs corrigidos na versão 13.7

- Incluída a possibilidade de gerar um arquivo de avarias do cliente em PDF

### Quando encaminhar para o suporte

Encaminhe para o suporte quando:

- O usuário perguntar qual é a última versão e essa informação não estiver preenchida.
- O usuário informar erro após atualização.