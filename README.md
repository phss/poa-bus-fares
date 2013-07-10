# poa-bus-fares

This project aims to provide some analysis and visualization of Porto Alegre's bus fares and companies.

A few questions I would like to explore are:

* What's the market/passenger share between the bus companies?
* Did the fare rise proportionally to economic growth/inflation?
* What's the passenger revenue in the last 10 years?
* Has the quality and security of the bus service improved over the last 10 years?
* Does the number of cars have an impact of the bus service/revenue?

It's inspired by the following blog, which provides a visualization of São Paulo's transport system: http://www.oeco.org.br/datacidades/27318-raio-x-do-sistema-de-transporte-municipal-de-sao-paulo

## Sources

The raw data was extracted and stored under 'data/raw'.

The following organizations were used as sources of data:

* EPTC: http://www2.portoalegre.rs.gov.br/eptc/default.php?p_secao=155
* Fundação Getulio Vargas (FGV): http://portalibre.fgv.br
* Portal Brasil: http://www.portalbrasil.net

Individual raw data sources:

| Source | Data | Link | Extraction Date |
| ------ | ---- | ---- | ----------------|
| EPTC | Passengers transported by bus | [passageiros_transportados_2012.pdf](http://lproweb.procempa.com.br/pmpa/prefpoa/eptc/usu_doc/passageiros_transportados_2012.pdf) | 2013-07-04 |
| EPTC | 'Equivalent' passengers transported by bus | [passageiros_equivalentes_2012.pdf](http://lproweb.procempa.com.br/pmpa/prefpoa/eptc/usu_doc/passageiros_equivalentes_2012.pdf) | 2013-07-08 |
| EPTC | KMs travelled | [media_mensal_rodagem_2012.pdf](http://lproweb.procempa.com.br/pmpa/prefpoa/eptc/usu_doc/media_mensal_rodagem_2012.pdf) | 2013-07-08 |
| EPTC | Bus fare increases | [evolucao_tarifaria_2012.pdf](http://lproweb.procempa.com.br/pmpa/prefpoa/eptc/usu_doc/evolucao_tarifaria_2012.pdf) | 2013-07-08 |
| EPTC | Robberies in buses | [media_mensal_indice_assaltos_2012.pdf](http://lproweb.procempa.com.br/pmpa/prefpoa/eptc/usu_doc/media_mensal_indice_assaltos_2012.pdf) | 2013-07-08 |
| EPTC | Service complaints | [reclamacoes_2012.pdf](http://lproweb.procempa.com.br/pmpa/prefpoa/eptc/usu_doc/reclamacoes_2012.pdf)  | 2013-07-08 |
| EPTC | Bus trips completed | [indice_cumprimento_viagens_icv_2012.pdf](http://lproweb.procempa.com.br/pmpa/prefpoa/eptc/usu_doc/indice_cumprimento_viagens_icv_2012.pdf) | 2013-07-08 |
| EPTC | Failed maintenance checks | [vistoria_2012.pdf](http://lproweb.procempa.com.br/pmpa/prefpoa/eptc/usu_doc/vistoria_2012.pdf) | 2013-07-08 |
| EPTC | Fleet age | [idade_frota_2012.pdf](http://lproweb.procempa.com.br/pmpa/prefpoa/eptc/usu_doc/idade_frota_2012.pdf) | 2013-07-08 |
| FGV/Portal Brasil | Inflation (IGP-DI) | [igp.html](http://www.portalbrasil.net/igp.htm) | 2013-07-09 |

