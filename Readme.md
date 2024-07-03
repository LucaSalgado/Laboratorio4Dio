# Labaratório 4 Dio

## Configuração
- Começamos criando alguns recursos
- O primeiro é o serviço de busca por IA do Azure "Azure AI Search"
- Depois criamos o recurso de "Azure AI Services"
- E por fim criamos um "Azure Storage"

## Populando o storage
-  Após a criação do storage é preciso configura-lo
-  Assim podemos criar um container
-  E em seguida faremos upload de arquivos contendo reviews para teste do laboratório

## Criar os dados cognitivos
- Em "Azure AI Services" na seção "conectar aos seus dados" selecionaremos a fonte dos dados como sendo "Azure Blob Storage"
- Em seguida nós preencheremos o formulário com as informações referentes ao container que populamos
- Depois de preenchido o formulário nós vamos associar o serviço de IA do Azure que criamos anteriormente
- E configurar o queremos que o serviço de busca faça
- Então iremos configurar os indices de busca

## Utilizando o conjunto de dados criado
- Voltemos para "Azure AI Search"
- Selecione "Explorador de pesquisa"
- Certifique-se de que o conjunto de dados criado está selecionado
- Agora podemos fazer pesquisas em nosso conjunto de dados
