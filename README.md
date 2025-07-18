# Prática - Azure Cognitive Search

## Criar recurso Azure AI Search

![Captura de Tela 2025-06-29 às 23.21.07.png](https://github.com/jeanandrade1/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexa-o-e-consulta-de-Dados/blob/main/images/Captura%201.png)

Criar o recurso **Azure AI Search**

![Captura de Tela 2025-06-29 às 23.24.27.png](https://github.com/jeanandrade1/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexa-o-e-consulta-de-Dados/blob/main/images/Captura%202.png)

- Selecionar a assinatura
- Selecionar o recurso ou crie
- Selecionar a instância (recomendo EUA pelo custo)
- Criar um nome
- Selecionar o preço **Gratuito**
- Clicar em **Examinar + Criar**

![Captura de Tela 2025-06-29 às 23.23.49.png](https://github.com/jeanandrade1/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexa-o-e-consulta-de-Dados/blob/main/images/Captura%203.png)

## Criar recurso Azure AI Serice

Ir em A**zure AI Serice**

![Captura de Tela 2025-06-29 às 23.25.43.png](https://github.com/jeanandrade1/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexa-o-e-consulta-de-Dados/blob/main/images/Captura%204.png)

- Selecionar a assinatura
- Selecionar o recurso
- Selecionar a instância (recomendo EUA pelo custo)
- Criar um nome
- Selecionar o preço **Standard S0**
- Clicar em **Examinar + Criar**

## Criar uma Storage

Ir em criar recursos e clicar **criar** em **Conta de armanzenamento**

![Captura de Tela 2025-06-29 às 23.31.48.png](https://github.com/jeanandrade1/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexa-o-e-consulta-de-Dados/blob/main/images/Captura%205.png)

- Selecione a assinatura
- Selecione o grupo de recursos
- Coloque o nome da conta de armazenamento
- Selecione a região (Preferência pelo EUA devido ao custo)
- Selecione o desempenho **Standard**
- Selecione a redundância **LRS**

![Captura de Tela 2025-06-29 às 23.36.07.png](https://github.com/jeanandrade1/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexa-o-e-consulta-de-Dados/blob/main/images/Captura%206.png)

Entrar no recurso

![Captura de Tela 2025-06-29 às 23.39.02.png](https://github.com/jeanandrade1/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexa-o-e-consulta-de-Dados/blob/main/images/Captura%207.png)

Liberar o acesso anônimo em **configuração** e **salvar**

![Captura de Tela 2025-06-29 às 23.39.46.png](https://github.com/jeanandrade1/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexa-o-e-consulta-de-Dados/blob/main/images/Captura%208.png)

Ir em **Armazenamento de dados** e **Contêiners**, **Adicionar Contêiner** e coloque um nome

![Captura de Tela 2025-06-29 às 23.42.41.png](https://github.com/jeanandrade1/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexa-o-e-consulta-de-Dados/blob/main/images/Captura%209.png)

Fazer o uploado dos arquivos em **Carregar**

Pode se usar os exemplos do link https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html#upload-documents-to-azure-storage:~:text=zipped%20coffee%20reviews

## Ir no Azure AI Search

Clicar em Importar dados

![Captura de Tela 2025-06-29 às 23.50.40.png](https://github.com/jeanandrade1/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexa-o-e-consulta-de-Dados/blob/main/images/Captura%2011.png)

- Selecionar **Armazenamento de Blob do Azure**
- Coloque um nome
- Clicar em **Escolher uma conexão existente**

![Captura de Tela 2025-06-29 às 23.56.42.png](https://github.com/jeanandrade1/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexa-o-e-consulta-de-Dados/blob/main/images/Captura%2012.png)

Selecionar o **contêiner** criado anteriormente

![Captura de Tela 2025-06-29 às 23.56.06.png](https://github.com/jeanandrade1/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexa-o-e-consulta-de-Dados/blob/main/images/Captura%2013.png)

Clicar em **Adiconar** habilidade cognitivas

Selecionar o recurso de IA criado anteriormente 

![Captura de Tela 2025-06-30 às 00.02.50.png](https://github.com/jeanandrade1/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexa-o-e-consulta-de-Dados/blob/main/images/Captura%2014.png)

Ir em **explorar dados** para testar a pesquisa

![Captura de Tela 2025-06-30 às 00.04.37.png](https://github.com/jeanandrade1/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexa-o-e-consulta-de-Dados/blob/main/images/Captura%2015.png)
