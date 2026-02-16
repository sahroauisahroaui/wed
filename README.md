<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lab 01 - Web Development</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header class="header-section">
        <h1>Web Application Development</h1>
        <p>Welcome to Lab 01 Repository</p>
    </header>

    <main class="container">
        <section class="card">
            <h2>Lab Objectives</h2>
            <ul class="list-items">
                <li>Set up a GitHub repository</li>
                <li>Create structured HTML files</li>
                <li>Apply CSS styling using classes</li>
                <li>Understand web layout basics</li>
            </ul>
        </section>

        <section class="card">
            <h2>Prerequisites</h2>
            <p>Computer with internet, Browser, and Text Editor (VS Code).</p>
        </section>
    </main>

    <footer class="footer-section">
        <p>&copy; 2026 Web Dev Lab Submission</p>
    </footer>

</body>
</html>
/* Body and Layout */
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: #f0f2f5;
    margin: 0;
    padding: 0;
    line-height: 1.6;
}

/* Header Styling */
.header-section {
    background-color: #004a99;
    color: white;
    text-align: center;
    padding: 40px 0;
}

/* Container and Cards */
.container {
    width: 85%;
    max-width: 800px;
    margin: 30px auto;
}

.card {
    background: #ffffff;
    padding: 25px;
    margin-bottom: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

/* List Styling */
.list-items {
    list-style-type: square;
    padding-left: 20px;
}

.list-items li {
    margin-bottom: 10px;
    color: #444;
}

/* Footer Styling */
.footer-section {
    text-align: center;
    padding: 20px;
    background: #333;
    color: #fff;
    position: relative;
    bottom: 0;
    width: 100%;
}
