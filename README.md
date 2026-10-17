# gustavombarbosadev.github.io

Site raiz do GitHub Pages. Serve para duas coisas:

1. **`.well-known/assetlinks.json`**: prova para o Android que o app **MB Controle** (APK) e o site
   `gustavombarbosadev.github.io` são do mesmo dono. Com isso, o app abre em tela cheia, sem a barra de endereço.
   Se gerar o APK de novo com **outra chave de assinatura**, troque este arquivo pelo novo `assetlinks.json`.
2. **`index.html`**: quem abrir `gustavombarbosadev.github.io` é levado direto para o MB Controle.

O arquivo `.nojekyll` é obrigatório: sem ele, o GitHub Pages esconde pastas que começam com ponto (como `.well-known`).
