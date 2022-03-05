# HTMLFormAStory
This is a project in HTML using forms to gather user input data.
<!DOCTYPE.html>
<html>
    <head>
        <meta charset="utf-8">
        <link rel="stylesheet" href="style.css">
        <link href="https://fonts.googleapis.com/css?family=Open+Sans" rel="stylesheet">
        <title>Form a Story</title>
    </head>
    <body>
        <section id="top">
            <img src="ttps://content.codecademy.com/courses/learn-html-forms/formAStoryLogo.svg" alt="Form A Story Logo">
        </section>
        <section id="main">
            <h1>Complete the Form -<br>Complete the Story!</h1>
            <hr>
            <form action="story.html" method="GET">
                <label for="animal-1">Animal:</label>
                <input id="animal-1" name="animal-1" type="text" required>
                <br>
                <label for="animal-2">Another Animal:</label>
                <input id="animal-2" name="animal-2" type="text" required>>
                <br>
                <label for="animal-3">One More Animal:</label>
                <input id="animal-3" name="animal-3" type="text" required>
                <br>
                <label for="adj-1">Adjective (past tense):</label>
                <input id="adj-1" name="adj-1" type="text" required>
                <br>
                <label for="verb-1">Verb (ends in -ing):</label>
                <input id="verb-1" name="verb-1" type="text" required>
                <label for="num-1">Number:</label>
                <input id="num-1" name="num-1" type="number" required>
                <br>
            </form>

        </section>
    </body>
</html>