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


Vale ressaltar que os microdados do OpenDatasus apresentam uma certa defasagem em relação ao que é publicado no LocalizaSUS.
Outras considerações estão dentro do script.
