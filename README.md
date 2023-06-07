# hse23_project


Ссылка на колаб: https://colab.research.google.com/drive/1Z0h03bNzdQBmyhZXYgOwIIJMWZ0iZGXE?usp=sharing


# EZH1


Белок поликомбовой группы (PcG). Каталитическая субъединица комплекса PRC2/EED-EZH1, которая метилирует "Lys-27" гистона H3, приводя к подавлению транскрипции пораженного гена-мишени.

экспрессия

![image](https://github.com/Tinver93/hse23_project/assets/115100892/7711ac3d-a90f-49c4-b34d-a372949ce3bb)


картинка комплекса PRC1

![image](https://github.com/Tinver93/hse23_project/assets/115100892/2f662ee3-e396-4b40-82ce-d5f9583cf60b)


## Подготовка 


В геномном браузере UCSC вобъём назание белка, выбра Gencode v43 'dense' и NCBI RefSeq 'pack'

Выберем там самый длинный вариант белка и перейдём на его страницу NCBI во вкладку fasta


фаста: https://www.ncbi.nlm.nih.gov/protein/NP_001982.2?report=fasta


создадим файл с назанием белка в своей папке на сервере при помощи vi и сохраним через :wq

для удобства скопируем себе папки histones и proteomes


исходные файлы лежат на серере в папке amsheynkin/project/ (порт 5222)


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

## Вывод

Исходя из тепловой карты, можно сказать, что перые признаки белка EZH1 пояляются у дрожжей (yeast)

А сосем явно виден он становится уже у мушки-дрозофилы
