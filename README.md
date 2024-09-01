# Projeto Humanis

### Sobre o que é? 
Chatbot voltado para cuidadores de idosos com alzheimer, com a finalidade de instruir e servir de conforto para os cuidadores não profissionais

### Técnologias usadas
```bash
Google Colab
Python
Langchain
ChromaDB
OpenAI API
Maritalk API
```

### Como utilizar ?
1. Extrair as licenças da API e colocar em um arquivo .env
```bash
  OPENAI_API_KEY="your_api_key"
  MARITALK_API_KEY="your_api_key"
```

2. Rodar a célula Streamlit para gerar o arquivo app.py
   
4. Extrair o IP do colab
   ```bash
   ! wget -q -O - ipv4.icanhazip.com
   ```
5. Executar o streamlit no colab
   ```bash
   ! streamlit run app.py & npx localtunnel --port 8501
   ```
6. Entrar no link e colar o IP do colab na senha

### Imagem do Humanis
[streamlit-app-2024-09-01-16-09-21.webm](https://github.com/user-attachments/assets/fca3cf25-3588-445e-a0e4-16afef210fba)

