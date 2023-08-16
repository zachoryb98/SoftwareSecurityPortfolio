# SoftwareSecurityPortfolio
Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a consulting company that creates unique financial plans for their customers. They are looking to modernize their systems and part of that includes making suere their custom software is up to date with the most current and effective security measures. They have reached out to Global Rain to seek expertise about how to better protect themselves from external threats.

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I think I did a good job carefully looking over the vulnerabilities in the dependency check. I found that a majority of the issues would be resolved by simply just updating the vulnerable packages to a newer version. After doing so there were little to no issues found in secondary run of the dependency check. There are a number of reasons to code securely. Number 1 being keeping bad guys away from you and your customer's sensitive data. This can lead to lawsuits which will cost the business money and their reputation. The value that Software security brings to a company is peace of mind. The reason I say this is the same as the reason it is important to code securely. Knowing that your company, your software, and even your data are protected by security measures saves the company the trouble of a legal issue, money, and ensures their customers trust in them.

What part of the vulnerability assessment was challenging or helpful to you?
At first I found it difficult to understand which ones were false positives and mostly just took my best guess. What finally helped me was on the final project I took the time to update the dependencies and was able to see most of them clear up as I slowly incremented the updates. I actually only updated spring boot all the way until there were no updates and no new errors with those updates. It left me with two issues. One of those issues was disputed and the other was related to a specific functionality that was not even used in the code. It was also useful to understand how to supress those false positives.


How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
