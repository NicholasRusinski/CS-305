# CS-305
Software Security course at SNHU

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a consulting company that develops individualized financial plans for their customers, where protecting their clients' information from attacks both at rest and in transit is of the utmost importance. This data can take the shape of accounting information, personal identification information, and various other liabilities. As the Global Rain Service Developer at Artemis Financial, I was tasked with recommending a solution to help protect this data from attackers.

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
One thing I did well is fully understand the customer's application and know where secure coding practices can be implemented for future improvements, because the sample code we provide is very simple. Code security is important because it provides protection for customer and system data from being used maliciously and potentially damaging reputations. 

What part of the vulnerability assessment was challenging or helpful to you?
Firstly, the most challenging aspect of the assessment was understanding how a spring boot rest application operates and the different syntax used. I haven't had much experience with a web platform that operates of requests. It was difficult at first to suggest secure coding improvement when you're not sure what the code is doing. A few youtube videos helped explain the different functions, which mad eit easier to spot where improvement could be made.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
Input validation would be the first improvement I would add since the code currently requires no user input. But future updates will require the use of user input to meet Artemis business requirements. Areas that allow a user to interact with a website are one of the first places that attackers will look to exploit since it allows the website to experience change, it allows the attackers to potentialy manipulate the website in an unintended ways.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
I added an HTTPS proxy to protect the data transmitted between the client and the server. Checksum verification is possible by adding a message digest library that allows one-way hashing of user information. Additionally, I updated all libraries to remove known vulnerabilities.  To check my code after it was refactored, I followed the same protocol as before running the static vulnerability report and used the assessment flow chart to check my code for potential security violations.


What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
The course does not provide much guidance on the actual coding requirements I found the user instructions for the library and platform very useful. For example, one of the assignments required us to use the java package summary, but the module had no formal instructions on how to use it. I was able to find the correct instructions in the Java manual with examples of how to use the different functions and using them to make a working checksum.


Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would show my second project from this course, because it best demonstrates the skills I have learned. To clean up any known vulnerabilities in the dependencies, I first needed to update maven, Secondly, update the platform to the latest Java version, and finally update to the latest Spring Boot version. The updates were not straightforward and required me to study the instructions and directions on the relevant websites to accurately apply them. This experience will prove its worth as new versions of the library are always being rolled out and staying updated is one step towards ensuring your application is secure.
