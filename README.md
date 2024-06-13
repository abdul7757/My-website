
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ransomware on Android Awareness</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        main {
            padding: 20px;
        }
        h1 {
            margin-top: 0;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
        }
        nav ul li {
            margin-bottom: 10px;
        }
        nav ul li a {
            color: #333;
            text-decoration: none;
            font-weight: bold;
            display: block;
            padding: 10px;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        nav ul li a:hover {
            background-color: #f0f0f0;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 10px 20px;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ransomware on Android Awareness</h1>
    </header>
    <main>
        <h2>Welcome</h2>
        <p>Welcome to our website dedicated to raising awareness about ransomware on Android devices. Explore the following pages to learn more about this growing threat and how to protect yourself.</p>
        <img src="Ransom1.jpg" alt="Ransomware Awareness" style="max-width: 100%; height: auto;">
        <nav>
            <ul>
               <li><a href="gave trivia.html">GAME TRIVIA part Beginner!!!</a></li>
                <li><a href="page2.html">What is Ransomware on Android?</a></li>
                <li><a href="page3.html">The Impact of Ransomware</a></li>
                <li><a href="page4.html">Prevention and Mitigation</a></li>
                <li><a href="page5.html">What is the Motivation and Aim</a></li>
                <li><a href="page6.html">What are Some Critical Problems?</a></li>
                <li><a href="page7.html">Solutions to Mitigate from Android Ransom?</a></li>
                <li><a href="page8.html">What is URL Spoofing?</a></li>
                <li><a href="page10.html">How do Hackers Try to Do Ransom?</a></li>
                <li><a href="page12.html">Tips and bits </a></li>
                <li><a href="page13.html">Social Media Sharing </a></li>
                <li><a href="page14.html">Android Ransomware Awareness</a></li>
                <li><a href="page15.html">Recovery Stories</a></li>
                <li><a href="page9.HTML">GAME TRIVIA Final!!!</a></li>
                <li><a href="page11.html">Feedback Form</a>

      
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Android Ransomware Quiz</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }
        h1 {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            margin: 0;
        }
        .container {
            margin: 50px auto;
            width: 80%;
            max-width: 600px;
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .question {
            font-size: 20px;
            margin-bottom: 20px;
        }
        .options button {
            display: block;
            margin: 10px auto;
            padding: 10px;
            width: 80%;
            max-width: 400px;
            font-size: 16px;
            cursor: pointer;
            border: 1px solid #ddd;
            background-color: #f9f9f9;
            border-radius: 5px;
        }
        .options button.correct {
            background-color: #4CAF50;
            color: white;
        }
        .options button.wrong {
            background-color: #f44336;
            color: white;
        }
        #next {
            display: none;
            margin-top: 20px;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
        }
        .score {
            font-size: 18px;
            margin-top: 20px;
            color: #333;
        }
        .result {
            font-size: 24px;
            font-weight: bold;
            margin-top: 20px;
        }
        .pass {
            color: #4CAF50;
        }
        .fail {
            color: #f44336;
        }
        #user-info {
            margin-top: 20px;
        }
        #user-info input {
            padding: 10px;
            font-size: 16px;
            width: 80%;
            max-width: 400px;
            margin-bottom: 20px;
        }
        #user-info button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
        }
        #result-container {
            display: none;
        }
        table {
            width: 100%;
            margin-top: 20px;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: center;
        }
        th {
            background-color: #f4f4f4;
        }
    </style>
</head>
<body>

<h1>Android Ransomware Quiz</h1>

<div id="user-info">
    <input type="text" id="username" placeholder="Enter your name">
    <button onclick="startQuiz()">Start Quiz</button>
</div>

<div id="quiz-container" class="container" style="display:none;">
    <div class="question" id="question"></div>
    <div class="options" id="options"></div>
    <button id="next" onclick="nextQuestion()">Next Question</button>
    <div class="score" id="score"></div>
    <div class="result" id="result"></div>
</div>

<div id="result-container" class="container">
    <h2>Results</h2>
    <table id="result-table">
        <thead>
            <tr>
                <th>Name</th>
                <th>Score</th>
            </tr>
        </thead>
        <tbody>
        </tbody>
    </table>
</div>

