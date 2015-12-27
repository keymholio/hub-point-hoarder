# Jive Point Hoarder
This script hoards points for you in the Jive-n Hub software. It opens Google
Chrome, creates a new poll and deletes that poll.

There is a small configuration at the top of the script that you can modify
to your Jive setup:

```
property jiveCreatePollUrl : "https://domain.jiveon.com/poll/create.jspa?containerType=3&containerID=2972&draftID=22174"
property amtOfPollsCreated : 1
property jiveDomain : "https://domain.jiveon.com"
property userToAssignPollTo : "someperson@yourcompany.com"
```

| Property  | Description  |
|---|---|
| jiveCreatePollUrl  |  Url of the new poll page. |
| amtOfPollsCreated  | How many polls you would like to automate. Each one gets you 5 points.  |
| jiveDomain |  The main domain of your jive setup. |
|  userToAssignPollTo | A specific person to show the poll. Hint: I like to use people that have left the company. ;)  |
