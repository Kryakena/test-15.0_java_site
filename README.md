# Подготовка к созданию сайта на JAVA

1. Скачать и установить JDK Development Kit 23.0.1 с официального сайта https://www.oracle.com/java/technologies/downloads/#jdk21-windows
![2024-11-13_00-33-53](https://github.com/user-attachments/assets/1a07d600-d297-4d31-be7d-e12f190920e7)

![[2024-11-13_00-33-53.png]]
3. в Windows нажать комбинацию клавиш "Windows+S", в поисковой строке набрать "перемен"
4. выбрать "Изменение среды текущего пользователя"
![[2024-11-13_11-54-44.png]]
5. нажать кнопку "Создать", чтобы создать переменную. Имя переменной: JAVA_HOME, значение переменной (путь к файлу): C:\Program Files\Java\jdk-23\bin\java.exe. Нажать кнопку "ОК"
![[2024-11-14_10-45-22.png]]
6. скачать архив с папкой Apache Maven с официального сайта 
![[2024-11-13_11-15-19.png]]
8. вытаскиваем из zip архива папку "apache-maven-3.9.9", запихиваем её в папку "Program Files", будет путь: C:\Program Files\apache-maven-3.9.9
9. Выбрать "Path" ("Изменение среды текущего пользователя" = "Shift+S") и нажать кнопку "Изменить". Потом кнопку "Создать" и вставить путь к файлу Maven "C:\Program Files\apache-maven-3.9.9\bin\mvn" Сохранить изменения кнопкой "ОК". Закрыть окно "Системные переменные" кнопкой "ОК"
10. Скачать и установить IntelliJ IDEA Community Edition https://www.jetbrains.com/idea/download/?section=windows
![[2024-11-13_00-35-05.png]]
3. зайти на сайт фреймворка Spring https://start.spring.io/
4. создать сборку в Spring:
	- заполнить поля Group и Artifact;
	- выбрать язык Java и его версию; 
	- фреймворк Maven (Apache Maven); 
	- добавить Зависимости:
		- **Spring Web**
		- **Thymeleaf**
![[2024-11-13_00-37-12.png]]
5. Нажать на кнопку "Generate"
6. Распаковать скаченный zip архив на диск D в папку с будущим проектом.