<script>
    const questions = [
    { question: "What is Android ransomware?", options: ["A type of software designed to enhance device performance.", "A type of malicious software designed to block access to a user's device or data until a ransom is paid.", "A security feature provided by Android to protect user data.", "An app that provides ransom payment services."], answer: "B) A type of malicious software designed to block access to a user's device or data until a ransom is paid." },
        { question: "How does Android ransomware infect devices?", options: ["Through official app stores like Google Play.", "Via email attachments from known contacts.", "By downloading updates from reputable sources.", "Through various means, including malicious apps downloaded from unofficial app stores, phishing emails, and compromised software."], answer: "D) Through various means, including malicious apps downloaded from unofficial app stores, phishing emails, and compromised software." },
        { question: "What should you do if your Android device is infected with ransomware?", options: ["Ignore it and continue using your device as usual.", "Immediately pay the ransom to regain access to your device.", "Disconnect it from the internet, restart in safe mode, and use antivirus software to remove the ransomware.", "Contact your device manufacturer for a replacement."], answer: "C) Disconnect it from the internet, restart in safe mode, and use antivirus software to remove the ransomware." },
        { question: "Can paying the ransom guarantee that access to your device or data will be restored?", options: ["Yes, paying the ransom always guarantees access restoration.", "No, there is no guarantee that paying the ransom will result in access restoration.", "Only if the ransom is paid within 24 hours of infection.", "Paying the ransom restores access but deletes all user data."], answer: "B) No, there is no guarantee that paying the ransom will result in access restoration." },
        { question: "How can Android users protect themselves from ransomware?", options: ["By downloading apps only from unofficial app stores.", "By avoiding antivirus software.", "By keeping their device's operating system and apps up to date, and using reputable antivirus software.", "By clicking on every link received via email."], answer: "C) By keeping their device's operating system and apps up to date, and using reputable antivirus software." },
        { question: "What are some famous examples of Android ransomware?", options: ["\"Lockdroid\" and \"WannaLocker\".", "\"Netflix\" and \"Instagram\".", "\"Google Drive\" and \"WhatsApp\".", "\"Google Play Services\" and \"Chrome\"."], answer: "A) \"Lockdroid\" and \"WannaLocker\"." },
        { question: "Can Android ransomware affect all Android devices?", options: ["No, only devices running older versions of Android are vulnerable.", "Yes, Android ransomware can potentially affect any Android device.", "Only devices with antivirus software installed are at risk.", "No, only rooted Android devices are vulnerable."], answer: "B) Yes, Android ransomware can potentially affect any Android device." },
        { question: "Is it possible to remove Android ransomware without paying the ransom?", options: ["No, paying the ransom is the only way to remove Android ransomware.", "Yes, it's possible to remove Android ransomware without paying the ransom by using antivirus software.", "Yes, but only if the device is factory reset.", "No, once infected, the device is permanently compromised."], answer: "B) Yes, it's possible to remove  Android ransomware without paying the ransom by using antivirus software." },
        { question: "What actions should Android users take to recover from a ransomware attack?", options: ["Pay the ransom and continue using the device as usual.", "Contact law enforcement and file a report.", "Disconnect the infected device from the internet, scan with antivirus software, restore from backup, and change passwords for online accounts if necessary.", "Do nothing and hope the ransomware goes away on its own."], answer: "C) Disconnect the infected device from the internet, scan with antivirus software, restore from backup, and change passwords for online accounts if necessary." },
        { question: "Which of the following is NOT a common sign of an Android device being infected with ransomware?", options: ["Unusual pop-up messages demanding payment.", "Inability to access files or apps.", "Significant improvement in device performance.", "Sudden decrease in device performance."], answer: "C) Significant improvement in device performance." }

    ];

    let currentQuestionIndex = 0;
    let score = 0;
    let username = '';

    function startQuiz() {
        username = document.getElementById('username').value;
        if (username.trim() === '') {
            alert('Please enter your name.');
            return;
        }
        document.getElementById('user-info').style.display = 'none';
        document.getElementById('quiz-container').style.display = 'block';
        displayQuestion();
    }

    function displayQuestion() {
        const questionElement = document.getElementById('question');
        const optionsElement = document.getElementById('options');
        const scoreElement = document.getElementById('score');
        const currentQuestion = questions[currentQuestionIndex];

        questionElement.textContent = currentQuestion.question;
        optionsElement.innerHTML = '';
        scoreElement.textContent = `Score: ${score}`;

        currentQuestion.options.forEach(option => {
            const button = document.createElement('button');
            button.textContent = option;
            button.onclick = () => checkAnswer(option, button);
            optionsElement.appendChild(button);
        });
    }

    function checkAnswer(selectedOption, button) {
        const currentQuestion = questions[currentQuestionIndex];
        if (selectedOption === currentQuestion.answer) {
            button.classList.add('correct');
            score++;
        } else {
            button.classList.add('wrong');
        }
        disableOptions();
        document.getElementById('next').style.display = 'block';
    }

    function disableOptions() {
        const options = document.querySelectorAll('.options button');
        options.forEach(option => {
            option.disabled = true;
            if (option.textContent === questions[currentQuestionIndex].answer) {
                option.classList.add('correct');
            }
        });
    }

    function nextQuestion() {
        currentQuestionIndex++;
        if (currentQuestionIndex < questions.length) {
            displayQuestion();
            document.getElementById('next').style.display = 'none';
        } else {
            displayResult();
        }
    }

    function displayResult() {
        const resultElement = document.getElementById('result');
        const containerElement = document.querySelector('#quiz-container');
        const resultContainer = document.getElementById('result-container');

        resultElement.textContent = `Final Score: ${score} out of ${questions.length}`;
        if (score >= 17) {
            resultElement.classList.add('pass');
            resultElement.textContent += ' - Congratulations! You Passed!';
        } else {
            resultElement.classList.add('fail');
            resultElement.textContent += ' - Sorry! You Failed!';
        }

        // Save result to table
        const resultTableBody = document.querySelector('#result-table tbody');
        const newRow = document.createElement('tr');
        const nameCell = document.createElement('td');
        const scoreCell = document.createElement('td');

        nameCell.textContent = username;
        scoreCell.textContent = score;

        newRow.appendChild(nameCell);
        newRow.appendChild(scoreCell);
        resultTableBody.appendChild(newRow);

        containerElement.style.display = 'none';
        resultContainer.style.display = 'block';
    }
</script>

</body>
</html>

<body>

<div class="container">
    <h1>Ransomware on Android</h1>
    <div class="image-container">
        <!-- Add your image here -->
        <img src="Ransom3.jpg" alt="Ransomware on Android">
    </div>
    <p>Ransomware on Android is a type of malicious software specifically designed to target Android mobile devicesssss. Similar to ransomware targeting computers, Android ransomware encrypts the files or locks the device, preventing the user from accessing their data or using their device until a ransom is paid. Here's how Android ransomware typically works:</p>

    <h2 class="infection">Infection:</h2>
    <p>Android ransomware can infect devices through various means, including malicious apps downloaded from third-party app stores, phishing links, or even legitimate-looking apps that have been compromised.</p>

    <h2 class="encryption">Encryption or Locking:</h2>
    <p>Once installed on the device, the ransomware may encrypt the files stored on the device's storage or lock the device entirely, preventing the user from accessing their data or using their device.</p>

    <h2 class="ransom-demand">Ransom Demand:</h2>
    <p>After encrypting or locking the device, the ransomware displays a message demanding payment (usually in cryptocurrency) in exchange for providing the decryption key or unlocking the device. The message often includes instructions on how to pay the ransom.</p>

    <h2 class="threats">Threats:</h2>
    <p>In some cases, Android ransomware may also threaten the user with consequences such as permanent data loss or the dissemination of sensitive information if the ransom is not paid within a certain timeframe.</p>

    <h2 class="payment">Payment:</h2>
    <p>If the victim decides to pay the ransom, they are instructed on how to do so, typically through cryptocurrency transactions. However, there is no guarantee that paying the ransom will result in the decryption key or device unlock code being provided.</p>

    <p>Android Ransomware</p>
    <p>© 2024 Android Ransomware Awareness</p>
</div>
  <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Impact of Ransomware</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color: #f5f5f5;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #333;
        }
        p {
            color: #666;
            margin-bottom: 20px;
        }
        ul {
            list-style-type: disc;
            margin-bottom: 20px;
            padding-left: 20px;
        }
        .image-container {
            text-align: center;
            margin-bottom: 20px;
        }
        img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .financial-loss {
            color: #FF5722;
        }
        .data-loss {
            color: #03A9F4;
        }
        .operational-disruption {
            color: #FFC107;
        }
        .reputation-damage {
            color: #673AB7;
        }
    </style>
<body>

