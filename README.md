
# online-learning-platform
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Online Learning Platform</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to E-Learning Platform</h1>
    </header>
    <main>
        <section id="videos">
            <h2>Video Lessons</h2>
            <video controls>
                <source src="lesson1.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
        </section>
        <section id="quiz">
            <h2>Quiz</h2>
            <p>What is 2 + 2?</p>
            <button onclick="checkAnswer(4)">4</button>
            <button onclick="checkAnswer(5)">5</button>
            <p id="quiz-result"></p>
            <p>What is 4+6?</p>
            <button onclick="checkAnswer(10)">10</button>
            <button onclick="checkAnswer(16)">16</button>
            <p id="quiz-result"></p>
            <p>What is 22-18?</p>
            <button onclick="checkAnswer(4)">4</button>
            <button onclick="checkAnswer(15)">15</button>
            <p id="quiz-result"></p>
            <p>What is 29 + 12?</p>
            <button onclick="checkAnswer(41)">41</button>
            <button onclick="checkAnswer(51)">51</button>
            <p id="quiz-result"></p>
            <p>What is 69-33?</p>
            <button onclick="checkAnswer(36)">36</button>
            <button onclick="checkAnswer(63)">63</button>
            <p id="quiz-result"></p>
            <p>What is 2268 - 1252?</p>
            <button onclick="checkAnswer(1016)">1016</button>
            <button onclick="checkAnswer(1017)">51017</button>
            <p id="quiz-result"></p>
        </section>
    </main>
    <script src="script.js"></script>
</body>
</html>
