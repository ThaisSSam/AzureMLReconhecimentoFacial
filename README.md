# Reconhecimento Facial e transformação de imagens em Dados no Azure ML
## Passo a passo
> [!NOTE]
> É necessário ter uma conta do Azure
### 1. Criar um recurso com o Azure Machine Learning 
  - Criar **Serviços Cognitivos**
  - Preencher os campos de **subscrição**, criando um **Grupo de Recursos** se não tiver um
  - Preencher a **Região**, a East US tem recursos mais baratos e é mais próxima do Brasil
  - Preencher o campo **Nome**
  - Preencher **Tipo de preço** Standard S0
  - Confirmar a checkbox de leitura de termos
  - Examinar+criar
  - Criar
### 2. Azure AI Vision Studio
  - Entrar no site [Azure Vision Studio](https://portal.vision.cognitive.azure.com/gallery/featured)
  - Click em **View all resources**
  - Seleciona o Recurso
  - Click em **Select as default resource**
  - E volte para a Tela inicial
### 3. Reconhecimento de Face
  - Vá para a aba **Face**
  - Click no card **Detect faces in an image**
  - Selecione o checkbox
  - Pode explorar [documenção](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/quickstarts-sdk/identity-client-library?tabs=windows%2Cvisual-studio&pivots=programming-language-javascript) e a [lista de referencias de API](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/identity-api-reference)
  - Teste com as imagens padrões ou faça upload de uma do seu gosto
  - ***Exemplo de imagem***
    
     ![Img1](/inputs/Img1.jpg)
  - ***Resultado***
    
      ![ImgRecFacial](/outputs/ImgRecFacial.png)

### 4. Reconhecimento de Caracteres
  - Vá para a aba **Optical character recognition**
  - Click no card **Extract text from images**
  - Selecione o checkbox
  - Pode explorar [documentação](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/concept-ocr), a [lista de referencias de API](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/quickstarts-sdk/image-analysis-client-library-40?tabs=visual-studio%2Cwindows&pivots=programming-language-javascript) e a [lista de idiomas](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/language-support)
  - Teste com as imagens padrões ou faça upload de uma do seu gosto
  - ***Exemplo de imagem***
    
     ![Img2](/inputs/Img2.png)
  - ***Resultado***
    
     ![ImgRecTxt](/outputs/ImgRecTxt.png)
### 5. Legenda em imagens
  - Vá para a aba **Image analysis**
  - Click no card **Add captions to images**
  - Selecione o checkbox
  - Pode explorar [documentação](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/concept-describe-images-40?tabs=image) e a [lista de referencias de API](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/quickstarts-sdk/image-analysis-client-library-40?tabs=visual-studio%2Clinux&pivots=programming-language-javascript)
  - Teste com as imagens padrões ou faça upload de uma do seu gosto
  - ***Exemplo de imagem***
    
    ![Img3](/inputs/Img3.jpg)
  - ***Resultado***

    ![ImgLegImg](/outputs/ImgLegImg.png)

  
  

