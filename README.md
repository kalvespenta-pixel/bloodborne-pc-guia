# Bloodborne no PC — site de links

Site estático, responsivo e em português, pronto para personalizar e publicar gratuitamente.

## Arquivos
- `index.html`: textos, títulos e URLs.
- `styles.css`: aparência e layout.

## Personalizar links
Abra `index.html` num editor de texto (por exemplo, Bloco de Notas ou VS Code).

1. Encontre os cartões na seção `id="downloads"`.
2. Em cada `<a class="resource-link placeholder" href="#editar-links"...>`, substitua `#editar-links` pela URL verdadeira, por exemplo `https://site-oficial.example/`.
3. Troque o texto `Adicionar link` por algo como `Abrir página oficial`.
4. Na seção do vídeo, substitua o `href="#editar-links"` pela URL do seu vídeo e o texto `Adicionar vídeo` por `Assistir no YouTube`.
5. Salve e abra `index.html` no navegador para conferir.

Use links confiáveis, de preferência páginas oficiais de ferramentas e documentação. Não hospede nem distribua arquivos do jogo protegidos por direitos autorais sem autorização.

## Publicar gratuitamente com GitHub Pages
1. Crie/entre numa conta em https://github.com/
2. Clique em **New repository**.
3. Dê um nome, por exemplo `bloodborne-pc-guia`, e escolha **Public**.
4. Crie o repositório.
5. Clique em **Add file → Upload files** e envie `index.html`, `styles.css` e `README.md` (não envie apenas a pasta zipada).
6. Clique em **Commit changes**.
7. Abra **Settings → Pages**.
8. Em **Build and deployment**, escolha **Deploy from a branch**.
9. Em **Branch**, selecione `main` e a pasta `/(root)`, depois clique em **Save**.
10. Aguarde a publicação. O GitHub mostrará o endereço em **Settings → Pages**, normalmente parecido com `https://SEU-USUARIO.github.io/bloodborne-pc-guia/`.

Após alterar links, envie novamente os arquivos editados e faça commit. A publicação pode levar alguns minutos.

## Alternativa
Cloudflare Pages também oferece hospedagem estática. Siga a documentação oficial: https://developers.cloudflare.com/pages/
