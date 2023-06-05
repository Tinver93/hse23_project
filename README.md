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
![image](https://github.com/Tinver93/hse23_project/assets/115100892/fa541837-8c0e-46ec-8bb5-31de6326726f)


![image](https://github.com/Tinver93/hse23_project/assets/115100892/099dbb25-728f-49fd-97c0-76888d0ebd11)


![image](https://github.com/Tinver93/hse23_project/assets/115100892/99659083-4100-49cb-9f62-e5cd2fcbe8da)


![image](https://github.com/Tinver93/hse23_project/assets/115100892/782cd905-fbb0-4f57-a5c0-75ae7912900c)


в целом для каждого гистона варианты очень похожи, поэтому можно считать их просто копиями друг друга и выбирать любые для дальнейших действий.



аналогично делаем blastp  для всех гистонов (создадим файлы гистонов с одним вариантом)


![image](https://github.com/Tinver93/hse23_project/assets/115100892/6592c322-b2c7-4f8d-83f3-9742d4153bac)



получаем:


![image](https://github.com/Tinver93/hse23_project/assets/115100892/41155186-a835-4f94-8aa1-99afac0279d0)




## Таблицы

Дальше состаим таблички с минимальным e-value для каждого из организмов, сперва с чистыми значениями e-value, потом с логарифмированными

![image](https://github.com/Tinver93/hse23_project/assets/115100892/07571415-81fa-4ae3-b865-bf5677238c6d)

![image](https://github.com/Tinver93/hse23_project/assets/115100892/dbb46fcc-4935-438b-9e15-9e2ecdf42fcf)


## Тепловая карта

![image](https://github.com/Tinver93/hse23_project/assets/115100892/c294ad4f-de82-4e87-bfd6-0d43bc44aa7c)


