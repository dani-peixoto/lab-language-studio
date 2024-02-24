# Análise de Sentimentos com Language Studio no Azure AI

Documentação criada para exemplificar a análise de sentimentos com o Language studio. Com base no resultado você consegue analisar o sentimento transmitido nas setenças e o nível de confiança.

> [!Important]
> Num navegador web, navegue até [**Language Studio**](https://language.cognitive.azure.com) para explorar todas as opções.

💡 Antes de iniciar no Language Studio é necessário criar um recurso no Azure.

- Loga no [**Portal Azure**](https://portal.azure.com)
- Clica em **"Criar um recurso"**
- Depois em **"IA + Machine Learning"**
- E para finalizar em **"Language Service"**

  ![Captura de tela de 2024-02-24 02-28-15](https://github.com/dani-peixoto/lab-language-studio/assets/3649843/b07002ce-5c11-4a82-904f-6c1577c58075)


## Configure seu recurso no Azure AI Language Studio
Em outra guia do navegador, abra o [**Language Studio**](https://language.cognitive.azure.com) e entre.

Quando solicitado em **Select an Azure resource**, faça as seguintes configurações:

- **Diretório do Azure:** diretório padrão, o diretório que você está usando
- **Assinatura do Azure:** selecione a assinatura que você está usando
- **Tipo de recurso:** idioma
- **Nome do recurso:** selecione o recurso de serviço de idioma que você acabou de criar

Em seguida, selecione **Concluído**.

## Analise sentimentos no Language Studio

1. Num navegador web, navegue até [**Language Studio**](https://language.cognitive.azure.com)

1. Na página inicial Bem-vindo ao **Language Studio**, selecione a guia **Classificar texto** e, em seguida, selecione o bloco **Analisar sentimento e extrair opiniões**.

1. Em Selecionar idioma do texto, selecione **Inglês**.

1. Em Selecione seu recurso do Azure, selecione seu recurso.

1. Digite seu próprio texto ou carregue um arquivo.

 ![Captura de tela de 2024-02-24 02-29-12](https://github.com/dani-peixoto/lab-language-studio/assets/3649843/fc3d1803-42e4-4008-affd-5fadbe971b61)

1. Marque a caixa para confirmar que a demonstração incorrerá em uso, e consequentemente em custos, e selecione **Executar**.

1. Revise a saída. Observe que o documento é analisado quanto ao sentimento, assim como cada frase. Selecione Sentence 1 para mostrar a análise de sentimento dessa frase.

  ![Captura de tela de 2024-02-24 02-29-41](https://github.com/dani-peixoto/lab-language-studio/assets/3649843/c0a73a39-6ddd-42e7-9188-15547464a7f8)

  

