<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site Scanner</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Website Scanner</h1>
    </header>
    <main>
        <section class="scan-section">
            <h2>Enter a URL to Scan:</h2>
            <input type="text" id="urlInput" placeholder="Enter a URL">
            <button id="scanButton">Scan</button>
        </section>
        <section class="results-section" id="resultsSection">
            <h2>Scan Results:</h2>
            <div id="scanResults"></div>
        </section>
    </main>
    <script src="script.js"></script>
</body>
</html>