<div class="container">
    <h1 style="text-align: center; color: #009688;">The Impact of Ransomware</h1>
    <p>Ransomware attacks can have significant and wide-ranging impacts, affecting individuals, businesses, and entire communities. Here are some of the key impacts:</p>
    
    <ul>
        <li class="financial-loss"><strong>Financial Loss:</strong> Ransomware attacks can result in direct financial losses due to the ransom payment demanded by the attackers. Additionally, businesses may suffer indirect financial losses due to downtime, loss of productivity, and the cost of restoring systems and data.</li>
        <li class="data-loss"><strong>Data Loss or Theft:</strong> Ransomware attacks often involve the encryption or theft of sensitive data. If the victim does not have backups or refuses to pay the ransom, they may permanently lose access to their data or have it leaked or sold by the attackers.</li>
        <li class="operational-disruption"><strong>Operational Disruption:</strong> Ransomware attacks can disrupt normal business operations by locking access to critical systems and data. This can result in downtime, loss of revenue, and damage to the organization's reputation.</li>
        <li class="reputation-damage"><strong>Reputation Damage:</strong> Organizations that fall victim to ransomware attacks may suffer reputational damage due to the loss of customer trust and confidence. This can have long-term consequences for their business relationships and market standing.</li>
    </ul>

    <div class="image-container">
        <!-- Add your image here -->
        <img src="Ransom2.jpg" alt="Impact of Ransomware">
    </div>
</div>

   <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Prevention and Mitigation</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color: #f5f5f5;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #333;
        }
        p {
            color: #666;
            margin-bottom: 20px;
        }
        ol {
            list-style-type: decimal;
            margin-bottom: 20px;
            padding-left: 20px;
        }
        .image-container {
            text-align: center;
            margin-bottom: 20px;
        }
        img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
    </style>

<body>

<div class="container">
    <h1 style="text-align: center; color: #009688;">Prevention and Mitigation</h1>
    <p>Ransomware attacks can be devastating, but there are steps you can take to protect yourself and mitigate the impact. Here are some prevention and mitigation measures:</p>
    
    <ol>
        <li><strong style="color: #009688;">Integrate code with security tools and machine learning for ransomware reduction:</strong> Utilize advanced security tools and machine learning algorithms to detect and prevent ransomware attacks in real-time.</li>
        <li><strong style="color: #FF5722;">Daily data backups for contingency in case of incidents:</strong> Regularly back up your important data to secure locations, such as cloud storage or external drives, to ensure you can recover your files in case of a ransomware attack.</li>
        <li><strong style="color: #FFC107;">Download apps only from official stores like Play Store:</strong> Avoid downloading apps from third-party sources, as they may contain malicious code. Stick to reputable app stores like Google Play Store for downloading apps.</li>
        <li><strong style="color: #673AB7;">Stay informed about the latest security measures:</strong> Keep yourself updated about the latest developments in cybersecurity and ransomware prevention techniques. Subscribe to security blogs, forums, and newsletters to stay informed about emerging threats.</li>
        <li><strong style="color: #03A9F4;">Prioritize online safety through education and awareness:</strong> Educate yourself and your organization about ransomware threats and best practices for prevention. Conduct regular cybersecurity awareness training sessions to ensure everyone knows how to recognize and respond to ransomware attacks effectively.</li>
    </ol>

    <div class="image-container">
       
        <img src="Ransom4.jpg" alt="Prevention and Mitigation">
    </div>
</div>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Motivation and Aim of Ransomware</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color: #f0f0f0;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        h1, h2, h3 {
            color: #333;
        }
        p {
            margin-bottom: 20px;
        }
        ul {
            list-style-type: disc;
            margin-bottom: 20px;
            padding-left: 20px;
        }
        li {
            margin-bottom: 10px;
        }
        .image-container {
            text-align: center;
            margin-bottom: 20px;
        }
        img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .financial {
            color: #009688;
        }
        .disruption {
            color: #FF5722;
        }
        .revenge {
            color: #673AB7;
        }
        .political {
            color: #FFC107;
        }
        .espionage {
            color: #03A9F4;
        }
    </style>
<body>

<div class="container">
    <h1>Motivation and Aim of Ransomware</h1>
    <div class="image-container">
        <!-- Add your image here -->
        <img src="Ransom5.jpg" alt="Ransomware Motivation">
    </div>
    <p>Ransomware attacks are motivated by various factors and aims, including:</p>
    <ul>
        <li class="financial"><strong>Financial Gain:</strong> One of the primary motivations behind ransomware attacks is financial gain. Attackers aim to extort money from individuals, businesses, or organizations by encrypting their files or locking their devices and demanding payment (usually in cryptocurrency) in exchange for providing the decryption key or unlocking the device.</li>
        <li class="disruption"><strong>Disruption and Chaos:</strong> Some attackers may aim to cause disruption and chaos by targeting critical infrastructure, essential services, or high-profile organizations.</li>
        <li class="revenge"><strong>Revenge or Retaliation:</strong> In some cases, ransomware attacks may be motivated by personal grievances or vendettas against specific individuals, businesses, or organizations. Attackers may seek revenge for perceived wrongs or seek to retaliate against competitors, rivals, or adversaries.</li>
        <li class="political"><strong>Political or Ideological Motives:</strong> Certain ransomware attacks may be motivated by political or ideological beliefs. Hacktivist groups or state-sponsored actors may target specific organizations or governments to promote a particular agenda, protest against perceived injustices, or disrupt political or social systems.</li>
        <li class="espionage"><strong>Espionage and Intelligence Gathering:</strong> In some cases, ransomware attacks may be used as a cover for espionage or intelligence gathering activities. Attackers may use ransomware to encrypt or steal sensitive data, such as trade secrets, intellectual property, or classified information, for use in future attacks or for sale on the black market.</li>
    </ul>
</div>
 <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Critical Problems Caused by Ransomware</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color: #f0f0f0;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        h1, h2, h3 {
            color: #333;
        }
        p {
            margin-bottom: 20px;
        }
        ul {
            list-style-type: disc;
            margin-bottom: 20px;
            padding-left: 20px;
        }
        li {
            margin-bottom: 10px;
        }
        .image-container {
            text-align: center;
            margin-bottom: 20px;
        }
        img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .data-loss {
            color: #FF5722;
        }
        .financial-loss {
            color: #03A9F4;
        }
        .reputational-damage {
            color: #FFC107;
        }
        .operational-disruption {
            color: #673AB7;
        }
        .infrastructure-vulnerabilities {
            color: #4CAF50;
        }
    </style>
<body>

