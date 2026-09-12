# GTA6 — Central de Vazamentos, Desenvolvimento e Curiosidades

Site de fã construído **100% em HTML puro** (sem CSS e sem JavaScript), reunindo em um só lugar as principais informações públicas sobre **Grand Theft Auto VI**: histórico de desenvolvimento, os dois grandes vazamentos conhecidos (2022 e 2026), personagens, elenco, mapa, veículos, rádios e easter eggs escondidos no GTA Online e no modo história de GTA V.

Projeto pessoal e educacional, **sem qualquer vínculo com a Rockstar Games ou a Take-Two Interactive**. Todo o conteúdo é baseado em material oficial já divulgado publicamente ou em reportagens de veículos de imprensa especializados, sempre citados nas próprias páginas.

## 🔗 Site publicado

O projeto está hospedado via GitHub Pages e pode ser acessado em:

**https://jhontropinha.github.io/GTA6/html/Home**

Se o link acima não abrir corretamente no navegador, use a versão com extensão:
**https://jhontropinha.github.io/GTA6/html/Home.html**

## 🎯 Objetivo do projeto

O repositório tem dois objetivos que caminham juntos:

- **Organizar em um só lugar** informações que hoje estão espalhadas por dezenas de reportagens, vídeos e posts sobre GTA VI — a linha do tempo de desenvolvimento, os vazamentos de 2022 e 2026, os personagens e o elenco confirmados, o mapa de Leonida, os veículos, as rádios e os easter eggs — sempre citando a fonte de cada informação na própria página.
- **Servir como exercício prático de HTML5 "puro"**: o site foi construído deliberadamente sem CSS e sem JavaScript, como forma de praticar o maior número possível de tags nativas da linguagem — tabelas, listas, multimídia, formulários, elementos interativos e marcação avançada de texto (ver "Tecnologias utilizadas" abaixo).

## 📁 Estrutura do repositório

```
GTA6/
├── html/     → 12 páginas do site (Home.html + Pagina1.html a Pagina11.html)
├── IMG/      → imagens de apoio, organizadas em subpastas por assunto
├── Video/    → vídeos usados nas páginas (trailers, reportagens, análises)
└── README.md
```

A pasta `IMG/` é dividida por tema. Entre as subpastas usadas nas páginas estão:

| Subpasta | Conteúdo |
| --- | --- |
| `Personagem/` | Imagens dos protagonistas Jason Duval e Lucia Caminos |
| `Atores/` | Fotos dos atores/atrizes confirmados do elenco |
| `Carros GTA/` e `Motos/` | Veículos confirmados/vazados de GTA VI |
| `Mapa GTA6/` | Imagem especulativa do mapa de Leonida |
| `Rádios/` | Logos das estações de rádio confirmadas |
| `Comunicados Rockstar Games/` | Prints dos comunicados oficiais sobre os dois vazamentos |
| `CyberLeek/` | Material sobre o vazamento de 2026 (logo, print da memecoin e intimação judicial em PDF) |
| `Easte Eggs GTA Online/` | Imagens dos easter eggs (quadro "Trust", mancha verde etc.) |
| `Arion Kurtaj/` | Fotos do responsável identificado pelo vazamento de 2022 |
| `Marketing GTA 6/` | Material sobre a campanha de marketing e a proposta com Miami-Dade |

*(o projeto também mantém pastas para Barcos, Helicópteros e Thumbnails de vídeo, usadas em pontos específicos do site.)*

## 📄 Conteúdo das páginas

