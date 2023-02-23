# CS305-Software_Security
**Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?**

Artemis Financial is a consulting company that develops individual financial plans for their customers. Making sure those financial plans are kept private is important to them. These financial plans contain information on savings, retirement, investments, and insurance, so keeping that information safe and secure should be a high priority for the company. 

**What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?**

When finding the software security vulnerabilities, I found solutions to try to mitigate any damages those vulnerabilites could cause. Keeping dependencies up to date is a huge part of this project's goal of making sure the code was secure. It is important to code securely to protect the company and the users of the application. Making sure the code is secure and best practices are used creates an overall positive view of the company. A company that has constant security issues or bugs in the code is not viewed as a trusted or reliable company. A company that always makes sure to secure the data of its users and make the experience as pleasant as possible will always be seen as a company more favorable to use by the public.

**What part of the vulnerability assessment was challenging or helpful to you?**

The most helpful part of the vulnerability assessment was learning how to look at the dependency check report. This let me know a lot of information on the different libraries that were being used and any security issues with them. It taught me how to easily find security issues and many of those issues were easy to fix. It also showed me how to supress false positive results which could be helpful in future projects.

**How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?**

I increased layers of security by making sure everything was as secure as possible and everythign was up to date and working as intended. The application is secure because it uses SHA-256 to encrypt the data and keep it secure from potential attackers. By making sure there were no bugs in the code, it creates a more secure application as well that will provide a better user experience. The main thing I would use in the future to assess vulnerabilites is the dependency check. This check also gives detailed descriptions of the vulnerabilites which can then be fixed.

**How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?**

To add layers of security to the application, I had to create a certificate using the java keytool. This was the main step for the client to be able to access a secure and trusted website. Refactoring the code, everything worked as intended after running it and looking for any issues. The dependency check also returned no more vulnerabilities.

**What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?**

Learning to use the java keytool could end  up being useful in the future. The keytool is helpful for making the applcation more secure when it comes to web applications. The dependency check will also be valuable as it can quickly and easily show vulnerabilities that can be pretty easily fixed.

**Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?**

I would show them my final report and let them know the process I went through for the project. The course has taught me a lot of information that could be incorporated to future assignments to make them more secure.
