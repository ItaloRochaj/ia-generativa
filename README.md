# IA Generativa na Microsoft Azure: Guia Prático

## Introdução

Este guia apresenta um passo a passo para explorar os recursos de **IA Generativa** com o **Microsoft Copilot** e **OpenAI** na Azure, incluindo filtros de conteúdo e geração de imagens.  

> ⚠ **Nota**: Para aprofundamento, consulte sempre a **documentação oficial**:  
> - [Microsoft Copilot](https://learn.microsoft.com/)  
> - [Azure OpenAI](https://learn.microsoft.com/en-us/azure/cognitive-services/openai/)  
> - [Content Filters in Azure OpenAI](https://learn.microsoft.com/en-us/azure/cognitive-services/openai/filters/)  

---

## Criação de Imagens com Microsoft Copilot

Explore o potencial da IA generativa para transformar descrições em imagens, unindo criatividade e tecnologia.  

![Imagem gerada](https://github.com/ItaloRochaj/ia-generativa-decolatech/blob/main/inputs/assets/2025-03-12_23-17.png)  

### Exemplos de Imagens Criadas:
![Imagem 1](https://github.com/ItaloRochaj/ia-generativa-decolatech/blob/main/inputs/assets/imagem2.png)  
![Imagem 2](https://github.com/ItaloRochaj/ia-generativa-decolatech/blob/main/inputs/assets/imagem3.png)  

---

## Extração de Texto a Partir de Imagens

A seguir, mostramos como configurar e testar a extração de texto de imagens usando **Azure AI Services**.

### 1. Criando um Recurso de Serviços de IA
1. Acesse o [Portal do Azure](https://portal.azure.com) e faça login.  
2. Clique em **+ Criar um recurso** e busque **Serviços de IA do Azure**.  
3. Escolha **Criar um Plano de Serviços de IA do Azure**.  
4. Preencha os seguintes campos:  
   - **Assinatura**: Sua assinatura ativa.  
   - **Grupo de Recursos**: Escolha ou crie um grupo.  
   - **Região**: Selecione *East US*.  
   - **Nome**: Defina um nome exclusivo.  
   - **Nível de Preços**: Escolha *Standard S0*.  
5. Marque a confirmação dos termos e clique em **Criar**.  

### 2. Acessando o Vision Studio  
Após a implantação, entre no **Vision Studio**, clique em **View all resources** e selecione o recurso criado.  

Selecionamos o recurso e clicamos em **Select as default resource**.  
![Selecionar recurso](https://github.com/ItaloRochaj/ia-generativa-decolatech/blob/main/inputs/assets/imagen7.png)  
![Configuração](https://github.com/ItaloRochaj/ia-generativa-decolatech/blob/main/inputs/assets/imagen8.png)  

### 3. Análise de Documentos  

Acesse a ferramenta de **Optical Character Recognition (OCR)** para testar a extração de texto.  
![OCR](https://github.com/ItaloRochaj/ia-generativa-decolatech/blob/main/inputs/assets/imagen9.png)  

Clique em **Try it out**, selecione uma imagem de teste ou carregue uma do seu computador.  
![Testando OCR](https://github.com/ItaloRochaj/ia-generativa-decolatech/blob/main/inputs/assets/imagen10.png)  

### Exemplos de Entrada e Saída:  
**Input 1 & Output 1:**  
![Exemplo 1](https://github.com/ItaloRochaj/ia-generativa-decolatech/blob/main/inputs/assets/2025-03-12_22-53.png)  

**Input 2 & Output 2:**  
![Exemplo 2](https://github.com/ItaloRochaj/ia-generativa-decolatech/blob/main/inputs/assets/imagem11.png)  

---

## Conclusão

Com este guia, aprendemos a explorar as funcionalidades da **IA Generativa no Azure**, desde a criação de imagens até a extração de texto com **OCR**. Essas tecnologias impulsionam a criatividade e otimizam processos em diversas áreas. Para aprofundar seus conhecimentos, explore a documentação oficial e realize seus próprios experimentos! 🚀  
