# Base de Vacinas Covid-19 do OpenDatasus

Esse script gera uma base para análise dos dados de vacinação contra a Covid-19. O formato da base já vem perfeito para ferramentas de BI.
É possível identificar pessoas com o esquema de vacinação atrasado.

Nesse sentido, segue o Dicionário da coluna "vacina_descricao_dose_2":**

---
**0** : *Indivíduos com segunda dose atrasada*

**1** : *Indivíduos com segunda dose já aplicada*

**2** : *Indivíduos que receberam vacina de dose única*

**8** : *Indivíduos com segunda dose já aplicada, porém sem correspondência de primeira dose na base*

**9** : *Indivíduos no intervalo entre doses*

---


Vale ressaltar que os microdados do OpenDatasus apresentam uma certa defasagem em relação ao que é publicado no LocalizaSUS. Além disso, em outra consideração importante, a célula #7 contém os nomes das vacinas que são colocados no sistema. Essa lista foi feita no dia 17/06, e novos nomes podem ter sido adicionados desde então. Por isso temos um script neste repositório que serve para extrair os nomes de vacinas no sistema, e pode ser verificado por cada usuário.

No link a seguir estão os arquivos com os microdados:
https://opendatasus.saude.gov.br/dataset/covid-19-vacinacao

Outras considerações estão dentro do script.
