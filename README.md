## Tripleten web_project_homeland

**Idioma:** PT
**Feito por:** Grasielle Damazio
**Roteiro por:** Triple Ten

## 🔗 Acesse o projeto
https://github.com/GrasiDamazio/web_project_homeland.git

## Descrição do projeto
Uma introdução sobre os funcionários da Triple Ten que estão espalhados ao redor do mundo. Além das telas maiores, nesse projeto o foco foi trazer responsividade para telas de diferentes tamanhos. Este projeto utiliza HTML5 e CSS3 para construir uma galeria responsiva com layout moderno, aplicando Flexbox, Grid Layout e Media Queries.

## Estrutura do projeto

## O projeto possui:

- Cor de fundo única em toda a página (#2b2f33 cinza);
- Cor de fonte única em toda a página (#ffffff branco);
- Fonte única (Inter, sans-serif);
- Consultas de mídia para trazer responsividade para telas de (762px e 320px);
- O CSS foi separado de acordo com os blocos aos quais pertencem;
- Header;
- Main;
- Footer.

## Header
- Header
- Logo
- Título
- Descrição
- Imagem

O bloco possui alinhamento central. Nas telas de 1280px, a imagem segue as margens do restante do bloco. Já nas telas de 762px e 320px, a mesma ocupa 100% do seu espaço, sem margens.

## Main

**Section Informations:**

- Título
- Parágrafo de citação
- Nome do autor da citação
- Parágrafo com o conteúdo

O bloco foi organizado utilizando display flex, com alinhamento flex-start. A citação e o autor foram organizados utilizando uma <div> para agrupá-los, e no CSS também foi utilizado display flex, com o alinhamento dos itens em flex-end, fazendo com que a citação e o autor fiquem em lados opostos do container.

**Section Photo Grid:**

8 imagens dispostas em:
- Desktop: 4 colunas e 2 linhas
- Tablet: 2 colunas e 4 linhas
- Mobile: 1 coluna e 8 linhas

Galeria criada com CSS Grid exibindo imagens organizadas em colunas.

**Section NFT Shop:**

**Duas colunas**

Coluna da direita:
- Título
- Imagem
- Botão

Coluna da esquerda:
- Título e nome do artista
- Parágrafo descritivo

Responsividade
- Tablet: redução de fontes e espaçamentos.
- Mobile: layout em coluna única com todos os elementos empilhados

A seção utiliza Grid para organizar os cards em coluna. Cada card usa CSS Grid para distribuir título, artista, imagem, texto e botão de forma estruturada.


## Footer

- Copyright

Na parte inferior está o copyright, contendo o símbolo "©", o ano e o nome do autor. O bloco se encontra no centro da página e foi alinhado usando alinhamento central.

**Consultas de mídia**

As consultas de mídia foram utilizadas para as telas menores e, nelas, foram alteradas apenas partes como as configurações de texto, paddings, margens e o tamanho que a imagem ocupava nas telas menores. A estrutura geral e as cores se mantiveram as mesmas.
