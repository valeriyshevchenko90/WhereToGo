
![IMG_6146](https://user-images.githubusercontent.com/25904307/104650994-55000280-56b7-11eb-978f-eb47afa21ce5.JPG)

# Where To Go with leaked account in the corporate environment.
Due to security assessments of different projects, I found different leaked/exposed accounts on the domain of the organization. But every time it was so difficult to discover the place where I can reuse those credentials and how can I expand my attack surface. 
This project should help researchers, pentesters, bounty-hunters to expand the risks of compromised accounts in the corporate environment.
 
 
 
# Story behind WhereToGo project
> Due Penetration testing activities for one customer it was discovered leaked employee credentials. First of all thouse crdentials were checked on the corporate environment but later on I realized that such credentials could work on other important cloud services. I started collecting such a list of popular technological services which might have high value in case of improper access.  
>
 
 
 
Service Name | Trusted login providers
------------ | -------------
[Gitlab](https://gitlab.com/users/sign_in) | Google, Salesforce, Github, Bitbucket, Twitter
[Travis CI](https://travis-ci.com/signin) | Github, Bitbucket, Gitlab, Assembla
[Grafana.com](https://grafana.com/login) | Google, Github, Microsoft
[Sentry](https://sentry.io/auth/login/) | Google, Github, Azure DevOps
[Slack](https://slack.com/signin#/signin) | Google
[Raygun](https://app.raygun.com/) | Github, Twitter, Facebook, Google
[Datadog](https://app.datadoghq.com/) | Google
[Atlassian](https://www.atlassian.com/) | Google, Microsoft, Apple
[Trello](https://trello.com/login) | Google, Microsoft, Apple
[Trailblazer](https://trailblazers.salesforce.com/) | Salesforce
[Bitbucket](https://bitbucket.org/product) | Google, Microsoft, Apple
[Elastic Cloud](https://cloud.elastic.co/) | Google, Microsoft
[Netdata Cloud](https://app.netdata.cloud/) | Google, Github
[Jetbrains](https://hub.jetbrains.com/) | Bitbucket
[GitHub](http://github.com) | -
[GitHub](http://github.com) | -
[GitHub](http://github.com) | -

##### ⚠️ Disclaimer The authors of this document take no responsibility for correctness. This project is merely here to help guide security researchers towards determining whether something is vulnerable or not, but does not guarantee accuracy. This project heavily relies on contributions from the public. The information included at this page is for educational purposes. 
