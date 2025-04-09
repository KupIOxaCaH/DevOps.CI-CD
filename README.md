# Домашнее задание к занятию "`DevOps.CI/CD`" - `Бойко Кирилл`

---

### Задание 1

**Что нужно сделать:**

1. Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.
2. Установите на машину с jenkins golang.
3. Используя свой аккаунт на GitHub, сделайте себе форк репозитория. В этом же репозитории находится дополнительный материал для выполнения ДЗ.
4. Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта go test . и docker build ..

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.


 
---

#### Решение 1

![Настройка проекта](https://https://github.com/KupIOxaCaH/DevOps.CI-CD/blob/main/img/1.PNG)
![Настройка проекта](https://https://github.com/KupIOxaCaH/DevOps.CI-CD/blob/main/img/2.PNG)
![Результат выполнения сборки](https://https://github.com/KupIOxaCaH/DevOps.CI-CD/blob/main/img/3.PNG)

---

### Задание 2

**Что нужно сделать:**

1. Создайте новый проект pipeline.
2. Перепишите сборку из задания 1 на declarative в виде кода.

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

---

#### Решение 2

![Настройка проекта](https://https://github.com/KupIOxaCaH/DevOps.CI-CD/blob/main/img/4.PNG)
![Настройка проекта](https://https://github.com/KupIOxaCaH/DevOps.CI-CD/blob/main/img/5.PNG)
![Результат выполнения сборки](https://https://github.com/KupIOxaCaH/DevOps.CI-CD/blob/main/img/6.PNG)

---

### Задание 3

**Что нужно сделать:**

1. Установите на машину Nexus.
2. Создайте raw-hosted репозиторий.
3. Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.
4. Загрузите файл в репозиторий с помощью jenkins.

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

---

#### Решение 3

![Настройка проекта](https://https://github.com/KupIOxaCaH/DevOps.CI-CD/blob/main/img/7.PNG)
![Настройка проекта](https://https://github.com/KupIOxaCaH/DevOps.CI-CD/blob/main/img/8.PNG)
![Настройка проекта](https://https://github.com/KupIOxaCaH/DevOps.CI-CD/blob/main/img/9.PNG)
![Результат выполнения сборки](https://https://github.com/KupIOxaCaH/DevOps.CI-CD/blob/main/img/10.PNG)

---

### Задание 4*

 Придумайте способ версионировать приложение, чтобы каждый следующий запуск сборки присваивал имени файла новую версию. Таким образом, в репозитории Nexus будет храниться история релизов.

Подсказка: используйте переменную BUILD_NUMBER.

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

---

#### Решение 4

![Настройка проекта](https://https://github.com/KupIOxaCaH/DevOps.CI-CD/blob/main/img/11.PNG)
![Настройка проекта](https://https://github.com/KupIOxaCaH/DevOps.CI-CD/blob/main/img/12.PNG)
![Настройка проекта](https://https://github.com/KupIOxaCaH/DevOps.CI-CD/blob/main/img/13.PNG)
![Результат выполнения сборки](https://https://github.com/KupIOxaCaH/DevOps.CI-CD/blob/main/img/14.PNG)
