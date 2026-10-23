# Lab1_WebServer

## Description
A simple Python web server that uses TCP sockets to handle HTTP requests. It serves HTML files and returns a `404 Not Found` response when a requested file does not exist.

## Files
- `webserver.py` — Python web server implementation.
- `HelloWorld.html` — Sample HTML page for testing.
- `screenshots/` — Screenshots of the test results.

## How to Run
1. Open Terminal and navigate to the project directory.
2. Start the server:

   ```bash
   python3 webserver.py
   ```

3. Open the following URL in your browser to view the sample page:

   http://127.0.0.1:6789/HelloWorld.html

4. To test a missing file, open:

   http://127.0.0.1:6789/MissingPage.html

5. Press `Control + C` in Terminal to stop the server.

