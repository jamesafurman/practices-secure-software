# practices-secure-software
Practices for Secure Software

Artemis Financial is a financial consulting company that develops individualized 
financial plans for customers, for purposes including savings, retirement, investments, 
and insurance. Since they handle customer finances, they need to adhere to US (and 
possibly international) legal standards for information security; secure software 
will also ensure they do not unethically handle third party funds irresponsibly, 
destroying, e.g., their clients’ pensions. Their main stated goal was to modernize 
their operations, and accordingly they commissioned Global Rain to secure their web 
application. 

I correctly identified vulnerabilities, identified how to resolve them, implemented 
the resolution, and then tested that implementation. It’s important to code securely 
to prevent unintended and potentially harmful use of software systems. Software security 
ensures a company’s financial security, ethicality, and legal compliance. Static testing 
was both challenging and beneficial, as it tested and improved my ability to read code as 
a language through the lens of security analysis. 

I ensured the functionality and security of my code by running it and applying multiple 
tools and approaches for identifying and resolving security flaws. In a real setting, I 
would prefer to simulate attacks to gain a fuller sense of the code’s security. The OWASP 
top 10 and related tools are helpful for ensuring a baseline of security. Distinguishing 
critically between trusted and untrusted data is a necessity for securing any application 
that is not fully self-contained. Practice manually reviewing code is also helpful for 
developing a sense of what vulnerabilities look like. 
