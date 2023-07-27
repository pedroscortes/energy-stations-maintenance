# Energy Stations Maintenance

Este repositório armazena estudos a respeito da manutenção de estações de distribuição de energia elétrica.

Segue, uma pequena descrição do problema:

A substituição de transformadores de distribuição se tornou um problema para as distribuidoras no Brasil, devido a crescente dos preços do equipamento nos últimos anos. Você, como cientista de dados da engenharia corporativa, precisa ajudar a equipe a criar insights para direcionar ações de mitigação desta questão, nas distribuidoras espalhadas por todo o país.

# Planilhas em anexo
Dados do Parque - Dados_Parque
Dados das Substituições - Dados_Substituição
Dados Climáticos - Dados_Climaticos

1- Calcule o Índice de Substituição de transformadores por Unidade de Negócio (UN) e total no ano de 2022.

2 - Calcule o parque de transformadores de distribuição segregando entre rural e urbano para o ano de 2022

3 - Calcule o total de descargas atmosféricas (raios) por Unidade de Negócio para o ano de 2022

*IST(UN) = ∑FALHAS(UN)/∑PARQUE(UN)*

*IST(grupo) = ∑FALHAS(total)/∑PARQUE(total)*

Importante: ∑Parque(UN) em 2022 = ∑quantidade de transformadores em Dez/22 na UN
Ex.: Parque da UN E1 em Maio/22 = ∑quantidade de transformadores em Maio/22

O time de engenharia já informou que a principal causa de substituição de transformadores é a incidencia de descargas atmosféricas (raios) em áreas rurais.
A expectativa dos engenheiros é ter maior previsibilidade e assertividade no direcionamento das ações de manutenção, para prevenção de falhas. Além disso, pretendem traçar metas do índice de substituição paras as Unidades de Negócio.

# Glossário: #
- Dados do Parque: quantidade de transformadores de distribuição em operação, segregados por mês, ano, localidade (urbano e rural), número de fases, tensão, potencia. Importante: a quantidade de transformadores é cumulativa, mês a mês.
- Dados das substituições: informações sobre os transformadores substituídos devido falhas nos equipamentos (queima ou avaria), segregado por localidade, data, situação, fabricante, data de fabricação, fase e potência do equipamento.
- Dados climáticos: histórico de descargas atmosféricas (raios) e chuva por unidade de negócio, mês e ano.
