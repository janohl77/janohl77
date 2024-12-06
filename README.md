<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wasserstoff: Die Energie der Zukunft - Quiz</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Wasserstoff Quiz: Die Energie der Zukunft</h1>
        <div id="quiz-container">
            <div id="question-container">
                <p id="question">Frage wird hier angezeigt</p>
            </div>
            <div id="options-container">
                <button class="option-btn" onclick="checkAnswer(0)">Antwort 1</button>
                <button class="option-btn" onclick="checkAnswer(1)">Antwort 2</button>
                <button class="option-btn" onclick="checkAnswer(2)">Antwort 3</button>
                <button class="option-btn" onclick="checkAnswer(3)">Antwort 4</button>
            </div>
            <div id="score-container">
                <p id="score">Punkte: 0</p>
            </div>
            <div id="result-container"></div>
        </div>
        <button id="start-btn" onclick="startQuiz()">Starte das Quiz</button>
    </div>
    <script src="script.js"></script>
</body>
</html>


