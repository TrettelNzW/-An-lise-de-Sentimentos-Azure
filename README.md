# Análise-de-Sentimentos-Azure
Projeto de Tutorial com Análise de Sentimentos Utilizando Azure


Passo a passo de experimento utilizando Language Studio para análise de texto com análise de sentimentos e opiniões.
Realizado como desafio de projeto no Bootcamp Microsoft Azure AI Fundamentals da Dio

Análise de Inputs Adicionais

Passo 1
Abrir a página do Portal https://portal.azure.com/#home e clicar para criar um recurso.

Passo 2
Com as funcionalidades adicionadas, basta clicar em "continue to create your resource"

Passo 3
Preencher as informações do recurso conforme imagem abaixo.
Escolha um resource group, um nome (que deve ser único), e o Pricing Tier deve ser Free F0.

Não esquecer de marcar a caixa com a observação de Responsabilidade AI.

E então clique em Review + create para a validação das informações

Passo 4
Depois da validação anterior, sua tela deve se parecer com esta.

Passo 5
Esta é a tela de finalização da criação do recurso.
Clique em "Go to resource group"

Esta é a tela que deve abrir

Passo 6
Abra a página do Language Studio (https://language.cognitive.azure.com/)[https://language.cognitive.azure.com/] com seu usuário logado.
Automaticamente é aberta uma modal com as informações a preencher conforme imagem abaixo. Informe a Azure Subscription, o Resource Type e o resource group que você criou, e clique em "Done".

Passo 7
Ainda no Language Studio, selecione a aba "Classify Text", e o card "Analyse Sentiment and mine opinions"

Passo 8
Selecione o idioma do texto a ser utilizado (English).
Copie o texto, fornecido pela documentação, na caixa de texto. Ver abaixo:
 Tired hotel with poor service
 The Royal Hotel, London, United Kingdom
 5/6/2018
 This is an old hotel (has been around since 1950's) and the room furnishings are average - becoming a bit old now and require changing. The internet didn't work and had to come to one of their office rooms to check in for my flight home. The website says it's close to the British Museum, but it's too far to walk.

Marque o box informativo
Clique em "Run"

Passo 9
Resultados
Ele traz o sentimento geral do texto

Traz também a análise de cada uma das frases
Ex.: Sentence 1 (basta clicar na aba da frase para abrir ou fechar)

Análise de inputs
Abaixo compartilho o resultado das frases que trouxe de exemplo em inputs
Sentence 1
Escolho o idioma, incluo a frase e inicio o teste:

Resultados:
Análise de Sentimento da Frase Completa
Análise Fragmento 1
Análise Fragmento 2
Análise Fragmento 3
Análise Fragmento 4
Sentence 2
Escolho o idioma, incluo a frase e inicio o teste:

Resultados:

Análise de Sentimento da Frase Completa
Análise Fragmento 1
Análise Fragmento 2
Análise Fragmento 3
Sentence 3
Escolho o idioma, incluo a frase e inicio o teste:

Resultados:
Análise de Sentimento da Frase Completa
Análise Fragmento 1
Análise Fragmento 2
Análise Fragmento 3