| # | Arquivo | Conteúdo |
| --- | --- | --- |
| — | `Home.html` | Apresentação do projeto, resumo rápido (protagonistas, engine, ambientação), linha do tempo simplificada e galeria |
| 1 | `Pagina1.html` | Linha do tempo detalhada do desenvolvimento, da pré-produção (2017) aos trailers oficiais |
| 2 | `Pagina2.html` | O vazamento de setembro de 2022: como aconteceu, o grupo Lapsus$ e a repercussão |
| 3 | `Pagina3.html` | Protagonistas (Jason e Lucia) e personagens importantes (Cal Hampton, Brian Heder, Boobie Ike, Dre'Quan Priest, Real Dimez, Raul Bautista, Valentina) |
| 4 | `Pagina4.html` | Quem é o hacker do vazamento de 2022 (Arion Kurtaj), como ele obteve acesso à build e o desfecho judicial |
| 5 | `Pagina5.html` | Easter eggs de GTA VI dentro do GTA Online e do modo história de GTA V (Schlott Construction, quadro "Trust", mancha verde) |
| 6 | `Pagina6.html` | Atores/atrizes confirmados, seus perfis e como a comunidade os identificou antes do anúncio oficial |
| 7 | `Pagina7.html` | Estações de rádio e músicas identificadas nos vazamentos de agosto de 2026 |
| 8 | `Pagina8.html` | O vazamento de 2026: o caso CyberLeek, a memecoin $CYBERLEEK, o comunicado da Rockstar e as intimações judiciais em andamento |
| 9 | `Pagina9.html` | Estratégia de marketing da Rockstar/Take-Two e a proposta de parceria com Miami-Dade, com formulário de opinião do leitor |
| 10 | `Pagina10.html` | Veículos confirmados: carros, motos, barcos e aeronaves |
| 11 | `Pagina11.html` | O mapa de Leonida: as 6 regiões confirmadas, locais nomeados e fauna |

## 🛠️ Tecnologias utilizadas

Construído propositalmente **sem CSS e sem JavaScript**, usando apenas HTML5. Recursos já em uso no site:

- Meta tags (`author`, `keywords`, `description`, `viewport`)
- Listas ordenadas e não ordenadas, e tabelas completas (`table`, `thead`, `tbody`, `th`)
- Multimídia: `video` (trailers e vídeos incorporados), `figure`/`figcaption`
- Elementos interativos `details`/`summary`
- Marcação de texto: `mark`, `blockquote`, `cite`, `del`/`ins`, `progress`/`meter`, `abbr`
- Elementos de formulário: `label`, `fieldset`, `legend` e `datalist` (Página 9)
- Menu de navegação consistente entre as páginas, com organização em pastas (`html/`, `IMG/`, `Video/`)


## ⚠️ Aviso importante

Este é um site de fã, sem fins lucrativos, feito apenas para fins educacionais e informativos:

- Sem qualquer vínculo oficial com a Rockstar Games ou a Take-Two Interactive.
- O site **não hospeda nem reproduz** vídeos, imagens ou textos vazados ilegalmente — os vazamentos são **descritos com base em reportagens públicas**, sempre citadas nas próprias páginas (BBC, CBS News, TechRadar, SVG, Tom's Hardware, CoinDesk, entre outras).
- Informações sobre pessoas envolvidas nos casos relatados (como o responsável identificado pelo vazamento de 2022) já eram amplamente divulgadas pela imprensa internacional antes de serem citadas aqui.

## 🚧 Estado atual e melhorias futuras

O projeto está em andamento e deve continuar sendo atualizado até (e depois) do lançamento do jogo, previsto — segundo o conteúdo do próprio site — para 19 de novembro de 2026. Pontos já identificados para as próximas versões:

- [ ] Padronizar a meta tag `author` em todas as páginas: atualmente a Home e as Páginas 1 a 5 e 8 usam "Fã-site não oficial de GTA VI", enquanto as Páginas 6, 7, 9, 10 e 11 usam o nome do desenvolvedor.
- [ ] Completar o formulário de opinião da Página 9 (ou criar um segundo formulário) com `select`, `radio`/`checkbox` e os inputs avançados `date`, `file` e `color`.
- [ ] Adicionar imagens próprias/autorais em `IMG/Mapa GTA6/`, hoje com apenas uma imagem especulativa reaproveitada tanto na Home quanto na Página 11.
- [ ] Manter a Página 8 atualizada conforme surgirem novidades na investigação do CyberLeek, que segue em aberto (diferente do caso de 2022, já com desfecho judicial em dezembro de 2023).
- [ ] Possíveis novas páginas: edições e pré-venda do jogo, trilha sonora completa por estação de rádio, e uma linha do tempo unificada cruzando todos os eventos do site.
- [ ] Preencher a seção "About" do repositório no GitHub (descrição e topics) e avaliar a adição de uma licença — o repositório está público, mas sem descrição, topics ou licença definidos no momento.

## Créditos

Projeto mantido por [Jhontropinha](https://github.com/Jhontropinha) no GitHub.
