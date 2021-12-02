# VulnApp

This was a group project in which we developed a series of deliberately insecure web applications which are
vulnerable to several common web attacks, found on the OWASP Top 10 Web Application
Security Risks list. Our group spent over a combined 400 hours researching and reverse engineering
common exploits found in web applications, as well as designing, implementing, and
deploying website instances that were used to demonstrate and test the various
vulnerabilities researched. We had mixed findings regarding the complexities of
defensive solutions to common vulnerabilities. While some attacks are easier to
implement than others, defensive strategies are all equally difficult to implement.
Defensive programming strategies require a holistic approach to programming; One that
does not compromise on any aspect of the program simply for convenience or limited
time for development. When web applications and the data they protect are
programmed from the very beginning with a realistic idea of what threats lurk beneath at
every step, they can truly be safe to use for the user.

In today's world of unending features and lack of privacy, it is impossible to predict every
single attack surface in existence. This is why the design and implementations of
various security principles should be built into the program since its inception. Some of
our group members found that working from the ground up in features was too difficult
to integrate with important security features, such as password encryption. It was found
that it would have been far easier to first implement an encryption algorithm and verify
an output, and then work around that to create the rest of the features of the application.
This is due to the fact that the data is easier to track and debug when you are a hundred
percent positive where it is going all the time.

As a team, we have exposed how some of the most common web attacks are facilitated. 
We have created documentation which includes ademonstration of each particular exploit, 
along with how to fix and prevent the issue from occurring in the end-user’s own applications. 
Our goal is to show the importance of observing good security practices during development by 
demonstrating the potential for exploitation when an application is not hardened against these 
common attack vectors.
