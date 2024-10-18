<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IP, URL, and Sensitive File Extractor</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #B8E2A3;
            color: #333;
            padding: 20px;
            margin: 0;
            border-radius: 5px;
            text-align: center; /* Center the content */
        }
        h1 {
            color: #4A90E2;
        }
        #inputData {
            width: 90%;
            height: 250px;
            margin: 20px auto; /* Center the input box */
            padding: 20px;
            border: 5px solid #ccc;
            border-radius: 5px;
            font-size: 14px;
            background-color: #e7f3ff; /* Light blue background for input */
        }
        #outputIPs, #outputURLs, #outputSensitive {
            width: 90%;
            height: 150px;
            margin: 10px auto; /* Center the output boxes */
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 14px;
            background-color: #e8f5e9; /* Light orange background for outputs */
        }
        button {
            padding: 10px 15px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 14px;
            margin: 5px;
        }
        button:hover {
            background-color: #357ABD;
        }
        .output-container {
            margin: 80px 0;
            text-align: center; /* Center buttons */
        }
        .clear-btn {
            background-color: #E94E77;
        }
        .clear-btn:hover {
            background-color: #D03A61;
        }
        .additional-input {
            text-align: center;
            margin: 3px 0;
            width: 90%; /* Center the additional input section */
        }
        #newSensitiveWords {
            width: 30%; /* Make input box wider */
            height: 50px; /* Increase height */
            padding: 10px; /* Add padding */
            border: 2px solid #ccc; /* Add border */
            border-radius: 5px; /* Rounded corners */
            font-size: 14px; /* Adjust font size */
        }
    </style>
</head>
<body>

<h1>Extractor Tool</h1>
<div class="note"
         made by <a href="https://x.com/enterlectury" target="_blank">Enterlectury🐱&zwj;🏍</a>.<br>
    </div>
<textarea id="inputData" placeholder="Paste your VIRUSTOTAL api data here..."></textarea>

<div class="output-container">
    <button onclick="extractUniqueIPs()">Extract Unique IPs</button>
    <button class="clear-btn" onclick="clearOutput('outputIPs')">Clear Output</button>
    <textarea id="outputIPs" placeholder="Unique IPs will appear here..." readonly></textarea>
</div>

<div class="output-container">
    <button onclick="extractUniqueURLs()">Extract Unique URLs</button>
    <button class="clear-btn" onclick="clearOutput('outputURLs')">Clear Output</button>
    <textarea id="outputURLs" placeholder="Unique URLs will appear here..." readonly></textarea>
</div>

<div class="output-container">
    <button onclick="extractSensitiveFiles()">Extract Sensitive Files URLs</button>
    <button class="clear-btn" onclick="clearOutput('outputSensitive')">Clear Output</button>
    <textarea id="outputSensitive" placeholder="Sensitive files URLs (iso, exe, zip, 7z, tar, gz, invoice, api, v1, secret, token, @, == , old, bak, dll)  will appear here... " readonly></textarea>
</div>

<!-- Add More Sensitive Words -->
<div class="additional-input">
    <h3>Add More Sensitive Words</h3>
    <input type="text" id="newSensitiveWords" placeholder="Enter new sensitive words (comma separated)..." title="Add words separated by commas">
    <button onclick="addSensitiveWords()">Add Sensitive Words</button>
</div>

<script>
    // Predefined sensitive words
    let sensitiveWords = [".iso", ".exe", ".zip", ".7z", ".tar", ".gz", ".dll", "invoice", "api", "secret", "token", "@", "%40", "==" , ".bak" , ".old" , "/v1" , "/v2" , "/v3" , "/v4" , "/v5"];

    // Function to extract unique IPs
    function extractUniqueIPs() {
        const input = document.getElementById("inputData").value;
        const ipRegex = /\b\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3}\b/g;
        const ips = input.match(ipRegex) || [];
        const uniqueIPs = [...new Set(ips)];
        document.getElementById("outputIPs").value = uniqueIPs.join("\n");
    }

    // Function to extract unique URLs
    function extractUniqueURLs() {
        const input = document.getElementById("inputData").value;
        const urlRegex = /(https?:\/\/[^\s]+)/g;
        const urls = input.match(urlRegex) || [];
        const uniqueURLs = [...new Set(urls)];
        document.getElementById("outputURLs").value = uniqueURLs.join("\n");
    }

    // Function to extract URLs with sensitive words in the path
    function extractSensitiveFiles() {
        const input = document.getElementById("inputData").value;
        const urlRegex = /(https?:\/\/[^\s]+)/g;
        const urls = input.match(urlRegex) || [];
        const sensitiveURLs = urls.filter(url => 
            sensitiveWords.some(word => url.includes(word))
        );
        document.getElementById("outputSensitive").value = sensitiveURLs.join("\n");
    }

    // Function to add new sensitive words
    function addSensitiveWords() {
        const newWords = document.getElementById("newSensitiveWords").value.trim();
        if (newWords) {
            const wordArray = newWords.split(',').map(word => word.trim()).filter(word => word);  // Split by commas, trim and filter empty values
            let addedWords = [];
            wordArray.forEach(word => {
                if (!sensitiveWords.includes(word)) {
                    sensitiveWords.push(word);
                    addedWords.push(word);
                }
            });
            if (addedWords.length > 0) {
                alert(`Added new sensitive words: ${addedWords.join(', ')}`);
            } else {
                alert("No new words added, they already exist in the list.");
            }
        }
        document.getElementById("newSensitiveWords").value = ""; // Clear input
    }

    // Function to clear output for a specified textarea
    function clearOutput(outputId) {
        document.getElementById(outputId).value = "";
    }
</script>

</body>
</html>
