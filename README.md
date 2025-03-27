[Uploading journa<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
    <title>V's Journal</title>
    <link rel="stylesheet" type="text/css" href="http://kgau.ru/istiki/study/labs/journal/basic.css" title="style" />
    <link rel="stylesheet" type="text/css" href="journal_layout.css" title="style" />
</head>
<body>
    <div id="main-container">
        <div id="header">
            <h1>Викины записки</h1>
            <h2>So fresh and so clean</h2>
        </div>
        
        <div class="journal-entry">
            <h2>1/12/14: Как есть крабов</h2>
            <p>
                <img src="4.img" alt="Инструменты для крабов" />
            </p>
            <p>
                Вчера я вспоминала как три месяца назад на Пагкоре кушала <a href="http://www.youtube.com/watch?v=EaVzYqQhq74">крабов</a>!
            </p>
            <p class="spacer"></p>
        </div>
        
        <div class="journal-entry">
            <h2>11/11/15: Подготовка</h2>
            <p>
                <img src="1.img" alt="Инструменты для крабов" />
            </p>
            <p>
                Подготовьте стол. От крабов много грязи и беспорядка, так что
                стол надо защитить. Положите плотную бумагу на стол, чтобы она
                впитывала сок и позволила потом быстро навести порядок. Приготовьте молоток для
                крабов, тупой нож, и щипцы для раскалывания клешней, если они у вас есть.
            </p>
            <p>
                Если вы еще не приготовили краба, сделайте это. <q>Приготовьте их
                на пару. Из голубых они превратятся в красных. Обычно крабов готовят на пару со
                слоем приправ.</q> Далее следующий этап: поедание краба
            </p>
            <p class="spacer"></p>
        </div>
        
        <div id="footer">
            <p>
                <a href="https://webster.cs.washington.edu/validate-html.php">
                    <img src="2.img" alt="Valid HTML5" />
                </a>
                <a href="https://webster.cs.washington.edu/validate-css.php">
                    <img src="3.img" alt="Valid CSS" />
                </a>
            </p>
        </div>
    </div>
</body>
</html>

/* Основные стили страницы */
body {
    background-image: url('background.gif');
    margin: 0 10%;
    font-family: Arial, sans-serif;
}

#main-container {
    background-color: white;
    border: 10px solid white;
    border-radius: 10px;
}

/* Стили заголовка */
#header {
    background-color: #A8F0F0;
    text-align: right;
    padding: 10px;
}

#header h2 {
    font-size: 14pt;
}

/* Стили записей журнала */
.journal-entry {
    background-color: #E8FBFB;
    border: 4px solid #C2E9E9;
    border-radius: 15px;
    padding: 5px;
    margin-top: 10px;
}

.journal-entry h2 {
    border-bottom: 2px dashed blue;
}

.journal-entry p {
    text-align: justify;
}

.journal-entry img {
    float: right;
    margin-left: 10px;
    margin-bottom: 10px;
}

/* Очистка float */
.spacer {
    clear: both;
}

/* Стили подвала */
#footer {
    border-top: 1px solid #C2E9E9;
    margin-top: 20px;
    padding-top: 10px;
}l.html…]()
