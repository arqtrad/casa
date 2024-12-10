# Casas tradicionais luso-brasileiras #

## Como contribuir

Seguir o [modelo de preenchimento](src/casa/casa.yml). Em caso de
dúvidas, consultar as fichas já preenchidas.

Os arquivos de mídia por ora não serão diretamente incluídos no
repositório, por motivos de custo. Temos a princípio duas opções para
referenciar imagens:

- [Wikimedia Commons](https://commons.wikimedia.org) se forem imagens em
  domínio público (fotos e desenhos muito antigos, por exemplo) ou
  material produzido por nós mesmos, inclusive desenhos em formato
  `.svg`;
- [Esta pasta no Pinterest](https://www.pinterest.com/abacoarq/arquitetura-tradicional/casa/)
  onde podemos carregar imagens em geral (mas não arquivos `.svg`).

Imagens que já são acessíveis a partir de um link direto para um
repositório existente (como o próprio Wikimédia Commons ou a Biblioteca
Nacional, por exemplo) podem ser apenas referenciadas, mas é
interessante criar uma cópia de segurança na pasta do Pinterest e no
nosso disco rígido.

## Estrutura dos arquivos ##

    .
    ├── _js
    │   └── search.js
    ├── _scss
    │   └── main.scss
    ├── assets
    │   ├── fonts
    │   ├── js
    │   └── media
    ├── src
    │   ├── _data
    │   ├── _includes
    │   ├── casa  # <-- Editar aqui!
    │   ├── docs
    │   ├── dwg   # <-- Editar aqui!
    │   ├── filters
    │   ├── media # <-- Editar aqui!
    │   ├── pages
    │   ├── utils
    │   ├── 404.html
    │   ├── index.md
    │   └── rss.njk
    ├── LICENSE
    ├── README.md
    ├── .eleventy.js
    ├── package-lock.json
    └── package.json

------------

 casa (c) 2023–2024 by Pedro P. Palazzo, Eduarda Viana & Eduarda Toscano
 
 casa is licensed under a
 Creative Commons Attribution 3.0 Unported License.
 
 You should have received a copy of the license along with this
 work.  If not, see <http://creativecommons.org/licenses/by/3.0/>.
