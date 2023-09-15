---
layout: page-with-side-nav
title: Documentatie StUF
folder_files:
  - title: Gebeurtenisbeschrijving BAG 2018 versie 1.0.2.pdf
    path: documenten\Gebeurtenisbeschrijving_BAG_2018_versie_1.0.2.pdf
    group: 310
    versie: 2018
    status: Definitief
    omschrijving: 
    datum: 20181023
  - title: Koppelvlak BAG.pdf 
    path: documenten\Koppelvlak_BAG.pdf
    group: 310
    versie: 1.01
    status: Definitief
    omschrijving: 
    datum: 20160218
  - title: Koppelvlak BAG (met renvooi).pdf
    path: documenten\Koppelvlak_BAG_(met_renvooi).pdf
    group: 310
    versie: 1.01
    status: Definitief
    omschrijving: 
    datum: 20160218
  - title: Processenhandboek BAG 2013.pdf 
    path: documenten\Processenhandboek_BAG_2013.pdf
    group: 310
    versie: 2013
    status: Definitief
    omschrijving: 
    datum: 201311
  - title: Processenhandboek v.2009
    path: documenten\Processenhandboek_v.2009.pdf
    group: 310
    versie: 2009
    status: 
    omschrijving: 
    datum: 20090731
  - title: Standaard testset BAG WOZ 1.0
    path: documenten\Standaard_testset_BAG_WOZ_1.0.zip
    group: 310
    versie: 1.0
    status: Onbekend
    omschrijving: 
    datum: 20130904
---

# Documentatie

## BAG 3.10

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th><th>Versiedatum</th>
		</tr>
	</thead>
	<tbody>
		{% for i in page.folder_files %}
			{% if i.group == 310 %} 
				<tr>
					<td>
					  <a href="{{ i.path | base_url }}">
						{{ i.title }}
					  </a>
					</td>
					<td>{{ i.versie }}</td>
					<td>{{ i.status }}</td>
					<td>{{ i.omschrijving }}</td>
					<td>{{ i.datum }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>
