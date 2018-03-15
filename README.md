# rips

## Aboutup
RIPS is the most popular static code analysis tool to automatically detect vulnerabilities in PHP applications. By tokenizing and parsing all source code files, RIPS is able to transform PHP source code into a program model and to detect sensitive sinks (potentially vulnerable functions) that can be tainted by userinput (influenced by a malicious user) during the program flow. Besides the structured output of found vulnerabilities, RIPS offers an integrated code audit framework. 

NOTE: RIPS 0.5 development is abandoned since 2013 due to its fundamental limitations. A complete rebuilt solution is available from RIPS Technologies that overcomes these limitations and performs state-of-the-art security analysis.

## Download + Installation
Install a local webserver parsing PHP files (should already be available if you develop PHP applications).
Download the latest version here.
Extract all files to your local webservers document root (e.g. /var/www/rips/)
goto http://localhost/rips/ and start scanning.