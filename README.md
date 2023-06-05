# hse23_project

## Подготовка 


В геномном браузере UCSC вобъём назание белка, выбра Gencode v43 'dense' и NCBI RefSeq 'pack'

Выберем там самый длинный вариант белка и перейдём на его страницу NCBI во вкладку fasta


фаста: https://www.ncbi.nlm.nih.gov/protein/NP_001982.2?report=fasta


создадим файл с назанием белка в своей папке на сервере при помощи vi и сохраним через :wq

для удобства скопируем себе папки histones и proteomes


исходные файлы лежат на серере в папке amsheynkin/project/


сделаем blastp для всех 11 файлов .faa


![image](https://github.com/Tinver93/hse23_project/assets/115100892/55210610-9f54-441e-93b0-74a75a0b76f9)


аналогично для всех гистонов (можно выбрать произвольный вариант из файло с гистонами)


![image](https://github.com/Tinver93/hse23_project/assets/115100892/6592c322-b2c7-4f8d-83f3-9742d4153bac)



получаем:


![image](https://github.com/Tinver93/hse23_project/assets/115100892/41155186-a835-4f94-8aa1-99afac0279d0)




## Таблицы

Дальше состаим таблички с минимальным e-value для каждого из организмов, сперва с чистыми значениями e-value, потом с логарифмированными