<div class="container">
    <h1>Critical Problems Caused by Ransomware</h1>
    <div class="image-container">
        <!-- Add your image here -->
        <img src="Ransom6.jpg" alt="Ransomware Problems">
    </div>
    <ul>
        <li class="data-loss"><strong>Data Loss and Theft:</strong> Ransomware attacks can result in the loss or theft of sensitive data, including personal information, financial records, intellectual property, and proprietary business data.</li>
        <li class="financial-loss"><strong>Financial Losses:</strong> Ransomware attacks can cause direct financial losses due to ransom payments, as well as indirect costs associated with downtime, lost productivity, forensic investigations, data recovery efforts, and legal expenses.</li>
        <li class="reputational-damage"><strong>Reputational Damage:</strong> Organizations that fall victim to ransomware attacks may suffer reputational damage due to the loss of customer trust and confidence.</li>
        <li class="operational-disruption"><strong>Operational Disruption:</strong> Ransomware attacks can disrupt normal business operations by locking access to critical systems and data, causing downtime, and disrupting supply chains and service delivery.</li>
        <li class="infrastructure-vulnerabilities"><strong>Critical Infrastructure Vulnerabilities:</strong> Ransomware attacks targeting critical infrastructure can have severe consequences for public safety, national security, and economic stability.</li>
    </ul>
</div>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Protecting Your Android Device from Ransomware</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color: #f0f0f0;
        }
        h1, h2, h3 {
            color: #333;
        }
        p {
            margin-bottom: 20px;
        }
        ol {
            margin-bottom: 20px;
            padding-left: 20px;
        }
        li {
            margin-bottom: 10px;
        }
        .tip {
            margin-bottom: 30px;
            padding: 20px;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .tip h3 {
            margin-top: 0;
        }
        .tip p:last-child {
            margin-bottom: 0;
        }
    </style>
<body>

<h1>Protecting Your Android Device from Ransomware</h1>

<div class="tip">
    <h3>1. Install Antivirus Software</h3>
    <p>Antivirus software can detect and remove ransomware from your device.</p>
    <p>Recommended antivirus apps:</p>
    <ul>
        <li><a href="#">Avast Mobile Security</a> - Offers real-time protection, scanning of installed apps and memory card content, and anti-theft features.</li>
        <li><a href="#">Bitdefender Mobile Security</a> - Provides on-demand and on-install scanning, anti-theft features, app lock, and web security.</li>
        <li><a href="#">Norton Mobile Security</a> - Includes antivirus, anti-malware, and anti-phishing features, as well as app scanning and privacy protection.</li>
    </ul>
    <p>Install an antivirus app from a reputable provider and keep it updated regularly to stay protected against the latest threats.</p>
</div>

<div class="tip">
    <h3>2. Keep Software Up-to-Date</h3>
    <p>Regularly update your device's operating system and apps to patch security vulnerabilities.</p>
    <p>Go to Settings > About phone > Software update to check for updates.</p>
    <p>Enable automatic updates for added convenience and security. Additionally, consider enabling automatic app updates from the Google Play Store.</p>
</div>

<div class="tip">
    <h3>3. Avoid Suspicious Links and Downloads</h3>
    <p>Be cautious when clicking on links or downloading files from unknown sources.</p>
    <p>Only download apps from the official Google Play Store to reduce the risk of malware. Avoid sideloading apps from third-party sources unless absolutely necessary.</p>
    <p>Use a secure browser with built-in protection against malicious websites. Look out for HTTPS encryption and verify website URLs before entering sensitive information.</p>
</div>

<div class="tip">
    <h3>4. Back Up Important Data</h3>
    <p>Regularly back up your data to a secure location to prevent loss in case of a ransomware attack.</p>
    <p>Use cloud storage services like Google Drive, Dropbox, or OneDrive for convenient and secure backups. Ensure that automatic backup features are enabled for important data such as photos, videos, and documents.</p>
    <p>Consider using a dedicated backup app for additional control and customization. Test your backups periodically to ensure their integrity and accessibility.</p>
</div>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>URL Spoofing</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color: #f5f5f5;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #333;
        }
        p {
            color: #666;
            margin-bottom: 20px;
        }
        .spoofing-method {
            margin-bottom: 20px;
            padding: 10px;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .spoofing-method h3 {
            color: #009688;
        }
        .spoofing-method p {
            color: #333;
        }
    </style>
<body>

<div class="container">
    <h1 style="text-align: center; color: #009688;">What is URL Spoofing?</h1>
    <p>A spoofed URL is a fraudulent link that is masked to look like a legitimate source in order to steal your data.</p>

    <div class="spoofing-method">
        <h3>4 MAIN WAYS OF URL Spoofing</h3>
        <p><strong>1. Misspelled links:</strong> People tend to skim read messages, which means hackers can send phishing emails with links that look just like trusted ones. It is enough to just change 1 character to register a new domain.</p>
        <p><strong>2. URL Shorteners:</strong> Another common way to spoof URLs is by using URL shorteners like bit.ly. However, they also make it easier for scammers to hide malicious links.</p>
        <p><strong>3. Links behind buttons or words:</strong> Hackers may send phishing emails pretending to be a trusted source and hyperlink malicious links to buttons or words. This trick is still used today, but it's relatively easy to spot.</p>
        <p><strong>4. Links with non-Latin Characters:</strong> The use of new scripts to register domains has created more opportunities for hackers. They can now use non-Latin characters to create homographic URLs, which look like Latin characters but come from a different alphabet. These URLs can deceive internet users into clicking on malicious links.</p>
    </div>

    <p style="text-align: center;"><strong>Android Ransomware</strong><br>© 2024 Android Ransomware Awareness</p>
</div>
  <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Android Ransomware Quiz</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }
        h1 {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            margin: 0;
        }
        .container {
            margin: 50px auto;
            width: 80%;
            max-width: 600px;
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .question {
            font-size: 20px;
            margin-bottom: 20px;
        }
        .options button {
            display: block;
            margin: 10px auto;
            padding: 10px;
            width: 80%;
            max-width: 400px;
            font-size: 16px;
            cursor: pointer;
            border: 1px solid #ddd;
            background-color: #f9f9f9;
            border-radius: 5px;
        }
        .options button.correct {
            background-color: #4CAF50;
            color: white;
        }
        .options button.wrong {
            background-color: #f44336;
            color: white;
        }
        #next {
            display: none;
            margin-top: 20px;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
        }
        .score {
            font-size: 18px;
            margin-top: 20px;
            color: #333;
        }
        .result {
            font-size: 24px;
            font-weight: bold;
            margin-top: 20px;
        }
        .pass {
            color: #4CAF50;
        }
        .fail {
            color: #f44336;
        }
    </style>

