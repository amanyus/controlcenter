## Welcome to Infrastructure-as-code Jenkins

![image](https://user-images.githubusercontent.com/31083956/69000699-d1aa1c00-090e-11ea-8517-28cacac60c0f.png)

1. When there is a request, GitHub will send out notification about the request. Once reviewed and approved by owner, GitHub will tell  Jenkins to execute the job.

1. Jenkins will execute the job based on schedule and also on-demand based on request in GitHub . The job can be anything from resetting password, generate new security key or allowing and blocking communication. The generated security key will be sent to user by email. Notification will be sent out for every job action.

1. The security key also can be stored in a security vault. We can destroy the security key once it is retrieved or after certain amount of period.
