# WEB-29183
WebStorm WEB-29183 reproducing project

Steps to reproduce:

1. checkout from git
1. open test/demo.js
1. click "Run" icon –> the file is executed as Node.js file
1. edit run configuration and remove the "demo.js" configuration that was created by the previous step
1. edit pacakage.json and remove "karma": "^1.7.1"
1. repeat steps 2 and 3 –> the file is executed properly as Mocha test
