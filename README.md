## <a href="http://java.u-rise.com/">4-х месячный Онлайн Курс по Java SE с собственным проектом на выходе</a>

# Вступительное занятие

## Необходимое ПО
-  <a href="http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html">JDK8</a>
-  <a href="http://git-scm.com/downloads">Git</a>
-  Аккаунт <a href="https://github.com/">GitHub</a>
-  <a href="http://www.jetbrains.com/idea/download/index.html">IntelliJ IDEA</a>

> Выбирать Ultimate, 30 days trial (нам понадобится Git, JavaScript, Tomcat, JSP). Учебный ключ выдается на первом занятии.

## Рекомендуемые книги
- <a href="http://myflex.org/books/java4kids/java4kids.htm">YAKOV FAIN: Программирование на Java для начинающих</a>
- <a href="https://habrahabr.ru/post/153373/">Книги по Java: от новичка до профессионала</a>
- <a href="http://scanlibs.com/java-effektivnoe-programmirovanie-2-e-izdanie">Джошуа Блох: Java. Эффективное программирование, 2-е издание</a>
- <a href="http://www.labirint.ru/books/87603/">Гамма, Хелм, Джонсон: Приемы объектно-ориентированного проектирования. Паттерны проектирования</a>
- <a href="http://www.bookvoed.ru/book?id=639284">Редмонд Э.: Семь баз данных за семь недель. Введение в современные базы данных и идеологию NoSQL.</a>

## Домашнее задание
- Установите ПО: Git, Java 8, IntelliJ IDEA
- Создайте локальную копию нашего проекта: `git clone https://github.com/School-IT-Programm/resume-storage.git`
> в результате у вас должен появится каталог `resume-storage`

- В IntelliJ IDEA создайте новый проект, выбрав каталог `resume-storage`

![image](https://cloud.githubusercontent.com/assets/18701152/14917746/38c4a20a-0e29-11e6-8985-c57911da57c4.png)

![image](https://cloud.githubusercontent.com/assets/18701152/14917800/71887238-0e29-11e6-9830-e557901892b4.png)

![image](https://cloud.githubusercontent.com/assets/18701152/15710172/6cb15a66-2811-11e6-8739-4e289d1ea799.png)

- Реализуйте класс `ArrayStorage`: хранение резюме на основе массива (методы `clear, get, save, delete, getAll, size`).
- Протестируйте реализацию, запустив `MainTestArrayStorage.main()`: в IDEA слева на полях зеленая стрелка.
- Протестируйте реализацию интерактивно с помощью `ReplTestArrayStorage.main()`.