<body>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Android Ransomware Quiz</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }
        h1 {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            margin: 0;
        }
        .container {
            margin: 50px auto;
            width: 80%;
            max-width: 600px;
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .question {
            font-size: 20px;
            margin-bottom: 20px;
        }
        .options button {
            display: block;
            margin: 10px auto;
            padding: 10px;
            width: 80%;
            max-width: 400px;
            font-size: 16px;
            cursor: pointer;
            border: 1px solid #ddd;
            background-color: #f9f9f9;
            border-radius: 5px;
        }
        .options button.correct {
            background-color: #4CAF50;
            color: white;
        }
        .options button.wrong {
            background-color: #f44336;
            color: white;
        }
        #next {
            display: none;
            margin-top: 20px;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
        }
        .score {
            font-size: 18px;
            margin-top: 20px;
            color: #333;
        }
        .result {
            font-size: 24px;
            font-weight: bold;
            margin-top: 20px;
        }
        .pass {
            color: #4CAF50;
        }
        .fail {
            color: #f44336;
        }
        #user-info {
            margin-top: 20px;
        }
        #user-info input {
            padding: 10px;
            font-size: 16px;
            width: 80%;
            max-width: 400px;
            margin-bottom: 20px;
        }
        #user-info button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
        }
        #result-container {
            display: none;
        }
        table {
            width: 100%;
            margin-top: 20px;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: center;
        }
        th {
            background-color: #f4f4f4;
        }
    </style>
</head>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Android Ransomware Quiz</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }
        h1 {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            margin: 0;
        }
        .container {
            margin: 50px auto;
            width: 80%;
            max-width: 600px;
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .question {
            font-size: 20px;
            margin-bottom: 20px;
        }
        .options button {
            display: block;
            margin: 10px auto;
            padding: 10px;
            width: 80%;
            max-width: 400px;
            font-size: 16px;
            cursor: pointer;
            border: 1px solid #ddd;
            background-color: #f9f9f9;
            border-radius: 5px;
        }
        .options button.correct {
            background-color: #4CAF50;
            color: white;
        }
        .options button.wrong {
            background-color: #f44336;
            color: white;
        }
        #next {
            display: none;
            margin-top: 20px;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
        }
        .score {
            font-size: 18px;
            margin-top: 20px;
            color: #333;
        }
        .result {
            font-size: 24px;
            font-weight: bold;
            margin-top: 20px;
        }
        .pass {
            color: #4CAF50;
        }
        .fail {
            color: #f44336;
        }
        #user-info {
            margin-top: 20px;
        }
        #user-info input {
            padding: 10px;
            font-size: 16px;
            width: 80%;
            max-width: 400px;
            margin-bottom: 20px;
        }
        #user-info button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
        }
        #result-container {
            display: none;
        }
        table {
            width: 100%;
            margin-top: 20px;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: center;
        }
        th {
            background-color: #f4f4f4;
        }
    </style>
</head>
<body>

<h1>Android Ransomware Quiz</h1>

<div id="user-info">
    <input type="text" id="username" placeholder="Enter your name">
    <button onclick="startQuiz()">Start Quiz</button>
</div>

<div id="quiz-container" class="container" style="display:none;">
    <div class="question" id="question"></div>
    <div class="options" id="options"></div>
    <button id="next" onclick="nextQuestion()">Next Question</button>
    <div class="score" id="score"></div>
    <div class="result" id="result"></div>
</div>

<div id="result-container" class="container">
    <h2>Results</h2>
    <table id="result-table">
        <thead>
            <tr>
                <th>Name</th>
                <th>Score</th>
            </tr>
        </thead>
        <tbody>
        </tbody>
    </table>
</div>

