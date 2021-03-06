# hse_hw3_chromhmm

## Часть 1
В рамках предыдузего ДЗ2 Были использованы данные PANC-1, для ДЗ3 не было достаточных данных.
![alt text](Panc1.png)


Были выбраны данные HepG2.
![alt text](HepG2.png)


### Скачивание файлов 
![alt text](files.png)

### Анализ меток с помощью ChromHMM:
Ссылка на Google Colab: https://colab.research.google.com/drive/16L_5GFkjNJGnarDiQLc0ayrdVGbRCsTp?usp=sharing

Для анализа был создан файл cellmarkfiletable.txt
![alt text](cellmarkfiletable.png)


#### Результатами кода в Google Colab стали:


1) Файлы из папки BinarizedData
2) html webpage_10.html и Hepg2_10_expanded.bed
3) Изображения из папки PictureChromHMM


#### Результаты:


![alt text](PictureChromHMM/EmissionParameters.png)
![alt text](PictureChromHMM/FoldEnrichment.png)
![alt text](PictureChromHMM/RefSeqTES.png)
![alt text](PictureChromHMM/RefSeqTSS.png)
![alt text](PictureChromHMM/TransitionParameters.png)


### UCSC GenomeBrowser 

Были сделаны следующие настройки:

![alt text](Genome/GenomeSettings.png)


Были получены следующие результаты:

![alt text](Genome/Genome1.png)

![alt text](Genome/Genome2.png)


### Анализ данных

Анализируем на основе следующих данных:

![alt text](PictureChromHMM/FoldEnrichment.png)


1) Выявлены цвета статусов

![alt text](results/color.png)


2) Определы статусы

![alt text](results/Results.png)

3) Итог

![alt text](results/ColorName.png)


## Часть 2
Были сделаны следующие настройки

![alt text](Genome/GenomeSettings2.png)

Итог:
![alt text](Genome/Genome3.png)
