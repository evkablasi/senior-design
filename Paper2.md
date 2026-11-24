Evka Blasi

As mentioned during our project briefing, SecurKart provides services for many different people and companies, including medical practices. As such, data protected by The Health Insurance Portability and Accountability Act of 1996 (HIPAA) and The Employee Retirement Income Security Act of 1974 (ERISA) exist in the same source control system which we will be using to work on our project. Building our product will not require us to work directly with any protected health information (PHI), but it may lead to some critical decisions or additions being made that we otherwise would not have considered seeing as our work will live in the same place and could directly impact access to PHI storage. 

## Summary
To ensure that our project does not mishandle any data, we first must define HIPAA and ERISA and the security laws that exist around them. HIPAA was created as a response to the growing use of technology for medical transactions and storing health information, and thus the growing need for privacy regulations [^1]. An amendment added in 2003, The Security Rule, goes into more detail about the responsibilities of companies to protect this information, which includes ensuring confidentiality and integrity, as well as anticipating any possible threats or breaches [^2]. ERISA sets standards and guidelines surrounding private-sector employee benefits, like retirement and health plans[^3]. The money and information involved in ERISA protected data could be so valuable that the United States Department of Labor created a document of best cybersecurity practices to keep this data safe, which emphasizes access controls, risk assessment, and data encryption [^4]. 

## As it Applies to Senior Design
In terms of how to apply HIPAA regulations and safety to our project, it is best to turn to the breakdown of administrative, physical, and technical safeguards.

Physical safeguards include workstation use and security, device, and media controls. I believe this is already covered by the laptops SecurKart has provided us with, seeing as all the work on creating our product is sequestered to these approved and secure devices that already live within the SecurKart system. This aspect is not entirely under our control, as we are depending on pre-existing security, but it is in our hands to use these devices appropriately and refrain from transferring any information, whether it be database design or source code, to our personal devices. 

Most of the technical safeguards, namely access control, authentication, and transmission security, deal with ensuring that only authorized users are able to access protected health information in all cases of where the data may exist. We accomplished these by setting up multi-factor authentication for our accounts. This means that not only if a person were able to electronically access this data, but even if they were able to bypass physical safeguards i.e. get their hands on one of our SecurKart laptops, they would hit a wall almost immediately. Another technical safeguard demands the protection of protected health information from being altered or destroyed. To comply with this, we will use a test network for all testing while developing our database, so that no other aspects of the source control system will be impacted and ensuring the preservation of all protected data. 

Administrative safeguards overlap a bit with technical and physical regarding access management and security management, but the one that stands out to me the most is security awareness and training, which calls for education of all employees on security policies and procedures. It occurs to me that we may need more information from SecurKart on how protected health information exists in their network and how our work could possibly impact it, which, depending on the extent, could be pertinent to ensuring that we respect HIPAA regulations during our developing. 


While the Employee Benefits Security Administration has outlined a list of 12 best practices for handling data in the context of ERISA regulations, the following three seem the most relevant to our purposes. 

First is having a formal, well documented cybersecurity program, a key aspect of which is to pre-establish strong policies and continue to add to them as incidents occur. However, the creation of the rules themselves is nothing without proper explanation of how to follow them and what is at stake. During our time so far collaborating with the Securkart team, it has been brought up numerous times how our work could interfere with their internals if we are not careful about working only in our test space ("Terms are effectively explained to users": check!). I believe all of our code will also be thoroughly reviewed by various members of the company before it is officially committed to interact with their existing work ("Approval by senior leadership": check!). 

Second is having strong access control procedures, whose two main components are authorization and authentication. We have limited access to their systems, we only have what Securkart has made available to us on our company provided laptops, which protects our team from accidentally causing greater issues beyond our project. We also have to change our unique passwords every 45 days in accordance with company policy and have Multi-Factor Authentication set up for our Securkart accounts through Microsoft Authenticator. 

Finally, implementing and managing a secure system development life cycle program, which includes "procedures for evaluating [...] externally developed applications including periodic reviews and updates" [^4]. This enforces just how important our biweekly meetings are with the Securkart team, and considering them in the context of ensuring data privacy and following PHI regulations, I am feeling more motivated to push the productivity of these meetings, especially as we begin to get into actual coding. 


It should be noted that the examples mentioned above are not a comprehensive list of every way that our project will interact with HIPAA and ERISA guidelines, but rather some possibilities to consider as we navigate creating our database. Many of the steps had already been covered by the Securkart team before we even began our involvement, which proves their responsibility around these laws as well as their ability to help us uphold them in our development process. It is interesting to consider how the scope of our project goes beyond our database and includes our interaction with the company as contractors. 

## Broader Implications
Global - 
While other countries certainly have their own legislation surrounding PHI, HIPAA and ERISA apply only within the United States. This would certainly be something to consider seriously if Securkart wanted to discuss international growth, but it is important to always keep in mind so as not to inhibit the possibility of global expansion or collaboration. There is also the consideration of data being stored in the cloud, which does not bend to borders. Luckily, Securkart has refrained from keeping information in the cloud in light of the many recent issues large companies have been facing with data breaches.

Economic - 
While ensuring the proper rules are followed during development could be costly with regard to time or extra hands and eyes that may be needed, it is certainly worth the upfront pay. HIPAA violation penalties can range from as cheap as a couple hundred bucks to millions of dollars if found guilty of willful neglect with no proven effort to fix the issue [^5]. 

Societal -
Although PHI seems like this very sterile thing because of the way it is referenced discussed, it is important to consider what it actually means- real people's data. Mishandling of this data could put people's identities and retirement funds at risk, so it really becomes a greater issue of creating trust with the public as well as upholding our code of ethics as engineers. 


[^1]: https://www.hhs.gov/hipaa/for-professionals/index.html
[^2]: https://www.hhs.gov/hipaa/for-professionals/security/laws-regulations/index.html
[^3]: https://www.dol.gov/general/topic/retirement/erisa
[^4]: https://www.dol.gov/sites/dolgov/files/ebsa/key-topics/retirement-benefits/cybersecurity/best-practices.pdf
[^5]: https://www.hipaajournal.com/hipaa-violation-fines/
