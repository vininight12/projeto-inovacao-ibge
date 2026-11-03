# Projeto: Análise da Pesquisa de Inovação do IBGE

Este projeto é um ponto de partida para um painel HTML que consulta dados do SIDRA/IBGE e apresenta os resultados retornados pela API.

## Objetivo
Explorar indicadores da Pesquisa de Inovação (PINTEC), documentar a fonte dos dados e produzir uma análise baseada somente em valores efetivamente retornados pelo IBGE.

## Estrutura
- `artefato/index.html`: painel web inicial.
- `skill/SKILL.md`: instruções reutilizáveis para orientar a análise.
- `dados/`: pasta reservada para dados exportados e evidências da consulta.

## Atenção sobre os dados
O identificador de tabela 5018 aparece em referência técnica relacionada à PINTEC, mas antes de usar os valores em conclusões acadêmicas, confira no SIDRA o nome exato da tabela, as variáveis, os períodos e a unidade de medida. O painel não inventa valores: ele exibe os registros retornados pela API ou informa que a consulta falhou.

## Como testar
1. Abra `artefato/index.html` no navegador com internet.
2. Clique em **Consultar API**.
3. Confira o status e os dados retornados. Se a API rejeitar os parâmetros, consulte a tabela no SIDRA e atualize a URL no campo do painel.
4. Registre no relatório o endereço da API utilizado, a data da consulta, o nome da tabela, a variável e os períodos.

## Publicar no GitHub
1. Entre em https://github.com/ e crie um repositório público chamado `projeto-inovacao-ibge`.
2. Envie estes arquivos mantendo a estrutura de pastas.
3. Abra `artefato/index.html` no repositório e confira se o arquivo foi enviado.
4. Para publicar o painel como site, entre em **Settings > Pages**, selecione a branch principal e a pasta `/ (root)` se o HTML estiver na raiz; alternativamente, mova `index.html` para a raiz ou configure a pasta `/artefato` conforme as opções disponíveis.
5. Compartilhe o link do repositório no SIGAA. Se usar GitHub Pages, compartilhe também o link do site.

## Fontes oficiais
- PINTEC: https://www.ibge.gov.br/estatisticas/multidominio/ciencia-tecnologia-e-inovacao/9141-pesquisa-de-inovacao.html
- SIDRA: https://sidra.ibge.gov.br/
- API SIDRA: https://apisidra.ibge.gov.br/
