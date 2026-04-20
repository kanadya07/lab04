# Отчет по лабораторной работе №4

## Тема работы

Изучение средств непрерывной интеграции.

## Цель работы

Познакомиться с файлами конфигурации для автоматической проверки проекта и
оформить репозиторий по методичке.

## Ход работы

### 1. Подготовка нового репозитория

Сначала я создала репозиторий `lab04` и перенесла туда проект из лабораторной
работы №3.

Команды:

```bash
git clone https://github.com/kanadya07/lab03.git lab04
cd lab04
git remote remove origin
git remote add origin https://github.com/kanadya07/lab04.git
```

### 2. Добавление Travis CI

Потом я создала файл `.travis.yml`, в котором указала команды сборки проекта
для Linux.

Пример команд:

```bash
touch .travis.yml
git add .travis.yml
git commit -m "Добавила Travis CI"
```

### 3. Добавление AppVeyor

После этого я создала файл `appveyor.yml` для Windows.

```bash
touch appveyor.yml
git add appveyor.yml
git commit -m "Добавила AppVeyor"
```

### 4. Проверка проекта локально

Перед оформлением репозитория проект можно собрать локально.

```bash
cmake -S . -B _build
cmake --build _build
```

### 5. Добавление задания и отчета

В конце я добавила `TASK.md` и `REPORT.md`.

```bash
git add TASK.md REPORT.md
git commit -m "Добавила задание и отчет"
git push origin master
```

## Что находится в репозитории

1. `TASK.md`
2. `REPORT.md`
3. `.travis.yml`
4. `appveyor.yml`
5. проект из лабораторной работы №3

## Вывод

Во время выполнения этой лабораторной работы я познакомилась с тем, как
оформляются файлы конфигурации для автоматической проверки проекта.

## Ссылка на репозиторий

https://github.com/kanadya07/lab04
