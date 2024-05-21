# Лаб_1 Использование основных инструментов для создания пользовательского интерфейса. 
#### Стартовый проект состоит из трех пакетов и MainActivity.kt.
- Структура содержимого:
    - `app:` имеет только одну компонуемую функцию, которая выступает в качестве корневого макета в вашем приложении. Вам не нужно будет его менять, так как это только навигация по приложению, которая уже настроена для вас!
    - `router:` имеет два вспомогательных класса для управления навигацией между экранами и кнопкой «Назад». Здесь тоже ничего менять не нужно.
    - `screens:` Состоит из нескольких составных функций для разных экранов. Вы реализуете их в этой главе, за исключением NavigationScreen.kt, который содержит макет для навигации, который уже создан для вас.
    - `MainActivity.kt:` содержит вызов setContent(), устанавливающий первую composable (компонуемую) функцию и действующий как корневой компонент пользовательского интерфейса.

#### Как только вы ознакомитесь с организацией файлов, создайте и запустите приложение. Вы увидите экран с базовой навигацией.
## Порядок выполнения лабораторной работы:
- Для выполнения лабораторной работы Вам нужно сделать Fork данного репозитория в свою учетную запись на GitHub.
- После чего осуществить [клонирование](https://docs.github.com/ru/desktop/contributing-and-collaborating-using-github-desktop/adding-and-cloning-repositories/cloning-and-forking-repositories-from-github-desktop) удаленного репозитория себе на компьютер.
- Открыть и запустить проект в Android Studio.
- Внести изменения в проект согласно файла с каждым пунктом заданиия.
- Зафиксировать изменения и отправить их на GitHub для каждого пункта задания (есть в Google class).
- Предъявить работу преподавателю: 
    - Запущенное приложение либо в эмуляторе, либо на телефоне;
    - Удаленный репозиторий в GitHub с историей изменений (commit) `(если истории фиксации изменений не будет - это будет приравниваться к невыполнению задания)`.
