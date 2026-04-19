# lab04

Лабораторная работа N4 по курсу "Технологии и методы программирования".

## Содержимое

- `TASK.md` - текст задания и домашней работы
- `REPORT.md` - отчет
- `.travis.yml` - конфигурация Travis CI
- `appveyor.yml` - конфигурация AppVeyor
- `formatter_lib` - статическая библиотека `formatter`
- `formatter_ex_lib` - статическая библиотека `formatter_ex`
- `solver_lib` - библиотека решения квадратного уравнения
- `hello_world_application` - пример использования `formatter_ex`
- `solver_application` - приложение с использованием `formatter_ex` и `solver`

## Локальная сборка

```bash
cmake -S . -B _build
cmake --build _build
```
