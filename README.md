# Online-Quiz-Maker
Online-Quiz-Maker
---/HTML ---
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OnlineQuizMaker</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <!-- header tag for heading -->
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#create">Create</a></li>
                <li><a href="#take">Take</a></li>
                <li><a href="#end">End</a></li>
            </ul>
        </nav>
    </header>
    <!--Main Content for Body -->
    <main>

        <!-- section for quiz or take button -->
        <section class="do-home">
            <br>

            <h1 id="home">Welcome to the Online Quiz Maker</h1>
            <p>Choose an Option:</p>

            <!-- quiz button -->
            <div class="cards-footer">
                <br>
                <a href="#create"><button id="createquizBtn" class="quiz-btn"> Creat Quiz</button></a>
                <br>
                <br>
            </div>
            <br>
            <!-- take button -->
            <div class="cards-footer">
                <br>
                <a href="#take"><button id="takequizBtn" class="quiz-btn">Take Quiz</button></a>
                <br>
                <br>
            </div>
            <br>
            <br>
            <br>
        </section>

        <section class="home">

            <h1 id="take">
                <!-- <<< take Quiz >>> -->
            </h1>
            <div class="packages-card">

                <div class="cards-content">

                    <h1>Multiple Choices Question: 1</h1>

                    <h3>
                        <strong>Question:</strong>

                        who is our foreign minister of india?
                    </h3>
                    <p>

                    <form>
                        <label>
                            <input type="radio" name="answer" value="A"> A. Amit shah
                        </label>
                        <label>
                            <input type="radio" name="answer" value="B"> B. Rajnath Singh
                        </label>
                        <label>
                            <input type="radio" name="answer" value="C"> C. Subrahmanyam Jaishankar

                        </label>
                        <label>
                            <input type="radio" name="answer" value="D"> D. Piyush Goyal
                        </label>

                        <br><br>

                    </form>

                    </p>
                </div>
                <!-- for submit button  -->
                <div class="cards-footer">

                    <button type="button" class="cta-button" onclick="checkAnswer()">Submit Answer</button>
                </div>
            </div>

            <div class="packages-card">

                <div class="cards-content">

                    <h1>Multiple Choices Question : 2</h1>
                    <h3>
                        <strong>Question:</strong>
                        Who is our foreign minister of india?
                    </h3>
                    <p>

                    <form>
                        <label>
                            <input type="radio" name="answer" value="A"> A. Amit shah
                        </label>
                        <label>
                            <input type="radio" name="answer" value="B"> B. Rajnath Singh
                        </label>
                        <label>
                            <input type="radio" name="answer" value="C"> C. Subrahmanyam Jaishankar

                        </label>
                        <label>
                            <input type="radio" name="answer" value="D"> D. Piyush Goyal
                        </label>

                        <br><br>

                    </form>

                    </p>
                </div>
                <!-- for submit button  -->
                <div class="cards-footer">

                    <button type="button" class="cta-button" onclick="checkAnswer()">Submit Answer</button>


                </div>
            </div>
            <div class="packages-card">

                <div class="cards-content">

                    <h1>Multiple Choices Question : 3</h1>
                    <h3>
                        <strong>Question:</strong>
                        Who is our foreign minister of india?
                    </h3>
                    <p>

                    <form>
                        <label>
                            <input type="radio" name="answer" value="A"> A. Amit shah
                        </label>
                        <label>
                            <input type="radio" name="answer" value="B"> B. Rajnath Singh
                        </label>
                        <label>
                            <input type="radio" name="answer" value="C"> C. Subrahmanyam Jaishankar

                        </label>
                        <label>
                            <input type="radio" name="answer" value="D"> D. Piyush Goyal
                        </label>

                        <br><br>

                    </form>

                    </p>
                </div>
                <!-- for submit button  -->
                <div class="cards-footer">

                    <button type="button" class="cta-button" onclick="checkAnswer()">Submit Answer</button>


                </div>
            </div>
        </section>
        <section class="quiz-part">

            <h1 id="create" class="home-part">

                <!-- <<<Creat Quiz>>> -->
            </h1>
            <h2> Create Your Own Quiz:</h2>

            <div class="packages-card">
                <div class="cards-content">

                    <h1> Make your Own Multiple Choice Questions</h1>
                    <p>Write Your Question Here</p>

                    <form>

                        <input type="text" class="input-box" placeholder="Write Your Question:">
                        <br><br>
                        <button type="button" class="bing">Submit Question</button>
                    </form>

                    <p>

                        Create Option
                        <from>

                            <label>
                                <input type="text" class="input-box" placeholder="Option 1:">
                            </label>
                            <br>
                            <label>
                                <input type="text" class="input-box" placeholder="Option 2:">
                            </label>
                            <br>
                            <label>
                                <input type="text" class="input-box" placeholder="Option 3:">
                            </label>
                            <br>
                            <label>
                                <input type="text" class="input-box" placeholder="Option 4:">
                            </label>
                            <br><br>

                        </from>
                    </p>

                </div>

               <div class="cards-footer">

                <button type="button" class="cta-button" onclick="checkAnswer()">Submit Option</button>
               </div>

            </div>

            <div class="packages-card">
                <div class="cards-content">
                    <h1>Make your Own Multiple Choice Questions</h1>

                    <p>Write Your question Here>>></p>
        
                    <form>
                        <input type="text" class="input-box" placeholder="Write Your Question:">
                        <br><br>
                        <button type="button" class="b">Submit Question</button>
                    </form>
        
              <p>
                Create Options >>>
                <form >
                <label>
                    <input type="text" class="input-box" placeholder="Option 1:">
                </label>
                
                <br>
                <label>
                    <input type="text" class="input-box" placeholder="Option 2:">
                </label>
                
                <br>
                <label>
                    <input type="text" class="input-box" placeholder="Option 3:">
                </label>
                
                <br>
                <label>
                    <input type="text" class="input-box" placeholder="Option 4:">
                </label>
                
                <br><br>
                
            </form>
        
            </p>

                </div>
                <div class="cards-footer">

                    <button type="button" class="cta-buttons" onclick="checkAnswer()">Submit Options</button>
              
              
            </div>
            </div>
        </section>
    </main>

    <footer class="footer">
        <p>&copy; 2024 Quiz Maker. All rights reserved.</p>
        <p>Name:Sri Krishna Mishra</p>
        <p>Find me on: <a href="https://www.linkedin.com/in/sri-krishna-mishra-0i/" target="_blank">LinkedIn</a></p>
        <p>Contact:990558****</p>
        <p>Email : pc78391@gmail.com</p>
    </footer>

    <script src="script.js" defer></script>
