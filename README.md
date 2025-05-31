# Nsc-grade-10-12-previous-question-papers-
papers = [     {"grade": "10", "subject": "Mathematics", "year": "2022"},     {"grade": "11", "subject": "Physical Sciences", "year": "2022"}, 
<!DOCTYPE html>
<html>
<head>
    <title>NSC App</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .container {
            max-width: 800px;
            margin: 40px auto;
            padding: 20px;
            background-color: #f9f9f9;
            border: 1px solid #ddd;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>NSC App</h1>
        <p>Created by Ntsako Malungane</p>
        <h2>Select Grade:</h2>
        <select id="grade">
            <option value="10">Grade 10</option>
            <option value="11">Grade 11</option>
            <option value="12">Grade 12</option>
        </select>
        <h2>Select Subject:</h2>
        <select id="subject">
            <option value="Mathematics">Mathematics</option>
            <option value="Physical Sciences">Physical Sciences</option>
            <option value="Life Sciences">Life Sciences</option>
        </select>
        <button id="get-paper-btn">Get Paper</button>
        <div id="paper-display"></div>
    </div>

    <script>
        const gradeSelect = document.getElementById('grade');
        const subjectSelect = document.getElementById('subject');
        const getPaperBtn = document.getElementById('get-paper-btn');
        const paperDisplay = document.getElementById('paper-display');

        getPaperBtn.addEventListener('click', () => {
            const grade = gradeSelect.value;
            const subject = subjectSelect.value;
            paperDisplay.innerHTML = `
                <h2>${subject} Paper for Grade ${grade}</h2>
                <p>Paper content will be displayed here.</p>
            `;
        });
    </script>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
    <title>NSC App</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
        }
    </style>
</head>
<body>
    <h1>NSC App</h1>
    <p>Created by Ntsako Malungane</p>
    <p>Download the app now!</p>
    <a href="[insert download link here]" download>
        <button style="padding: 10px 20px; font-size: 16px;">Download Now</button>
    </a>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
    <title>NSC App</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .container {
            max-width: 800px;
            margin: 40px auto;
            padding: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>NSC App</h1>
        <p>Created by Ntsako Malungane</p>
        <h2>Previous Question Papers (2015-2024)</h2>
        <ul>
            <li><a href="                           
            <li><a href="#grade11">Grade 11</a></li>
            <li><a href="                           
        </ul>

        <h2 id="grade10">Grade 10</h2>
        <ul>
            <li><a href="path/to/grade10-term1-2015.pdf" target="_blank">Grade 10 Term 1 2015</a></li>
            <li><a href="path/to/grade10-term2-2015.pdf" target="_blank">Grade 10 Term 2 2015</a></li>
            <li><a href="path/to/grade10-term3-2015.pdf" target="_blank">Grade 10 Term 3 2015</a></li>
            <li><a href="path/to/grade10-term4-2015.pdf" target="_blank">Grade 10 Term 4 2015</a></li>
            <!-- Repeat for each year and term -->
        </ul>

        <h2 id="grade11">Grade 11</h2>
        <ul>
            <li><a href="path/to/grade11-term1-2015.pdf" target="_blank">Grade 11 Term 1 2015</a></li>
            <li><a href="path/to/grade11-term2-2015.pdf" target="_blank">Grade 11 Term 2 2015</a></li>
            <li><a href="path/to/grade11-term3-2015.pdf" target="_blank">Grade 11 Term 3 2015</a></li>
            <li><a href="path/to/grade11-term4-2015.pdf" target="_blank">Grade 11 Term 4 2015</a></li>
            <!-- Repeat for each year and term -->
        </ul>

        <h2 id="grade12">Grade 12</h2>
        <ul>
            <li><a href="path/to/grade12-term1-2015.pdf" target="_blank">Grade 12 Term 1 2015</a></li>
            <li><a href="path/to/grade12-term2-2015.pdf" target="_blank">Grade 12 Term 2 2015</a></li>
            <li><a href="path/to/grade12-term3-2015.pdf" target="_blank">Grade 12 Term 3 2015</a></li>
            <li><a href="path/to/grade12-term4-2015.pdf" target="_blank">Grade 12 Term 4 2015</a></li>
            <li><a href="path/to/grade12-exam-2015.pdf" target="_blank">Grade 12 Exam 2015</a></li>
            <!-- Repeat for each year and term -->
        </ul>
    </div>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
    <title>NSC App</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .container {
            max-width: 800px;
            margin: 40px auto;
            padding: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>NSC App</h1>
        <p>Created by Ntsako Malungane</p>
        <h2>Previous Question Papers and Memoranda</h2>
        <ul>
            <li><a href="                           
            <li><a href="#grade11">Grade 11</a></li>
            <li><a href="                           
        </ul>

        <h2 id="grade10">Grade 10</h2>
        <ul>
            <li><a href="question-papers/grade10/2015/term1.pdf" target="_blank">Grade 10 Term 1 2015 Question Paper</a> | <a href="memoranda/grade10/2015/term1-memo.pdf" target="_blank">Memorandum</a></li>
            <li><a href="question-papers/grade10/2015/term2.pdf" target="_blank">Grade 10 Term 2 2015 Question Paper</a> | <a href="memoranda/grade10/2015/term2-memo.pdf" target="_blank">Memorandum</a></li>
            <!-- Repeat for each year and term -->
        </ul>

        <h2 id="grade11">Grade 11</h2>
        <ul>
            <li><a href="question-papers/grade11/2015/term1.pdf" target="_blank">Grade 11 Term 1 2015 Question Paper</a> | <a href="memoranda/grade11/2015/term1-memo.pdf" target="_blank">Memorandum</a></li>
            <li><a href="question-papers/grade11/2015/term2.pdf" target="_blank">Grade 11 Term 2 2015 Question Paper</a> | <a href="memoranda/grade11/2015/term2-memo.pdf" target="_blank">Memorandum</a></li>
            <!-- Repeat for each year and term -->
        </ul>

        <h2 id="grade12">Grade 12</h2>
        <ul>
            <li><a href="question-papers/grade12/2015/term1.pdf" target="_blank">Grade 12 Term 1 2015 Question Paper</a> | <a href="memoranda/grade12/2015/term1-memo.pdf" target="_blank">Memorandum</a></li>
            <li><a href="question-papers/grade12/2015/term2.pdf" target="_blank">Grade 12 Term 2 2015 Question Paper</a> | <a href="memoranda/grade12/2015/term2-memo.pdf" target="_blank">Memorandum</a></li>
            <li><a href="question-papers/grade12/2015/exam.pdf" target="_blank">Grade 12 Exam 2015 Question Paper</a> | <a href="memoranda/grade12/2015/exam-memo.pdf" target="_blank">Memorandum</a></li>
            <!-- Repeat for each year and term -->
        </ul>
    </div>
    <a href="download-link" download>
        <button style="padding: 10px 20px; font-size: 16px;">Download NSC App</button>
    </a>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
    <title>NSC App</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .container {
            max-width: 800px;
            margin: 40px auto;
            padding: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>NSC App</h1>
        <p>Created by Ntsako Malungane</p>
        <h2>Previous Question Papers and Memoranda</h2>
        <ul>
            <li><a href="                           
            <li><a href="#grade11">Grade 11</a></li>
            <li><a href="                           
        </ul>

        <h2 id="grade10">Grade 10</h2>
        <ul>
            <li><a href="question-papers/grade10/2015/term1.pdf" target="_blank">Grade 10 Term 1 2015 Question Paper</a> | <a href="memoranda/grade10/2015/term1-memo.pdf" target="_blank">Memorandum</a></li>
            <!-- Repeat for each year and term -->
        </ul>

        <h2 id="grade11">Grade 11</h2>
        <ul>
            <li><a href="question-papers/grade11/2015/term1.pdf" target="_blank">Grade 11 Term 1 2015 Question Paper</a> | <a href="memoranda/grade11/2015/term1-memo.pdf" target="_blank">Memorandum</a></li>
            <!-- Repeat for each year and term -->
        </ul>

        <h2 id="grade12">Grade 12</h2>
        <ul>
            <li><a href="question-papers/grade12/2015/term1.pdf" target="_blank">Grade 12 Term 1 2015 Question Paper</a> | <a href="memoranda/grade12/2015/term1-memo.pdf" target="_blank">Memorandum</a></li>
            <!-- Repeat for each year and term -->
        </ul>

        <h2>Video Tutorials</h2>
        <ul>
            <li>
                <iframe width="560" height="315" src="https://www.youtube.com/embed/video-id1" title="Grade 10 Math Tutorial" frameborder="0" allowfullscreen></iframe>
                <p>Grade 10 Math Tutorial</p>
            </li>
            <li>
                <iframe width="560" height="315" src="https:                                                                                                                        
                <p>Grade 11 Physical Sciences Tutorial</p>
            </li>
            <li>
                <iframe width="560" height="315" src="https://www.youtube.com/embed/video-id3" title="Grade 12 Life Sciences Tutorial" frameborder="0" allowfullscreen></iframe>
                <p>Grade 12 Life Sciences Tutorial</p>
            </li>
        </ul>
    </div>
    <a href="download-link" download>
        <button style="padding: 10px 20px; font-size: 16px;">Download NSC App</button>
    </a>
</body>
</html>