<script>
    const questions = [
        { question: "What is Android ransomware?", options: ["A type of malware that encrypts the user's files and demands payment for decryption", "A security feature in Android devices to protect against ransomware attacks", "A type of app that enhances the performance of Android devices", "A feature in Android devices for backing up data automatically"], answer: "A type of malware that encrypts the user's files and demands payment for decryption" },
        { question: "Which encryption algorithm is commonly used in Android ransomware?", options: ["MD5", "SHA-1", "AES", "RSA"], answer: "AES" },
        { question: "What is obfuscation in the context of Android ransomware?", options: ["A technique to hide the ransomware's code and make it harder to analyze", "A method for encrypting the victim's files", "A feature in Android devices for securing sensitive data", "A tool for removing ransomware from infected devices"], answer: "A technique to hide the ransomware's code and make it harder to analyze" },
        { question: "How do attackers distribute Android ransomware?", options: ["Through malicious links, email attachments, or fake apps", "Through official app stores like Google Play", "Through system updates pushed by the device manufacturer", "Through antivirus software"], answer: "Through malicious links, email attachments, or fake apps" },
        { question: "Which payment method is commonly used by attackers in Android ransomware attacks?", options: ["Credit card", "Bank transfer", "Cryptocurrency", "PayPal"], answer: "Cryptocurrency" },
        { question: "What is the purpose of dynamic code loading in Android ransomware?", options: ["To download and execute malicious code at runtime", "To encrypt the victim's files", "To hide the ransomware's code from detection", "To decrypt the victim's files"], answer: "To download and execute malicious code at runtime" },
        { question: "What is the consequence of not paying the ransom in an Android ransomware attack?", options: ["The victim's files will be decrypted for free", "The attacker will release the victim's files without any harm", "The victim's files will remain encrypted and inaccessible", "The attacker will delete the victim's files"], answer: "The victim's files will remain encrypted and inaccessible" },
        { question: "How can users protect their Android devices from ransomware attacks?", options: ["By installing antivirus software and keeping it up to date", "By disabling security features on their devices", "By downloading apps from third-party app stores", "By sharing personal information with unknown sources"], answer: "By installing antivirus software and keeping it up to date" },
        { question: "What is a common sign that a device may be infected with ransomware?", options: ["The device's battery drains unusually fast", "The device displays a ransom note demanding payment", "The device automatically updates its software frequently", "The device's screen flickers intermittently"], answer: "The device displays a ransom note demanding payment" },
        { question: "What is the primary goal of Android ransomware?", options: ["To steal the user's personal information", "To encrypt the user's files and demand a ransom for decryption", "To display unwanted advertisements", "To improve the device's performance"], answer: "To encrypt the user's files and demand a ransom for decryption" },
        { question: "What should a user do if their Android device is infected with ransomware?", options: ["Pay the ransom immediately", "Disconnect from the internet and seek professional help", "Restart the device in safe mode", "Ignore the ransom note and continue using the device"], answer: "Disconnect from the internet and seek professional help" },
        { question: "How can users avoid downloading malicious apps that may contain ransomware?", options: ["By downloading apps only from reputable sources like Google Play Store", "By disabling antivirus software", "By installing as many apps as possible to confuse the ransomware", "By never updating their device"], answer: "By downloading apps only from reputable sources like Google Play Store" },
        { question: "What role does social engineering play in Android ransomware attacks?", options: ["It tricks users into installing the ransomware", "It encrypts the user's files", "It decrypts the user's files after payment", "It improves the device's performance"], answer: "It tricks users into installing the ransomware" },
        { question: "Why is code signing used in Android ransomware?", options: ["To make the ransomware appear legitimate", "To increase the speed of encryption", "To reduce the size of the ransomware file", "To ensure the ransomware is open-source"], answer: "To make the ransomware appear legitimate" },
        { question: "What is the purpose of a ransom note in ransomware attacks?", options: ["To provide instructions on how to decrypt the files for free", "To inform the victim that their files have been encrypted and howto pay the ransom", "To apologize for the inconvenience caused", "To offer a reward for detecting the ransomware"], answer: "To inform the victim that their files have been encrypted and how to pay the ransom" },
        { question: "What is string obfuscation in the context of ransomware?", options: ["Hiding the code that encrypts the files", "Encrypting the strings in the ransomware's code to make it harder to analyze", "Making the user interface more user-friendly", "Encrypting the user's passwords"], answer: "Encrypting the strings in the ransomware's code to make it harder to analyze" },
        { question: "How can dynamic code loading benefit ransomware?", options: ["By reducing the size of the initial ransomware payload", "By allowing the ransomware to download additional malicious components at runtime", "By making the ransomware open-source", "By improving the performance of the device"], answer: "By allowing the ransomware to download additional malicious components at runtime" },
        { question: "What is a common feature of ransomware payment instructions?", options: ["Detailed steps on how to purchase cryptocurrency", "Instructions on contacting law enforcement", "Information on how to uninstall the ransomware", "Suggestions for improving device security"], answer: "Detailed steps on how to purchase cryptocurrency" },
        { question: "What is a potential consequence of paying the ransom in a ransomware attack?", options: ["Guaranteed recovery of all encrypted files", "Increased likelihood of future attacks", "Immediate protection from future ransomware attacks", "Legal immunity from any further attacks"], answer: "Increased likelihood of future attacks" },
        { question: "Why is RSA encryption used alongside AES in some ransomware attacks?", options: ["To provide a secondary layer of encryption for additional security", "To encrypt the AES encryption key, making it harder to decrypt the files without the RSA key", "To make the ransomware open-source", "To speed up the encryption process"], answer: "To encrypt the AES encryption key, making it harder to decrypt the files without the RSA key" }
    ];

    let currentQuestionIndex = 0;
    let score = 0;
    let username = '';

    function startQuiz() {
        username = document.getElementById('username').value;
        if (username.trim() === '') {
            alert('Please enter your name.');
            return;
        }
        document.getElementById('user-info').style.display = 'none';
        document.getElementById('quiz-container').style.display = 'block';
        displayQuestion();
    }

    function displayQuestion() {
        const questionElement = document.getElementById('question');
        const optionsElement = document.getElementById('options');
        const scoreElement = document.getElementById('score');
        const currentQuestion = questions[currentQuestionIndex];

        questionElement.textContent = currentQuestion.question;
        optionsElement.innerHTML = '';
        scoreElement.textContent = `Score: ${score}`;

        currentQuestion.options.forEach(option => {
            const button = document.createElement('button');
            button.textContent = option;
            button.onclick = () => checkAnswer(option, button);
            optionsElement.appendChild(button);
        });
    }

    function checkAnswer(selectedOption, button) {
        const currentQuestion = questions[currentQuestionIndex];
        if (selectedOption === currentQuestion.answer) {
            button.classList.add('correct');
            score++;
        } else {
            button.classList.add('wrong');
        }
        disableOptions();
        document.getElementById('next').style.display = 'block';
    }

    function disableOptions() {
        const options = document.querySelectorAll('.options button');
        options.forEach(option => {
            option.disabled = true;
            if (option.textContent === questions[currentQuestionIndex].answer) {
                option.classList.add('correct');
            }
        });
    }

    function nextQuestion() {
        currentQuestionIndex++;
        if (currentQuestionIndex < questions.length) {
            displayQuestion();
            document.getElementById('next').style.display = 'none';
        } else {
            displayResult();
        }
    }

    function displayResult() {
        const resultElement = document.getElementById('result');
        const containerElement = document.querySelector('#quiz-container');
        const resultContainer = document.getElementById('result-container');

        resultElement.textContent = `Final Score: ${score} out of ${questions.length}`;
        if (score >= 17) {
            resultElement.classList.add('pass');
            resultElement.textContent += ' - Congratulations! You Passed!';
        } else {
            resultElement.classList.add('fail');
            resultElement.textContent += ' - Sorry! You Failed!';
        }

        // Save result to table
        const resultTableBody = document.querySelector('#result-table tbody');
        const newRow = document.createElement('tr');
        const nameCell = document.createElement('td');
        const scoreCell = document.createElement('td');

        nameCell.textContent = username;
        scoreCell.textContent = score;

        newRow.appendChild(nameCell);
        newRow.appendChild(scoreCell);
        resultTableBody.appendChild(newRow);

        containerElement.style.display = 'none';
        resultContainer.style.display = 'block';
    }
</script>


</body>
</html>

<body>

