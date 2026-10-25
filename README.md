# Mas, e se?

Site do canal [Mas, e se?](https://www.youtube.com/@youtubemasese): perguntas que mudam tudo, respondidas de um jeito simples e visual.

Site estático (HTML + CSS), publicado na Netlify direto deste repositório.

## Páginas

- `index.html`: página inicial (vídeo, artigos, temas, newsletter e apoio)
- `e-se-a-lua-desaparecesse.html`: artigo de exemplo e modelo para os próximos
- `apoie.html`: formas de apoiar e "Anuncie no canal"
- `obrigado.html`: confirmação da newsletter
- `404.html`: página não encontrada

## Como publicar um artigo novo

1. Copie `e-se-a-lua-desaparecesse.html` com um nome novo (ex.: `e-se-os-dinossauros-voltassem.html`).
2. Troque título, descrição, texto e o vídeo.
3. Adicione um card na seção "Artigos" do `index.html`.

## Newsletter

O formulário usa o Netlify Forms. No painel da Netlify, em **Forms**, ative a detecção de formulários; os e-mails cadastrados aparecem lá.

## Pix (página Apoie)

Os botões de R$ 1, R$ 2, R$ 5, R$ 10 e "outro valor" geram o QR Code e o código copia e cola sozinhos.
Para ativar, abra `apoie.html`, procure **CONFIGURAÇÃO DO PIX** e preencha `chave`, `nome` e `cidade`.
Enquanto estiver em branco, a página mostra "O Pix entra no ar em breve".

## Vídeo do YouTube

Quando o primeiro vídeo sair, siga o comentário na seção "Último vídeo" do `index.html`.
