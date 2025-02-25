# Resumo da Página HTML

Esta página HTML exibe um título principal, um parágrafo de texto, uma imagem, um vídeo e um áudio. Abaixo está um resumo dos elementos incluídos e o que cada tag e atributo faz:

## Estrutura Básica

- `<!DOCTYPE html>`: Declara o tipo de documento como HTML5.
- `<html lang="en">`: Inicia o documento HTML e define o idioma como inglês.
- `<head>`: Contém metadados sobre o documento.
  - `<meta charset="UTF-8">`: Define a codificação de caracteres como UTF-8.
  - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Configura a viewport para garantir que a página seja renderizada corretamente em dispositivos móveis.
  - `<title>Document</title>`: Define o título da página que aparece na aba do navegador.

## Corpo do Documento

- `<body>`: Contém o conteúdo visível da página.

### Título Principal

- `<center>`: Centraliza o conteúdo dentro da tag.
  - `<h1>titulo principal</h1>`: Define um título de nível 1 com o texto "titulo principal".

### Parágrafo

- `<center>`: Centraliza o conteúdo dentro da tag.
  - Texto: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto sint, expedita est excepturi culpa eligendi et itaque ullam quia, maiores aliquam dolorem molestiae tempora libero sunt quod praesentium odio. Libero!"

### Imagem

- `<center>`: Centraliza o conteúdo dentro da tag.
  - `<img src="./assets/images/Screenshot_8.png" alt="teste imagem">`: Exibe uma imagem localizada no caminho especificado em `src` e mostra o texto alternativo "teste imagem" caso a imagem não possa ser exibida.

### Vídeo

- `<center>`: Centraliza o conteúdo dentro da tag.
  - `<video width="500" controls>`: Exibe um vídeo com largura de 500 pixels e controles de vídeo habilitados.
    - `<source src="./assests/videos/vav.mp4" type="video/mp4">`: Define a fonte do vídeo e o tipo de arquivo como MP4.

### Áudio

- `<center>`: Centraliza o conteúdo dentro da tag.
  - `<audio controls>`: Exibe um player de áudio com controles habilitados.
    - `<source src="./assets/audios/audio.mp3" type="audio/mpeg">`: Define a fonte do áudio e o tipo de arquivo como MPEG.
    - Texto: "Seu navegador não suporta o elemento de áudio." (Exibido caso o navegador não suporte o elemento `<audio>`).

## Comentários

- `<!-- Comentário -->`: Comentários no código HTML que explicam o propósito de cada tag.

Cada elemento está centralizado na página usando a tag `<center>`.