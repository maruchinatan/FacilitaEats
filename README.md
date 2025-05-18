# FacilitaEats - Seu Assistente de Restaurantes com IA

Bem-vindo ao FacilitaEats! Este projeto usa a Inteligência Artificial do Google (API Gemini) para te ajudar a escolher restaurantes e pratos. Ele foi desenvolvido como um notebook do Google Colab.

## Como Usar no Google Colab

1.  **Abra no Colab:**
    * A maneira mais fácil é encontrar o arquivo `.ipynb` principal neste repositório e clicar no botão "Open in Colab" que geralmente aparece no topo.

2.  **IMPORTANTE: Configure sua Chave de API do Google Gemini:**
    * Para o código funcionar, você precisa da sua própria chave de API do Google.
    * No Colab, no painel da esquerda (se não estiver aparecendo, clique no ícone `>` para expandir), procure e clique no ícone de **Chave (🔑 Secrets)**.
    * Clique em **"+ ADD A NEW SECRET"** (Adicionar novo segredo).
    * No campo **"Name"** (Nome), digite exatamente: `GOOGLE_API_KEY`
    * No campo **"Value"** (Valor), cole a sua chave de API do Google Gemini. (Você pode obter uma no [Google AI Studio](https://aistudio.google.com/app/apikey)).
    * **Ligue o interruptor "Notebook access"** (Acesso ao notebook) para esta chave.
    * *Este é o jeito seguro de usar sua chave sem colocá-la no código!*

3.  **Instale as Bibliotecas (se necessário):**
    * O notebook tentará instalar as bibliotecas que precisa. Se você ver uma célula de código no início do notebook com `!pip install -r requirements.txt`, execute-a.

4.  **Execute o Código:**
    * Agora, é só rodar as células do notebook em ordem!

## Observações
* A parte de extrair cardápios de sites de restaurantes é experimental e pode não funcionar para todos os sites.
* Você está usando sua própria cota da API do Google. Se usar muito, pode encontrar um erro de limite de uso (erro 429).
