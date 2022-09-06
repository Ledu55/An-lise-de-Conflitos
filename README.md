# Dashboard - Acompanhamento de Conflitos 

---

Acesse o Dashboard [Aqui][Dashboard]

# 1.0 Contexto

O setor de Recursos Humanos da empresa EverestGroup deseja identificar os fatores que influenciam no 
surgimento de conflitos dentro da organização e monitorar os conflitos para evitar que surjam
novos gatilhos de conflito. Para isso, foi solicitado uma ferramenta que permita a exploração e
acompanhamento dos dados fornecidos.

# 2.0 A Solução

A solução aplicada neste projeto foi uma visualização de dados em formato de Dashboard para
permitir exploração e visualização dinâmica.

## 2.1 Fonte de Dados

Os dados utilizados nesse projeto foram extraídos do site [DataWorld][dataworld].

## 2.2 Análise de Variáveis 
Para entender os dados disponíveis e organiza-los de forma lógica foi criado um mapa de atributos
onde as variáveis são categorizadas e agrupadas. É possível também já identificar as variáveis que
podem ser candidatas para se tornar filtros de seleção, onde dispor nas abas do dashboard e quais
novas variáveis podem ser criadas.


![Variáveis](https://github.com/Ledu55/An-lise-de-Conflitos/blob/master/Imagens/Análise%20de%20Variáveis.jpg)

## 2.3 Engenharia de variáveis

Além da criação das variáveis indicadas no mapa de atributos, se fez necessário a criação de uma
nova tabela com dados Fictícios de funcionários e colunas com o preenchimento de regras 
relacionadas às variáveis já existentes.

Todo o processo de criação das variáveis e da nova tabela pode ser visualizado [aqui][jupyter] 
por meio de um jupyter notebook.

## 2.4 Relacionamento

Na nova tabela criada foi copiada a variável Id do funcionário e com ela foi possivel criar o
relacionamento de 1:1 entre as tabelas no Powerbi.

## 3.0 Resultado





[Dashboard]: https://app.powerbi.com/view?r=eyJrIjoiOWRhNWRjZjktYTMzZi00YjUwLWI5OTMtYzBlODA3ODM5YTFjIiwidCI6IjI1ZDM2M2EyLTRjNzktNDRlNy05N2I3LWVkZjgxZGY3ZTYwOSJ9&pageName=ReportSection
[dataworld]: https://data.world/markbradbourne/rwfd-real-world-fake-data-season-2/workspace/file?filename=HR_Attrition.csv
[jupyter]: https://github.com/Ledu55/An-lise-de-Conflitos/blob/master/tratamento_dados.ipynb
