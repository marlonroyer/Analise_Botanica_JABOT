# Análise Botânica - JABOT (EVB)

Ferramenta web para análise exploratória de dados de coleções botânicas exportadas no formato JABOT.

## Funcionalidades

- **Upload** de planilhas `.xlsx` no formato JABOT
- **Estatísticas de Taxonomia**: famílias, gêneros e espécies (contagem por binômio)
- **Hábito de crescimento**: distribuição por categoria
- **Herbário de origem**: registros e espécies distintas por sigla
- **Gráficos interativos** (barras, pizza, horizontal)
- **Exportação** dos resultados em `.xlsx` com múltiplas abas

## Como usar

1. Acesse: `https://seu-usuario.github.io/analise-botanica-jabot/`
2. Carregue sua planilha exportada do JABOT/speciesLink
3. Visualize as estatísticas e gráficos
4. Exporte os resultados em Excel

## Tecnologias

- HTML5 + CSS3 + JavaScript (Vanilla)
- [SheetJS](https://sheetjs.com/) - Leitura/escrita de arquivos Excel
- [Chart.js](https://www.chartjs.org/) - Gráficos interativos
- [Font Awesome](https://fontawesome.com/) - Ícones

## Formato da planilha de entrada

Colunas obrigatórias: `family`, `genus`, `sp1`, `habito`, `sigla_colbot_origem`

Consulte a [documentação do JABOT](http://jabot.sibbr.gov.br/) para detalhes.

## Contribuições

Sugestões e melhorias são bem-vindas! Abra uma issue ou envie um PR.

## Licença

Este projeto no momento é voltado para o uso interno.
