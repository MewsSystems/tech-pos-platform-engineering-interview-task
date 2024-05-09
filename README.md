# Mews - Platform engineering team interview task

Please complete and return this technical test before attending your interview at Mews. This isn't something we would like you to spend a long time on, we recommend no more than 2 hours. You can give us the results in any way that makes sense to you. If sharing a GitHub repository, please make it private and grant access to the GitHub usernames at the bottom of the page.

Your response to this technical assessment will be used to start a technical discussion at your interview. We're more interested in how you approach the problem and implement your solution than in finding a correct answer to the question.

# The task 

You are given a file containing JSON data about requests on production for some time interval. Here is an example log line:

`{"TimeStamp":"2021-08-26T13:00:01.584","Endpoint":"/api/reservations/add","StatusCode":200,"Duration":470}`

Each line contains the endpoint name and the request duration. Several deployments happened in the given interval with bugs that made some endpoints slower (regressed).

Your task is to find which requests regressed and also the approximate time of it with a 5 minute tolerance. Write some code that reads in `logs.txt` and outputs the name of the endpoints that regressed and the time when it approximately happened. Use any programming language you feel comfortable with.

# Github usernames
- [terrybrown](https://github.com/terrybrown)
- [schafric](https://github.com/schafric)
- [philjhale](https://github.com/philjhale)
