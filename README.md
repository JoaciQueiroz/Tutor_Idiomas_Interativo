# 🎤 Tutor de Idiomas Interativo

Este projeto é um **tutor de idiomas interativo** desenvolvido em **Google Colab**, que permite ao usuário praticar fala e escuta em diferentes cenários.  
O fluxo completo é: **captura de áudio → transcrição → tradução → síntese de voz → reprodução**.

---

## 🚀 Funcionalidades

- **Captura de áudio no navegador**  
  Utiliza JavaScript integrado ao Colab para gravar a voz do usuário diretamente pelo microfone.

- **Reconhecimento de fala (Speech-to-Text)**  
  Implementado com o **Vosk**, um modelo open source de reconhecimento de fala offline, garantindo transcrição gratuita e sem necessidade de chave da OpenAI.

- **Tradução automática**  
  Usa a biblioteca **Google Translate (googletrans)** para traduzir frases do português para o inglês (ou outros idiomas).

- **Síntese de voz (Text-to-Speech)**  
  Converte a resposta traduzida em áudio usando **gTTS (Google Text-to-Speech)**.

- **Reprodução no Colab**  
  O áudio final é reproduzido diretamente no notebook, permitindo prática de pronúncia e escuta.

---

## 🛠️ Tecnologias utilizadas

- **Google Colab** → ambiente de execução em nuvem.  
- **JavaScript + Python** → integração para captura de áudio.  
- **Vosk** → reconhecimento de fala offline.  
- **pydub + ffmpeg** → conversão e manipulação de arquivos de áudio.  
- **googletrans** → tradução automática.  
- **gTTS** → conversão de texto em voz.  
- **IPython.display** → reprodução de áudio no notebook.

---
