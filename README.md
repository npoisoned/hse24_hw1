# hse24_hw1
https://colab.research.google.com/drive/14VLaa3MqGjFNpqnqn0HGVMSV13AgjrL7?usp=sharing

В отличие от секвенирования ДНК или РНК, бисульфитное секвенирование приводит к изменениям в соотношении нуклеотидов в ДНК. Это происходит за счет конверсии цитозина в тимин под воздействием бисульфита, что делает распределение цитозина и гуанина неравномерным в последовательности. Таким образом, после обработки ДНК бисульфитом количество цитозинов становится меньше, чем количество гуанинов из-за химических изменений в структуре нуклеотидов.

![image](https://github.com/npoisoned/hse24_hw1/assets/90446751/3e3556ff-6c9c-4fc6-b5ac-a0571e061595)

![image](https://github.com/npoisoned/hse24_hw1/assets/90446751/02f88f27-be1f-45c7-91c9-969c1adc2bf1)

![image](https://github.com/npoisoned/hse24_hw1/assets/90446751/64b06f9e-ad0a-4bd8-819e-0524cdd12e2a)

![image](https://github.com/npoisoned/hse24_hw1/assets/90446751/0bc34e80-9eef-48fa-a1ef-93f6d7d8970b)

![image](https://github.com/npoisoned/hse24_hw1/assets/90446751/8d895d14-a166-4769-bfcf-c2acc76d7645)

![image](https://github.com/npoisoned/hse24_hw1/assets/90446751/a5d6530f-88a2-461f-9c87-b073a7e604e9)

![image](https://github.com/npoisoned/hse24_hw1/assets/90446751/ef8d2ff9-9517-4a02-99be-358da545026d)

### Сводная таблица с числом ридов, закартированных на участки, и процентом дупликации.

| SRA accession | Stage    | Риды на 11347700-11367700 | Риды на 40185800-40195800 | Процент дупликаций |
| - | - |---------------------------|---------------------------|--------------------|
| SRR5836473 | 8 cell   | 551                       | 194                       | 81.72%             |
| SRR3824222 | Epiblast | 1344                      | 565                       | 97.09%             |
| SRR5836475 | ICM      | 797                       | 274                       | 90.93%             |

### Гистограммы с распределением цитозинов по хромосоме
Изучение графиков позволяет отследить изменение частоты и уровня метилирования цитозинов на трех ключевых стадиях эмбрионального развития мыши.

На стадии 8-клеточного эмбриогенеза наблюдается отсутствие метилирования в 50% случаев, что говорит о высокой изменчивости метилирования на данной стадии развития.

На стадии внутриклеточной массы (ICM) проявление метилирования еще реже, что указывает на низкую частоту этого биохимического процесса в этом контексте эмбрионального развития.

В эпибласте, следующей стадии развития, наблюдается резкое увеличение уровня метилирования, что подчеркивает изменчивость эпигенетических маркеров на разных этапах эмбрионального развития мыши.

![image](https://github.com/npoisoned/hse24_hw1/assets/90446751/6993045c-5796-4f35-a596-6127a89d863d)

![image](https://github.com/npoisoned/hse24_hw1/assets/90446751/d5b1d324-ffa5-4f84-a093-a03bbac38331)

![image](https://github.com/npoisoned/hse24_hw1/assets/90446751/335f74cb-eeb6-4d91-88cc-9a4f04009c15)

## M-bias  
Изменения в уровне метилирования наблюдаются при переходе между различными этапами эмбрионального развития. На первой стадии, 8-клеточном этапе, присутствует высокий уровень метилирования, около 42%. Однако, когда происходит переход ко второй стадии - внутриклеточной массе (ICM), процент метилирования значительно снижается, до чуть более 20%. На стадии эпибласта происходит резкое увеличение уровня метилирования, достигая более высокого уровня.

Эти изменения могут быть поняты как результат дифференцировки тканей в процессе эмбрионального развития. Низкий уровень метилирования на второй стадии (ICM) может быть связан с регуляцией генов, которая поддерживает пластичность клеток. На стадии эпибласта, вероятно, активируются эпигенетические процессы, сопутствующие дифференцировке, что приводит к резкому увеличению уровня метилирования до более стабильного и высокого уровня.
### 8cell
![image](https://github.com/npoisoned/hse24_hw1/assets/90446751/1345df3d-e859-4299-b499-7b5d5ce4b9ed)

### epiblast
![image](https://github.com/npoisoned/hse24_hw1/assets/90446751/736c3d31-cfc8-4694-9996-8684d27848ca)
### icm
![image](https://github.com/npoisoned/hse24_hw1/assets/90446751/02003103-a0fd-4280-a98a-085f1dc23ccb)


## Визуализация метилирования и покрытия

Процент метилирования зависит от стадии эмбрионального развития (8cell, epiblast, icm). Сначала покрытие и метилирование резко уменьшаются на стадии icm, а на стадии epiblast увеличиваются.
![image](https://github.com/npoisoned/hse24_hw1/assets/90446751/5e75e7aa-272b-4354-b51c-0f4a4014b1f9)


