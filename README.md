<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>퀴즈</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; margin-top: 50px; }
        .quiz-container { max-width: 400px; margin: auto; border: 1px solid #ddd; padding: 20px; border-radius: 10px; }
        button { margin-top: 10px; padding: 10px; font-size: 16px; cursor: pointer; }
    </style>
</head>
<body>

    <div class="quiz-container">
        <h2>호시노 겐의 생일은 언제일까요?</h2>
        <button onclick="checkAnswer(1)">1번: 1985.12.18</button><br>
        <button onclick="checkAnswer(2)">2번: 1982.06.09</button><br>
        <button onclick="checkAnswer(3)">3번: 1981.01.28</button><br>
        <button onclick="checkAnswer(4)">4번: 1955.06.11</button>
    </div>

    <script>
        function checkAnswer(choice) {
            if (choice === 3) {
                alert("정답!");
            } else {
                alert("미안하지만 다음 기회에.");
            }
        }
    </script>

</body>
</html>
