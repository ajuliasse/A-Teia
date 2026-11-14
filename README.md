# A Teia

**O que está documentado, o que é alegação e o que ninguém provou.**

Um dossiê jornalístico interativo sobre Flávio Bolsonaro. O projeto foi construído como um documento HTML único, autônomo e de código aberto.

## O que tem dentro?

- **Versão Resumo (5 min):** Aberta por padrão, dividida em três eixos de análise (meritocracia, corrupção e família).
- **Dossiê Completo:** Acessível via botão ou `#completo`, com linha do tempo de 73 eventos, filtros, busca e propostas de campanha.
- **A Teia (Grafo):** Uma visualização gráfica interativa (usando `vis-network`) que mapeia as conexões entre personagens, empresas e órgãos públicos, diferenciando relações documentadas de investigações em curso.

## Princípios do projeto

- **Documento, não panfleto.** Fatos nus, sem adjetivos.
- **Fontes abertas.** Alegações têm donos ("segundo a PF", "Flávio alega") e o status de cada informação está marcado (Documentado, Alegação, Contestado).
- **Presunção de inocência.** Defesas e contestações dos citados sempre incluídas no texto.
- **A régua é a mesma.** O leitor é convidado a aplicar os mesmos critérios (Meritocracia, Corrupção, Família) ao outro lado da história. O julgamento final é sempre do leitor.

## Projeto Espelho

Este repositório faz parte de um projeto de dois lados. O documento espelho, sobre Lula e o PT, pode ser acessado em:
👉 **[A Régua](https://ajuliasse.github.io/A-Regua/)**

## Tecnologia

- **HTML5 / CSS3:** Grid/Flexbox, variáveis CSS, e dark mode nativo.
- **JavaScript Vanilla:** Sem frameworks.
- **[vis-network](https://visjs.github.io/vis-network/):** Biblioteca utilizada para renderizar o grafo interativo.

## Licença

Código aberto para consulta pública, estudos de caso de UX/UI e jornalismo de dados.