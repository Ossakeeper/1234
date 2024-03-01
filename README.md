<p align = "center">МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ<br>
РОССИЙСКОЙ ФЕДЕРАЦИИ<br>
ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ<br>
ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ<br>
«САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</p>
<br><br><br><br><br><br>
<p align = "center">Институт естественных наук и техносферной безопасности<br>Кафедра информатики<br>Шинкаренко Никита Александрович</p>
<br><br><br>
<p align = "center"><br><strong>Лабораторная работа №1.«Введение вэб-разработку»</strong><br>01.03.02 Прикладная математика и информатика</p>
<br><br><br><br><br><br><br><br><br><br><br><br>
<p align = "right">Научный руководитель<br>
Соболев Евгений Игоревич</p>
<br><br><br>
<p align = "center">г. Южно-Сахалинск<br>2024 г.</p>
<br><br><br><br><br><br><br><br><br><br><br><br>

<h1 align = "center">Введение</h1>

<p><b>Android Studio</b> — интегрированная среда разработки (IDE) для работы с платформой Android, анонсированная 16 мая 2013 года на конференции Google I/O. В последней версии Android Studio поддерживается Android 4.1 и выше.</p>
<p><b>Kotlin</b> — это кроссплатформенный статически типизированный язык программирования общего назначения высокого уровня. Kotlin предназначен для полного взаимодействия с Java, а версия стандартной библиотеки Kotlin для JVM зависит от библиотеки классов Java, но вывод типов позволяет сделать ее синтаксис более кратким. Kotlin в основном нацелен на JVM, но также компилируется в JavaScript (например, для интерфейсных веб-приложений, использующих React) или собственный код через LLVM (например, для собственных приложений iOS, разделяющих бизнес-логику с приложениями Android). Затраты на разработку языка несет JetBrains, а Kotlin Foundation защищает торговую марку Kotlin.</p>

<br>
<h1 align = "center">Цели и задачи</h1>


<p>Создание сайта с информацией обо мне.</p>

<p>ФУНКЦИОНАЛЬНЫЕ ТРЕБОВАНИЯ</p>
<ul>
<li>Наличие фотографии</li>
<li>Отображение информации обо мне: Имя, Возраст, Достижения,Хобби</li>
<li>Вся информация о персонажах задаётся внутри программы</li>
</ul>

<p></p>



<h1 align = "center">Решение</h1>

<p>Для выполнения этой лабораторной работы, я пользовался:</p>

<ul>
<li>Материалом в сети интернет</li>
</ul>

<h2 align = "center">index.html</h2>

```kotlin
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="icon" type="image/x-icon"href="ic.icon">
</head>
<style>
    .gifka{
        margin-left: "-20px";
        margin-bottom: "-5px";
    }
    .baton{
        opacity: 1
    }
    .baton:disabled {opacity: 0;}
</style>
<body style="background-color: darkgrey;">
    <h1> Информация обо мне </h1>
    <h2>
        <pre>
        Мое имя: Шинкаренко Никита Александрович 
        Полных лет: 20
        Достижения:  <img id="gif" class="gifka" src="loading.gif" height="20px"  style="margin-left: 0px; margin-bottom: -5px; display: none;"> <button id="bat" class="baton" onclick="dis()" style="margin-left: -30px;">Посмотреть</button>
        Мое хобби: Особых увлечений нет
        Фотография: <div ><img src="carbs.jpg" height="100px" style="margin-left: 100px; margin-top: 1px;"></div>
        </pre>     
    </h2>
    <script>
        function dis(){
            bat.disabled=true;
            document.getElementById("gif").style.display = "inline";
        }
    </script>
</body>
</html>
```




<h1 align = "center">Результат</h1>

<p align = "center"><img src="Screenshot_4.png" alt="first screen"></p>

<h1 align = "center">Вывод</h1>
<p>По итогу проделанной лабораторной работы, я создал свой первый сайт.</p>
