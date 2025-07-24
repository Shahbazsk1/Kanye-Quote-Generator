# Kanye-Quote-Generator
<h2>🔎 Description:</h2>
<p>This is a fun GUI-based Python project that fetches and displays random quotes by Kanye West using the Kanye REST API. Every time the user clicks the Kanye button, a new quote is fetched from the internet and displayed on a stylized graphical window.</p>
<h3>Modules and Libraries Used</h3>
<ol>
  <li>tkinter
    <ul>
      <li>Provides tools to build the graphical user interface (GUI), including the window, button, canvas, and text elements.</li>
      <li><strong>Documentation:</strong><a href="https://docs.python.org/3/library/tkinter.html" target="_blank">https://docs.python.org/3/library/tkinter.html</a></li>
  </li>
    <li>request
      <ul>
        <li><strong>Purpose:</strong> Sends a GET request to the Kanye REST API to fetch a random quote.</li>
        <li><strong>Documentation:</strong><a href="https://docs.python-requests.org" target="_blank">https://docs.python-requests.org</a></li>
    </li>
</ol>
<h3>🌐 API Used</h3>
<p>✅ Kanye REST API</p>
<ul>
  <il><strong>URL:</strong> <a href="https://api.kanye.rest/" target="_blank">https://api.kanye.rest/</a></il>
  <li><strong>Purpose:</strong> Returns a random Kanye West quote in JSON format.</li>
  <li><strong>No authentication required:</strong> Free and public.</li><br>
  <p><strong>Example Response:</strong><br>
    {<br>
      "quote": "I feel like I’m too busy writing history to read it."<br>
    }<br>
  </p>
</ul>










