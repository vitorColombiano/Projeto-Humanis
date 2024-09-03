# Projeto Humanis

### Autores
Os autores desse projeto são Laura Lisbôa e Vitor Colombiano, ambos alunos da Universidade Federal de São Paulo.
Com a finalidade de desenvolver um projeto final para a disciplina de Inteligência Artificial, formaram uma dupla durante três meses para obter resultados diante dos conhecimentos colocados em práticas.  

### Sobre o que é? 
Chatbot voltado para cuidadores de idosos com Alzheimer, com a finalidade de instruir e servir de conforto para os cuidadores não-profissionais. 

### Tecnologias usadas
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

### Links sobre o projeto
Para acessor nossa apresentação entre no [link](https://www.canva.com/design/DAGNrhdoEI8/NJsopshRf0OuOtMAYpvuyg/edit?utm_content=DAGNrhdoEI8&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) e para acessar nossa base de dados acesse esse [drive](https://drive.google.com/drive/folders/1tG4bflIjV4JhitL6aPCUZAg3GVHPT3Wl).

### Imagem do Humanis
[streamlit-app-2024-09-01-16-09-21.webm](https://github.com/user-attachments/assets/fca3cf25-3588-445e-a0e4-16afef210fba)

