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


теперь надо разобраться с гистонами

сделаем выравнивание для каждого из файлов гистонов
![image](https://github.com/Tinver93/hse23_project/assets/115100892/748f33a8-6720-4b5b-99b4-7323641b8913)


![image](https://github.com/Tinver93/hse23_project/assets/115100892/d95999f1-fdf4-4075-9d67-36f32adef323)


![image](https://github.com/Tinver93/hse23_project/assets/115100892/56d00923-e0e3-4ac2-a75c-d4b43971eb62)


![image](https://github.com/Tinver93/hse23_project/assets/115100892/9205661d-9719-4506-90cd-ae5e49ac4443)


в целом для каждого гистона варианты очень похожи, поэтому можно считать их просто копиями друг друга и выбирать любые для дальнейших действий.



аналогично делаем blastp  для всех гистонов (создадим файлы гистонов с одним вариантом)


![image](https://github.com/Tinver93/hse23_project/assets/115100892/6592c322-b2c7-4f8d-83f3-9742d4153bac)



получаем:


![image](https://github.com/Tinver93/hse23_project/assets/115100892/41155186-a835-4f94-8aa1-99afac0279d0)




## Таблицы

Дальше состаим таблички с минимальным e-value для каждого из организмов, сперва с чистыми значениями e-value, потом с логарифмированными
