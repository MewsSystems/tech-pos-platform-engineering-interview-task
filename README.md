# Mews - Platform engineering team interview task

Please complete and return this technical test before attending your interview at Mews. This isn't something we would like you to spend a long time on, roughly 2-3 hours. You can give us the results in any way that makes sense to you. If sharing a GitHub repository, please make it private and grant access to the GitHub usernames at the bottom of the page.

Your response to this technical assessment will be used to start a technical discussion at your interview. We're more interested in how you approach the problem and implement your solution than in finding a correct answer to the question.

# The task 

You are given a file containing JSON data about requests on production for some time interval. Here is an example log line:

`{"TimeStamp":"2024-08-30T13:00:01.584","Endpoint":"/api/invoices/add","StatusCode":200,"Duration":470}`

Each line contains the endpoint name and the request duration. Several deployments happened in the given interval with bugs that made some endpoints slower (regressed).

Your task is to find which requests regressed and also the approximate time of it with a 5 minute tolerance. Write some code that reads in `logs.txt` and outputs the name of the endpoints that regressed and the time when it approximately happened. Use any programming language you feel comfortable with.

Please also include:
* Instructions on how execute your application. Bear in mind it may not be a technology we are familiar with.
* Any comments to explain your thinking.
* Focus on making your code readable. It's more difficult to assess a task like this if it's hard to understand what the code is doing.

# GitHub usernames
- [toncid](https://github.com/toncid)
- [michal-gondar-mews](https://github.com/michal-gondar-mews)
- [terrybrown](https://github.com/terrybrown)
- [philjhale](https://github.com/philjhale)
