# GTA6 — Central de Vazamentos, Desenvolvimento e Curiosidades

Projeto de fã, **100% em HTML puro** (sem CSS e sem JavaScript), reunindo em um só lugar tudo o que já
se sabe publicamente sobre **Grand Theft Auto VI**: histórico de desenvolvimento, os dois grandes
vazamentos (2022 e 2026), personagens, elenco, mapa, veículos, rádios e easter eggs escondidos em
GTA V Online.

Este é um projeto pessoal/educacional, sem qualquer vínculo com a Rockstar Games ou a Take-Two
Interactive. O conteúdo é baseado em material oficial já divulgado publicamente ou em reportagens de
veículos de imprensa especializados, sempre citados nas próprias páginas.

## 🔗 Ver o site publicado

O projeto está hospedado via GitHub Pages e pode ser acessado diretamente aqui:

**[https://jhontropinha.github.io/GTA6/html/Home](https://jhontropinha.github.io/GTA6/html/Home)**

*(caso o link acima não funcione no seu navegador, use a versão com extensão:
[.../html/Home.html](https://jhontropinha.github.io/GTA6/html/Home.html))*

## 📁 Estrutura de pastas

```
GTA6/
├── html/     → 12 páginas do site (Home.html + Pagina1.html até Pagina11.html)
├── IMG/      → imagens, organizadas em 14 subpastas por assunto
├── Video/    → vídeos usados nas páginas (trailers, análises, reportagens)
├── Audio/    → áudio usado na Página 4
└── README.md
```

A pasta `IMG/` está dividida por tema:

| Subpasta                       | Conteúdo                                                        |
|---------------------------------|------------------------------------------------------------------|
| `Arion Kurtaj/`                 | Fotos do hacker do vazamento de 2022 (inclusive no tribunal)      |
| `Atores/`                       | Fotos dos atores/atrizes confirmados do elenco                   |
| `Barcos/`                       | Embarcações confirmadas de GTA VI (Marquis, Airboat)              |
| `Carros GTA/`                   | Carros confirmados/leaked de GTA VI                               |
| `Comunicados Rockstar Games/`   | Prints dos comunicados oficiais (vazamentos de 2022 e 2026)       |
| `CyberLeek/`                    | Material sobre o vazamento de 2026: logo, print da memecoin e a intimação judicial (PDF) |
| `Easte Eggs GTA Online/`        | Imagens dos easter eggs (quadro "Trust", mancha verde etc.)       |
| `Helicopteros/`                 | Aeronaves confirmadas (Maverick, Buzzard)                         |
| `Mapa GTA6/`                    | Imagens do mapa de Leonida                                        |
| `Marketing GTA 6/`              | Material sobre a campanha de marketing do jogo                    |
| `Motos/`                        | Motocicletas confirmadas (Alvino)                                 |
| `Personagem/`                   | Imagens dos protagonistas                                         |
| `Rádios/`                       | Logos/artes das estações de rádio                                 |
| `Thumbs/`                       | Thumbnails usados como poster de vídeos                           |

## 📄 Páginas do site

| # | Arquivo | Conteúdo |
|---|---|---|
| — | `Home.html` | Apresentação do projeto e índice de todas as páginas |
| 1 | `Pagina1.html` | Linha do tempo detalhada do desenvolvimento do jogo |
| 2 | `Pagina2.html` | O vazamento de setembro de 2022: o que aconteceu, o grupo Lapsus$, conteúdo vazado e repercussão |
| 3 | `Pagina3.html` | Protagonistas (Jason e Lucia) e personagens importantes (Cal Hampton, Brian Heder, Boobie Ike, Dre'Quan Priest, Real Dimez, Raul Bautista e Valentina) |
| 4 | `Pagina4.html` | Quem é o vazador de 2022, como ele obteve acesso à build, o julgamento e o desfecho |
| 5 | `Pagina5.html` | Easter eggs de GTA VI dentro de GTA Online e do modo história (Schlott Construction, quadro "Trust", mapa de Leonida) |
| 6 | `Pagina6.html` | Lista de atores/atrizes confirmados, seus perfis e os personagens que interpretam |
| 7 | `Pagina7.html` | Estações de rádio e músicas identificadas nos vazamentos de agosto de 2026 do CyberLeek |
| 8 | `Pagina8.html` | O vazamento de 2026: o caso CyberLeek, a memecoin, o comunicado da Rockstar, as intimações judiciais e o desfecho até agora |
| 9 | `Pagina9.html` | Estratégia de marketing da Rockstar, a proposta de parceria com Miami-Dade, e formulário de opinião do leitor |
| 10 | `Pagina10.html` | Veículos confirmados: carros, barcos, helicópteros e motos |
| 11 | `Pagina11.html` | O mapa de Leonida: as 6 regiões, locais nomeados, fauna e o tamanho especulado |

## 🛠️ Tecnologias e requisitos técnicos

O projeto foi construído propositalmente **sem CSS e sem JavaScript**, usando apenas HTML5, como
exercício de domínio das tags da linguagem.

**Já presentes no site:**
- Meta tags (`author`, `keywords`, `description`, `viewport`)
- Listas ordenadas e não ordenadas (`ol`, `ul`, `li`)
- Tags isoladas e de texto (`hr`, `br`, `b`, `i`, `u`)
- Tabelas completas em todas as 12 páginas (`table`, `tr`, `td`, `th`, `thead`, `tbody`)
- `label`, `fieldset` e `legend` (Página 9)
- `datalist` (Página 9)
- Navegação fluida por menu em todas as páginas, com organização em pastas (`html/`, `IMG/`, `Video/`, `Audio/`)
- Multimídia: `video` (6 páginas), `audio` (Página 4), `figure`/`figcaption` (7 páginas), `iframe` (Página 8)
- Elementos interativos `details`/`summary` (9 páginas)
- Marcação avançada de texto: `cite`, `mark`, `blockquote` (amplamente usados), `abbr`, `del`/`ins`, `progress`, `meter`

**Ainda faltam no site (ver "Melhorias planejadas" abaixo):**
- `select`, `radio` e `checkbox` — não aparecem em nenhuma página no momento
- Inputs avançados `date`, `file` e `color` — também ausentes

## 🚧 Melhorias planejadas para o futuro

Este projeto está em andamento e deve continuar sendo atualizado até (e depois) do lançamento do
jogo, previsto para **19 de novembro de 2026**. Itens já identificados para as próximas versões:

- [ ] Completar o formulário da Página 9 (ou criar um segundo formulário) com `select`, `radio`/`checkbox`
      e os inputs avançados `date`, `file` e `color`, que o projeto ainda não usa em lugar nenhum.
- [ ] Padronizar a meta tag `author` em todas as páginas — hoje `Home`, `Pagina9`, `Pagina10` e
      `Pagina11` usam um padrão, `Pagina1` a `Pagina5` e `Pagina8` usam outro, e `Pagina6`/`Pagina7`
      não têm essa meta tag.
- [ ] Adicionar imagens próprias na pasta `IMG/Mapa GTA6/` (hoje só há uma imagem especulativa,
      usada tanto na Home quanto na Página 11).
- [ ] Revisar pequenos erros de digitação em textos alternativos (`alt`) e legendas.
- [ ] Possíveis novas páginas: edições e pré-venda do jogo, trilha sonora/artistas licenciados por
      estação de rádio, e uma linha do tempo unificada cruzando todos os eventos do site.
- [ ] Manter a Página 4 e a Página 8 atualizadas conforme o caso do vazador de 2022 e a investigação
      do CyberLeek tiverem novidades (nenhum dos dois casos está oficialmente encerrado).

## ⚠️ Aviso

Este é um site de fã, sem fins lucrativos, feito apenas para fins educacionais e informativos. Não
reproduzimos vídeos, imagens ou textos vazados ilegalmente — todo o conteúdo é descrito com base em
material oficial ou em reportagens públicas, sempre citadas nas próprias páginas.