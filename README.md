# AutomationPractiseAssignment
1. Add this dependency by running npm install -g allure-commandline --save-dev
2. Run your tests using npx wdio run ./wdio.conf.js in the terminal of visual studio code and generate test result data (ie, after running it will generate allure-results folder).
3. From the same project directory run, allure generate --clean reports/allure-results/ && allure open in the terminal of visual studio code
4. On successfull execution it will generate one more folder allure-report in your directory and also allue report will be opened.
