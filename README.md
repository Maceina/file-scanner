# File Scanner
File scanner task with node.js

# Instructions:
1. Clone or download this repositpry.
2. Run command "npm install" to install necessary dependencies.
3. Run comman "npm start" to start the server.
4. In your browser go to: http://localhost:3000/scan?path=testfiles
5. In this case "scan" path accepts a parameter called: "path" with a property "testfiles" which is a directory where all scanned files are stored in this case "./testfiles".
6. To list all scanned files go to: http://localhost:3000/list
7. If you remove files from scanned directory and again go to http://localhost:3000/scan?path=testfiles the http://localhost:3000/list url returns all the files that exist with a value of "true" and deleted ones with a value of "false".
8. In your browser go to http://localhost:3000/download-state and you can see all the scanned files from a directory you provided or multiple directories if you run scan on different directories. 