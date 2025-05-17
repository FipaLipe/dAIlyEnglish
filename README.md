# 📚✨ Projeto DailyEnglish: Seu Dia a Dia Virando Vocabulário de Inglês com IA para o Anki! ✨📚

![image](https://github.com/user-attachments/assets/b75be7ad-8acc-4f58-84c7-deda1b80278a)


Olá! 👋 Bem-vindo ao DailyEnglish! Este projeto nasceu da ideia de transformar a sua rotina em uma ferramenta poderosa para aprender inglês. Cansado de listas de vocabulário genéricas? Com o DailyEnglish, você usa a sua própria experiência diária para criar flashcards personalizados para o Anki!

## 🤔 Como Funciona?

É super simples!

1.  **Você descreve o seu dia:** Escreva um resumo em português das suas atividades, pensamentos ou o que você quiser compartilhar sobre o seu dia.
2.  **A Mágica da IA Acontece:** Nosso notebook Google Colab, utilizando a inteligência artificial do Gemini, analisa o seu texto.
3.  **Vocabulário Personalizado:** A IA identifica os termos, frases curtas e expressões mais relevantes e úteis do seu resumo.
4.  **Flashcards Prontos:** Gera automaticamente uma lista de flashcards em formato CSV (`frente;verso`), pronta para ser importada diretamente no Anki.

O resultado? Flashcards com vocabulário que VOCÊ realmente usou ou encontrou no seu dia, facilitando a memorização e tornando o aprendizado mais contextualizado e eficaz! 💪

## 🚀 Começando

Para usar o DailyEnglish, você precisará:

1.  **Uma conta Google:** Para acessar o Google Colab.
2.  **Uma API Key do Google AI:** Você pode obter uma gratuitamente. [Instruções aqui](https://ai.google.dev/tutorials/setup).
3.  **O aplicativo Anki:** Disponível para desktop e mobile. [Baixe aqui](https://apps.ankiweb.net/).

**Passo a passo:**

1.  Abra o notebook `dailyenglish.ipynb` no Google Colab.
2.  Insira a sua API Key do Google AI na seção correspondente (é seguro, ela fica privada na sua conta Colab!).
3.  Execute as células do notebook.
4.  Quando solicitado, insira o resumo do seu dia.
5.  O notebook irá gerar o arquivo `flashcards.csv`.
6.  Baixe o arquivo `flashcards.csv`.
7.  Importe o arquivo `flashcards.csv` no seu Anki. [Veja como importar no Anki](https://docs.ankiweb.net/importing.html).
8.  Comece a estudar o seu vocabulário personalizado! 🧠

## 🤖 A Tecnologia Por Trás

Este projeto é alimentado pelo modelo **Gemini** do Google AI, executado em um notebook Google Colab. A flexibilidade e o poder da IA generativa nos permitem analisar seu texto e extrair o vocabulário de forma inteligente.

---

Feito com ❤️ e inteligência artificial! ✨
