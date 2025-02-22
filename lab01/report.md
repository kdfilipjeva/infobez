---
## Front matter
title: "Отчет о выполнении лабораторной работы"
subtitle: "Лабораторная работа №1"
author: "Филипьева Ксения Дмитриевна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.3
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Выполнить первичную установку операционной системы.

# Задание

Установить и настроить операционную систему Rocky.

# Выполнение лабораторной работы

Создание виртуальной машины (рис. [-@fig:1]).

![виртуальная машина](image/klab1s1.png){#fig:1 width=100%}

Созданная виртуальная машина (рис. [-@fig:2]).

![виртуальная машина](image/klab1s2.png){#fig:2 width=100%}

Выбор языка установки (рис. [-@fig:3]).

![процесс установки](image/klab1s3.png){#fig:3 width=100%}

Дополнительные параметры установки (рис. [-@fig:4]).

![процесс установки](image/klab1s4.png){#fig:4 width=100%}

Выбор предустановленных программ (рис. [-@fig:5]).

![процесс установки](image/klab1s5.png){#fig:5 width=100%}

Выбор места установки (рис. [-@fig:6]).

![процесс установки](image/klab1s6.png){#fig:6 width=100%}

Установка пароля для корневого пользователя (рис. [-@fig:7]).

![процесс установки](image/klab1s7.png){#fig:7 width=100%}

Создание основного пользователя (рис. [-@fig:8]).

![процесс установки](image/klab1s8.png){#fig:8 width=100%}

Финальная установка (рис. [-@fig:9]).

![наконец-то установим](image/klab1s9.png){#fig:9 width=100%}

Команда dmesg (рис. [-@fig:10]).

![выполнение заданий](image/klab1s10.png){#fig:10 width=100%}

Команда dmesg | less (рис. [-@fig:11]).

![выполнение заданий](image/klab1s11.png){#fig:11 width=100%}

Версия линукса (рис. [-@fig:12]).

![выполнение заданий](image/klab1s12.png){#fig:12 width=100%}

Частота процессора (рис. [-@fig:13]).

![выполнение заданий](image/klab1s13.png){#fig:13 width=100%}

Модель процессора (рис. [-@fig:14]).

![выполнение заданий](image/klab1s14.png){#fig:14 width=100%}

Свободная память (рис. [-@fig:15]).

![выполнение заданий](image/klab1s15.png){#fig:15 width=100%}

Гипервизоры (рис. [-@fig:16]).

![выполнение заданий](image/klab1s16.png){#fig:16 width=100%}

Файловая система (рис. [-@fig:17]).

![выполнение заданий](image/klab1s17.png){#fig:17 width=100%}

# Выводы

Мы провели первичную настройку операционной системы Rocky на виртуальной машине.

# Ответы на вопросы

### 1. Какую информацию содержит учётная запись пользователя?

Учётная запись пользователя в Linux содержит следующую информацию:
- **Имя пользователя** (login): уникальное имя, под которым пользователь входит в систему.
- **Пароль**: защищает доступ к учётной записи.
- **UID (User ID)**: уникальный идентификатор пользователя.
- **GID (Group ID)**: идентификатор группы, к которой принадлежит пользователь по умолчанию.
- **Домашний каталог**: каталог, который становится текущим при входе пользователя в систему.
- **Командная оболочка**: указывает на используемую командную оболочку.

### 2. Укажите команды терминала и приведите примеры:

#### Для получения справки по команде
```bash
man [команда]
```
Пример: `man ls`

#### Для перемещения по файловой системе
```bash
cd [путь]
```
Пример: `cd /home/user`

#### Для просмотра содержимого каталога
```bash
ls [опции] [путь]
```
Пример: `ls -l /home/user`

#### Для определения объёма каталога
```bash
du -sh [путь]
```
Пример: `du -sh /home/user/Documents`

#### Для создания/удаления каталогов/файлов:
   - Создать каталог:
     ```bash 
     mkdir [имя_каталога]
     ```
   Пример: `mkdir mydir`
   - Удалить пустой каталог:
     ```bash 
     rmdir [имя_каталога]
     ```
   Пример: `rmdir mydir`
   - Удалить файл или не пустой каталог с подтверждением:
     ```bash 
     rm -i [-r] [имя_файла/каталога]
     ```
   Пример для файла: `rm file.txt`, для не пустого каталога — `-r`: `rm -ri mydir`

#### Для задания определённых прав на файл/каталог:
```bash 
chmod ugo[+-=][права] filename  
# u — user, g — group, o — others; + добавляет права, – удаляет права; = устанавливает указанные права.

# Например,
chmod u+x filename # Добавляет право на выполнение владельцу файла filename

# Используя числовые коды прав доступа (напр., chmod 755):
chmod 755 filename # Права rwx для владельца и rx для остальных групп и пользователей.
```

#### Для просмотра истории команд:
```bash 
history  
# Показывает список последних введенных команд с их номерами.

!n  
# Повторяет выполнение n-й команды из истории. Например !5 повторит пятую команду из списка history.

!!  
# Повторяет последнюю введенную команду.

Ctrl+R  
# Поиск по истории ввода через обратный поиск.
```

### 3. Что такое файловая система? Приведите примеры с краткой характеристикой

Файловая система — это способ организации данных на носителях информации (жестких дисках, SSD и т.д.), позволяющий операционной системе эффективно управлять данными. Она обеспечивает структурированное хранение файлов и папок.

**Примеры файловых систем в Linux с их характеристиками:** 

| ФС        | Характеристика                                                                                       |
|-----------|-----------------------------------------------------------------------------------------------------|
| Ext2      | Старая версия без журналирования; поддерживает до 2 ТБ данных                                        |
| Ext3      | Включает журналирование для восстановления после сбоя                                                |
| Ext4      | Популярная современная ФС с поддержкой до 1 Эксабайта                                               |
| JFS       | Быстрое восстановление после сбоя питания; низкое потребление процессорных ресурсов                  |
| XFS       | Высокопроизводительная; хорошо работает с большими файлами                                           |
| Btrfs      | Поддерживает контроль целостности данных и snapshot'и                                                |

### 4. Как посмотреть, какие файловые системы подмонтированы в ОС?

Для того чтобы посмотреть какие файловые системы подмонтированы в ОС Linux можно использовать следующие методы:

1. Использовать утилиту mount без аргументов:

    ```bash 
    mount    
    ```

2. Просмотреть вывод `/proc/mounts` или `/etc/fstab`:

    ```plaintext 
    cat /proc/mounts   
    cat /etc/fstab    
    ```

3. Команда df также может дать полезную информацию о монтированных разделах:

    ```plaintext 
    df   
    ```

### 5. Как удалить зависший процесс

Чтобы удалить зависший процесс необходимо его остановить или завершить принудительно через терминал:

1. Определите PID процесса при помощи ps или top/pstree/h-top/tophtop:

   ```plaintext 
   ps aux   
   top    
   pstree   
   htop    
   ```

2.a Если процесс можно остановить мягко (`SIGTERM`):

       ```plaintext     
       kill PID_processa      
       ```

2.b Если процесс не реагирует (`SIGKILL`):

       ```plaintext     
       killall process_name      
       killall SIGKILL PID_processa      
       pkill process_name      
       pkill SIGKILL PID_processa      			
