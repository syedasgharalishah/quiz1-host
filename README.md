<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Dawn Editorial With Urdu Translation – 25 February 2025</title>
  <style>
    /* General Layout & Prevent Text Selection */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f8f9fa;
      line-height: 1.6;
      color: #333;
      -webkit-user-select: none; /* Chrome/Safari */
      -moz-user-select: none;    /* Firefox */
      -ms-user-select: none;     /* IE10+ */
      user-select: none;         /* Standard */
    }
    /* Top Banner */
    .banner {
      background-color: #001f3f;
      color: #fff;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 20px;
    }
    .banner .left { text-align: left; font-size: 1em; }
    .banner .center { text-align: center; font-size: 1.8em; font-weight: bold; }
    .banner .right { text-align: right; font-size: 1em; }
    /* Headline & Info Box */
    .headline {
      background-color: #e0e0e0;
      text-align: center;
      padding: 10px;
      font-size: 1.8em;
    }
    .info-box {
      background-color: #ffea00;
      border: 2px solid #f39c12;
      margin: 20px auto;
      padding: 10px;
      width: 90%;
      text-align: center;
      font-size: 1.2em;
    }
    .info-box span { font-weight: bold; color: #d35400; }
    /* Editorial Title */
    .editorial-title {
      text-align: center;
      margin: 30px 0 20px;
      font-size: 2.4em;
      font-weight: bold;
      border-bottom: 3px solid #ccc;
      padding-bottom: 10px;
    }
    .editorial-title div {
      font-size: 0.6em;
      margin-top: 5px;
      color: #555;
    }
    /* Name Entry */
    #nameSection {
      width: 90%;
      margin: 20px auto;
      text-align: center;
    }
    #userName {
      padding: 8px;
      font-size: 1em;
    }
    /* Quiz Section */
    .quiz-section {
      background-color: #fff;
      border: 2px solid #f39c12;
      margin: 20px auto;
      padding: 20px;
      width: 90%;
    }
    .quiz-section h2 { text-align: center; margin-bottom: 10px; }
    .quiz-section .question { margin-bottom: 15px; }
    .quiz-section label { display: block; margin: 4px 0; }
    .quiz-section button {
      display: block;
      margin: 20px auto;
      padding: 10px 20px;
      font-size: 1em;
    }
    .timer {
      text-align: center;
      font-size: 20px;
      color: red;
      font-weight: bold;
    }
    /* Footer */
    .footer {
      background-color: #001f3f;
      color: #fff;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }
    /* Expired Message Style */
    .expired-message {
      text-align: center;
      color: red;
      font-size: 1.8em;
      margin-top: 40px;
    }
  </style>
  <script>
    // --- Chrome-Only Check ---
    if (navigator.vendor !== "Google Inc." || !navigator.userAgent.match(/Chrome/)) {
      document.write('<h1 style="font-family:Arial, sans-serif; text-align:center; margin-top:50px;">Please open this page in Google Chrome.</h1>');
      throw new Error("Not Google Chrome. Please use Google Chrome.");
    }
    
    // --- Disable Right-Click, Copy, and Text Selection ---
    document.addEventListener("contextmenu", function(e) { e.preventDefault(); }, false);
    document.addEventListener("copy", function(e) { e.preventDefault(); }, false);
    document.onselectstart = function() { return false; };

    // --- Quiz Configuration ---
    // Set quiz duration to 2 minutes (120000 ms)
    const expiryDuration = 120000;

    // Retrieve or set the quiz start time from localStorage.
    let storedStart = localStorage.getItem("quizStartTime");
    if (!storedStart) {
      storedStart = Date.now();
      localStorage.setItem("quizStartTime", storedStart);
    } else {
      storedStart = parseInt(storedStart, 10);
    }

    // Function to check if the quiz has expired.
    function checkExpiry() {
      const now = Date.now();
      if (now - storedStart >= expiryDuration) {
        const container = document.getElementById("quizContainer");
        if (container) {
          container.innerHTML = '<div class="expired-message"><h2>Link Expired</h2><p>This quiz is no longer active.</p><button onclick="resetQuizLink()">Reset Quiz (for testing)</button></div>';
        }
        return true;
      }
      return false;
    }

    // For testing purposes: resets the quiz by clearing stored start time.
    function resetQuizLink() {
      localStorage.removeItem("quizStartTime");
      location.reload();
    }
  </script>
</head>
<body>
  <!-- Top Banner -->
  <div class="banner">
    <div class="left">Tuesday 25 February 2025</div>
    <div class="center">Dawn</div>
    <div class="right">03265762698</div>
  </div>
  
  <!-- Headline & Information Box -->
  <div class="headline">
    Dawn Editorial With Urdu Translation – 25 February 2025
  </div>
  <div class="info-box">
    Monthly Charges: <span>500 PKR</span> | Daily Dawn editorials are shared in our <span>WhatsApp group</span>
  </div>
  
  <!-- Editorial Title -->
  <div class="editorial-title">
    Afghan resettlement
    <div>Published in Dawn, February 25th, 2025</div>
  </div>
  
  <!-- Name Entry Section -->
  <div id="nameSection">
    <label for="userName" style="font-size: 1.2em;">Enter Your Name:</label>
    <input type="text" id="userName" name="userName">
  </div>
  
  <!-- Quiz Section -->
  <div id="quizContainer" class="quiz-section">
    <h2>MCQ Quiz – 2 Minute Challenge</h2>
    <p class="timer" id="quizTimer">Time Left: 02:00</p>
    <form id="quizForm">
      <!-- Question 1 -->
      <div class="question">
        <p>1. What does the term <em>resettle</em> mean?</p>
        <label><input type="radio" name="q1" value="B"> To permanently relocate</label>
        <label><input type="radio" name="q1" value="A"> To stay in the same place</label>
        <label><input type="radio" name="q1" value="C"> To temporarily move</label>
        <label><input type="radio" name="q1" value="D"> To abandon an area</label>
      </div>
      <!-- Question 2 -->
      <div class="question">
        <p>2. What is meant by an <em>unenviable challenge</em>?</p>
        <label><input type="radio" name="q2" value="C"> A difficult situation</label>
        <label><input type="radio" name="q2" value="A"> A desirable opportunity</label>
        <label><input type="radio" name="q2" value="B"> A minor issue</label>
        <label><input type="radio" name="q2" value="D"> An unexpected benefit</label>
      </div>
      <!-- Question 3 -->
      <div class="question">
        <p>3. What does <em>denied resettlement</em> imply?</p>
        <label><input type="radio" name="q3" value="B"> Rejected the opportunity to relocate</label>
        <label><input type="radio" name="q3" value="A"> Accepted the relocation offer</label>
        <label><input type="radio" name="q3" value="C"> Temporarily relocated</label>
        <label><input type="radio" name="q3" value="D"> Volunteered for relocation</label>
      </div>
      <!-- Question 4 -->
      <div class="question">
        <p>4. Which term describes a shortage of essential resources?</p>
        <label><input type="radio" name="q4" value="B"> Resource crunch</label>
        <label><input type="radio" name="q4" value="A"> Influx</label>
        <label><input type="radio" name="q4" value="C"> Dialogue</label>
        <label><input type="radio" name="q4" value="D"> Resettlement</label>
      </div>
      <!-- Question 5 -->
      <div class="question">
        <p>5. What does <em>vetted</em> mean?</p>
        <label><input type="radio" name="q5" value="B"> Thoroughly examined</label>
        <label><input type="radio" name="q5" value="A"> Ignored</label>
        <label><input type="radio" name="q5" value="C"> Briefly reviewed</label>
        <label><input type="radio" name="q5" value="D"> Celebrated</label>
      </div>
      <!-- Question 6 -->
      <div class="question">
        <p>6. What does <em>morally incumbent</em> mean?</p>
        <label><input type="radio" name="q6" value="A"> Ethically required</label>
        <label><input type="radio" name="q6" value="B"> Legally binding</label>
        <label><input type="radio" name="q6" value="C"> Emotionally driven</label>
        <label><input type="radio" name="q6" value="D"> Socially optional</label>
      </div>
      <!-- Question 7 -->
      <div class="question">
        <p>7. Which word describes individuals who betray their country?</p>
        <label><input type="radio" name="q7" value="A"> Traitors</label>
        <label><input type="radio" name="q7" value="B"> Refugees</label>
        <label><input type="radio" name="q7" value="C"> Vetted</label>
        <label><input type="radio" name="q7" value="D"> Approved</label>
      </div>
      <!-- Question 8 -->
      <div class="question">
        <p>8. In this context, what does <em>suspended</em> mean?</p>
        <label><input type="radio" name="q8" value="A"> Temporarily halted</label>
        <label><input type="radio" name="q8" value="B"> Permanently cancelled</label>
        <label><input type="radio" name="q8" value="C"> Resumed</label>
        <label><input type="radio" name="q8" value="D"> Guaranteed</label>
      </div>
      <!-- Question 9 -->
      <div class="question">
        <p>9. What does <em>sent back</em> mean?</p>
        <label><input type="radio" name="q9" value="C"> Returned to one’s country of origin</label>
        <label><input type="radio" name="q9" value="A"> Permanently resettled</label>
        <label><input type="radio" name="q9" value="B"> Relocated temporarily</label>
        <label><input type="radio" name="q9" value="D"> Invited to stay</label>
      </div>
      <!-- Question 10 -->
      <div class="question">
        <p>10. What does the term <em>dialogue</em> refer to?</p>
        <label><input type="radio" name="q10" value="B"> A conversation or discussion</label>
        <label><input type="radio" name="q10" value="A"> A formal speech</label>
        <label><input type="radio" name="q10" value="C"> A written document</label>
        <label><input type="radio" name="q10" value="D"> A legal contract</label>
      </div>
      <!-- Question 11 -->
      <div class="question">
        <p>11. What is meant by a <em>direct effect</em>?</p>
        <label><input type="radio" name="q11" value="B"> An immediate impact</label>
        <label><input type="radio" name="q11" value="A"> A delayed consequence</label>
        <label><input type="radio" name="q11" value="C"> An indirect influence</label>
        <label><input type="radio" name="q11" value="D"> An insignificant result</label>
      </div>
      <!-- Question 12 -->
      <div class="question">
        <p>12. What does <em>influx</em> mean?</p>
        <label><input type="radio" name="q12" value="B"> A large arrival</label>
        <label><input type="radio" name="q12" value="A"> A large departure</label>
        <label><input type="radio" name="q12" value="C"> A temporary absence</label>
        <label><input type="radio" name="q12" value="D"> A controlled exit</label>
      </div>
      <!-- Question 13 -->
      <div class="question">
        <p>13. What does <em>approved</em> mean in the article?</p>
        <label><input type="radio" name="q13" value="B"> Authorized or accepted</label>
        <label><input type="radio" name="q13" value="A"> Rejected</label>
        <label><input type="radio" name="q13" value="C"> Suspended</label>
        <label><input type="radio" name="q13" value="D"> Delayed</label>
      </div>
      <!-- Question 14 -->
      <div class="question">
        <p>14. Which term refers to the formal process of relocating refugees?</p>
        <label><input type="radio" name="q14" value="A"> Resettlement programme</label>
        <label><input type="radio" name="q14" value="B"> Resource crunch</label>
        <label><input type="radio" name="q14" value="C"> Dialogue</label>
        <label><input type="radio" name="q14" value="D"> Influx</label>
      </div>
      <!-- Question 15 -->
      <div class="question">
        <p>15. What does <em>traitors</em> mean?</p>
        <label><input type="radio" name="q15" value="B"> Those who betray their country</label>
        <label><input type="radio" name="q15" value="A"> Loyal citizens</label>
        <label><input type="radio" name="q15" value="C"> New immigrants</label>
        <label><input type="radio" name="q15" value="D"> Government officials</label>
      </div>
      <!-- Question 16 -->
      <div class="question">
        <p>16. What is the meaning of <em>without delay</em>?</p>
        <label><input type="radio" name="q16" value="C"> Immediately</label>
        <label><input type="radio" name="q16" value="A"> Eventually</label>
        <label><input type="radio" name="q16" value="B"> Later</label>
        <label><input type="radio" name="q16" value="D"> Postponed</label>
      </div>
      <!-- Question 17 -->
      <div class="question">
        <p>17. What does <em>forcibly repatriated</em> mean?</p>
        <label><input type="radio" name="q17" value="B"> Sent back by force</label>
        <label><input type="radio" name="q17" value="A"> Voluntarily relocated</label>
        <label><input type="radio" name="q17" value="C"> Given citizenship</label>
        <label><input type="radio" name="q17" value="D"> Exempt from relocation</label>
      </div>
      <!-- Question 18 -->
      <div class="question">
        <p>18. In the article, what does the term <em>White House</em> refer to?</p>
        <label><input type="radio" name="q18" value="B"> The official residence of the U.S. President</label>
        <label><input type="radio" name="q18" value="A"> A local government building</label>
        <label><input type="radio" name="q18" value="C"> A cultural center</label>
        <label><input type="radio" name="q18" value="D"> A museum</label>
      </div>
      <!-- Question 19 -->
      <div class="question">
        <p>19. What does <em>uncertainty</em> mean in this context?</p>
        <label><input type="radio" name="q19" value="B"> A state of unpredictability</label>
        <label><input type="radio" name="q19" value="A"> A state of surety</label>
        <label><input type="radio" name="q19" value="C"> A clear decision</label>
        <label><input type="radio" name="q19" value="D"> A formal agreement</label>
      </div>
      <!-- Question 20 -->
      <div class="question">
        <p>20. Which term indicates an alliance of Western nations?</p>
        <label><input type="radio" name="q20" value="A"> Western coalition</label>
        <label><input type="radio" name="q20" value="B"> Resettlement programme</label>
        <label><input type="radio" name="q20" value="C"> Dialogue</label>
        <label><input type="radio" name="q20" value="D"> Resource crunch</label>
      </div>
      <button type="button" onclick="submitQuiz()">Submit Quiz</button>
    </form>
    <div id="quizResult" style="text-align:center; font-size:18px; margin-top:20px;"></div>
  </div>
  
  <!-- Footer -->
  <div class="footer">
    Subscribe for daily vocabulary updates, current affairs, and complete editorial translations.<br>
    Contact: 03265762698 | Join our WhatsApp group now!
  </div>
  
  <!-- Quiz Timer & Submission Script -->
  <script>
    // Timer variables for 2 minutes (120 seconds)
    let timeLeft = 120;
    let quizTimerInterval;
    
    function startQuizTimer() {
      quizTimerInterval = setInterval(function() {
        if (checkExpiry()) {
          clearInterval(quizTimerInterval);
          return;
        }
        timeLeft--;
        let minutes = Math.floor(timeLeft / 60);
        let seconds = timeLeft % 60;
        document.getElementById("quizTimer").innerHTML = "Time Left: " +
          (minutes < 10 ? "0" : "") + minutes + ":" +
          (seconds < 10 ? "0" : "") + seconds;
        if (timeLeft <= 0) {
          clearInterval(quizTimerInterval);
          submitQuiz();
        }
      }, 1000);
    }
    
    function submitQuiz() {
      // Ensure the user has entered their name.
      const nameInput = document.getElementById("userName");
      if (!nameInput.value.trim()) {
        alert("Please enter your name before submitting the quiz.");
        return;
      }
      
      clearInterval(quizTimerInterval);
      const form = document.getElementById("quizForm");
      const formData = new FormData(form);
      let score = 0, attempted = 0;
      const totalQuestions = 20;
      const correctAnswers = {
        q1: "B", q2: "C", q3: "B", q4: "B", q5: "B",
        q6: "A", q7: "A", q8: "A", q9: "C", q10: "B",
        q11: "B", q12: "B", q13: "B", q14: "A", q15: "B",
        q16: "C", q17: "B", q18: "B", q19: "B", q20: "A"
      };
      
      for (let i = 1; i <= totalQuestions; i++) {
        let q = "q" + i;
        if (formData.has(q)) {
          attempted++;
          if (formData.get(q) === correctAnswers[q]) {
            score++;
          }
        }
      }
      
      // Display results with the user's name.
      document.getElementById("quizResult").innerHTML =
        "Name: " + nameInput.value + "<br>" +
        "You attempted " + attempted + " out of " + totalQuestions +
        " questions.<br>Your score: " + score + " out of " + totalQuestions;
      
      // OPTIONAL: Send results to your server using fetch/AJAX here.
      /*
      fetch('YOUR_SERVER_ENDPOINT', {
        method: 'POST',
        headers: { 'Content-Type': 'application/json' },
        body: JSON.stringify({ name: nameInput.value, attempted, score })
      })
      .then(response => response.json())
      .then(data => console.log('Result saved:', data))
      .catch(error => console.error('Error:', error));
      */
      
      // Disable further input.
      const inputs = form.querySelectorAll("input");
      inputs.forEach(input => input.disabled = true);
      form.querySelector("button").disabled = true;
    }
    
    window.onload = function() {
      if (!checkExpiry()) {
        startQuizTimer();
      }
    };
  </script>
</body>
</html>
