assignment 2
In this assignment, I created two Bash scripts to perform different tasks.

For Task 1, I checked the HTTP response code of a website (guvi.in). While testing, I received an HTTP 301 status code, which indicates that the website is permanently redirected to another URL, typically from HTTP to HTTPS. Since this is expected behavior and not an error, I used the `curl -L` option to follow the redirect and obtain the final HTTP response.

For Task 2, I wrote a script to process a text file line by line using a `while` loop. The script keeps track of the line numbers and starts processing from the 5th line onward. It checks whether a line contains the word "welcome" and, if it does, replaces every occurrence of the word "give" with "learning" using the `sed` command before printing the updated result.
