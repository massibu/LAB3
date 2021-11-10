# РОССИЙСКИЙ УНИВЕРСИТЕТ ДРУЖБЫ НАРОДОВ
## Факультет физико-математических и естественных наук
## Кафедра прикладной информатики и теории вероятностей

**ОТЧЕТ**
 **ПО ЛАБОРАТОРНОЙ РАБОТЕ № 2**
 
 *дисциплина:        Операционные системы*

 Студент:     МАССИБУ ДАВИД ЛЕВИ

 Группа: НПИбд 01-20

 **МОСКВА 2021 г.**
 ### Цель работы :
 Изучить идеологию и применение средств контроля версий.
 ### Ход работы:
 1. Я создал учётную запись на https://github.com
 ![](https://raw.githubusercontent.com/massibu/image/main/image3/1.jpg)

 2. Я настроил систему контроля версий git и добавил SSH keys.
 ![](https://raw.githubusercontent.com/massibu/image/main/image3/2.png)
![](https://raw.githubusercontent.com/massibu/image/main/image3/3.jpg)

 3. Создал структуру каталога лабораторных работ.
 ![](https://raw.githubusercontent.com/massibu/image/main/image3/4.png)

 4. Создал репозиторий на GitHub.
 ![](https://raw.githubusercontent.com/massibu/image/main/image3/5.jpg)

 5. Подключение репозитория к github
 - Мы сначала клонируем репозиторий в каталоге
- Инициализируем системы git: git init
- Создаём заготовку для файла README.md: echo "# lab2" >> README.md git add 
README.md
![](https://raw.githubusercontent.com/massibu/image/main/image3/6.jpg)
- Делаем первый коммит : git commit -m "first commit"/ git branch -M main/ git 
remote add origin git@github.com:massibu/lab2.git
- и выкладываем на github: git push -u origin main.ss
![](https://raw.githubusercontent.com/massibu/image/main/image3/7.jpg)

6. Первичная конфигурация
- Добавил файл лицензии
- Добавил шаблон игнорируемых файлов
- Затем скачал шаблон для с
- Добавил новые файлы
- Выполнил коммит
- Отправил на github

![](https://raw.githubusercontent.com/massibu/image/main/image3/8.png)
![](https://raw.githubusercontent.com/massibu/image/main/image3/9.jpg)

7. Конфигурация git-flow
- Инициализировал git-flow
- Проверил что я на ветке develop
- Создал релиз с версией 1.0.0
- Запишем версию:
- Добавим в индекс:
- Залил релизную ветку в основную ветку
- Отправил данные на github
- Создал релиз на github.
![](https://raw.githubusercontent.com/massibu/image/main/image3/10.jpg)
![](https://raw.githubusercontent.com/massibu/image/main/image3/11.png)
![](https://raw.githubusercontent.com/massibu/image/main/image3/12.png)
![](https://raw.githubusercontent.com/massibu/image/main/image3/13.jpg)
### Вывод:
Я Изучил идеологию и применение средств контроля версий.