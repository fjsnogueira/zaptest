## ZAProxy: Using Protractor to identify Web Applications vulnerabilities

The "The BodgeIt Store" sample application is used [https://github.com/psiinon/bodgeit.git]([https://github.com/psiinon/bodgeit.git])

# Challenges completed using this automation

|No   |    Challenge                                                                                    |  Completed    |
|-----|-------------------------------------------------------------------------------------------------|---------------|
|01.  |    Login as test@thebodgeitstore.com 	                                                        | Yes            |
|02.  |    Login as user1@thebodgeitstore.com 	                                                        | Yes            |
|03.  |    Login as admin@thebodgeitstore.com 	                                                        | Yes            |
|04.  |    Find hidden content as a non admin user 	                                                    | Yes            |
|05.  |    Find diagnostic data 	                                                                    | No            |
|06.  |    Level 1: Display a popup using: <script>alert("XSS")</script>.                               | No            |
|07.  |    Level 2: Display a popup using: <script>alert("XSS")</script>                                | No            |
|08.  |    Access someone else's basket 	Not implemented/tested yet :(                               | :(            |
|09.  |    Get the store to owe you money 	                                                            | No            |
|10.  |    Change your password via a GET request 	                                                    | No            |
|11.  |    Conquer AES encryption, and display a popup using: <script>alert("H@cked A3S")</script> 	    | No            |
|12.  |    Conquer AES encryption and append a list of table names to the normal results.               | No            |



export PATH="/Applications/OWASP ZAP.app/Contents/Java/:$PATH"

#For Contributors

npm install

npm run ./node_modules/protractor/bin/webdriver-manager update

node ./node_modules/grunt-protractor-runner/node_modules/protractor/bin/webdriver-manager update