<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
</head>
<body>
  <img src="https://th.bing.com/th/id/OIG1.9k8tQqmP95ioQAeA8Uym?w=1024&h=1024&rs=1&pid=ImgDetMain" alt="Project Image">
    <h1>Dark Web Crawler </h1>

  <h2>Description:</h2>
    <p>
  This project implements a web crawler integrated with a Flask web application to crawl a given URL, extract various information such as HTML content, title, meta tags, 
  links, images, and perform text content analysis. The crawled data is then displayed in a dashboard interface.
    </p>
   <h2>Features:</h2>
    <ul>
        <li><strong>Web Crawling:</strong> Utilizes concurrent web crawling techniques to fetch HTML content, title, meta tags, links, images, and other relevant information from a given URL.</li>
        <li><strong>Text Content Analysis:</strong> Analyzes the text content extracted from the crawled webpage using TextBlob, providing sentiment analysis metrics such as polarity and subjectivity.</li>
        <li><strong>Keyword Occurrence:</strong> Counts the occurrences of predefined keywords within the HTML content of the webpage.</li>
        <li><strong>Dashboard Interface:</strong> Provides a user-friendly web interface built with Flask, allowing users to input URLs and view the crawled data along with analysis results.</li>
    </ul>
    <h2>Dependencies:</h2>   
    <ul>
        <li><code>concurrent.futures</code>: For concurrent execution of web crawling tasks.</li>
        <li><code>requests</code>: For making HTTP requests to fetch webpages.</li>
        <li><code>BeautifulSoup</code>: For parsing HTML content.</li>
        <li><code>Flask</code>: For building the web application and dashboard.</li>
        <li><code>TextBlob</code>: For text content analysis.</li>
    </ul>
    <h2>Setup:</h2>
    <ol>
        <li>Ensure Python and pip are installed on your system.</li>
        <li>Install the required dependencies using pip:
            <pre>pip install requests beautifulsoup4 Flask textblob</pre>
        </li>
        <li>Run the Flask application by executing the <code>app.py</code> script:
            <pre>python app.py</pre>
        </li>
        <li>Access the web interface by opening a web browser and navigating to <code>http://localhost:5511</code>.</li>
    </ol>
    
<h2>Contact</h2>
    <p>For inquiries, you can reach me on <a href="https://www.linkedin.com/in/abhijith-soman-5b597225b//">LinkedIn</a>.</p>
</body>
</html>