<div class="container">
    <h1 style="text-align: center; color: #009688;">How do Hackers Try to Do Ransom?</h1>
    <p>Hackers attempt to carry out ransomware attacks through various methods, but the primary objective is to gain unauthorized access to a system or network, encrypt important files or data, and then demand payment (usually in cryptocurrency) from the victim to provide the decryption key. Here's a general overview of how hackers typically execute ransomware attacks:</p>
    
    <div class="attack-method">
        <h3>Phishing Emails</h3>
        <p>One common method is through phishing emails. Attackers send emails that appear to be from legitimate sources, often containing malicious links or attachments. When users click on these links or download attachments, it installs the ransomware onto their system.</p>
    </div>

    <div class="attack-method">
        <h3>Exploiting Vulnerabilities</h3>
        <p>Hackers exploit vulnerabilities in software or operating systems to gain access to systems or networks. They often target systems that haven't been updated with the latest security patches, making them more susceptible to exploitation.</p>
    </div>

    <div class="attack-method">
        <h3>Remote Desktop Protocol (RDP) Attacks</h3>
        <p>Attackers may exploit weak or default credentials for Remote Desktop Protocol (RDP) connections to gain access to systems. Once inside, they can deploy ransomware across the network.</p>
    </div>

    <div class="attack-method">
        <h3>Social Engineering</h3>
        <p>Sometimes hackers use social engineering techniques to trick employees or users into providing access credentials or other sensitive information, which they then use to access systems and deploy ransomware.</p>
    </div>

    <div class="attack-method">
        <h3>Brute Force Attacks</h3>
        <p>Hackers use automated tools to repeatedly guess usernames and passwords until they gain access to a system or network. Once inside, they deploy ransomware.</p>
    </div>

    <p style="text-align: center;"><strong>Android Ransomware</strong><br>© 2024 Android Ransomware Awareness</p>
</div>
<meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Android Ransomware Awareness</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            color: #333;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #007bff;
        }
        label {
            font-weight: bold;
            color: #555;
        }
        input[type="text"],
        textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
            border-radius: 4px;
            resize: vertical;
        }
        input[type="submit"] {
            background-color: #007bff;
            color: #fff;
            border: none;
            padding: 12px 20px;
            border-radius: 4px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        input[type="submit"]:hover {
            background-color: #0056b3;
        }
    </style>
<body>
    <div class="container">
        <h1>Android Ransomware Awareness</h1>
        <p>Welcome to our website dedicated to raising awareness about Android ransomware. We value your feedback!</p>
        <form action="#" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="feedback">Feedback/Question/Issue:</label>
            <textarea id="feedback" name="feedback" rows="5" required></textarea>

            <input type="submit" value="Submit">
        </form>
    </div>
<meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personalized Tips for Cybersecurity</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            color: #333;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #007bff;
        }
        p {
            margin-bottom: 20px;
        }
        .tip {
            margin-bottom: 20px;
            padding: 10px;
            background-color: #f9f9f9;
            border-left: 4px solid #007bff;
            border-radius: 4px;
        }
    </style>
<body>
    <div class="container">
        <h1>Personalized Tips for Cybersecurity</h1>
        <p>Here are some personalized tips and recommendations based on your browsing behavior:</p>

        <!-- Placeholder for personalized tips -->
        <div id="personalizedTips">
            <div class="tip">
                <h3>Tip 1: Use Strong Passwords</h3>
                <p>Ensure your passwords are complex and unique for each account to prevent unauthorized access.</p>
            </div>
            <div class="tip">
                <h3>Tip 2: Enable Two-Factor Authentication (2FA)</h3>
                <p>Enhance your account security by enabling two-factor authentication wherever possible.</p>
            </div>
            <!-- You can add more personalized tips here -->
        </div>
    </div>

    <!-- Script to fetch personalized tips from the backend -->
    <script>
        // Simulated personalized tips (replace this with actual data retrieval from your backend)
        var personalizedTips = [
            { tip: "Tip 3: Keep Software Updated", description: "Regularly update your operating system and software to patch security vulnerabilities." },
            { tip: "Tip 4: Be Wary of Phishing Emails", description: "Avoid clicking on suspicious links or downloading attachments from unknown senders." }
            // Add more personalized tips as needed
        ];

        // Function to display personalized tips
        function displayPersonalizedTips() {
            var personalizedTipsContainer = document.getElementById("personalizedTips");
            personalizedTips.forEach(function(tip) {
                var tipHtml = "<div class='tip'>" +
                                "<h3>" + tip.tip + "</h3>" +
                                "<p>" + tip.description + "</p>" +
                              "</div>";
                personalizedTipsContainer.innerHTML += tipHtml;
            });
        }

        // Call the function to display personalized tips when the page loads
        window.onload = displayPersonalizedTips;
    </script>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Share Cybersecurity Tips</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            color: #333;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #007bff;
        }
        .share-buttons {
            margin-top: 20px;
        }
        .share-button {
            display: inline-block;
            margin-right: 10px;
            border-radius: 4px;
            overflow: hidden;
            cursor: pointer;
            transition: transform 0.3s ease;
        }
        .share-button img {
            width: 60px;
            height: 60px;
            object-fit: cover;
            border-radius: 50%;
            border: 2px solid #007bff;
        }
        .share-button:hover {
            transform: scale(1.1);
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Share Cybersecurity Tips</h1>
        <p>Help spread awareness about cybersecurity by sharing valuable tips with your friends and followers!</p>

        <div class="share-buttons">
            <div class="share-button" onclick="shareOnFacebook()">
                <img src="fb.jpg" alt="Facebook">
            </div>
            <div class="share-button" onclick="shareOnTwitter()">
                <img src="x.jpg" alt="Twitter">
            </div>
            <div class="share-button" onclick="shareOnWhatsApp()">
                <img src="wa.jpg" alt="WhatsApp">
            </div>
            <div class="share-button" onclick="shareOnInstagram()">
                <img src="ig.jpg" alt="Instagram">
            </div>
            <!-- Add more social media buttons as needed -->
        </div>
    </div>

    <!-- JavaScript functions for social media sharing -->
    <script>
        function shareOnFacebook() {
            // Replace "YOUR_URL" with the URL you want to share
            var url = "YOUR_URL";
            window.open("https://www.facebook.com/sharer/sharer.php?u=" + encodeURIComponent(url), "_blank");
        }

        function shareOnTwitter() {
            // Replace "YOUR_URL" with the URL you want to share
            var url = "YOUR_URL";
            window.open("https://twitter.com/intent/tweet?url=" + encodeURIComponent(url), "_blank");
        }

        function shareOnWhatsApp() {
            // Replace "YOUR_URL" with the URL you want to share
            var url = "YOUR_URL";
            window.open("https://api.whatsapp.com/send?text=" + encodeURIComponent(url), "_blank");
        }

        function shareOnInstagram() {
            // Replace "YOUR_URL" with the URL you want to share
            var url = "YOUR_URL";
            window.open("https://www.instagram.com/share?url=" + encodeURIComponent(url), "_blank");
        }

        // Add more functions for other social media platforms if needed
    </script>
</body>
</html>

    <div class="container">
        <h1>Android Ransomware Awareness</h1>

        <!-- Downloadable Guides Section -->
        <div class="section">
            <h2 class="section-title">Downloadable Guides</h2>
            <div class="guide">
                <div class="card">
                    <h3>Guide 1: Protecting Against Ransomware</h3>
                    <p>This guide covers the best practices to keep your devices safe from ransomware attacks, including tips on secure browsing, software updates, and more.</p>
                    <a href="https://www.cisa.gov/stopransomware/how-can-i-protect-against-ransomware" class="button">Click the link</a>
                </div>
                <div class="card">
                    <h3>Guide 2: Steps to Take if Infected</h3>
                    <p>If you suspect your device is infected, this guide provides step-by-step instructions on immediate actions to minimize damage and recover your data.</p>
                    <a href="https://www.avast.com/c-how-to-remove-ransomware-android#:~:text=Focus%20on%20prevention%201%201.%20Immediately%20isolate%20infected,dealing%20with.%20...%203%203.%20Remove%20the%20ransomware" class="button">Click the link</a>
                </div>
                <div class="card">
                    <h3>Guide 3: Recovery Plan</h3>
                    <p>Develop a comprehensive recovery plan with this guide, including backup strategies, data recovery options, and how to prevent future attacks.</p>
                    <a href="https://www.crowdstrike.com/cybersecurity-101/ransomware/ransomware-recovery/" class="button">Click the link</a>
                </div>
            </div>
        </div>

        <!-- Tool Recommendations Section -->
        <div class="section">
            <h2 class="section-title">Tool Recommendations</h2>
            <div class="tools">
                <div class="card">
                    <h3>Tool 1: Antivirus Software</h3>
                    <p>Protect your devices with top-rated antivirus software. Check out our recommendations for the best options available.</p>
                    <a href="https://www.malwarebytes.com/mwb-download" class="button" target="_blank">View Tools</a>
                </div>
                <div class="card">
                    <h3>Tool 2: Ransomware Protection</h3>
                    <p>Discover specialized tools designed to prevent and remove ransomware from your devices. Learn more about these essential tools.</p>
                    <a href="https://www.kaspersky.com/anti-ransomware-tool" class="button" target="_blank">View Tools</a>
                </div>
                <div class="card">
                    <h3>Tool 3: Backup Solutions</h3>
                    <p>Ensure your data is safe with reliable backup solutions. Explore our top picks for cloud and local backup services.</p>
                    <a href="https://www.techradar.com/best/best-backup-software" class="button" target="_blank">View Tools</a>
                </div>
            </div>
        </div>
    </div>

  <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Recovery Stories</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f4f7f6;
            color: #333;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: #ffffff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #007bff;
            text-align: center;
        }
        .section {
            margin-bottom: 40px;
            padding: 20px;
        }
        .section-title {
            border-bottom: 3px solid #007bff;
            padding-bottom: 10px;
            margin-bottom: 20px;
            text-align: center;
        }
        .stories {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            gap: 20px;
        }
        .story-card {
            background-color: #e9f5ff;
            border-radius: 10px;
            padding: 20px;
            width: 45%;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            position: relative;
            overflow: hidden;
        }
        .story-card h3 {
            color: #0056b3;
        }
        .story-card p {
            color: #333;
        }
        .story-card .button {
            display: inline-block;
            background-color: #007bff;
            color: #fff;
            padding: 10px 20px;
            border-radius: 4px;
            text-decoration: none;
            transition: background-color 0.3s ease;
        }
        .story-card .button:hover {
            background-color: #0056b3;
        }
        .story-card:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }
        .story-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(135deg, rgba(0, 123, 255, 0.15) 0%, rgba(255, 255, 255, 0) 100%);
            z-index: 0;
            opacity: 0.5;
            transition: opacity 0.3s ease;
        }
        .story-card:hover::before {
            opacity: 0.8;
        }
        .story-card .content {
            position: relative;
            z-index: 1;
        }
        .external-link {
            color: #007bff;
            text-decoration: none;
            transition: color 0.3s ease;
        }
        .external-link:hover {
            color: #0056b3;
        }
    </style>
