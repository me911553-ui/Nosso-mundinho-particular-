# Nosso Mundinho — Mary & Higor ♡

Site romântico responsivo com álbum de fotos, contador de namoro, seção “Abra quando…”, quiz, jogo da memória, cartinhas surpresa, caça ao tesouro e roleta do amor.

## Arquivos
- `index.html`: estrutura do site.
- `style.css`: visual, cores e responsividade.
- `script.js`: contador, cartas e jogos.

## Testar no celular ou computador
1. Extraia o ZIP.
2. Abra `index.html` no navegador. Para uma experiência melhor, use Chrome.
3. Clique nos jogos e nos envelopes para testar.

## Personalizar as fotos
O botão “Adicionar fotos do celular” mostra imagens durante a sessão atual do navegador. Para que as fotos apareçam para todo mundo no site publicado:
1. Crie uma pasta chamada `fotos` ao lado de `index.html`.
2. Coloque suas imagens lá, por exemplo `foto1.jpg`.
3. No `index.html`, troque um bloco `<div class="photo-placeholder ...">...</div>` por:
   `<img src="fotos/foto1.jpg" alt="Mary e Higor juntos" style="width:100%;aspect-ratio:4/4.5;object-fit:cover">`
4. Repita para cada foto e publique novamente.

## Personalizar mensagens
Abra `script.js` e edite os textos dentro do objeto `letters`, da lista `surpriseNotes` e das listas `missions` e `quiz`. Salve o arquivo e atualize o site.

## Publicar de graça com GitHub Pages
1. Crie uma conta gratuita em https://github.com/ (se ainda não tiver).
2. Crie um repositório público, por exemplo `nosso-mundinho`.
3. Envie `index.html`, `style.css`, `script.js` e a pasta `fotos` (se usar fotos).
4. No repositório, entre em **Settings → Pages**.
5. Em **Build and deployment**, escolha **Deploy from a branch**.
6. Escolha a branch `main` e a pasta `/ (root)`; clique em **Save**.
7. Aguarde alguns minutos. O GitHub mostrará o endereço do site nessa mesma página, normalmente no formato `https://SEU-USUARIO.github.io/nosso-mundinho/`.
8. Copie o endereço e mande para o Higor.

## Importante
- O site não envia dados para nenhum servidor e não tem login.
- As fotos escolhidas pelo botão de upload são temporárias no navegador; siga o passo de personalização para incluí-las de forma permanente.
- A música não foi incluída automaticamente para evitar inserir uma faixa com direitos autorais. Se quiser, você pode adicionar um áudio próprio ou livre de direitos.
- O contador usa a data local 07/07/2025.
