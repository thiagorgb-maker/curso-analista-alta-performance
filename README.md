# Curso — Analista de Alta Performance (Volume 1)

Site de leitura tipo "curso online" com o conteúdo completo do livro: introdução, os 22 capítulos das 4
partes e os 5 apêndices + referências. Menu lateral por parte/capítulo, barra de progresso, marcação
automática de capítulo lido (salva no navegador da pessoa) e botões de Anterior/Próximo.

## Estrutura de arquivos
```
index.html
assets/
  capa.jpeg
```
Mantenha essa estrutura ao subir para o GitHub — o `index.html` referencia a imagem em `assets/capa.jpeg`.

## Como publicar de graça no GitHub Pages

1. Crie um repositório novo no GitHub (ex: `curso-analista-alta-performance`).
2. Faça upload do `index.html` e da pasta `assets` (com `capa.jpeg` dentro), mantendo a mesma estrutura —
   em "Add file → Upload files", arraste a pasta inteira.
3. No repositório, vá em **Settings → Pages**.
4. Em "Source", selecione a branch `main` e a pasta `/ (root)`. Clique em **Save**.
5. Em 1-2 minutos o curso estará disponível em:
   `https://SEU-USUARIO.github.io/curso-analista-alta-performance/`

## Como funciona
- O menu lateral (ícone ☰ no celular) lista todas as partes e capítulos — clique em qualquer um para ir direto.
- Cada capítulo abre com epígrafe, texto, exemplos de código, tabelas, os boxes "Dica do Especialista /
  Erro Comum / Caso Real", resumo e exercícios — exatamente como no livro.
- Ao abrir um capítulo, ele é marcado como lido automaticamente (✓ no menu) e a barra de progresso no topo
  atualiza. Isso fica salvo no navegador de cada pessoa (não é compartilhado entre usuários).
- Basta compartilhar o link do site — não é preciso login nem servidor.

## Se quiser editar depois
Todo o conteúdo está dentro do `index.html`, dividido em blocos `<article class="page" id="...">` — um por
capítulo/apêndice. Você pode editar o texto diretamente ali com qualquer editor de texto.
