## Transcrevendo Áudio com Python e Google Generative AI

Este repositório fornece um script Python que utiliza a biblioteca Google Generative AI para gerar texto a partir de um arquivo de áudio. O script utiliza o modelo Gemini 1.5 Pro-Latest, um modelo de linguagem poderoso que pode transcrever e gerar texto criativo e informativo.

**Funcionalidades:**

* **Transcrição de áudio:** O script pode transcrever o conteúdo de um arquivo de áudio em formato texto.
* **Configuração de segurança:** O script permite configurar filtros de segurança para evitar a geração de conteúdo inadequado ou ofensivo.

**Requisitos:**

* Ter uma conta no Google Cloud Platform (GCP).
* Ter a biblioteca Google Generative AI instalada em seu ambiente Python.
* Possuir um arquivo de áudio no formato .wav, .mp3, .opus ou .flac.

**Como usar:**

1. Clone este repositório no seu computador.
2. Instale a biblioteca Google Generative AI: `pip install google-generativeai`
3. Crie um projeto no GCP e ative a API Generative Language.
4. Obtenha a chave de API do seu projeto GCP.
5. Substitua `GOOGLE_API_KEY` no código `main.py` pela sua chave de API.
6. Execute o script `python main.py`.
7. Siga as instruções na tela para selecionar o arquivo de áudio e configurar as opções de geração de texto.

**Exemplos de Uso:**

* **Transcrever uma palestra:** Utilize o script para transcrever uma palestra em áudio e gerar um resumo do conteúdo.
* **Criar um artigo de notícias:** Forneça ao script a gravação de uma entrevista e peça que ele gere um artigo de notícias com base nas informações da entrevista.
* **Escrever uma história:** Utilize o script para gerar uma história criativa a partir de um diálogo de um filme ou livro.
* **Transcrever conversas:** Utilize o script para transcrever áudios recebidos de conversas feitas de plataformas de conversação.

**Imagens dos Códigos:**

**Código 1: Instalação da Biblioteca e Configuração da API**

![image](https://github.com/leolpc21/voz_para_todos/assets/43275999/0634c322-5a67-48a3-80cf-ad9c15f06160)

**Descrição:** Este código instala a biblioteca Google Generative AI e configura a API usando sua chave de API do GCP.

**Código 2: Upload de Arquivo**

![image](https://github.com/leolpc21/voz_para_todos/assets/43275999/82f774df-c3e8-460e-a449-bc612e94fdc0)

**Descrição:** Este código faz o upload de um arquivo de áudio.

**Código 3: Geração de Conteúdo**

![image](https://github.com/leolpc21/voz_para_todos/assets/43275999/4eac3103-e1eb-43a7-8526-0eb3e405a066)

**Descrição:** Utiliza o modelo Gemini 1.5 Pro-Latest para gerar texto a partir da transcrição do áudio.

**Código 4: Formatação e Exibição do Resultado**

![image](https://github.com/leolpc21/voz_para_todos/assets/43275999/b7a1fbd7-1602-4770-a743-48fa2b01c188)

**Descrição:** Este código formata o texto gerado pelo modelo em Markdown e o exibe na tela do usuário.

**Observações:**

* O código de simulação de upload de arquivo é apenas para fins de demonstração. Em um ambiente real, você precisará usar um método adequado para fornecer o conteúdo do arquivo de áudio ao script.
* As bibliotecas `IPython.display` e `Markdown` são específicas para o Google Colab e podem não funcionar em outros ambientes.
* O modelo Gemini 1.5 Pro-Latest é um modelo pago. Você precisará se cadastrar para um plano pago da Google Generative AI para usá-lo em produção.

**Esperamos que este repositório seja útil para você!**

**Contribuições:**

Sinta-se à vontade para contribuir com este repositório enviando pull requests com melhorias, correções de bugs ou novos recursos.