<body>
    <div class="container">
        <h1>Recovery Stories</h1>

        <!-- Recovery Stories Section -->
        <div class="section">
            <h2 class="section-title">Success Stories</h2>
            <div class="stories">
                <div class="story-card">
                    <div class="content">
                        <h3>Story 1: ABC Corp's Swift Recovery</h3>
                        <p>ABC Corp faced a severe ransomware attack that encrypted their critical data. Learn how they swiftly recovered using robust backup strategies and professional cybersecurity help. <a href="https://www.csoonline.com/article/3533453/ransomware-attacks-case-studies-and-examples.html" class="external-link" target="_blank">Read full story</a></p>
                        <a href="https://www.marshmclennan.com/insights/publications/2021/may/surviving-a-ransomware-attack.html" class="button" target="_blank">Read More</a>
                    </div>
                </div>
                <div class="story-card">
                    <div class="content">
                        <h3>Story 2: Freelance Designer's Data Rescue</h3>
                        <p>When a freelance designer's work files were locked by ransomware, they feared losing everything. Discover how regular backups and quick action saved their business. <a href="https://www.bbc.com/news/technology-54427092" class="external-link" target="_blank">Read full story</a></p>
                        <a href="https://blog.icons8.com/articles/the-best-cybersecurity-practices-for-freelance-designers/" class="button" target="_blank">Read More</a>
                    </div>
                </div>
                <div class="story-card">
                    <div class="content">
                        <h3>Story 3: Healthcare Provider's Secure Recovery</h3>
                        <p>A healthcare provider's patient data was targeted by a ransomware attack. Find out how they protected sensitive information and restored operations without paying the ransom. <a href="https://www.zdnet.com/article/how-this-hospital-recovered-from-a-ransomware-attack-without-paying-the-ransom/" class="external-link" target="_blank">Read full story</a></p>
                        <a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9856685/" class="button" target="_blank">Read More</a>
                    </div>
                </div>
                <div class="story-card">
                    <div class="content">
                        <h3>Story 4: Small Business's Fight Back</h3>
                        <p>A small business's systems were compromised by ransomware. Learn about their recovery journey and the steps they took to fortify their cybersecurity defenses. <a href="https://www.kaspersky.com/blog/small-business-recovery-ransomware/38604/" class="external-link" target="_blank">Read full story</a></p>
                        <a href="https://www.researchgate.net/publication/380360965_Cybersecurity_Challenges_and_Solutions_for_Small_Businesses" class="button" target="_blank">Read More</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>

