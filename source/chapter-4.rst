Розділ 4. Інструкції для розробників щодо роботи з відкритими даними про регуляторні акти
############################################################

4.1. Валідація даних
**************************************************
Валідація даних у таблицях list і plan визначається наступними умовами й способами (Таблиці 7-8).

	.. csv-table:: Таблиця 7. Валідація даних таблиці list
		:header-rows: 1
		:file: _assets/listValidation.csv


	.. csv-table:: Таблиця 8. Валідація даних таблиці plan
		:header-rows: 1
		:file: _assets/planValidation.csv


4.2. Модель даних та RDF-серіалізації набору
**************************************************

Модель даних для переліку регуляторних актів включає п’ять класів: регуляторний акт (RegulatoryAct), відстеження результативності регуляторного акта (Evaluation), звіт про відстеження результативності (Report), регуляторний орган (RegulatoryAgency), нормативно-правовий акт, яким було ухвалено регуляторний акт (LegalAct).

	.. centered:: *Рисунок 1 - UML-модель даних переліку регуляторних даних*

	.. image:: _assets/listUML.png
		:alt: Рисунок 1 - UML-модель даних переліку регуляторних даних
		:width: 600 px
		:align: center


Для плану підготовки регуляторних актів: проект регуляторного акту (Project), розробник (Creator), регуляторний акт (RegulatoryAct), регуляторний орган (RegulatoryAgency), нормативно-правовий акт, яким буде ухвалено регуляторний акт (LegalAct).

	.. centered:: *Рисунок 2 - UML-модель даних плану підготовки регуляторних актів*

	.. image:: _assets/planUML.png
		:alt: Рисунок 2 - UML-модель даних плану підготовки регуляторних актів
		:width: 600 px
		:align: center


Для синтаксичної прив’язки використані словники `Dublin Core Terms <http://dublincore.org/>`_, `FOAF <http://xmlns.com/foaf/spec/>`_, `Schema <https://schema.org/>`_, `The Organization Ontology <https://www.w3.org/TR/vocab-org/>`_, `SKOS <https://www.w3.org/TR/swbp-skos-core-spec/>`_, `RDF Schema <https://www.w3.org/TR/rdf-schema/>`_ (Таблиця 9-11).


	.. csv-table:: Таблиця 9 - Використання основних словників
		:header-rows: 1

		Назва словника,Префікс,Простір імен
		Dublin Core Terms,dct,http://purl.org/dc/terms/
		FOAF,foaf,http://xmlns.com/foaf/0.1/
		Schema,schema,http://schema.org/
		The Organization Ontology,org,http://www.w3.org/ns/org#
		SKOS,skos,http://www.w3.org/2004/02/skos/core#
		RDF Schema,rdfs,http://www.w3.org/2000/01/rdf-schema#


	.. csv-table:: Таблиця 10 - Прив’язка моделі даних переліку регуляторних актів до існуючого синтаксису словників
		:file: _assets/listMapping.csv
		:header-rows: 1


	.. csv-table:: Таблиця 11 - Прив’язка моделі даних плану підготовки регуляторних актів до існуючого синтаксису словників
		:file: _assets/planMapping.csv
		:header-rows: 1
