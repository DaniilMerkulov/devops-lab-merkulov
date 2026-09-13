University: [ITMO University](https://itmo.ru/ru/)
Faculty: [FICT](https://fict.itmo.ru)
Course: [Введение в веб технологии]
Year: 2025/2026
Group: U4125
Author: Меркулов Даниил
Lab: Lab0
Date of create: 13.09.2026
Date of finished: [будет указано после защиты]

## Цель работы
Научиться создавать репозитории, настраивать рабочее окружение и изучать основы работы с Git и GitHub.

## Ход выполнения работы

1. Создан аккаунт на GitHub, сгенерирован SSH-ключ (`ssh-keygen -t ed25519`) и добавлен в настройки GitHub для безопасного подключения без пароля.
2. Создан репозиторий `devops-lab-merkulov` на GitHub.
3. Репозиторий склонирован на локальный компьютер командой `git clone`.
4. Создан файл `README.md` с описанием проекта и планом изучения DevOps.
5. Создан файл `.gitignore` со стандартными исключениями для macOS.
6. Создана и активирована ветка `develop` (`git checkout -b develop`).
7. Создан файл `CONTRIBUTING.md` с правилами участия в проекте.
8. Изменения зафиксированы командой `git commit -m "Initial project setup"` и отправлены на GitHub (`git push`).
9. Создан Pull Request из ветки `develop` в `main`.
10. Pull Request смёржен в `main`, ветка `develop` удалена (и на GitHub, и локально).

## Результаты
- Создан и настроен репозиторий на GitHub: `devops-lab-merkulov`
- Настроено рабочее окружение (Git, SSH-ключ)
- Пройден полный цикл работы с ветками: создание ветки → коммит → Pull Request → merge → удаление ветки

## Вывод
В ходе работы изучены основы Git и GitHub: создание репозитория, работа с ветками, механизм Pull Request и слияние изменений.

