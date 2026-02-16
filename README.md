# 🎙️ Assistente de Voz Inteligente com Google Gemini

Este projeto foi desenvolvido como resposta a um **Desafio de Projeto da DIO**, com o objetivo de integrar tecnologias de Speech-to-Text, IA Generativa e Text-to-Speech em uma aplicação prática utilizando Python.

A proposta original utilizava a API da OpenAI com Whisper e ChatGPT. Nesta implementação, realizei uma adaptação estratégica para o Google Gemini, explorando melhor aproveitamento de cotas gratuitas e novas possibilidades da API.

---

## 📌 Sobre o Projeto

A aplicação recebe um texto (simulando uma transcrição de áudio), envia para um modelo de IA generativa (Gemini) e converte a resposta em áudio utilizando Google Text-to-Speech.

O projeto demonstra integração entre APIs, manipulação de dados textuais e geração de áudio, com foco em aplicações backend voltadas para IA conversacional.

---

## 🚀 Tecnologias Utilizadas

- Python 3.x  
- Google Gemini API (modelo `gemini-1.5-flash-latest`)  
- gTTS (Google Text-to-Speech)  
- Google Colab  
- Gerenciamento de credenciais com `google.colab.userdata` (Secrets)

---

## 🛠️ Funcionalidades

- Integração com LLM para geração de respostas contextuais  
- Conversão automática de texto em áudio (.wav)  
- Gerenciamento seguro de API Key via Secrets  
- Migração arquitetural da solução original (OpenAI) para Google Gemini  
- Estrutura organizada para facilitar manutenção e evolução  

---

## 🔄 Adaptação do Desafio

O desafio original propunha a integração entre:

- Whisper (Speech-to-Text)  
- API ChatGPT (OpenAI)  
- Google Text-to-Speech  

Nesta versão, implementei:

- Substituição da API da OpenAI pelo Google Gemini  
- Ajustes na estrutura de requisição e tratamento de resposta  
- Melhor organização do fluxo da aplicação  
- Adequação ao gerenciamento seguro de credenciais  

---

## 📋 Como Executar o Projeto

### 1️⃣ Obtenha uma API Key
Acesse o Google AI Studio e gere sua chave gratuita.

### 2️⃣ Configure no Google Colab
- Abra o notebook no Colab  
- Clique no ícone 🔑 (Secrets)  
- Crie a chave com o nome: `GOOGLE_API_KEY`  
- Cole sua API Key  
- Habilite o acesso ao notebook  

### 3️⃣ Execute
Rode as células em ordem e defina a variável `transcription` com o texto desejado.

---

## 📂 Estrutura do Código

Fluxo da aplicação:

1. Gravação de Áudio Com Python (e Uma Pitada de JavaScript) 🎤 
2. Reconhecimento de Fala com Whisper (OpenAI) 🧠
3. Integração com a API do Gemini 💬
4. Sintetizando a Resposta do Gemini Como Voz (gTTS) 🔊

---

## 🎯 Objetivo

Demonstrar integração entre múltiplas APIs, manipulação de texto e áudio e aplicação prática de IA generativa em um contexto backend.

---

## 👨‍💻 Autor

**Rogério Oliveira**

Pós-graduando em Segurança da Informação e Análise Forense  
Bacharel em Sistemas de Informação – CESMAC  
Tecnólogo em Gestão de Sistemas de Informação – FAA/IESA  
Profissional com experiência em Infraestrutura, Dados e Desenvolvimento
