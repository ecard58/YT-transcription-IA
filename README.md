# Youtube Transcription Project

Projeto desenvolvido durante o BoraCodar 31 - RocketSeat.

(Adendo: por alguma razão o projeto não está funcionando corretamente na porta 5173, mas funciona perfeitamente na 5174... caso alguém saiba qual a razão, ficarei satisfeito em saber também)

Este projeto consiste em uma aplicação web para transcrição de áudio de vídeos do YouTube para texto. Ele utiliza a API do YouTube para carregar o vídeo desejado, extrai o áudio do vídeo, realiza a transcrição do áudio para texto e exibe a transcrição na página web.

## Funcionalidades

- Cole a URL de um vídeo do YouTube na caixa de texto e clique em "Transcrever" para iniciar o processo de transcrição.
- O vídeo será carregado e o áudio será extraído e transcrita.
- Após a transcrição, o texto será exibido na página, segmentado em trechos para facilitar a leitura.

## Pré-requisitos

Para executar este projeto localmente, é necessário ter instalado:

- Node.js
- NPM (gerenciador de pacotes do Node.js)

## Como executar

1. Clone este repositório para o seu ambiente local:

git clone https://github.com/ecard58/YT-transcription-IA.git


2. Instale as dependências do projeto:

npm install

3. Inicie o servidor local e o frontend:

npm run server

npm run dev

## Estrutura do Projeto

- `index.html`: Arquivo HTML da aplicação.
- `src/`: Diretório contendo os arquivos JavaScript da aplicação.
- `main.js`: Arquivo principal da aplicação, responsável por controlar o fluxo de execução.
- `youtube-api.js`: Módulo contendo funções para interação com a API do YouTube.
- `transcribe.js`: Módulo para transcrição de áudio para texto.
- `render.js`: Módulo para renderização da transcrição na página HTML.
- `loading.js`: Módulo para exibição de mensagens de carregamento na página.

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript
- Axios (para requisições HTTP)
- @phosphor-icons/web (para ícones)
- @xenova/transformers (para transcrição de áudio)

## Infos adicionais

O vídeo tutorial do projeto está disponível em: https://app.rocketseat.com.br/classroom/bora-codar/lesson/transcricao-de-video-com-ia-nodejs-whisperai-transformersjs-bora-codar-31

HTML, CSS e links para documentação disponibilizados pelo autor [Mayk Brito](https://github.com/maykbrito) em: https://www.fronteditor.dev/gists/64e6ade5434ccd23e6ad89d50cafea3b/view

Repositório do projeto do autor: https://github.com/maykbrito/boracodar31





