<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Online Math Test</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f8ff;
            margin: 20px;
        }

        h1 {
            color: #333;
        }

        form {
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            width: 70%;
        }

        .question {
            margin-bottom: 20px;
        }

        img {
            width: 300px;
            border-radius: 10px;
            margin-bottom: 20px;
        }

        textarea {
            width: 100%;
        }

        input[type="submit"] {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        input[type="submit"]:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <h1>Online Math Test</h1>

    <!-- Young woman teaching math -->
    <img src="https://cdn.pixabay.com/photo/2017/01/31/13/14/woman-2022243_1280.png" alt="Young woman teaching math">

    <!-- START OF TEST -->

    <form>

        <!-- Name Field -->
        <label for="studentName"><strong>Enter Your Name:</strong></label><br><br>
        <input type="text" id="studentName" name="studentName" placeholder="Your name here"><br><br>

        <!-- Multiple Choice Question 1 -->
        <div class="question">
            <p><strong>1. What is 8 &plus; 5?</strong></p>

            <input type="radio" id="q1a" name="question1">
            <label for="q1a">11</label><br>

            <input type="radio" id="q1b" name="question1">
            <label for="q1b">13</label><br>

            <input type="radio" id="q1c" name="question1">
            <label for="q1c">15</label>
        </div>

        <!-- Multiple Choice Question 2 -->
        <div class="question">
            <p><strong>2. What is 12 &times; 2?</strong></p>

            <input type="radio" id="q2a" name="question2">
            <label for="q2a">20</label><br>

            <input type="radio" id="q2b" name="question2">
            <label for="q2b">24</label><br>

            <input type="radio" id="q2c" name="question2">
            <label for="q2c">26</label>
        </div>

        <!-- Multiple Choice Question 3 -->
        <div class="question">
            <p><strong>3. What is 18 &divide; 3?</strong></p>

            <input type="radio" id="q3a" name="question3">
            <label for="q3a">5</label><br>

            <input type="radio" id="q3b" name="question3">
            <label for="q3b">6</label><br>

            <input type="radio" id="q3c" name="question3">
            <label for="q3c">7</label>
        </div>

        <!-- Word Problem -->
        <div class="question">
            <p><strong>4. Word Problem:</strong></p>

            <p>
                Sarah had 15 apples. She gave 4 apples to her friend and bought 7 more apples.
                How many apples does Sarah have now?
            </p>

            <textarea rows="6" placeholder="Type your answer here..."></textarea>
        </div>

        <!-- Submit Button -->
        <input type="submit" value="Submit Test">

    </form>

    <!-- END OF TEST -->

</body>
</html>
