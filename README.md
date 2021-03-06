# Курс "Нейронные сети и глубокое обучение" Самарского университета  
Лектор Артем Владимирович Никоноров, д.т.н., artniko@gmail.com  
Ассистент Виктория Витальевна Евдокимова, аспирант Самарского университета, data.science.sbj@gmail.com


Курс основывается на предыдущих более обзорных лекциях и туториалах по глубокому обучению и его приложениях, в частности, вот [небольшая обзорная лекция](https://youtu.be/Gpq1PFUee88) в Кавказском Математическом Центре. Также во многом этот курс является адаптацией известнейшего курса http://cs231n.stanford.edu/  

## 6235 - Зачет и экзамен (январь 2021).  

Зачет по лабораторным 25.12.20 с 11.30, подробности в чате в личном кабинете.  
Консультация в 10-00 25 января 2021 в zoom, ссылка будет позднее.  
Экзамен 26 января 2021.  

[Вопросы.](https://github.com/da0c/DL_Course_SamU/blob/master/Exams_2021/DL_Exam.pdf)   
[Примеры задач.](https://github.com/da0c/DL_Course_SamU/blob/master/Exams_2021/MidTerm.pdf)   

## График проведения курса 2020-2021.
**Лекционный курс закончен, видеозаписи 2020-21 годов приведены ниже.**  

Телеграмм группа курса:
https://t.me/DL_SamU_2020

Лекции раз в две недели по понедельникам.
Продолжительность лекции два астрономических часа.

[Видеозапись первой лекции](https://www.youtube.com/watch?v=BKG1wEATYOU)


## Предварительный лекционный план.

План может меняться в процессе курса.  

**Лекция 1. Классификация, основанная на данных**   
[Видеозапись лекции 14.09.2020](https://www.youtube.com/watch?v=BKG1wEATYOU)  
Введение в курс.  
Задача классификации изображений.  
Подходы основанные на данных.  
Линейная классификация и knn-классификатор.  
  
[Презентация к лекции 1](https://github.com/da0c/DL_Course_SamU/blob/master/lections/Lection_1_ImClass.pdf)  

**Лекция 2. Функции потерь и оптимизация.**  
[Видеозапись лекции 28.09.2020](https://www.youtube.com/watch?v=3uOIqTNclPA)  
Мультиклассовый SVM и его функция потерь.  
Софтмакс и мультимодальная логистическая регрессия.  
Оптимизация функции потерь.  
Стохастический градиентный спуск (SGD).  
  
[Презентация к лекции 2](https://github.com/da0c/DL_Course_SamU/blob/master/lections/Lection_1_SGD.pdf)  

**Лекция 3. Нейронные сети и обратное распространение ошибки.**  
[Видеозапись лекции 28.09.2020](https://www.youtube.com/watch?v=3uOIqTNclPA)  
Классификация с точки зрения нейронной сети.  
Многослойный перцептрон.  
Представление сети в виде вычислительного графа.
Алгоритм обратного распространения ошибки на вычислительном графе.  
  
[Презентация к лекции 3](https://github.com/da0c/DL_Course_SamU/blob/master/lections/Lection_1_BP.pdf)  

**Лекция 4. Сверточные сети (СНС).**  
История.  
Основные операции СНС.  
Применение СНС вне задач машинного зрения.  

[Презентация к лекции 4](https://github.com/da0c/DL_Course_SamU/blob/master/lections/Lecture_4_CNN1.pdf)

**Лекция 5. Инструментарий глубокого обучения.**  
[Видеозапись лекции 30.10.2020](https://www.youtube.com/watch?v=E0F11tV92sU&feature=youtu.be)  
CPU vs GPU vs TPU.  
Пакеты глубокого обучения, Tensorflow, Keras и другие.  
Вычислительные графы СНС.  



**Лекция 6. Обучение СНС, часть 1.**  

[Видеозапись лекции 09.11.2020](https://youtu.be/0pHAWXmDnIM)  

Активационные функции, обработка данных сетью.  
Пакетная нормализация и другие трюки.  
Transfer learning.

[Презентация к лекции 6](https://github.com/da0c/DL_Course_SamU/blob/master/lections/lecture_6_Training1.pdf)  

**Лекция 7. Обучение СНС, часть 2.**  

[Видеозапись лекции 23.11.2020](https://youtu.be/1ypE6fz5zXo)  

Политики обновления гиперпараметров.  
Тюнинг процесса обучения.
Аугментация данных.  

[Презентация к лекции 7](https://github.com/da0c/DL_Course_SamU/blob/master/lections/lecture_7_Training2.pdf)  

**Лекция 8. Архитектуры СНС**  

[Видеозапись лекции 07.12.2020](https://youtu.be/07AcZgtoipc)  

Базовые архитектуры - AlexNet, VGG, GoogleNet, ResNet, UNET и другие.  

[Презентация к лекции 8](https://github.com/da0c/DL_Course_SamU/blob/master/lections/lecture_8_Arch.pdf)  

**Лекция 9. Генеративные и рекуррентные модели**  

[Видеозапись лекции 23.12.2020](https://youtu.be/XWd6XYPVYdM)  

1. RNN/LSTM.  
Механизм attention.
Обработка естественного языка.

[Презентация к лекции 9.1](https://github.com/da0c/DL_Course_SamU/blob/master/lections/lecture_9_1.pdf)  

2. GAN сети.

[Презентация к лекции 9.2](https://github.com/da0c/DL_Course_SamU/blob/master/lections/lecture_9_2.pdf)  

3. Детектирование и сегментация.

[Презентация к лекции 9.3](https://github.com/da0c/DL_Course_SamU/blob/master/lections/lecture_9_3.pdf)  


**Лекция 10. Нейростевые модели и исуксственный интеллект**  

[Видеозапись лекции 10, 18.01.2021](https://youtu.be/409okL3L6CY)  


## План лабораторных работ.

План может меняться в процессе курса.  

**Л.Р. 1**  
kNN, многоклассовый SVM, SoftMax.  
[Материалы к лабораторной](https://github.com/da0c/DL_Course_SamU/blob/master/lab_1-2/assignment1.ipynb).

**Л.Р. 2**  
Двухслойная сеть.  
[Материалы к лабораторной](https://github.com/da0c/DL_Course_SamU/blob/master/lab_1-2/assignment2.ipynb).

**Л.Р. 3**  
Многослойный перцептрон, обратное распространение ошибки, сверточные сети.   
[Материалы к лабораторной](https://github.com/da0c/DL_Course_SamU/blob/master/lab_3/assignment3.ipynb).   

**Л.Р. 4**  
Использование библиотеки Tensorflow для обучения СНС.  
[Материалы к лабораторной](https://github.com/da0c/DL_Course_SamU/blob/master/lab_4/assignment4.ipynb).  

**Л.Р. 5**  
Решение прикладной задачи с применением СНС.

Задание на Л.Р. 5: 
1) Определите задачу.
2) Предложите ее решение на основе СНС.
3) Реализуйте предложенное решение с использованием библиотеки глубокого обучения (например, Tensorflow). 
4) Опишите результаты работы в виде статьи по шаблону конференции [ИТНТ](http://itnt-conf.org/index.php/materialy/shablony). 


Интересные задачи можно найти в сборниках следующих конференций:  
[CVPR: IEEE Conference on Computer Vision and Pattern Recognition](https://openaccess.thecvf.com/CVPR2019)  
[ICCV: International Conference on Computer Vision](https://openaccess.thecvf.com/ICCV2019)  
[ECCV: European Conference on Computer Vision](https://openaccess.thecvf.com/ECCV2018)  
или на сайте [Kaggle](https://www.kaggle.com/) . 



## Литература и дополнительные источнки  

1. Отличная книга на русском по глубокому обучению -  
[С. И. Николенко, А. Кадурин, Е. В. Архангельская, Глубокое обучение. Погружение в мир нейронных сетей. 2018](https://www.ozon.ru/context/detail/id/154415719/)  
2. Отличная книга по техническим аспектам реализации на Python -  
[Шолле Франсуа, Глубокое обучение на Python](https://www.ozon.ru/context/detail/id/145615583/)  

3. [Лекционный курс К.В. Воронцова по машинному обучению](http://www.machinelearning.ru/wiki/index.php?title=%D0%9C%D0%B0%D1%88%D0%B8%D0%BD%D0%BD%D0%BE%D0%B5_%D0%BE%D0%B1%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B5_%28%D0%BA%D1%83%D1%80%D1%81_%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D0%B9%2C_%D0%9A.%D0%92.%D0%92%D0%BE%D1%80%D0%BE%D0%BD%D1%86%D0%BE%D0%B2%29).
4. [Видеолекция академика Ю.И. Журавлева](https://www.youtube.com/watch?v=R3CMqrrIWOk) об истоках машинного обучения в СССР и о сочетании эвристики и науки в распознавании образов.  
5. Видеолекции С.И. Николенко по GAN сетям [1](https://www.youtube.com/watch?v=SlJgPIOlpiI), [2](https://www.youtube.com/watch?v=w38m5mTrG_M&t=1147s).
Хорошая проерка ваших знаний, на выходе из настоящего курса вы полностью понимать то, что говорится в этих лекциях по GAN.  





