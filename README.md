# Guizz Worlds — World Rescue

Site estático para recuperar a elegibilidade de conquistas em mundos Minecraft Bedrock. O arquivo `.mcworld` é processado localmente no navegador.

- Site: <https://guizz-worlds.github.io/>
- Repositório: <https://github.com/guizz-worlds/guizz-worlds.github.io>
- Publicação: GitHub Pages, branch `main`, pasta raiz.

A página inicial `https://guizz-worlds.github.io/` abre a ferramenta diretamente, sem tela de redirecionamento. Os endereços antigos em `/tools/` continuam disponíveis para links já compartilhados.

## SEO e idiomas

O World Rescue tem páginas próprias para 15 idiomas, com metadados localizados e links `hreflang` entre as versões. O sitemap fica em <https://guizz-worlds.github.io/sitemap.xml> e o `robots.txt` informa esse endereço aos robôs de busca. Depois de atualizar páginas, é possível notificá-las aos mecanismos compatíveis com IndexNow.

Esses recursos ajudam os buscadores a descobrir e entender as páginas, mas não garantem indexação nem posição nos resultados. Evite criar páginas repetidas ou listas artificiais de palavras-chave.

Para solicitar a indexação no Google:

1. Adicione a propriedade de prefixo de URL `https://guizz-worlds.github.io/` no [Google Search Console](https://search.google.com/search-console/).
2. Conclua a verificação solicitada pelo Google para o site.
3. Em **Sitemaps**, envie `https://guizz-worlds.github.io/sitemap.xml`.

No Bing, adicione o site ao [Bing Webmaster Tools](https://www.bing.com/webmasters/) para acompanhar rastreamento e indexação. Essas etapas exigem acesso às contas do proprietário.

## Atualizar o site

Edite os arquivos deste diretório, faça um commit e envie para `main`. O GitHub Pages publica as alterações automaticamente.

O arquivo `.nojekyll` mantém os recursos em `_next/` disponíveis. Os caminhos dos recursos são relativos para funcionar na raiz do domínio do GitHub Pages.

## Domínio próprio

Para usar um domínio próprio, configure-o em **Settings → Pages → Custom domain** e ajuste os registros DNS do domínio no provedor responsável.

O endereço `https://guizz-worlds.github.io/` é o domínio gratuito de site de usuário/organização do GitHub. Ele é publicado pelo repositório `guizz-worlds.github.io` da organização `guizz-worlds`.
