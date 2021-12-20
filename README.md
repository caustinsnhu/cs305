# CS305: Artemis Financial Practices for Secure Software Report

## Client
The client was Artemis Financial, a finical consulting company looking to modernize operations and software.   The client wanted us to assist with ensuring their product was using secure software practices and secure communication.  In particular, Artemis Financial wanted to added file verification and SSL/TLS security to their web application.  

## What Went Well
Using the OWASP maven dependecy checker was boon to for identifying vulnerablilities introduced by third party dependencies.  Setting that up and esuring that dependencies had no know dependices was a critical first step.  This is important in code security because it reduces or removes well know attack vectors that are often exploited by off the shelf scripts.  It is also important to use the depedency checker because it can provide some saftey when adding new dependencies.  

## Process

The process of identifying vunerable third party software was extreamly helpful this is because as stated it helps with avoid attacks introduced by third parties.  Additionaly, the process of reviewing code to check for developer error that introduce vulnerablities is helpful but also challenging.  This is because that code review process requires context with building secure code as well as some practice at reviewing code and looking for non-obvious issues.

## Approach
The approach to introducing layers of security was done by 
1) Examining dependencies for known issues using a dependency checking tool such as the maven OWASP plugin.
2) Manuly reviewing code and applying the VAPFD flow diagram to focus your code inspection efforts.
3) Identify and document the vulnerabilities as well as a mitigation approach.

In the future I would certainly employ the VAPFD flow and use dependency checking tool.


## Ensuring Functionality and Security
Once the code was modified it's functionality was ensured by testing the code functions as expected.  Additionaly, security is tested by attempting to perform the actions that would be know to be insecure.  In the sample code I didn't write functional tests but, in a real-world, non-academic project functional tests would be built along with penetration tests that attempt to find issues before a user, customer or attacker.

## Helpful Resources.
I think the most useful resource from this project was the OWASP dependency checker plugin for maven.  Additionaly, the VAPFD flow diagram is very helpful for focusing the code review process.

## Potential Showcase
As a potential showcase for future employers, I think the use of the OWASP maven dependency checker is likely the most useful item.