</body>

</html>

---/CSS ---
body {

    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {

    background-color: black;
    color: white;
    padding: 10px;
}

nav ul {

    list-style: none;
    display: flex;
    justify-content: space-around;
}

nav a {

    color: lightblue;
    text-decoration: none;

}

main {

    text-align: center;
    margin-top: 50px;
}

.footer {

    background-color: black;
    color: white;
    text-align: center;
    justify-content: space-between;
}

.question-card {
    background-color: black;
    max-width: 400px;
    margin: 0 auto;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 0 10px rgb(0, 0, 0, 0.1);

}

h1 {
    font-size: 24px;
    color: #333;
}

p {

    font-size: 18px;
    margin-bottom: 20px;
}

label {

    display: block;
    font-size: 16px;
    margin-bottom: 10px;   
}

input[type="radio"] {

    margin-right: 5px;
}

.packages {

    background-color:#f5f5f5 ;
    padding: 50px 0;
    text-align: center;
}

.packages h2 {

    font-size: 32px;
    margin-bottom: 30px;
}

.packages-card {

    background-color: #ffffff;
    border-radius: 10px;
    box-shadow: 0px 2px 6px rgb(0, 0, 0, 0.1);
    padding: 0;
    margin: 20px;
    display: inline-block;
    width: calc(33.33% - 40px);
    vertical-align: top;
    box-sizing: border-box;
    overflow: hidden;
}

.cards-content img {

    max-width:100px;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
}

.cards-content {

    padding: 20px;
}

.cards-content h3 {

    font-size: larger;
    margin: 10px 0;
}

.cards-content p {

    color: #777777;
    margin-bottom: 15px;

}

.cards-footer {

    padding: 20px;
    background-color: #7d7d7d;
}

.packages-card .cta-buttons {

    background-color: rgb(227, 50, 79);

}

.quiz-btn {

    background-color: #ff9800;
    color: #ffffff;
    border: none;
    padding:10px 20px;
    font-size: 16px;
    cursor: pointer;
    border-radius: 5px;
    font-weight: bold;
    translate: background-color 0.3 ease;
}

.quiz-btn:hover {
    background-color: #FFB74D;
  }
  
.quiz-part {

    background-color: #333;
}

  
.input-box {
    width: 300px;
    padding: 10px;
    border: 3px solid lightgreen;
    border-radius: 50px;
    font-size: 16px;
  }

.do-home {

    color: purple;
    background-color: lightgreen;
}
