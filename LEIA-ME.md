# Pandora — Site institucional + página de projetos

Esta versão mantém **Pandora como marca principal**, recuperando a identidade visual do arquivo original: laranja `#F0440D`, creme `#FFF1E9`, azul-escuro `#101326`, Poppins e assets originais.

## Abrir

Extraia o ZIP e abra `index.html` no navegador. A navegação **Projetos** abre a página separada `projetos.html`.

## Personalizar projetos e equipe

Edite o arquivo `dados.js`.

- `projetos`: adicione ou altere os objetos com nome, descrição, status etc.
- `marca`: caminho da logo, por exemplo `assets/logo-fenara.png`.
- `capa`: caminho da arte de capa (se preenchido, aparece em vez da marca).
- `cores`: principal, fundo e texto, específicas de cada projeto **somente na aba Projetos**.
- `colaboradores`: adicione pessoas reais e seus papéis, por projeto.
- `links`: links de projeto, repositório ou apresentação.
- `contato`: link da Pandora, como `mailto:...` ou um endereço HTTPS.

Exemplo de campos dentro de um projeto:

```js
marca: 'assets/logo-fenara.png',
colaboradores: [
  { nome: 'Nome real', papel: 'Front-end e UI', link: 'https://github.com/usuario' },
  { nome: 'Outra pessoa', papel: 'Pesquisa e conteúdo' }
],
links: [
  { rotulo: 'Repositório', url: 'https://github.com/usuario/repositorio' }
]
```

Os integrantes não foram preenchidos automaticamente para evitar atribuições fictícias. O SEA também está com descrição provisória até a apresentação oficial. A seção de soluções descreve frentes da marca; não implica serviços comercialmente disponíveis.

## Arquivos

- `index.html`: site principal institucional da Pandora.
- `projetos.html`: vitrine dos projetos com janela de detalhes e créditos.
- `styles.css`: design responsivo, paleta original.
- `script.js`: navegação, cards, janela de detalhes.
- `dados.js`: conteúdo editável.
- `assets/`: mascote e artes originais reaproveitadas.

Recomenda-se testar no navegador, especialmente em dispositivos móveis, antes de publicar.
