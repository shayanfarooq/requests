Welcome to JS Network Request Sniffer! 🚀 This Go script is designed to scan and analyze JavaScript files for various network request patterns. Whether you're a security analyst, developer, or just a curious coder, this tool helps you spot XMLHttpRequest, Fetch API, and jQuery AJAX snippets within JavaScript files from any URLs you provide.

Features
Concurrent Processing: Utilizes a pool of worker threads to efficiently handle multiple URLs simultaneously.
Pattern Detection: Identifies and extracts code snippets for:
XMLHttpRequest
Fetch API
jQuery AJAX
Detailed Fetch API requests with method, headers, and optional body.
Color-Coded Output: Enjoy a clear and colorful console output with differentiated information:
Green for matched snippets
Yellow for category labels
Red for errors
Usage
Run the Script:

sh
Copy code
go run main.go
Input URLs:
Pipe or type URLs into the script's standard input. Each URL should be on a new line.

View Results:
The script will output detected network request patterns for each URL, formatted for easy reading.

Example
sh
Copy code
echo "[URL]" | go run main.go
Code Snippets Detected
The script categorizes snippets into:

XMLHttpRequest
Fetch API
jQuery AJAX
Detailed Fetch API Requests
Requirements
Go 1.18 or higher
Contribution
Feel free to open issues or pull requests to contribute to this project. We welcome feedback and enhancements!
