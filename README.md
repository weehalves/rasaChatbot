# Projeto Chatbot Rasa

Este projeto é um assistente virtual desenvolvido com Rasa. Ele foi projetado para lidar com consultas de suporte técnico, vendas e cobranças.

## Pré-requisitos

Antes de rodar a aplicação, certifique-se de ter os seguintes pré-requisitos instalados em sua máquina:

- [Python 3.8+](https://www.python.org/downloads/)
- [Pip](https://pip.pypa.io/en/stable/installation/)
- [Node.js](https://nodejs.org/)
- [Rasa](https://rasa.com/docs/rasa/installation/)

## Instalação

1. **Clone o repositório**:
   git clone https://github.com/weehalves/rasaChatbot
   cd rasaChatbot

2. Crie e ative um ambiente virtual (opcional, mas recomendado):

python -m venv venv
source venv/bin/activate  # Para Linux/Mac
venv\Scripts\activate     # Para Windows


3. Instale as dependências do Rasa:

pip install -r requirements.txt

4. Instale o Rasa (se ainda não estiver instalado):

pip install rasa==3.1.0

## Execução

1. Treine o modelo Rasa:

rasa train

2. Inicie o servidor do Rasa:

rasa run



