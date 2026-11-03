---
name: analise-pintec-ibge
description: Orienta a consulta, validação, análise e apresentação de dados oficiais da Pesquisa de Inovação (PINTEC) do IBGE.
---

# Skill: Análise da PINTEC do IBGE

## Objetivo
Produzir uma análise clara e verificável de indicadores da Pesquisa de Inovação (PINTEC), usando dados consultados em fonte oficial do IBGE e criando um artefato HTML.

## Regras obrigatórias
1. Use apenas dados retornados pela API oficial do SIDRA/IBGE ou publicados em páginas oficiais do IBGE.
2. Nunca invente números, percentuais, datas, nomes de variáveis ou conclusões.
3. Antes de analisar, confirme o título da tabela, a variável, a unidade de medida, o território e os períodos consultados.
4. Registre o endereço exato da API, a data da consulta e a fonte oficial.
5. Trate campos vazios, símbolos especiais e valores indisponíveis como dados ausentes; não os converta automaticamente em zero.
6. Não compare indicadores de pesquisas ou universos diferentes sem explicar as diferenças metodológicas.
7. Diferencie claramente o que é dado observado, cálculo derivado e interpretação.
8. Se a consulta falhar ou os metadados não estiverem confirmados, informe a limitação e não apresente conclusões numéricas.

## Fluxo de trabalho
1. Identificar a tabela da PINTEC no SIDRA.
2. Conferir metadados, variáveis, períodos, território e unidade.
3. Consultar a API oficial e guardar a resposta original em `dados/`.
4. Limpar os dados sem apagar símbolos ou metadados importantes.
5. Calcular comparações apenas quando unidades e definições forem compatíveis.
6. Criar gráficos com título, unidade, período e fonte.
7. Escrever uma interpretação breve, sem afirmar causalidade quando os dados mostram apenas associação ou variação.
8. Atualizar o painel HTML e documentar a metodologia no README.

## Saída esperada
- Indicadores identificados e com fonte.
- Tabela dos dados efetivamente consultados.
- Gráfico ou visualização coerente com os dados.
- Interpretação dos resultados e limitações.
- Link para a API e para a página oficial do IBGE.
