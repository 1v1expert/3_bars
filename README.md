# Ближайшие бары
<hr> </hr>

[Здесь](http://data.mos.ru/opendata/7710881420-bary) есть много разных данных, в том числе список московских баров. Его можно скачать в формате json.

Тут реализован скрипт, который рассчитает:

* самый большой бар;
* самый маленький бар;
* самый близкий бар (текущие gps-координаты ввести с клавиатуры).

## Как запустить

Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

Запуск на Linux:

$python3.5 bars.py

    пример ответа скрипта

    > The biggest bar ->                                                                                                                                     
    > Name:  Спорт бар «Красная машина»                                                                                                                      
    > Seats Count:  450                                                                                                                                      
    > Coordinates 55.7011146292467670 37.6382285008039050                                                                                                    
    > The smallest bar - >                                                                                                                                   
    > Name:  БАР. СОКИ                                                                                                                                       
    > Seats Count:  0                                                                                                                                        
    > Coordinates 55.8461447588834330 37.3580592058223000                                                                                                    
    > The closest bar - >                                                                                                                                    
    > Name:  Хилл Фиш                                                                                                                                        
    > Seats Count:  80                                                                                                                                       
    > Coordinates 55.7673510000000000 37.6776210000000000 
